               ---
layout: post
title: Innovative Project Proposal
author: [Henry Lin]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is to specify a Innovative Project proposal and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
## Futre Home Applications
<iframe width="560" height="315" src="https://www.youtube.com/embed/jo-Vt6_p7z8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/4mwculdQ1XE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
### Homework Report
**Contents:**<br>
* **應用與功能說明**
  - Specify the future home application, and Describe the key features
  - Describe the key features which may be applied to the home space (kitchen, living room, play room, study room, bed room)
* **設計考量與所需相關技術**
  - List all design considerations and the required technologies
* **系統方塊圖**
  - Draw a System Block Diagram

---
## 救援用無人機
### 應用功能說明
1. 環境監測：溫濕度感測+瓦斯偵測+空氣品質偵測 
2. 影片拍攝：拍攝危險角度的影片
3. 傳送物資：對於偏遠地方的物資輸送

### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式:四軸旋翼
2. 供電方式:電池＋充電(type C)
3. 聯網方式: WiFi 或 BLE to中控電腦

**所需相關技術：**
1. 飛行姿態偵測與控制: ESP32 + MPU6050 + PID controller
2. 溫濕度感測 & 氣體偵測: HTU21D +  MQ7 + MQ135
3. 紅外線遙控: IR-LED 
4. 影像傳輸: ESP32-CAM模組
5. 距離遙測: VL53LoX
5. 物品夾具：懸吊掛勾, 磁鐵吸吊
6. 服務器: 具AI加速(GPU)
  - 影像物件偵測辨識: CSL-YOLO

### 系統方塊圖
![](https://raw.githubusercontent.com/Henry911222/MCU-project/main/images/%E5%BE%AE%E6%8E%A7%E5%88%B6%E5%99%A8.png)
![](https://raw.githubusercontent.com/Henry911222/MCU-project/main/images/343922685_1382662665904531_1255439180559653735_n.jpg)
<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


