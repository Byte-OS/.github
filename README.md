# This is a README for Byte-OS Org

## Trait List

> 这里有一些可以复用的模块（特指 Rust），如下：

| 模块 | 链接 | 介绍 |
| ---  | --- | ---  |
| arm_gic | https://github.com/Byte-OS/arm_gic | arm 通用中断控制器, Thanks ArceOS |
| arm_pl011 | https://github.com/Byte-OS/arm_pl011 | arm_pl011 串口, Thanks ArceOS |
| backtrace | https://github.com/Byte-OS/backtrace | 在发生 panic 的时候调用，能显示异常的函数地址(Only Riscv) |
| percpu | https://github.com/Byte-OS/percpu | 定义 percpu 数据，需要修改链接脚本, Thanks ArceOS |
| timestamp | https://github.com/Byte-OS/timestamp | 可以将时间戳转换为时间结构，有 rtc 设备会比较有用 |
| vfscore | https://github.com/Byte-OS/vfscore | 虚拟文件系统，包含文件抽象 |
| cv1811-sd | https://github.com/Byte-OS/cv1811-sd | cv1811h 的 sd 卡驱动，也许是 cvitek-sd 都通用 |
| crate_interface | https://github.com/Byte-OS/crate_interface | 可以有效解决循环依赖的问题，可以利用 trait 实现底层调上层, Thanks ArceOS |
| lose-net-stack | https://github.com/Byte-OS/lose-net-stack | 一个轻量级的网络协议栈，也许在一些资源受限的设备上比较有效，支持 TCP，UDP |
| rustfs | https://github.com/Byte-OS/rust-fatfs | Fork https://github.com/rafalh/rust-fatfs.git, 做了一些修改，可以手动 flush |
