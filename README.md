# ロボットシステム学課題1
LED制御用デバイスドライバ
## 概要
2つのLEDを二進数の桁に見立てた点灯制御
## 使用した物
- Raspberry Pi
- LED ×2
- 抵抗330[Ω] ×2
## 使用方法
LEDをGPIO24と25にLEDを接続し次のコマンドで操作    
```
echo 0 > /dev/myled0    
echo 1 > /dev/myled0   
echo 2 > /dev/myled0   
echo 3 > /dev/myled0
```
- 0で消灯  　
- 1でLED1点灯 LED2消灯
- 2でLED1消灯 LED2点灯
- 3で両方が点灯  
## 実演
https://www.youtube.com/watch?v=bhYd5JF9buI
