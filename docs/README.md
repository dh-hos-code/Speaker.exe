<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 1.24.1021.1 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FSpeakerexe%2F12410211-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FSpeakerexe%2F12410211-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FSpeakerexe%2F12410211-NasDHSolutions.json)
- ✨: Yêu cầu - Hỗ trợ thay đổi cách gọi bệnh nhân vào quầy tiếp nhận và vào phòng khám
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/707
## [v.1.24.1021.0]()
push test
## [v.1.24.0926.0]()
- ✨: Mở chức năng gọi bệnh tại phòng khám - BV Sa Đéc
![](https://i.imgur.com/PGcWAY4.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660
## [v.1.24.0924.1]()
- 🐛: Cấu hình loa phát 91 để gọi chung cho 23 phân khu 91,92 BV Thốt Nốt (push lại)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649
## [v.1.24.0924.0]()
- 🐛: Cấu hình loa phát 91 để gọi chung cho 23 phân khu 91,92 BV Thốt Nốt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648
## [v.1.24.0923.0]()
- 🐛: Cấu hình loa phát 91 để gọi chung cho 3 phân khu 91,92,93 BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648
## [v.1.24.0920.0]()
- ✨: Mở chức năng gọi bệnh cho BV BV Thốt Nốt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649
## [v.1.24.0919.0]()
- ✨: Mở chức năng gọi bệnh cho BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648
## [v.1.24.0606.4]()
- 🐛: fix lỗi không gọi được khi cấu hình theo loa phát
- 📕: Chỉnh sửa SQL lấy thông tin từ bảng current.goibenh

## [v.1.24.0606.3]()
- 🐛: fix lỗi không gọi được khi cấu hình theo loa phát
- 📕: Chỉnh sửa SQL lấy thông tin từ bảng current.goibenh
    sql ban đầu  :  sql = sql + " module in (" + this.sModule + ") ";
    sql thay đổi :	 sql = sql + " module in ('" + this.sModule + "') ";

## [v.1.24.0606.2]()
- 🐛: fix lỗi không gọi được khi cấu hình theo loa phát
- 📕: Chỉnh sửa SQL lấy thông tin từ bảng current.goibenh
   * sql ban đầu  :  sql = sql + " module in (" + this.sModule + ") ";
   * sql thay đổi :	 sql = sql + " module in ('" + this.sModule + "') ";

## [v.1.24.0606.1]()
- 🐛: fix lỗi không gọi được khi cấu hình theo loa phát
- 📕: Chỉnh sửa SQL lấy thông tin từ bảng current.goibenh
   * sql ban đầu  :  sql = sql + " module in (" + this.sModule + ") ";
   * sql thay đổi :	 sql = sql + " module in ('" + this.sModule + "') ";

## [v.1.24.0606.0]()
- 🐛: fix lỗi không gọi được khi cấu hình theo loa phát
- 📕: Chỉnh sửa SQL lấy thông tin từ bảng current.goibenh
   * sql ban đầu  :  sql = sql + " module in (" + this.sModule + ") ";
   * sql thay đổi :	 sql = sql + " module in ('" + this.sModule + "') ";

## [v.1.24.0605.0]()
- 🐛: Update thời gian đọc đối với gọi bệnh nhân ưu tiên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0604.0]()
- ✨: Cập nhật chức năng gọi bệnh bằng dll DH.GoiBenh.dll
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0526.0]()
- ✨: Thêm chức năng gọi bệnh cho Trà Cú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368