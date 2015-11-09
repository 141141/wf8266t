# WF8266T-TFT 開發板介紹

![](../imgs/DSC01945_1000.jpg)

## 預設電路
因為 TFT 驅動需要 SPI 的腳位，我們已預先定義了以下腳位功能，其中除了 GPIO14 GPIO16 會影響到 TFT 顯示外，其它的腳位可依實際情況評估使用。

* GPIO0 : UPDATE(紅色按鍵), DHT11(DATA) / DHT22(DATA)
* GPIO1 : Tx
* GPIO2 : None
* GPIO3 : Rx
* GPIO4 : SD Card CS
* GPIO5 : None
* GPIO12: MISO
* GPIO13: MOSI
* GPIO14: SCK
* GPIO15: CS
* GPIO16: LED
* *ADC : None