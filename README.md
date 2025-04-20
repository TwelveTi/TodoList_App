ID: 221100883.

NAME: Phan Dinh Trung.

# React Native ToDo App

Một ứng dụng quản lý công việc đơn giản được xây dựng bằng React Native và Expo, cho phép người dùng thêm, sắp xếp và xóa công việc cùng với ngày đến hạn.

---

## Tính năng chính

- Thêm công việc mới với tên và ngày đến hạn.  
- Xóa công việc bằng một nút bấm.  
- Chọn ngày đến hạn bằng DatePicker thân thiện.  
- Sắp xếp danh sách theo:
  - Tên công việc  
  - Ngày đến hạn  

---

## Mục tiêu học tập

Ứng dụng giúp sinh viên thực hành các kỹ năng quan trọng trong phát triển giao diện người dùng với React Native.

### Input Controls

- TextInput: nhập tên công việc  
- Button hoặc TouchableOpacity: thêm công việc  

Giúp sinh viên hiểu cách xử lý dữ liệu nhập từ người dùng.

### Menus

- Sử dụng react-native-material-menu để hiển thị menu lựa chọn  
- Menu bao gồm: Sort by name, Sort by date  

Giúp sinh viên thực hành tạo menu và xử lý lựa chọn.

### Pickers

- Sử dụng @react-native-community/datetimepicker để chọn ngày đến hạn  

Giúp sinh viên làm quen với các thành phần chọn ngày trong ứng dụng thực tế.

---

## Công nghệ sử dụng

- React Native (Expo)  
- TypeScript  
- React Navigation  
- DateTimePicker  
- Material Menu  
- AntDesign Icons  

---

## Cài đặt

### Bước 1: Cài đặt Java

Yêu cầu Java 17 trở lên.  
Tải tại: https://www.oracle.com/in/java/technologies/downloads/archive/  
Sau khi cài, cấu hình JAVA_HOME.

macOS: xem hướng dẫn qua video hoặc tài liệu Baeldung.

Kiểm tra bằng lệnh:

```bash
java -version
```

---

### Bước 2: Cài đặt Android Studio

Làm theo video #15 trong khoá học.

---

### Bước 3: Cấu hình biến môi trường ANDROID_HOME

**Windows:**  
Thêm biến môi trường:

```env
ANDROID_HOME=C:\Users\Username\AppData\Local\Android\Sdk
```

Thêm vào PATH:

```
C:\Users\Username\AppData\Local\Android\Sdk\platform-tools  
C:\Users\Username\AppData\Local\Android\Sdk\emulator
```

**macOS:**  
Dùng VPN nếu không truy cập được hướng dẫn.  
Xem thêm tại: https://reactnative.dev/docs/environment-setup

Kiểm tra cấu hình:

```bash
adb --version
```

Nếu hiển thị phiên bản `adb`, bạn đã cài đặt thành công.

# Clone dự án
git clone <your-repo-url>

# Cài đặt thư viện
npm install --legacy-peer-deps

# Chạy dự án
npm start
```
