# WifiHaLow_研究
+ 作者: HsiupoYeh
+ 更新日期: 2025-08-24

### WifiHaLow (IEEE 802.11ah) 簡介
+ 整個字讀起來像是 **"歪ㄈㄞ、黑漏"** 。
+ IEEE 802.11ah是802.11家族的一項無線網路標準，由IEEE標準協會制定，旨在透過 1Ghz 免授權頻段提供低功耗、長距離的**無線區域網路**（WLAN），Wi-Fi聯盟自2016年定名為WiFi HaLow。
+ 台灣地區免執照頻段: 922-928MHz、920-925MHz。
  + 註: 使用Lora協定的**Meshtastic**，在台灣預設是使用923.875MHz，目前有人推廣改用920.125MHz。
  + 註2: **HT-H7608 Wi-Fi HaLow 路由器** 使用的天線支援: 902~928 MHz。

### 選擇硬體
+ 中國公司Heltec Automation設計的**HT-H7608 Wi-Fi HaLow 路由器**。
  + 產品頁面：https://heltec.cashier.ecpay.com.tw/product/000000000781290
  + 說明書: https://resource.heltec.cn/download/HT-H7608/HT-H7608_1.0.pdf
  + 特色：MCU用MT7628。
  + 優點：
    + 便宜、台灣有官網可購買。
    + 低功耗，可用USB TypeC供電，也有附5V/2A變壓器。實際使用平均功耗低於2W。資料傳輸時可能高至3.5W。
    + 工業規格運作溫度: -40°C to 85°C 。
    + 同時可以一起運作Wifi 2.4GHz。
    + 高速傳輸: 150Kbps ~ 32Mbps 。
  + 缺點：中國產品。
 
### 重置按鈕
+ 按鈕非常小，要用針戳。沒必要應該不會需要按他。
+ 長按10秒工廠重置。其他的秒數請參考說明書。

### 初次設定(上網用的主機)
+ 參考資料: https://docs.heltec.org/en/wifi_halow/ht-h7608/index.html
+ 上電會亮紅燈，接著閃爍，然後變成黃或綠燈有出現的時候，表示已經開機完成。
+ 如果已經是在閃爍
+ 管理者帳戶: root
+ 預設密碼: heltec.org
