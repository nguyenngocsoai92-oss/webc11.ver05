# VBNA Chapter 11 — V7 đang hoàn thiện

Ngày rà soát: 24/09/2026. **Chưa đủ điều kiện go-live.** Không sử dụng dữ liệu cá nhân thật trong giao diện HTML thử nghiệm.

Nguồn quyết định: file Excel `VBNA_C11_V6_Ra_soat_va_Chot_Final.xlsx` anh đã chỉnh và các xác nhận trong cuộc trò chuyện. Bản gốc Excel và website-v6 được giữ nguyên.

## Đã thực hiện

- Đối chiếu 230 ô thay đổi; giữ toàn văn nguồn tổng quan VBNA trong giao diện.
- Trang chủ có hai nút đăng nhập/khách mời cạnh nhau, ba nhà sáng lập, bản đồ ở menu chính và chân trang theo bố cục mới. Chưa có đủ ảnh, tên và địa chỉ chính thức.
- Sửa nền tảng tính doanh thu theo thời điểm xác nhận, lọc hai bên là hội viên C11, phân biệt buổi họp chính, loại điểm danh trùng, công nợ đã duyệt theo ngày chốt. Báo cáo thêm phạm vi tính; tỷ lệ là số có định dạng phần trăm khi xuất Excel.
- Bổ sung máy chủ Django: tài khoản, quyền từng hạng mục có thể bỏ tích quyền mặc định, thông báo theo đối tượng, tệp riêng tư, hàng đợi email và nhật ký.
- Chức năng sinh nhật cho hội viên và khách mời: kiểm tra ngày sinh, tránh gửi lặp trong năm, AI soạn theo nhóm tuổi, không đoán năm sinh còn thiếu. Thiếu cấu hình AI/Gmail sẽ không báo gửi thành công.

## Phạm vi chưa hoàn tất

Giao diện HTML vẫn là bản thử dùng dữ liệu trình duyệt. Máy chủ mới chưa nối toàn bộ các trang; chưa có dữ liệu chung xuyên thiết bị cho toàn hệ thống. Chưa chuyển các nghiệp vụ cơ hội, tài chính, báo cáo và Lucky Draw lên máy chủ. Chưa nghiệm thu toàn bộ 158 đầu mục. Vì vậy không đưa thư mục này lên hosting như một website hoàn chỉnh.

Xem [báo cáo bàn giao](V7_Ra_soat_va_dieu_kien_golive.md), [230 điều chỉnh](V7_230_dieu_chinh.md) và [hướng dẫn máy chủ](server/README.md).

Các tài liệu V6 còn trong thư mục là tài liệu lịch sử, không chứng nhận trạng thái V7. Gói bàn giao V7 loại các tài liệu lịch sử, dữ liệu thử, môi trường cài đặt và thông tin bí mật.
