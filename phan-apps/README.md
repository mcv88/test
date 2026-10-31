# phan-apps - update source

Nguon cap nhat cho cac app cua Phan, khong phai repo code chinh.

- `versions.json`: moi app 1 muc, gom versionCode, versionName, apkFile, b64Url.
- `*.apk.b64`: APK duoc base64 hoa (vi GitHub MCP chi day duoc file text), app tai ve roi giai ma base64 thanh APK roi cai.
- Cap nhat app: build APK moi, base64 hoa, day file .b64 moi len, sua versions.json cho dung versionCode moi. App cu se thay versionCode moi > versionCode hien tai va tu tai ve cai.
- App All-in-One (Cai Dat Tat Ca) khong co trong danh sach nay vi file cua no lon (chua adb ARM64); no duoc cap nhat bang cach tai APK moi tu Muse, roi nut "Cap nhat tat ca tu GitHub" trong no se cap nhat 4 app tren tu day.
