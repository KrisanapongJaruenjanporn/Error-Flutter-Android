# Flutter & Android Studio Error

## Flutter support java sdk version 17
- https://www.oracle.com/java/technologies/downloads/#java17
<br>
## Check path Flutter
Edit environment variables for your account > เลือกที่ Path > กดปุ่ม Edit
<img width="359" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/9c646d52-968f-4621-b194-d761b2604e12">
<br>
เปิด ทดลองรัน ใน cmd พิมพ์ where flutter dart
<br>
<img width="357" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/c3c55cd3-78e8-40d1-ab74-7d1af241a232">
<br>

### พิมพ์ flutter doctor บน cmd

<br>
ถ้าขึ้นแบบนี้
❌
<br>
<mark>ERROR unable to locate android sdk</mark>
<br>
<img width="563" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/03659bae-d21c-4931-8b1c-81ef8e2e3771">
<br>
วิธีแก้
<br>
 
- 1 เปิด Android Studio
- 2 SDK Tools
- 3 ตืก Android SDK Command-line Tools ออกแล้วติดตั้งให้
- 4 copy Android SDK Location <img width="698" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/7084b6d1-52f3-4115-aea1-e70c31c08a9b">
- 5 เปิด cmd พิมพ์ ```flutter config --android-sdk <Android SDK Location>```
- 6 เปิด cmd ให้ พิมพ์ ```flutter doctor```

ถ้าขึ้น ✔️ <br>
<img width="693" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/2f5fd072-3802-4437-88c3-3414a324d908">
---

## Check Flutter & Dart SDK Path
<br>
<img width="394" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/b6d26713-3734-4fda-a0a7-ace06755c9a2">
<br>
 ## ไม่เจอปุ่ม main.dart ?
<br>
<img width="208" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/7e086aa4-b05a-461b-b711-f372c323a4a4">
<br>
❌❌❌
<br>
<img width="226" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/ec17fa4f-f1e9-4d78-af5a-90292b67a243">
<br>
<img width="394" alt="image" src="https://github.com/KrisanapongJaruenjanporn/Error-Flutter-Android/assets/121858059/b6d26713-3734-4fda-a0a7-ace06755c9a2">
<br>
เช็ค Flutter & Dart ให้ถูก

แล้ว Run Devices เดียวมันขึ้นเอง
<br>
✔️✔️✔️
<br>
วิธีแก้

