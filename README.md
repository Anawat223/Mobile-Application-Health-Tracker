1.	การติดตั้ง Flutter SDK
    1. เข้าเว็บไซต์ [https://flutter.dev/](https://flutter.dev/ "https://flutter.dev/")
	2. กดปุ่ม Get started แล้วทำการติดตั้ง Flutter SDK ตามระบบปฏิบัติการ 
	3. หลังจากดาวน์โหลด Flutter SDK แล้วให้สร้างโฟลเดอร์ src ขึ้นมาแล้วแยกไฟล์ flutter ที่ดาวน์โหลดมาใส่ในโฟลเดอร์ src 
	4. ค้นหา Edit environment variables for your account ที่ตัวเครื่อง แล้ว Edit Path User variables นำ Path \src\flutter\bin ของ Flutter SDK ที่ได้ติดตั้งไปเพิ่มใน User variables 
	5. ตรวจสอบสถานะของการติดตั้ง Flutter SDK โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง ``flutter doctor``
2.	การติดตั้ง Android Studio
	1. เข้าเว็บไซต์ [https://developer.android.com/studio](https://developer.android.com/studio "https://developer.android.com/studio")
	2. กดปุ่ม Download Android Studio
	3. ตั้งตั้ง Android Studio
	4. ติดตั้ง Android SDK โดยเข้าเมนู SDK Manager แล้วเลือกเวอร์ชันของ Android SDK ที่ต้องการติดตั้ง
	5. ติดตั้ง Flutter plugin โดยเข้าเมนู Setting และกดคำว่า Plugin แล้วทำการค้นหา Flutter plugin แล้วจึงกด Download
	6. ตั้งค่า Path ของ Android SDK โดยเข้าเมนู Edit environment variables for your account ที่ตัวเครื่อง
	7. กดปุ่ม New ที่ช่อง User variables
	8. ใส่คำว่า ``ANDROID_SDK_ROOT`` ที่ช่อง Variable name ในส่วนของ User Variable
	9. ใส่ Path ของ Android SDK ที่ช่อง Variable value เช่น C:\Users\Mighty.Muad\AppData\Local\Android\Sdk
	10. เพิ่ม New Path ของ Android SDK ทั้งหมด 3 Path เช่น
	11. C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\tools
	12. C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\tools\bin
	13. C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\platform-tools
3.  การติดตั้ง Node.js
    1. เข้าเว็ปไซต์ [https://nodejs.org/en/download](https://nodejs.org/en/download "https://nodejs.org/en/download")
    2. กดปุ่ม “Download Node.js v20.12.0”
	3. ติดตั้ง Node.js ตาม installer
4.  การติดตั้ง Visual Studio Code
	1. เข้าเว็บไซต์ [https://code.visualstudio.com/](https://code.visualstudio.com/ "https://code.visualstudio.com/")
    2. กดปุ่มดาวน์โหลด
	3. ติดตั้ง Visual Studio Code
	4. เข้าไปที่โปรแกรม Visual Studio Code แล้วค้นหา Dart Extension แล้วทำการติดตั้ง Extension
	5. ตรวจสอบสถานะของการติดตั้ง Visual Studio Code และ Dart Extension โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง ``flutter doctor``
5. การติดตั้งส่วนจัดการเบื้องหลัง
	1. Clone github project: [https://github.com/MydudeEiEi/Health-Tracker.git](https://github.com/MydudeEiEi/Health-Tracker.git "https://github.com/MydudeEiEi/Health-Tracker.git")
	2. เปิดโปรแกรม Visual Studio Code
	3. เปิดโปรเจคที่ clone มาผ่านโปรแกรม Visual Studio Code
	4. รันคำสั่ง ``flutter pub get``
	5. นำไฟล์ google-services.json ที่โหลดจาก Firebase ไปไว้ในโฟลเดอร์ Health-Tracker\android\app\google-services.json
	6. Launch Emulator โดยการกด Ctrl+Shift+P เลือก Flutter: Launch Emulator
	7. เปิด main_page.dart แล้วกด F5 เพื่อ Run and Debug
	8. ตั้งค่า Android license โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง ``Flutter doctor --android-licenses``
	9. ตรวจสอบสถานะของการติดตั้ง Android Studio, Android SDK และ Flutter plugin โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง ``flutter doctor``
	10. สร้าง Virtual devices
	11. เข้าไปที่โปรแกรม Android Studio
	12. เข้าเมนู AVD Manager
	13. กด Create Virtual Device โดยสร้างตามขั้นตอนของ Android Studio
	14. ตรวจสอบการเชื่อมต่อกับ Virtual Device โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง ``flutter doctor``