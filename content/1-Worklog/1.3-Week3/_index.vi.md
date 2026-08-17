---
title: "Worklog Tuần 3"
date: 2026-06-15
weight: 3
chapter: false
pre: " <b> 1.3. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF
      # Chọn chính xác tên các cột trong bảng Markdown muốn in ra PDF

reportHeadings:           # Chọn chính xác các tiêu đề (Heading) muốn trích xuất ra PDF
  - Mục tiêu tuần 3
  - Các công việc cần triển khai trong tuần này
  - Kết quả đạt được tuần 3
---

Mục tiêu tuần 3:
* Tìm hiểu giải pháp lưu trữ đối tượng Amazon S3 và mạng phân phối nội dung AWS CloudFront.
* Thực hành triển khai một trang web serverless lên Cloud.

Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu ch vụ lưu trữ đối tượng Amazon S3, tính năng Static Website Hosting, cơ chế phân quyền Bucket Policy và cơ chế chia sẻ tài nguyên CORS. <br> - Tìm hiểu mạng phân phối nội dung Amazon CloudFront, cơ chế bộ nhớ đệm Edge Location và phương thức bảo mật chứng chỉ SSL/TLS. <br> - Thực hành: đưa website tĩnh với chức năng ghi nhận thông tin cơ ban lên lưu trữ Amazon S3, kích hoạt Static Website Hosting, cấu hình Bucket Policy và CORS. <br> - Thiết lập Amazon CloudFront Distribution phân phối trang web an toàn qua giao thức HTTPS và kiểm thử khả năng truy cập qua đường dẫn CloudFront.| 15/06/2026 | 15/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Viết tài liệu phân tích yêu cầu hệ thống cho dự án Quản lý công việc. <br> - Nhóm họp lại, trình bày các bản phân tích yêu cầu hệ thống của mỗi người để thống nhất thành một bản hoản chỉnh cuói cùng | 16/06/2026 | 16/06/2026 |  |
| 4 | - Tham khảo và bắt đầu thiết kế sơ lược cấu trúc, bố cục và vị trí của các thành phần chính ở giao diện mỗi trang cho website. <br> - Lựa chọn tông màu chủ đạo à tạo trước các thành phần chính. | 17/06/2026 | 17/06/2026 |  |
| 5 | - Thiết kế bản mockup các trang sau cho website: <br>&emsp; + Màn hình Sign-in <br>&emsp; + Sidebar <br>&emsp; + User setting <br>&emsp; + Dashboard <br>&emsp; + Tasks (list view) <br>&emsp; + White board | 18/06/2026 | 19/06/2026 |  |
| 6 | - Tiếp tục thiết kế bản mockup các trang sau cho website: <br>&emsp; + Kanban view  <br>&emsp; + Calendar view <br>&emsp; + Timeline view <br>&emsp; + Workflow <br>&emsp; + Statistics Analytics <br> - Thực hiện nối prototype tương tác. | 19/06/2026 | 21/06/2026 |  |

Kết quả đạt được tuần 3:
* Nắm được nguyên lý và thực hành xong quy trình đưa ứng dụng web serverless lên Cloud bằng S3 và CloudFront. Cách chặn/quản lý quyền truy cập trưc tiếp vào S3.
* Phân tích và thống nhất hoàn toàn bộ tài liệu Yêu cầu phần mềm với cả nhóm.
* Hoàn thành bản thiết kế UI/UX trên Figma đầy đủ các màn hình.
