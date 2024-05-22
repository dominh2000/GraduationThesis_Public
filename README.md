<h1 align="center">Đồ án tốt nghiệp - Graduation Thesis</h1>

<p align="center">
    <img src="https://custom-icon-badges.demolab.com/badge/material%20you-EA0202?style=for-the-badge&logoColor=white&logo=material-you" alt="material_you">
    <img src="https://img.shields.io/badge/Api%2021+-gray?logo=android&logoColor=white&style=for-the-badge" alt="min_api_21">
    <img src="https://img.shields.io/badge/Api%2023+-blue?logo=android&logoColor=white&style=for-the-badge" alt="min_api_23">
    <img src="https://img.shields.io/badge/Kotlin-a503fc?logo=kotlin&logoColor=white&style=for-the-badge" alt="kotlin">
    <img src="https://img.shields.io/badge/Jetpack%20Compose-03C54F?logo=jetpackcompose&logoColor=white&style=for-the-badge" alt="jetpack_compose">
    <img src="https://img.shields.io/badge/Firebase-FFAA00?logo=firebase&logoColor=white&style=for-the-badge" alt="firebase">
</p>

<div align="center">

[<img src="https://play.google.com/intl/vi/badges/static/images/badges/vi_badge_web_generic.png"
alt='Get it on Google Play'
height="80">](https://play.google.com/store/apps/details?id=minhtd.projects.englishrevision.app)

</div>

* Đề tài: Xây dựng ứng dụng Android ôn thi tuyển sinh lớp 10 Hà Nội môn tiếng Anh.
* Sinh viên: Trần Đỗ Minh.
* Lớp: D18CNPM2 PTIT.
* Bảo vệ ngày: 11 tháng 1 năm 2023.
* Phiên bản [1.0](https://github.com/dominh2000/GraduationThesis_Public/releases/tag/v1.0) là phiên bản dùng để bảo vệ
  trước hội đồng chấm Đồ án tốt nghiệp.
* Các phiên bản sau 1.0 là các bản nâng cấp, bổ sung chức năng và sửa lỗi.

## Các chức năng của ứng dụng

1. Đăng ký, đăng nhập, đăng xuất, quên mật khẩu, đổi mật khẩu.
2. Luyện tập theo các dạng của đề thi.
3. Luyện đề thi thử.
4. Xem lịch sử kết quả ôn luyện.
5. Thống kê kết quả ôn luyện.
6. Thiết lập nhắc nhở luyện tập.
7. Theo dõi kết nối Internet của thiết bị và hiển thị thông báo khi có thay đổi.
8. Tùy chọn Dynamic Theming (với Android 12+) và chế độ tối.
9. Tùy chọn tối ưu mức sử dụng pin với Android 6+.
10. Xem thông tin chi tiết của ứng dụng.
11. Widget ở màn hình nền.
12. Xóa dữ liệu người dùng (tài khoản & lịch sử luyện tập).

## Tải xuống

Click vào huy hiệu "Tải trên Google Play" ở đầu trang để tải xuống phiên bản mới nhất của ứng dụng trên
[Google Play](https://play.google.com/store/apps/developer?id=Minh+Blackice).
Hoặc có thể chuyển đến mục [Releases](https://github.com/dominh2000/GraduationThesis_Public/releases) và tải xuống file
APK
của phiên bản mới nhất.

Từ phiên bản [1.1.3](https://github.com/dominh2000/GraduationThesis_Public/releases/tag/v1.1.3) trở lên, ứng dụng có sự
thay đổi
về không gian tên. Nếu đã cài đặt các phiên bản
từ [1.1.2](https://github.com/dominh2000/GraduationThesis_Public/releases/tag/v1.1.2)
trở xuống của ứng dụng, cần gỡ cài đặt chúng trước khi cài đặt phiên bản mới.

Từ phiên bản [1.2.16](https://github.com/dominh2000/GraduationThesis_Public/releases/tag/v1.2.16) trở lên, ứng dụng chỉ hỗ trợ
các thiết bị chạy tối thiểu là Android 6 (cấp độ API 23).

## Công nghệ và kỹ thuật sử dụng

1. MVVM, Repository pattern, Clean Architecture.
2. [Material 3](https://developer.android.com/reference/kotlin/androidx/compose/material3/package-summary),
   [Jetpack Compose](https://developer.android.com/jetpack/compose),
   [Jetpack Glance](https://developer.android.com/jetpack/compose/glance),
   [UDF pattern](https://developer.android.com/jetpack/compose/architecture#udf).
3. [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
   [Hilt](https://developer.android.com/training/dependency-injection/hilt-android),
   [Navigation Compose](https://developer.android.com/jetpack/compose/navigation),
   [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager),
   [Preferences DataStore](https://developer.android.com/topic/libraries/architecture/datastore).
4. Firebase [Authentication](https://firebase.google.com/docs/auth),
   [Cloud Firestore](https://firebase.google.com/docs/firestore),
   [Crashlytics](https://firebase.google.com/docs/crashlytics),
   [Performance Monitoring](https://firebase.google.com/docs/perf-mon),
   [Google Analytics](https://firebase.google.com/docs/analytics).
5. [Coil Compose](https://coil-kt.github.io/coil/compose/),
   [Lottie Compose](https://github.com/airbnb/lottie/blob/master/android-compose.md),
   [Konfetti](https://github.com/DanielMartinus/Konfetti),
   [LazyColumnScrollbar](https://github.com/nanihadesuka/LazyColumnScrollbar).
