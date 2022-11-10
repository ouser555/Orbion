# Orbion space mouse 
  
## Orbion是很棒的設計，不過原版Orbion有幾個坑，需要DIY者自行解決

  1.列印件的STL檔有些地方尺寸不對，開孔位置沒開孔，需要修改
  
  2.Firmware的Encorder部分有問題，大部分市面上的編碼器會動作不正常
  
  3.需要買的零件孔位會對不到
  
    a.joystick模組，孔位有可能會買到差一點的，可以靠擴孔解決。
  
    b.encorder模組，會很不容易買到需要的。
      
      1.這個底板孔位和編碼器柄長
      
      2.編碼器底座高度都會不一樣
      
      3.轉動1齒步進幾格，有的1格有的2格。
        
  
  4.三個金屬按鍵缺點(但是好看)
    
    a.很貴
    
    b.不好買
    
    c.不好按
    
    d.擺放位置不好
    
  5.
  
## 檔案

* /Orbion_FW_v0.26.5/是已經修改過的Firmware
  
  a.修改過了Encorder，有稍微好用一些，還不到完美
  
  b.原本是1.3吋的OLED(128x64)，改成SSD1306 0.96吋的(128x32)
  
  c.統一參數 #define joyThroth 30 ，joystick最小觸發閥值，可以根據自己的joystick彈簧鬆緊度調整到剛好不影響Encorder操作的最小極限值。
  
## 改成QMK
