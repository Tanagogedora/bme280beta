# Sensor Extension for micro:bit
# micro:bit 用 BME280 センサー拡張機能

You can measure atmospheric pressure, temperature, and humidity.  
Sensor values are based on the official BME280 datasheet.


気圧・気温・湿度の測定が可能です。センサー仕様は BME280 のデータシートに基づいています。

 
> ⚠️ **この拡張機能は現在ベータ版です。動作確認中の機能が含まれます。ご使用の際はご注意ください。**

> 🔗 Demo Page:**デモページを見る: [https://tanagogedora.github.io/bme280beta/](https://tanagogedora.github.io/bme280beta/)

---
## 📦 How to Use / 使い方
### As a MakeCode Extension
1. Open [https://makecode.microbit.org/](https://makecode.microbit.org/)
1. Create a new project
1. Click the gear icon (⚙) in the top-right → select “Extensions”
1. Paste the following URL to add the extension  
	 `https://github.com/tanagogedora/bme280beta` 

---

### MakeCode 拡張機能としての使用方法

1. MakeCode [https://makecode.microbit.org/](https://makecode.microbit.org/)を開く
1. 「新しいプロジェクト」をクリック
1. 画面右上のギアボタン（⚙）をクリックし、「拡張機能」を選択 
1. 下記の URL を検索または貼り付けてインポート    
	`https://github.com/tanagogedora/bme280beta`


---

### 🖼 Example Blocks / ブロック例

![BME280 ブロック](https://github.com/Tanagogedora/bme280beta/blob/master/BME280Block.jpeg?raw=true)

---

### ✏️ To modify the extension source code in MakeCode:

1. Open [https://makecode.microbit.org/](https://makecode.microbit.org/)
1. Click "Import" → "Import URL"  
1. Paste this URL  
   `https://github.com/tanagogedora/bme280beta`


---

### ✏️ MakeCode 上で編集

1. MakeCode [https://makecode.microbit.org/](https://makecode.microbit.org/) を開く
1. 「読み込む」→「URLから読み込む…」を選択
1. 以下の URL を貼り付けてインポート   
	`https://github.com/tanagogedora/bme280beta`

---

## 🧪 Sensor Specification (Based on Datasheet) / 測定仕様（参考：データシートより）


| Measurement(測定対象) | Range(範囲) | Accuracy(精度) | Resolution(分解能) |
|-----------|------------------|-------------------|--------------------|
| Pressure(気圧) | 300 ～ 1100 hPa | ±1.0 ～ 1.7 hPa | ±0.16 Pa |
| Temperature(気温) | -40 ～ +85 ℃ | ±0.5 ～ 1.0 ℃ | ±0.01 ℃ |
| Humidity(湿度) | 0～100% | ±3% | ±0.008% |

※ 上記の値は BME280 の公式データシートに基づく参考値です。

#### メタデータ (検索、レンダリングに使用)

* for PXT/microbit
<script>
makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");
</script>
