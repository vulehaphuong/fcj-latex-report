---
title: "Worklog Tuần 6"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF
      # Chọn chính xác tên các cột trong bảng Markdown muốn in ra PDF

reportHeadings:           # Chọn chính xác các tiêu đề (Heading) muốn trích xuất ra PDF
  - Mục tiêu tuần 6
  - Các công việc cần triển khai trong tuần này
  - Kết quả đạt được tuần 6
---

Mục tiêu tuần 6:

* Nghiên cứu cơ chế xác thực AWS Cognito.
* Cấu hình các biến môi trường, đồng bộ dữ liệu thực tế và push bản build lên AWS Organization. 

\noindent Các công việc cần triển khai trong tuần này


| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|--|------------------------------------------------|--------|-----------|
| 2 | - Tìm hiểu cơ chế quản lý người dùng của Amazon Cognito cùng phương thức bảo mật bằng JWT Tokens: User Pools, Identity Pools, JWT Tokens. \newline - Xin backend và các biến môi trường gồm API URL, cognito region, user id, client id từ nhóm. \newline - Bổ sung thư viện SDK thao tác với AWS Cognito. Tích hợp SDK Cognito vào luồng đăng nhập React, đồng bộ luồng Authentication. | 06/07/2026 | 06/07/2026 |  |
| 3 | - Cập nhật environment file. \newline - Sửa lại code để tích hợp màn hình Login, Sign-in thực tế với dịch vụ AWS Cognito User Pool qua SDK. | 07/07/2026 | 07/07/2026 |  |
| 4 | - Kết nối RESTful API, tiến hành đồng bộ dữ liệu các màn hình với Backend APIs. \newline - Loại bỏ dữ liệu Mock Data, thay thế bằng cách gọi API thực tế tới địa chỉ VITE_API_URL. \newline - Kết nối API thực tế cho trang Dashboard, Tasks, Kanban Board, Calendar, Timeline, Breakdown Statistics, Saved Filters, Custom Workflow và Import/Export. | 08/07/2026 | 10/07/2026 |  |
| 5 | - Tìm hiểu thêm về ánh xạ dữ liệu. \newline - Tiếp tục tinh chỉnh code frontend cho khớp với dữ liệu backend. \newline - Bổ sung phần xử lý các trạng thái: chờ tải dữ liệu, thông báo thành công, thông báo lỗi. | 09/07/2026 | 09/07/2026 |  |
| 6 | - Đẩy web tĩnh lên Amazon S3 thuộc bằng tài khoản IAM được cung , tạo Invalidation trên CloudFront Distribution để cập nhật giao diện. \newline - Thực hiện kiểm thử khi tích hợp toàn bộ luồng dữ liệu hai chiều giữa frontend và backend. Tạo tài khoản tạo mới, chỉnh sửa, xóa công việc, lưu bộ lọc, thêm workflow, xuất file JSON/CSV thực tế qua API. \newline - Sửa chữa các lỗi bất đồng bộ dữ liệu và khắc phục lỗi chặn chia sẻ tài nguyên CORS. | 10/07/2026 | 12/07/2026 |  |

\noindent Kết quả đạt được tuần 6:

* Đồng bộ các trang frontend với RESTful APIs và xác thực AWS Cognito cho Authentication.
* Triển khai frontend lên môi trường AWS Organization.