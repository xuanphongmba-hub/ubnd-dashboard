# Bảng theo dõi nhiệm vụ Lãnh đạo UBND tỉnh Đắk Lắk

Dashboard theo dõi tiến độ chuẩn bị các nội dung trình **Kỳ họp thứ Hai, HĐND tỉnh khóa XI (nhiệm kỳ 2026–2030)**, phân công cho Chủ tịch và các Phó Chủ tịch UBND tỉnh.

## Tổng quan số liệu (cập nhật 11h00 ngày 08/6/2026)

- **29** nội dung trình kỳ họp (trong đó **14 Nghị quyết** theo danh mục chi tiết).
- **19** nội dung đã trình UBND tỉnh.
- UBND tỉnh có Công văn số 8035/UBND-TH (05/6/2026) yêu cầu các sở, ngành trình UBND tỉnh **trước ngày 08/6/2026**.
- Hạn hoàn thành thủ tục, ký gửi HĐND tỉnh: **chậm nhất 17/6/2026** (gửi 35 bộ hồ sơ).

Phân bổ theo lãnh đạo:

| Mục | Đồng chí lãnh đạo | Chức danh | Số nội dung | Đã trình |
|----|-------------------|-----------|:-----------:|:--------:|
| I | Chủ tịch UBND tỉnh | Chủ tịch | 3 | 2 |
| II | Hồ Thị Nguyên Thảo | Phó Chủ tịch Thường trực | 5 | 3 |
| III | Nguyễn Thiên Văn | Phó Chủ tịch | 10 | 9 |
| IV | Trương Công Thái | Phó Chủ tịch | 7 | 1 |
| V | Đào Mỹ | Phó Chủ tịch | 4 | 4 |

## Tính năng

- Thẻ chỉ số tổng quan (KPI) và đồng hồ đếm ngày còn lại đến hạn.
- Biểu đồ tiến độ tổng thể và thanh tiến độ riêng cho từng đồng chí lãnh đạo.
- **Tra cứu theo từng lãnh đạo**: bấm vào tên để lọc toàn bộ dashboard theo đồng chí đó.
- Tìm kiếm; lọc theo tiến độ (Đã trình / Chưa trình) và theo loại (Nghị quyết / Báo cáo).
- Bảng chi tiết đầy đủ 7 cột, hỗ trợ in ấn.

## Cách sử dụng

Mở trực tiếp `index.html` bằng trình duyệt — không cần cài đặt gì. Toàn bộ là một file HTML tĩnh, chạy được cả khi ngoại tuyến (chỉ cần mạng để tải phông chữ).

## Cập nhật dữ liệu

Dữ liệu nằm trong mảng `TASKS` ở phần `<script>` của file `index.html`. Mỗi nội dung gồm các trường:
`l` (mã lãnh đạo), `type` (`NQ`/`BC`), `status` (`submitted`/`pending`), `content`, `org`, `vp`, `div`, `note`.
Mọi con số thống kê được tính tự động từ mảng này.

---
*Nguồn: Văn phòng UBND tỉnh — cập nhật 11h00 ngày 08/6/2026. Bảng phục vụ công tác chỉ đạo, điều hành.*
