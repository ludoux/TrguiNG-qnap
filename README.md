# TrguiNG-qnap
qpkg app of TrguiNG, works for TransmissionBT4 (not 3)

为 QNAP 平台创建的 TrguiNG 软件包，仅适用于 TransmissionBT4 (而不是 3)

### TL;DR
1. Install [TransmissionBT 4](https://www.myqnap.org/product/transmissionbt-4) made by QoolBox first. I will not get a penny from your installation.
2. **Understand that YOU TAKE YOUR OWN RISK to use the qpkg file made by a person you don't even meet or know.**
3. Install TrguiNG qpkg made by ludoux in [releases page](https://github.com/ludoux/TrguiNG-qnap/releases). Remember to select the correct platform. If you need another platform, reply to this post.

### 长话短说

1. 首先安装由 QoolBox 制作的 [TransmissionBT 4](https://www.myqnap.org/product/transmissionbt-4)。我将不会从您的安装中得到一分钱。
2. **请理解，如果您使用陌生人创建的 qpkg 文件，您需要自行承担风险。**
3. 在 [releases page](https://github.com/ludoux/TrguiNG-qnap/releases) 安装 ludoux 制作的 TrguiNG-zh qpkg。请记住选择正确的平台。

### Platform Selection
- X86_64 (Intel/AMD)
- arm-x41 / arm-x31 ARMV7 (ARM 32bits)
- arm_64 ( aarch64 / armv8 64bits )


### Introduction
I used QDK_2.3.13 to pack the TrguiNG as a qpkg file for QNAP users to install it directly to use this webui, and it only works for TransmissionBT 4 (**not 3**).

It was built and tested on my own NAS(TS-453Dmini as x86_64) with QTS 5.2.0+

It will rename the original `public_html` of Tr4 to `public_html_old` and create a link to TrguiNG folder, as the [Transmission4 web control](https://www.myqnap.org/product/transmission4-web-control/) do.

### Reference
https://blog.233so.com/2020/05/qdk-quick-start-guide-zh
