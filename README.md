# user-device-checker
網頁顯示異常? 
用此快速檢測使用者的裝置與瀏覽器相關。  
https://jimmysu15.github.io/user-device-checker/

### 現有功能
- 瀏覽器 JS、Cookies 功能是否運作正常  
- 偵測瀏覽器名稱、版本、瀏覽器引擎、OS 資訊  
- 是否為 IE 或 Edge 系列  
- 裝置日期時間  
- 裝置類型資訊  
- 是否在 in app Browser 內   
- Google CDN 是否正常讀取  
- ICONFONT 是否正常顯示
- TypeSquare, Google Webfont 是否正常顯示
- 是否調整瀏覽器字型設定   
- 是否屏蔽 Google Analytics   
- 螢幕亮度對比是否正常  
- 是否使用 Adblock
- Flash 是否被屏蔽   
- 螢幕解析度比例是否正確   
- 彈跳視窗是否會被阻擋    
- alert/confirm 是否正常   
- 是否支援 APNG、WEBP、SVG
- IP 位置、IP 換算國家
- 瀏覽器 html geolocation 資訊與台灣縣市對照

### 預期增加
- 偵測 ublock
- 網路斷線時顯示提示
- 防毒軟體主動防護造成的 499 error 
- 英文語系版

### 本工具部分技術使用以下資源
- Material icons https://material.io/icons/ (Iconfont)
- f2etw/detect-inapp https://jimmysu15.github.io/user-device-checker/f2etw/detect-inapp (是否為 inapp 瀏覽器環境)
- vergrabber http://vergrabber.kingu.pl/ (瀏覽器的最新版本號資料)
- modernizr https://modernizr.com/ (偵測瀏覽器 touch 功能)
- mydevice.io http://mydevice.io/ (偵測瀏覽器縮放)
- enchroma - TEST YOUR COLOR VISION http://enchroma.com/test/instructions/
- 顏色共識 http://rodert.pixnet.net/blog/post/36082979
- ua-parser-js http://faisalman.github.io/ua-parser-js/ (UserAgent 相關解析)
- Mario Klingemann https://codepen.io/quasimondo/ (背景特效)
- Free ActionScript http://www.freeactionscript.com/tag/dynamic-explosion-effects/
- essoduke/jQuery-TWzipcode https://code.essoduke.org/twzipcode/ (地址位置對應台灣縣市區域)
- ipify.org http://ipify.org/ (取得使用者IP)
- GeoNames http://www.geonames.org/ (取得使用者IP)
- FreeGeoIP https://freegeoip.net/ (取得使用者IP、經緯度、國家)
- PostMail https://postmail.invotes.com/ (email 寄信功能)
