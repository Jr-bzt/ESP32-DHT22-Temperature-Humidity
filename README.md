# ESP32-DHT22-Temperature-Humidity
ESP32 AIoT demo, read temperature and humidity data by DHT22

## 项目介绍
使用 ESP32 读取 DHT22 温湿度传感器数据，可用于物联网环境监测。

## 硬件清单
- ESP32 开发板
- DHT22 温湿度传感器
- 杜邦线


## 接线参考
| DHT22 | ESP32 |
|-------|-------|
| VCC   | 3.3V  |
| GND   | GND   |
| DATA  | GPIO （自行修改代码引脚） |

> 提示：DHT22 建议搭配 4.7k~10k 上拉电阻。

## 依赖库
- DHT sensor library
- Adafruit Unified Sensor

## 使用方法
1. 在 Arduino IDE / PlatformIO 安装上面的依赖库
2. 修改代码里的数据引脚，和实际接线保持一致
3. 编译上传至 ESP32
4. 打开串口监视器查看温湿度输出

## License
MIT
