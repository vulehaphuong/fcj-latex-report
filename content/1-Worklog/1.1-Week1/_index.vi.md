---
title: "Worklog Tuần 1"
date: 2026-06-03
weight: 1
chapter: false
pre: " <b> 1.1. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF

reportType: worklog       # Kích hoạt script tối ưu bảng cho PDF

reportTableColumns:       # Chọn các cột trong bảng Markdown muốn in ra PDF
  - Thứ
  - Công việc
  - Ngày bắt đầu
  - Ngày hoàn thành

reportHeadings:           # Chọn các tiêu đề muốn trích xuất ra PDF
  - Mục tiêu tuần 1
  - Các công việc cần triển khai trong tuần này
  - Kết quả đạt được tuần 1
---

Mục tiêu tuần 1:

* Kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Tìm hiểu, nắm được các nội quy, quy định của doanh nghiệp trogn quá trình thực tập.
* Hiểu các dịch vụ AWS cơ bản, cách sử dụng Console & CLI.

Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 4 | - Làm quen với các thành viên và admin FCAJ <br> - Đọc và lưu ý các nội quy, quy định tại đơn vị thực tập <br> - Tìm hiểu về địa điểm thực tập <br> - Tạo tài khoản FCAJ Portal, cập nhật thông tin cá nhân và đăng ký lịch lên văn phòng hàng tuần. | 03/06/2026 | 03/06/2026 | <https://hcm-rules.awsfcaj.com/> |
| 5 | - Tìm hiểu AWS Cloud và các loại dịch vụ cơ bản: <br>&emsp; + Compute - E2C/Lambda(Serverless) <br>&emsp; + Storage - S3 <br>&emsp; + Networking - VPC/CloudFront <br>&emsp; + Database - DynamoDB <br>&emsp; + IAM | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/> |
| 6 | - Xem xét các chính sách, điều khoản & lưu ý khi sử dụng AWS. <br> - Tạo tài khoản AWS Free Tier <br> - Tìm hiểu AWS Console & AWS CLI <br> - **Thực hành:** <br>&emsp; + Thiết lập thiết lập ngân sách, gửi cảnh báo với dịch vụ AWS Budgets để kiểm soát chi phí.  <br>&emsp; + Cài đặt & cấu hình AWS CLI sử dụng các lệnh căn bản | /06/2026 | 05/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/> |

Kết quả đạt được tuần 1:

* Nắm được tổng quan về AWS và các nhóm dịch vụ nền tảng mà nó cung cấp (Compute, Storage, Networking, Database, Security & Management).
* Đã tạo thành công tài khoản AWS Free Tier và các cài đặt cần  cùng hạn mức cảnh báo chi phí.
* Làm quen với thao tác tìm kiếm dịch vụ, quản lý tài nguyên trên giao diện AWS Management Console.
* Cài đặt và cấu hình thành công AWS CLI trên máy cá nhân. (Cấu hình Access Key, Secret Key, Default Region).
* Thực hành,biết  thao tác cơ bản bằng CLI: tạo profile mặc định cũng như quản lý và tạo thêm các profile khác, kiểm tra cấu hình tài khoản, truy vấn danh sách Region.