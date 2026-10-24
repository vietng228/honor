# HONOR DEBLOAT

Ứng dụng self ADB cho HONOR bởi [Việt Xiaomi](https://github.com/vietng228).

Website: https://vietng228.github.io/honor/

APK universal và mã nguồn: thư mục `downloads/`.

## Cập nhật OTA

Ứng dụng kiểm tra `https://vietng228.github.io/honor/update.json` mỗi ngày hoặc khi nhấn Kiểm tra cập nhật. Khi có bản mới tương thích, app mở trình duyệt để tải APK; người dùng xác nhận cài đè qua Android.

Để phát hành: tăng versionCode/versionName, build với cùng khóa ký riêng, tải APK và source ZIP vào downloads, cập nhật SHA256SUMS.txt rồi cập nhật update.json sau cùng (versionCode, versionName, minSdk, apkUrl, sha256, notes). Không thay URL update.json. Không đưa khóa ký lên repo.

Mã nguồn và giấy phép thư viện đi kèm trong source ZIP. Ảnh chụp giao diện thật trên Android giả lập. Không phải sản phẩm chính thức của HONOR.
