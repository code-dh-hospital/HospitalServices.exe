<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1011.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalServicesexe%2F32410110-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalServicesexe%2F32410110-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalServicesexe%2F32410110-NasDHSolutions.json)
- 🐛: **💼**: **_Lỗi - Services gửi checkin lỗi không lấy được mã  DV_**
- ✨: Thực hiện theo mô tả [XML130/Hau-gui-checkin-xml.md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/Hau-gui-checkin-xml.md)
- 🐛: Chỉnh lỗi khi gửi thành công chỉ set checkin_cls = 1, checkin_thuoc=1, checkin_vtyt=1 (nếu có)
- 🐛: Kiểm tra nếu MA_DICH_VU, MA_VAT_TU, MA_THUOC có mới thực hiện gửi. ***Tránh lỗi*** ![](https://i.imgur.com/q1385Ty.png)
- ✨: ***Xử lý ghi nhận lỗi khi gửi API, nếu hồ sơ, checkin gửi lỗi quá 20 lần, sẽ không gửi hồ sơ, checkin này nữa.***
- ✨: ***Lưu ý: Cập nhật cấu trúc*** ![](https://i.imgur.com/0QT8JzM.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/104
## [v.3.24.1006.0]()
- 🐛: **💼**: **_Hỗ trợ khách hàng - Services Gửi hồ sơ_**
- 🐛: Chỉnh lỗi không gửi được hồ sơ ![](https://i.imgur.com/zY0FnCO.png) ![](https://i.imgur.com/yt5eWwh.png) ![](https://i.imgur.com/x3Bgyaf.png)
- ✨: ***Thay đổi mỗi lần gửi dữ liệu sẽ lấy 100 hồ sơ hoặc checkin để thực hiện***
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/120
## [v.3.24.1004.0]()
- 🐛: **💼**: **_Lỗi - Gửi tự động những BN tháng cũ_**
- 🐛: Chỉnh lỗi lấy sai ngày checkin và ngày thanh toán để gửi hồ sơ ![](https://i.imgur.com/gQv1VUc.png)
- ☑: https://github.com/dh-hos/dhg.hospitalservices/issues/22
## [v.3.24.0921.0]()
- 🐛: **💼**: **_Hỗ trợ khách hàng - Services gửi hồ sơ tới 19 hồ sơ là không gửi tiếp_**
- 🐛:Chỉnh lỗi lấy hồ sơ để gửi dữ liệu ![](https://i.imgur.com/D0OAJ9a.gif)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/102
## [v.3.24.0917.0]()
- ✨: **💼**: **_Yêu cầu - Thực hiện gửi bảng Check in tự động._**
- ✨: ***Chức năng cấu hình gửi tự động theo loại checkin hoặc hồ sơ*** ![](https://i.imgur.com/cAuOKkF.png)
- ✨: ***Bỏ các chức năng gửi hồ sơ theo 4210, thay bằng chức năng gửi CheckIn và Hồ sơ 4750***![](https://i.imgur.com/if3yoev.png)
- ✨: ***Video kiểm thử việc gửi dữ liệu lên cổng đào tạo*** [Video](https://www.youtube.com/watch?v=KBXGYXtGaG0)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/587
## [v.3.24.0916.0]()
- ✨: **💼**: **_Yêu cầu - Thực hiện gửi bảng Check in tự động._**
- ✨: ***Chức năng cấu hình gửi tự động theo loại checkin hoặc hồ sơ*** ![](https://i.imgur.com/cAuOKkF.png)
- ✨: ***Bỏ các chức năng gửi hồ sơ theo 4210, thay bằng chức năng gửi CheckIn và Hồ sơ 4750***![](https://i.imgur.com/if3yoev.png)
- ✨: ***Video kiểm thử việc gửi dữ liệu lên cổng đào tạo*** [Video](https://www.youtube.com/watch?v=KBXGYXtGaG0)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/587
## [v.3.24.0617.0]()
- 🐛: Fix Yêu cầu - Xác định mã lý do vào viện trên bảng kê 6556 và XML 4210 ( trường hợp bệnh nhân có giấy xác nhận cư trú) ![](https://i.imgur.com/lJrTENa.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389