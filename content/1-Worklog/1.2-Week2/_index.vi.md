---
title: "Worklog Tuần 2"
date: 2026-06-08
weight: 2
chapter: false
pre: " <b> 1.2. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF
      # Chọn chính xác tên các cột trong bảng Markdown muốn in ra PDF

reportHeadings:           # Chọn chính xác các tiêu đề (Heading) muốn trích xuất ra PDF
  - Mục tiêu tuần 2
  - Các công việc cần triển khai trong tuần này
  - Kết quả đạt được tuần 2
---

Mục tiêu tuần 2:

* Thực hành các bài hướng dẫn, workshop AWS căn bản theo lộ trình trang The First Cloud Journey.
* Họp nhóm thống nhất đề tài Web Cloud và phân chia công việc.
* Nắm vững cơ chế quản lý truy cập và bảo mật tài nguyên AWS với IAM.
* Khai phá hạ tầng mạng riêng ảo Amazon VPC và các thành phần cốt lõi.

\noindent Các công việc cần triển khai trong tuần này

\renewcommand{\arraystretch}{1.5} % Tăng khoảng cách trên-dưới (padding dọc)
\setlength{\tabcolsep}{8pt}       % Tăng khoảng cách trái-phải (padding ngang)

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| --- | --- | --- | --- |
| 2 | - Tìm hiểu chủ đề đầu tiên "Khám phá dịch vụ AWS" \newline - Thực hành: tạo IAM User, phân quyền cho từng tài khoản theo role | 08/06/2026 | 08/06/2026 |
| 3 | - Tìm hiểu tổng quan Amazon VPC, Subnets, EC2 Instance, SSH connection, EBS volume. \newline - Thực hành: \newline \hspace*{1em} + Dựa theo hướng dẫn, tạo máy chủ E2C, NAT Gateway <br>&emsp;  + cấu hình Site-to-Site <br>&emsp;  + ... <br>&emsp;  + Dọn dẹp tài nguyên sau khi thực hành. | 09/06/2026 | 09/06/2026 |
| 4 | - Ghép nhóm, thống nhất đề tài lựa chọn là "Xây dựng và phát triển ứng dụng Web Quản lý công việc trên nền tảng Cloud" và định hướng kiến trúc công nghệ. \newline - Phân chia nhiệm vụ | 10/06/2026 | 10/06/2026 |
| 5 | - Nghiên cứu các loại máy chủ EC2, hình ảnh AMI, đĩa cứng EBS, User Data và Meta Data. \newline - Thực hành: \newline \hspace*{1em} + Dựa theo hướng dẫn hởi tạo Key Pair bảo mật cho kết nối SSH <br>&emsp;  + Viết script User Data tự động cài đặt Web Server Nginx trên máy chủ EC2 | 11/06/2026 | 11/06/2026 |
| 6 | - Tìm hiểu và thực hành công cụ lập trình AWS Cloud9 cùng VS Code AWS Toolkit. \newline - Cấu hình đĩa lưu trữ cho máy chủ EC2 phục vụ lập trình trên Cloud. | 12/06/2026 | 12/06/2026 |

\noindent Kết quả đạt được tuần 2:

* Học hiểu kiến thức về mạng ảo, cách khởi tạo và quản lý máy chủ EC2.
* Thành lập nhóm, chốt đề tài và xác định công việc.
* Học được cách sử dụng các công cụ Cloud9 và AWS Toolkit.