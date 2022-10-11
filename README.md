Boot from Live Linux, 從隨身碟 Linux 開機
---
- Mac: Press [option] and power on, 選取 [option] 並打開電源
  - Choose [EFI boot], press [F2], and [F2], 選取 [EFI boot] 再 [F2], 再 [F2]  
  - add the fowllowing after " initrd=initrd.xz “, 在前面指令後面加入,
    load=Python35 login=root
- MsWindows, setup BIOS to boot from Linux Disk, 設定 BIOS 支持從隨身碟開機


Setup the display, 設定顯示器解析度
---
change the revolution of display if necessary, 如有需要, 依照下列方式調整螢幕解析度

- Choose [K], at left bottom, [Applications], [Settings], [KDE System Settings],
  [Size & Orientation], choose one your favorite, for instance 1280x1024, [Apply].
  從左下端選取 [K], 然後 [Applications], [Settings], [KDE System Settings],
  [Size & Orientation], 依照你的喜好選取時候解析度, 例如  1280x1024,

Startup 啟動 Jupyter Notebook
---
Press [IPyNB] to activate Jupyter notebook, with root and null passwords.
選取 桌面上 [IPyNB] 啟動 Jupyter notebook, 使用 root 身分和空的密碼


notes 其他
---

1. change the power save setting from the right bottom icon, [battery], right click to 
   change the setting. 避免進入睡眠設定, 從右下角 右按 [battery] 圖形 修改自動睡眠裝置.
2. if on the power save mode, the root's password, toor, should be asked to re-login.
   如果進入自動睡眠模式, 使用 root 的密碼 “toor”, 重新進入.
3. The system is live system in default; this means that users have to save the result 
   before shutdown the box. Restore the data from [Delphin], the file management found
   on the bottom menu, The usb stick is recognised under [devices], for instance: KINSTON 
   系統為 live system, 代表關機前必須把工作的資料儲存到隨身碟, 儲存方法, 使用最下方目錄的檔案總管 [Delphin], 進入左邊 [devices] 隨身碟的代號, 例如 KINSTON.
4. The IPython data is on USB stick and in the folder, NetworkSecurityIntroduction,
   在隨身碟方面的 IPython 資料都放在 NetworkSecurityIntroduction 目錄中, 
   - open [Delphin], enter in USB stick, 打開 [Delphin], 進入隨身碟
   - [Split] the Windows, and the new one enters into [root], 選取 [Split], 並變更右邊的視窗進入 [root] 目錄,
   - copy or link the  [NetworkSecurityIntroduction] to [root], the latter is prefered since you have not necessary to restore back the data back. 將左邊的  [NetworkSecurityIntroduction] 複製或者連結到右邊的 [root] 目錄之中, 比較建議使用連結的方式, 因為問題是不用再回存資料.

Jupyter Notebook from Mac,  Mac 系統的Jupyter Notebook
===
This USB stick also comes with Jupyter Notebook. In Mac OS sys, startup up Jupyter notebook by portableUSB.sh. 隨身碟已經包涵Jupyter Notebook, 在 Mac 作業系統中, 使用portableUSB.sh 啟動 Jupyter Notebook.