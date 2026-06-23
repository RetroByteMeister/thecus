1. Unzip file to USB root folder, at least need following 4 files:
factory_test.sh
xusb_reset_default
xusb_reset_passwd
xusb_upgrade

1-1. If went to update FW, rename from "xusb_upgrade" to "usb_upgrade", 
   and copy firmware upgrade file to USB root folder. 
1-2. If went to Reset Default, rename from "xusb_reset_default" to "usb_reset_default".

1-3. If went to Reset root password, rename from "xusb_reset_passwd" to "usb_reset_passwd".
1-4. Above 3 function CAN"T exectue together!!

2. Power off NAS.
3. Plug USB into NAS and power up.
4. Since process completed and NAS going to power off automatically.


*******************************************


1. 更新F/W
  把F/W檔放到這目錄,並將xusb_upgrade改名為usb_upgrade

2. Reset Default
  把xusb_reset_default改名為usb_reset_default

3. Reset root password
  把xusb_reset_passwd改名為usb_reset_passwd


三個功能不能同時執行.
