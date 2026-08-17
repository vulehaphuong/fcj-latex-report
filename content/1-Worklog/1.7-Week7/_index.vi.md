---
title: "Worklog Tuần 7"
date: 2026-07-13
weight: 7
chapter: false
pre: " <b> 1.7. </b> "

# Các tùy chọn cho bản PDF LaTeX
includeInReport: true     # Đổi thành false nếu muốn ẩn trang này trong bản in PDF
      # Chọn chính xác tên các cột trong bảng Markdown muốn in ra PDF

reportHeadings:           # Chọn chính xác các tiêu đề (Heading) muốn trích xuất ra PDF
  - Mục tiêu tuần 7
  - Các công việc cần triển khai trong tuần này
  - Kết quả đạt được tuần 7
---

Mục tiêu tuần 7:

* Cùng nhóm kiểm thử, chỉnh sửa và cải tiến để hoàn thiện phiên bản cuối cùng của trang web
* Soạn thảo báo cáo.

\noindent Các công việc cần triển khai trong tuần này

\renewcommand{\arraystretch}{1.5} % Tăng khoảng cách trên-dưới (padding dọc)
\setlength{\tabcolsep}{8pt}       % Tăng khoảng cách trái-phải (padding ngang)

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|--|--------------------------------------------------|--------|---------|
| 2 | - Cùng nhóm kiểm thử toàn bộ Chức năng, kiểm tra log và database. \newline - Tập hợp các góp ý về lỗi hiển thị, layout chưa ưng ý, điểm thao tác chưa mượt, một số lỗi về lưu dữ liệu. | 13/07/2026 | 13/07/2026 |  |
| 3 | - Chỉnh sửa frontend theo góp ý của nhóm và re-deploy bản sửa đổi giao diện lên S3 Bucket và CloudFront  | 14/07/2026 | 14/07/2026 |  |
| 4 | - Tìm kiếm và cung cấp các thông số kỹ thuật về giải pháp Frontend React TS cho thành viên phụ trách viết báo cáo kỹ thuật. | 15/07/2026 | 15/07/2026 |  |
| 5 | - Rà soát dữ liệu kỹ thuật của báo cáo. | 16/07/2026 | 16/07/2026 |  |
| 6 | - Viết review 2 buổi sự kiện đã tham gia cho phần Event Participated trong AWS workshop | 17/07/2026 | 17/07/2026 |  |

\noindent Kết quả đạt được tuần 7:

* Sửa đổi hoàn chỉnh các góp ý giao diện từ nhóm và re-deploy thành công bản Frontend hoàn thiện lên S3 và CloudFront.