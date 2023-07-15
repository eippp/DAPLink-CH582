# [DAPLink-Ch582](https://github.com/SoCXin/DAPLink-CH582)

[CMSIS-DAP](https://github.com/OS-Q/DAPLink) compliant debugger based on [Ch582F](https://item.szlcsc.com/3483855.html)

编译环境依赖：[MounRiver Studio](http://mounriver.com/download)  

## Features

- [x] CMSIS-DAP V2.1
- [x] SWD
- [ ] JTAG
- [ ] UART
- [x] Connected & Running LED

## Usage

| Function | Label | GPIO |
|:-|:-:|:-:|
| JTAG_TDI | TDI | A0 |
| JTAG_TDO | TDO | A1 |
| JTAG_TMS | TMS  | A2 |
| JTAG_TCK | TCK  | A15 |
| SWD_SWDIO | TMS | A2 |
| SWD_SWCLK | TCK | A15 |
| nRESET | RTS | A4 |
| UART TX | TX | B7 |
| UART RX | RX | B4 |

Notice that 3.3V level I/O is required.

