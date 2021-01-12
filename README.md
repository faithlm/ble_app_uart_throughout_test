# ble_app_uart_throughout_test
使用nrf52832如何达到最大的传输速率并做一个简单的速率测试

# 使用说明
clone代码到`nRF5_SDK_17.0.2_d674dde\examples\ble_peripheral` 目录下。

打开`ble_app_uart-_throughout_test\pca10040\s132\ses`下工程文件

编译下载到nrf52DK中

使用手机nrf_connect搜索广播名`Nordic_test` 并连接
nrf_connect下载地址：

手机端使能uart服务cccd，打开notify。

连接状态，单击一次button1，即可开始测速，测速结果打印在rtt log中。
