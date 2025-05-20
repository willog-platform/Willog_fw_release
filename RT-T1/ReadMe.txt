* 구분
 1. J-Link Donwload
   - .hex 파일 이용
 
 2. USB DFU Download
   - .zip 파일 이용

* How to download DFU file.
  - nrfutil.exe 파일을 펌웨어와 같은 폴더로 복사
  - 사용법 : nrfutil.exe dfu usb-serial -pkg [PACKAGE_FILE] -p [COM_PORT]
  - 예제 : nrfutil.exe dfu usb-serial -pkg rt-t1_app_package_20250417_154254.zip -p COM4