## ❝ Easily Remove Xiaomi Bloatware Without Root ❞
### ✍️ Tanpa root dan tanpa UBL kamu bisa uninstall aplikasi bawaan / bloatware, khususnya XIAOMI.

**GUIDE**


<details>
<summary>💽 𝙄𝙣𝙨𝙩𝙖𝙡𝙖𝙨𝙞</summary>

1. Extract File .zip 
2. Klik kanan installer.exe ⇒ Run as administrator ⇒ Yes
3. Muncul terminal ktik Y ⇒ enter ⇒ Y ⇒ enter ⇒ Y ⇒ enter
4. Muncul installer window ⇒ next ⇒ finish
5. Close terminal
  
</details>


---


<details>
<summary>✅ 𝙑𝙚𝙧𝙞𝙛𝙞𝙠𝙖𝙨𝙞</summary>

1. Aktifkan Developer Mode di HP xioami
    - Pergi ke `⚙️ Settings` di xiaomi kamu ⇒ `About phone` ⇒ Ketuk `MIUI version` 8X sampai muncul keterangan `You are now developers!`.
    - Masih di `⚙️ Settings` ⇒ `Additional settings` ⇒ `Developer options` ⇒ `Aktifkan USB debugging` ⇒ Cek List persyaratannya - pilih `OK`.

2. Sambungkan Hp xioami kamu dengan laptop/PC yang sudah terinstall adb (keadaan HP menyala dan tidak terkunci)
  
</details>


---


<details>
<summary>📲 𝙄𝙣𝙞𝙨𝙞𝙖𝙨𝙞</summary>

1. Kembali ke PC
    - Buka directory `C:\` ⇒ masuk ke folder `adb` atau `Minimal ADB and Fastboot`
    - 1. Pilih `cmd-here.exe` ⇒ Klik kanan ⇒ `Run as administrator` ⇒ `Yes`
    - 2. Atau tekan `shift + klik kanan` ⇒  `open command window here` atau `Open PowerShell window here`

2. Terbuka terminal ketik atau salin perintah berikut
    ```cirru
    adb devices
    ```
3. Muncul izin otorisasi di HP

	- jika muncul permission (izin) pilih `OK`
	
	🥵🤯😵‍💫
    
	- jika gagal (unauthorized) putuskan koneksi HP dengan PC ⇒ cek kabel ⇒ cek lagi USB debugging
	- sambung kembali ⇒ dan ulangi perintah `adb devices`
	
	😃👏🥳
    
	- jika berhasil akan muncul command berikut diterminal CMD
    
    ```cirru
	C:\Minimal ADB and Fastboot>adb devices
	List of devices attached
	* daemon not running; starting now at tcp:5037
	* daemon started successfully
	xxxxxxxx        unauthorized
    ```

	- `xxxxxxxx` adalah idPhone kamu yang ditangkap saat ini
	- untuk memastikannya kamu bisa ulangi perintah `adb devices` (shortcut= kamu bisa tekan 🔼 panah atas di keyboard kamu)
  
</details>


---


<details>
<summary>🪦 𝙀𝙠𝙨𝙚𝙠𝙪𝙨𝙞 - 𝙪𝙣𝙞𝙣𝙨𝙩𝙖𝙡𝙡</summary>

1.  Jika telah terdeteksi ketikan perintah dibawah & enter ⌨️
	```cirru
	adb shell
	```

	- sekarang muncul codename xiaomi kamu (kini jembatan telah terbentuk)
    
       C:\Minimal ADB and Fastboot>adb shell

       codename:/ $

✍️✍️✍️

2. Ketik perintah & enter ⌨️
    ```cirru
    pm uninstall -k --user 0 'com.xxx.xxx'
    ```

    - contoh :
    
    ```cirru
    pm uninstall -k --user 0 'com.caf.fmradio'
    ```
    
    ```cirru
    pm uninstall -k --user 0 'com.miui.fmservice'
    ```

3. jika berhasil akan muncul `Success` di terminal.
  
</details>


---


<details>
<summary>🔎 𝙈𝙚𝙣𝙚𝙢𝙪𝙠𝙖𝙣 𝙙𝙚𝙩𝙖𝙞𝙡 𝙣𝙖𝙢𝙖 𝘼𝙥𝙥</summary>

1. pergi ke pengaturan di HP kamu ⇒ pergi ke `Apps` atau `aplikasi` ⇒ `Manage Apps` atau `app info`
2. Pilih app yang yang dicari ⇒ ketuk tanda `ⓘ info` ⇒ temukan namanya di `APK name`


    - Untuk melihat versi yang diinstall
    ```cirru
    adb --version
    ```
		
    - Untuk keluar
    ```cirru
    exit
    ```
		
    - untuk clear/membersihkan jendela terminal
    ```cirru
    cls
    ```
  
</details>


---


⚠️
🛑
<details open>
<summary>**𝘽𝙀𝙍𝘽𝘼𝙃𝘼𝙔𝘼‼️ ☣️☢️**</summary>

***Perhatikan setiap app yang akan di uninstall,  JANGAN ASAL-ASALAN!
salah uninstall bisa berakibat malfungsi-brick- hingga bootloop.***


tapi kalau terlanjur terjadi??

siapkan kopi☕🚬  camilan🍟🍿  kuota📳🌐  ⇒ googling di yandex.
  
</details>



😃 𝙎𝙚𝙢𝙤𝙜𝙖 𝙗𝙚𝙧𝙢𝙖𝙣𝙛𝙖𝙖𝙩  
⚛️ 𝙀𝙇𝙆𝙃𝙊𝙀𝙍𝙄
