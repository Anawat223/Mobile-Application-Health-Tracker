1.	การติดตั้ง Flutter SDK
  1.1	เข้าเว็บไซต์ https://flutter.dev/
  1.2	กดปุ่ม Get started แล้วทำการติดตั้ง Flutter SDK ตามระบบปฏิบัติการ
  1.3	หลังจากดาวน์โหลด Flutter SDK แล้วให้สร้างโฟลเดอร์ src ขึ้นมาแล้วแยกไฟล์ flutter ที่ดาวน์โหลดมาใส่ในโฟลเดอร์ src
  1.4	ค้นหา Edit environment variables for your account ที่ตัวเครื่อง แล้ว Edit Path User variables นำ Path \src\flutter\bin ของ Flutter SDK ที่ได้ติดตั้งไปเพิ่มใน User variables
  1.5	ตรวจสอบสถานะของการติดตั้ง Flutter SDK โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง flutter doctor
2.	การติดตั้ง Android Studio
  2.1	เข้าเว็บไซต์ https://developer.android.com/studio
  2.2	กดปุ่ม Download Android Studio
  2.3	ตั้งตั้ง Android Studio
  2.4	ติดตั้ง Android SDK โดยเข้าเมนู SDK Manager แล้วเลือกเวอร์ชันของ Android SDK ที่ต้องการติดตั้ง
  2.5	ติดตั้ง Flutter plugin โดยเข้าเมนู Setting และกดคำว่า Plugin แล้วทำการค้นหา Flutter plugin แล้วจึงกด Download
  2.6	ตั้งค่า Path ของ Android SDK โดยเข้าเมนู Edit environment variables for your account ที่ตัวเครื่อง
      1.	กดปุ่ม New ที่ช่อง User variables
      2.	ใส่คำว่า ANDROID_SDK_ROOT ที่ช่อง Variable name ในส่วนของ User Variable
      3.	ใส่ Path ของ Android SDK ที่ช่อง Variable valueเช่น C:\Users\Mighty.Muad\AppData\Local\Android\Sdk
      4.	เพิ่ม New Path ของ Android SDK ทั้งหมด 3 Path เช่น
          4.1 C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\tools
          4.2 C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\tools\bin
          4.3 C:\Users\Mighty.Muad\AppData\Local\Android\Sdk\platform-tools
3.	การติดตั้ง Node.js
  1.	เข้าเว็ปไซต์ https://nodejs.org/en/download
  2.	กดปุ่ม “Download Node.js v20.12.0”
  3.	ติดตั้ง Node.js ตาม installer
4.	การติดตั้ง Visual Studio Code
  1.	เข้าเว็บไซต์ https://code.visualstudio.com/
  2.	กดปุ่มดาวน์โหลด
  3.	ติดตั้ง Visual Studio Code
  4.	เข้าไปที่โปรแกรม Visual Studio Code แล้วค้นหา Dart Extension แล้วทำการติดตั้ง Extension
  5.	ตรวจสอบสถานะของการติดตั้ง Visual Studio Code และ Dart Extension โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง flutter doctor
5.	การติดตั้งส่วนจัดการเบื้องหลัง
  1.	Clone github project: https://github.com/MydudeEiEi/Health-Tracker.git
  2.	เปิดโปรแกรม Visual Studio Code
  3.	เปิดโปรเจคที่ clone มาผ่านโปรแกรม Visual Studio Code
  4.	รันคำสั่ง flutter pub get
  5.	นำไฟล์ google-services.json ที่โหลดจาก Firebase ไปไว้ในโฟลเดอร์ Health-Tracker\android\app\google-services.json
  6.	Launch Emulator โดยการกด Ctrl+Shift+P เลือก Flutter: Launch Emulator
  7.	เปิด main_page.dart แล้วกด F5 เพื่อ Run and Debug
  8.	ตั้งค่า Android license โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง Flutter doctor --android-licenses
  9.	ตรวจสอบสถานะของการติดตั้ง Android Studio, Android SDK และ Flutter plugin โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง flutter doctor
  10.	สร้าง Virtual devices
    1	เข้าไปที่โปรแกรม Android Studio
    2	เข้าเมนู AVD Manager
    3	กด Create Virtual Device โดยสร้างตามขั้นตอนของ Android Studio
    4	ตรวจสอบการเชื่อมต่อกับ Virtual Device โดยเข้าไปที่ Command prompt แล้วพิมพ์คำสั่ง flutter doctor

