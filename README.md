# Android_TH_Bai3_1

Đây là một ứng dụng Android cơ bản minh họa cách chuyển đổi giữa **MainActivity (Đăng ký - Register)** và **LoginActivity (Đăng nhập - Login)** bằng **Intent**.  

> **Lưu ý:** Ứng dụng **chưa hỗ trợ** chức năng "Quên mật khẩu" (Forgot Password).

## 🛠 Chức năng chính

- **Đăng ký (Register)**: Người dùng có thể nhập thông tin đăng ký và chuyển đến màn hình đăng nhập.
- **Đăng nhập (Login)**: Nhập thông tin đăng nhập và xác thực tài khoản.
- **Chuyển đổi giữa các màn hình**: Sử dụng `Intent` để di chuyển giữa **MainActivity** và **LoginActivity**.

## 📂 Cấu trúc dự án

```
📦 Android_TH_Bai3_1
 ┣ 📂 app
 ┃ ┣ 📂 src/main/java/com/example/android_th_bai3_1
 ┃ ┃ ┣ 📜 MainActivity.java   # Màn hình đăng ký
 ┃ ┃ ┣ 📜 LoginActivity.java  # Màn hình đăng nhập
 ┃ ┣ 📂 src/main/res/layout
 ┃ ┃ ┣ 📜 activity_main.xml   # Giao diện đăng ký
 ┃ ┃ ┣ 📜 activity_login.xml  # Giao diện đăng nhập
 ┣ 📜 build.gradle.kts
 ┣ 📜 settings.gradle.kts
```

## 🚀 Cách chạy ứng dụng

1. **Clone** repository này về máy của bạn:

   ```bash
   git clone https://github.com/tkim-061203/Android_TH_Bai3_1.git
   ```

2. **Mở dự án bằng Android Studio**.

3. **Xây dựng và chạy ứng dụng** trên máy ảo (AVD) hoặc điện thoại thật:

   - Nhấn **Shift + F10** hoặc bấm vào **Run ▶**.

## 🔄 Cách hoạt động

1. Khi ứng dụng chạy, màn hình chính (`MainActivity`) sẽ hiển thị giao diện đăng ký.
2. Sau khi đăng ký, ứng dụng sẽ sử dụng `Intent` để chuyển sang màn hình đăng nhập (`LoginActivity`).
3. Màn hình đăng nhập có thể nhận dữ liệu từ màn hình đăng ký (nếu có lưu lại).
4. Chưa có tính năng **"Quên mật khẩu" (Forgot Password)**.

## 🏗 Công nghệ sử dụng

- **Ngôn ngữ:** Java
- **Framework:** Android SDK
- **Intent**: Dùng để chuyển đổi giữa các Activity
