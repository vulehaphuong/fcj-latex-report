---
title: "Worklog Tuần 5"
date: 2026-06-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF
      # Chọn chính xác tên các cột trong bảng Markdown muốn in ra PDF

reportHeadings:           # Chọn chính xác các tiêu đề (Heading) muốn trích xuất ra PDF
  - Mục tiêu tuần 5
  - Các công việc cần triển khai trong tuần này:
  - Kết quả đạt được tuần 5:
---

Mục tiêu tuần 5: Lập trình phần frontend cho các trang còn lại trong tuần này và kiểm thử luồng người dùng và logic xử lý.

Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|--|--------------------------------------------------|--------|--------|
| 2 | - Nghiên cứu các hiện thực cơ chế tạo 1 canva trống có khả năng kéo dài vô tận bằng đồ thị. Cách thực hiện cơ chế kéo thả ảnh từ nơi khác vào và lưu ảnh lại. \newline - Thực hiện trang Whiteboard với chức năng trên, thêm chức năng tự động lưu Digital Inking của người dùng.| 29/06/2026 | 29/06/2026 |  |
| 3 | - Viết hàm lấy và hiển thị dữ liệu dưới dạng biểu đồ tròn, thêm bộ lọc hiển thị thống kê theo cột(thường là các trạng thái cần làm/đang làm/đã làm), theo thời gian hoặc phân loại. \newline - Lập trình ô tìm kiếm theo tên task, bộ lọc task theo các thuộc tính. | 30/06/2026 | 30/06/2026 |  |
| 4 | - Lập trình giao diện tạo bộ lọc tùy chỉnh bao gồm tập hợp nhiều điều kiện khác nhau. \newline - Thêm phần hiển thị các bộ lọc đã lưu, tính năng áp dụng bộ lọc nhanh. | 01/07/2026 | 01/07/2026 |  |
| 5 | - Sửa lại code, bỏ trang Whiteboard. \newline - Lập trình trang Import and Export gọi api (tạm để trống) xử lý việc chuyển đổi và xuất dữ liệu dưới dạng file Json và Csv và ngược lại. | 02/07/2026 | 02/07/2026 |  |
| 6 | - Tạo bộ dữ liệu mẫu - Mock Data gồm danh sách công việc, trạng thái, danh mục, cấu hình quản lý trạng thái client. \newline - Đóng gói frontend ra tập tĩnh. Tải bản build tĩnh lên Amazon S3 cá nhân, kết nối CloudFront Distribution, đưa giao diện lên môi trường Cloud. \newline - Kiểm thử giao diện người dùng, kiểm tra tài nguyên, tính năng các nút bấm, luồng chuyển trang và ghi lại các lỗi phát sinh. \newline - Fix bug | 03/07/2026 | 06/07/2026 |  |

Kết quả đạt được tuần 5:

* Hoàn thiện tất cả các chức năng chính của frontend.
* Tạo bộ dữ liệu Mock Data mẫu và triển khai kiểm thử giao diện trên tài khoản AWS cá nhân.
* Sửa các lỗi phát sinh trong quá trình kiểm thử.