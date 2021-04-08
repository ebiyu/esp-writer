# esp-writer

ESP32・ESP8266にコードを書き込むためのライタ回路です。

RTS/DTRによる自動リセット機能が実装されています。

![](/doc/schema.png)

## 使用部品

秋月電子のUSBシリアルモジュールを活用しています。

https://akizukidenshi.com/catalog/g/gK-06693/


## ピン配置

書き込みには6ピンを利用します。

1. EN
2. RXD
3. TXD
4. (none)
5. BOOT
6. GND
