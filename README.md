# ❝Easily-Remove-Xiaomi-Bloatware-Without-Root❞
### ✍️𝙐𝙣𝙞𝙣𝙨𝙩𝙖𝙡𝙡 𝘼𝙥𝙥 𝙗𝙡𝙤𝙖𝙩𝙬𝙖𝙧𝙚 𝙓𝙞𝙖𝙤𝙢𝙞
**Tanpa root dan tanpa UBL kamu bisa uninstall aplikasi bawaan / bloatware, khususnya XIAOMI.**



💽 𝙄𝙣𝙨𝙩𝙖𝙡𝙖𝙨𝙞
1. Extract File .zip
2. Klik kanan installer.exe ⇒ Run as administrator ⇒ Yes
3. Muncul terminal ktik Y ⇒ enter ⇒ Y ⇒ enter ⇒ Y ⇒ enter
4. Muncul installer window ⇒ next ⇒ finish
5. Close terminal



✅ 𝙑𝙚𝙧𝙞𝙛𝙞𝙠𝙖𝙨𝙞
1. Aktifkan Developer Mode di HP xioami
    - Pergi ke ⚙️ Settings di xiaomi kamu ⇒ About phone ⇒ Ketuk 'MIUI version' 8X sampai muncul keterangan `You are now developers!`.
    - Masih Di menu Settings ⇒ Additional settings ⇒ Developer options ⇒ Aktifkan USB debugging ⇒ Cek List persyaratannya - pilih OK.

2. Sambungkan Hp xioami kamu dengan laptop/PC yang sudah terinstall adb (keadaan HP menyala dan tidak terkunci)


📲 𝙄𝙣𝙞𝙨𝙞𝙖𝙨𝙞
1. Kembali ke PC
    - Buka directory C:\ ⇒ masuk ke folder 'adb' atau 'Minimal ADB and Fastboot'
    - pilih `cmd-here.exe` ⇒ Klik kanan ⇒ `Run as administrator` ⇒ Yes
    - atau tekan 'shift + klik kanan' ⇒  'open command window here' atau 'Open PowerShell window here'

2. Terbuka terminal ketik perintah berikut
    ```
    adb devices
    ```
3. Muncul izin otorisasi di HP

	- jika muncul permission (izin) pilih `OK`
	
	🥵🤯😵‍💫
    
	- jika gagal (unauthorized) putuskan koneksi HP dengan PC ⇒ restart ⇒ cek kembali USB debugging
	- sambung kembali ⇒ dan ulangi perintah adb devices
	
	😃👏🥳
    
	- jika berhasil akan muncul command berikut diterminal CMD
    
    ```
	C:\Minimal ADB and Fastboot>adb devices
	List of devices attached
	* daemon not running; starting now at tcp:5037
	* daemon started successfully
	xxxxxxxx        unauthorized
    ```

	- `xxxxxxxx` adalah serialphone kamu yang ditangkap saat ini
	- untuk memastikannya kamu bisa ulangi perintah adb devices (shortcut-nya kamu bisa tekan 🔼 - panah atas di keyboard kamu)



🪦 𝙀𝙠𝙨𝙚𝙠𝙪𝙨𝙞 - 𝙪𝙣𝙞𝙣𝙨𝙩𝙖𝙡𝙡

1.  Jika telah terdeteksi ketikan perintah dibawah & enter ⌨️
	adb shell

	- sekarang muncul codename xiaomi kamu (kini jembatan telah terbentuk)
    
       C:\Minimal ADB and Fastboot>adb shell

       codename:/ $

✍️✍️✍️

2. Ketik perintah & enter ⌨️

	`pm uninstall -k --user 0 'com.corporate.installerName'`

    - contoh :
    
    ```
    pm uninstall -k --user 0 'com.caf.fmradio'
    ```
    
    ```
    pm uninstall -k --user 0 'com.miui.fmservice'
    ```

3. jika berhasil akan muncul `Success` di terminal.




🔎 𝙈𝙚𝙣𝙚𝙢𝙪𝙠𝙖𝙣 𝙙𝙚𝙩𝙖𝙞𝙡 𝙣𝙖𝙢𝙖 𝘼𝙥𝙥
1. pergi ke pengaturan di HP kamu ⇒ pergi ke Apps /aplikasi ⇒ Manage Apps /app info
2. Pilih app yang yang dicari ⇒ ketuk tanda `ⓘ info` ⇒ temukan namanya di APK name


    - Untuk melihat versi yang diinstall
    ```
    adb --version
    ```
		
    - Untuk keluar
    ```
    exit
    ```
		
    - untuk clear/membersihkan jendela terminal
    ```
    cls
    ```


⚠️
🛑

**𝘽𝙀𝙍𝘽𝘼𝙃𝘼𝙔𝘼‼️ ☣️☢️**

***Perhatikan setiap app yang akan di uninstall,  JANGAN ASAL-ASALAN!
salah uninstall bisa berakibat malfungsi-brick- hingga bootloop.***


tapi kalau terlanjur terjadi??

siapkan kopi☕🚬  camilan🍟🍿  kuota📳🌐  ⇒ googling di yandex.

😃 𝙎𝙚𝙢𝙤𝙜𝙖 𝙗𝙚𝙧𝙢𝙖𝙣𝙛𝙖𝙖𝙩  
⚛️ 𝙀𝙇𝙆𝙃𝙊𝙀𝙍𝙄

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
