ID: 221100883.

NAME: Phan Dinh Trung.

# 📅 React Native ToDo App

Một ứng dụng quản lý công việc đơn giản được xây dựng bằng **React Native** và **Expo**, giúp bạn thêm, sắp xếp và xoá các công việc kèm ngày đến hạn.

---

## 🚀 Tính năng chính

- ✅ **Thêm công việc mới** với tên và ngày đến hạn.
- 🗑️ **Xoá công việc** bằng một nút bấm đơn giản.
- 📅 **Chọn ngày đến hạn** bằng DatePicker thân thiện.
- 📋 **Sắp xếp danh sách** theo:
  - 🔠 Tên công việc
  - 📆 Ngày đến hạn

---

## 🧠 Mục tiêu học tập

Ứng dụng này giúp sinh viên nắm vững các kiến thức sau:

### 📌 Input Controls

- **`TextInput`**: Dùng để nhập tên công việc.
- **`Button`** / `TouchableOpacity`: Dùng để thêm công việc mới khi nhấn.

➡️ Giúp sinh viên hiểu cách xử lý **input người dùng** trong React Native.

---

### 📌 Menus

- Dùng **`react-native-material-menu`** để hiển thị menu tùy chọn.
- Menu gồm các chức năng:
  - **Sort by name**
  - **Sort by date**

➡️ Sinh viên sẽ thực hành **tạo menu** và xử lý **sự kiện lựa chọn**.

---

### 📌 Pickers

- Sử dụng **`@react-native-community/datetimepicker`** để chọn ngày đến hạn cho mỗi công việc.

➡️ Cho phép người học làm quen với các **thành phần chọn ngày** phổ biến trong ứng dụng thực tế.

---

## 🏗️ Công nghệ sử dụng

- **React Native** (Expo)
- **TypeScript**
- **React Navigation**
- **DateTimePicker**
- **Material Menu**
- **AntDesign Icons**

---

## 📦 Cài đặt

🛠 Cấu hình môi trường phát triển
✅ Bước 1: Cài đặt môi trường Java
Yêu cầu Java 17 trở lên.

Tải Java tại:
👉 https://www.oracle.com/in/java/technologies/downloads/archive/

Sau khi cài xong, cần cấu hình JAVA_HOME.

Với macOS:
Hướng dẫn chi tiết:
🔗 Video
🔗 Baeldung Guide

Kiểm tra cài đặt:

bash
Copy
Edit
java -version

✅ Bước 2: Cài đặt Android Studio
Đã được hướng dẫn trong video #15 của khoá học.

✅ Bước 3: Cấu hình biến môi trường ANDROID_HOME
Với Windows:
env
Copy
Edit
ANDROID_HOME=C:\Users\Username\AppData\Local\Android\Sdk
Cập nhật Path:

makefile
Copy
Edit
C:\Users\Username\AppData\Local\Android\Sdk\platform-tools  
C:\Users\Username\AppData\Local\Android\Sdk\emulator
Với macOS:
Dùng VPN nếu không truy cập được tài liệu hướng dẫn.

Có thể tham khảo: https://reactnative.dev/docs/environment-setup

Kiểm tra cấu hình:
bash
Copy
Edit
adb --version
Nếu hiển thị thông tin phiên bản adb, bạn đã cấu hình thành công.

```bash
# Clone dự án
git clone <your-repo-url>

# Cài đặt thư viện
npm install --legacy-peer-deps

# Chạy dự án
npm start
```
