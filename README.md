# Model-Map-NguocDong — Bản Đồ Quy Hoạch 3D Chương 1 (Game "Xóm Trọ" / Ngược Dòng)

Website giả lập quy hoạch bản đồ 3D cho **Chương 1** dựa trên tài liệu thiết kế game `game-concept-v0.2.md` (lấy cảm hứng từ *Nobody: The Turnaround*, bối cảnh Cần Thơ — Việt Nam, nhân vật chuẩn: nữ cử nhân **An** cao `1.65 m`).

## 🚀 Cách mở nhanh
- Mở trực tiếp file `index.html` trên trình duyệt (hoặc chạy `CHAY_WEB_3D.bat` trên Windows).
- Không cần cài đặt server hay thư viện phụ thuộc.

## ✨ Tính năng chính
1. **Quy hoạch trực quan 5 Khu vực & 16 Công trình Chương 1** (Tỉ lệ chuẩn `1 đơn vị = 1 mét`):
   - **Khu A (Tây Bắc)**: Khu Vực Chợ Đêm (giống Bạc Liêu / Đà Lạt) — Cổng chào, Sạp ẩm thực đêm, Sạp đồ si 25K, Bậc thang quảng trường bán vé số.
   - **Khu B (Chính Bắc)**: Khu Nhà Trọ Cần Thơ — Dãy phòng trọ cấp 4 (Phòng số 3 của An có *Tấm bằng Cử nhân trên nóc tủ gỉ sét*), Nhà chủ trọ 2 tầng, Tiệm tạp hóa Cô Tư & Tiệm Photocopy, Vựa ve chai & cột điện tờ rơi vay nóng.
   - **Khu C (Đông Bắc)**: Khu Nhà Nghỉ Ánh Sao (3 tầng) & Khách Sạn Mini Tây Đô (4 tầng).
   - **Khu D (Tây Nam)**: Khu Ăn Uống Giống Hẻm 51 (4 Cụm Quán chữ nhật ngang) — Cơm bình dân 20K & Xe xôi, Lẩu nướng vỉa hè 99K, Trà sữa sinh viên & Cà phê cóc, Quán nhậu đêm & Bàn cá độ/tài xỉu.
   - **Khu E (Đông Nam)**: Khu Các Công Ty Lớn Sầm Uất — Cao ốc văn phòng *Mekong Tower* (5 tầng), Công ty Đa cấp *"Việc nhẹ lương cao"*, Tiệm cầm đồ & Tín dụng 24H, Trung tâm Gia sư & Kế toán *Tương Lai*.
2. **Hệ thống 9 Tuyến Đường & Hẻm Nội Bộ**:
   - Đầy đủ Đại lộ chính ngang, Đường đôi dọc khu Đông, Đường nhánh Chợ Đêm, Phố đi bộ chợ đêm, Hẻm nội bộ xóm trọ trước phòng An, Đường trước Nhà nghỉ/Khách sạn, Lòng Hẻm 51, Phố thương mại nội khu Công ty, và Đường vành đai phía Nam.
3. **Mở rộng Nhà / Đường & Ghi chữ tên ô trực tiếp**:
   - **Nhấp đúp (Double-Click)** vào bất kỳ ô nhà hoặc con đường nào trên 3D để đổi **Chữ Tên Ô** (hiển thị ngay trên nóc nhà và dưới mặt đất).
   - **Thanh Mở Rộng Nhanh (`+2m`, `-2m`, `+1 Tầng`)** và chế độ **`✋ Kéo Ô`** để dịch chuyển vị trí trực tiếp bằng chuột.
   - **Tự động sinh Prompt giao AI vẽ Blender (`bpy`)** chuẩn kích thước `Rộng × Sâu × Cao` mét cho từng ô được chọn.
   - **Thu gọn / Mở rộng toàn màn hình 3D (`🗖`)** chỉ với 1 nút bấm.

## 📁 Cấu trúc thư mục
- `index.html`: Giao diện và Engine kết xuất 3D tương tác.
- `map_data.js`: Dữ liệu tọa độ, kích thước, vai trò cốt truyện Chương 1 của 5 Khu vực, 9 Tuyến đường và 16 Công trình.
- `docs/game-concept-v0.2.md`: Tài liệu ý tưởng cốt truyện & cơ chế game v0.2.
- `docs/quy_hoach_ban_do_chuong_1.md`: Bảng tổng hợp quy hoạch chi tiết.
- `CHAY_WEB_3D.bat`: Script mở nhanh trên Windows.
