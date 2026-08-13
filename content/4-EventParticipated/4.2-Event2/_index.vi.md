---
title: "Event 2"
date: 2026-07-11
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch “Automated Security, SLA Monitoring & AWS Certification Roadmap”

### Mục Đích Của Sự Kiện

- Xây dựng lộ trình chiến lược và phương pháp ôn luyện để chinh phục chứng chỉ AWS Certified Cloud Practitioner cho sinh viên và kỹ sư mới bắt đầu.
- Giới thiệu giải pháp tự động hóa an ninh mạng toàn diện cho ứng dụng Web thông qua agent tự hành AWS Security Agent tích hợp AI.
- Hướng dẫn quy trình triển khai kiểm thử xâm nhập tự động, đánh giá mã nguồn và rà soát thiết kế kiến trúc trong môi trường DevSecOps.

### Danh Sách Diễn Giả

- **Ngo Le Tan Huy** - AWS Cloud Specialist
- **Nguyen Huynh Son** - Infrastructure Support Engineer tại Endava, Ex-Infrastructure Reliability Engineer tại SPS, AWS Student Builder Group Leader (HUFLIT)
- **Thinh Nguyen (Nguyen Tuan Thinh)** - DevOps/DevSecOps/Cloud Engineer tại Styl Solutions, First Cloud AI Journey Member

### Nội Dung Nổi Bật

#### Chiến Lược Luyện Thi Chứng Chỉ AWS Cloud Practitioner (AWS CLF-C02)

**Cấu trúc bài thi CLF-C02**: Bài thi gồm 65 câu hỏi trắc nghiệm thực hiện trong 90 phút và được cộng thêm 30 phút đối với thí sinh không nói tiếng Anh bản ngữ, điểm đạt là 700/10001000, chứng chỉ có thời hạn 3 năm. Bài thi không yêu cầu kỹ năng viết code hay cấu hình hệ thống phức tạp mà tập trung vào bức tranh tổng quan về điện toán đám mây. <br>
- **4 Phần kiến thức chính**:
  - *Cloud Concepts (24%)*: Các lợi ích cốt lõi của Cloud, AWS Well-Architected Framework (6 trụ cột) và AWS Cloud Adoption Framework (AWS CAF).
  - *Security and Compliance (30%)*: Mô hình trách nhiệm chia sẻ, quản lý truy cập IAM, bảo mật hạ tầng (Security Groups vs NACLs, AWS Shield/WAF) và dịch vụ tuân thủ AWS Artifact.
  - *Cloud Technology and Services (34%)*: Hạ tầng toàn cầu (Region, AZ, Edge Location) và các nhóm dịch vụ Compute (EC2, Lambda), Storage/Database (S3, EBS, RDS, DynamoDB), Networking (VPC, Route 53).
  - *Billing, Pricing, and Support (12%)*: Các mô hình giá EC2, công cụ quản lý chi phí (AWS Budgets, Cost Explorer) và các gói Support (Basic, Developer, Business, Enterprise).
- **Phương pháp ôn tập hiệu quả**: 
    - Sử dụng tư duy "Map Keyword" (gắn 1-2 từ khóa thực tế cho mỗi dịch vụ, ví dụ: Decouple → SQS, Data monetization → Business Perspective).
    - Tập trung phân tích nguyên nhân sai của các đáp án trong đề thi thử thay vì làm quá nhiều đề, kết hợp thực hành trên tài khoản AWS Free Tier.
- **Mẹo làm bài phỏng vấn & thi cử**: 
    - Sử dụng phương pháp loại trừ để nhanh chóng loại bỏ 2 đáp án vô lý.
    - Không suy nghĩ quá phức tạp vì bài thi tập trung vào kiến thức cơ bản. 
    - Lưu ý các bẫy ngôn ngữ như "Not", "Least cost", "Most scalable" và tận dụng tính năng "Flag for review" để quay lại câu khó sau.


#### Kiến Thức Cốt Lõi Về Đám Mây AWS Và Mô Hình Trách Nhiệm Chia Sẻ
- **6 Lợi ích cốt lõi của AWS Cloud**:
    - Chuyển đổi chi phí đầu tư cố định sang chi phí vận hành biến đổi
    - Tối ưu quy mô lớn
    - Dừng việc dự đoán năng lực hạ tầng
    - Tăng tốc độ và sự linh hoạt
    - Ngưng chi phí bảo trì Data Center
    - Mở rộng quy mô toàn cầu trong vài phút.
- **Khung kiến trúc chuẩn (AWS Well-Architected Framework)**: Gồm 6 trụ cột cốt lõi:
    - Vận hành xuất sắc (Operational Excellence)
    - Bảo mật (Security)
    - Độ tin cậy (Reliability)
    - Hiệu suất hoạt động (Performance Efficiency)
    - Tối ưu chi phí (Cost Optimization)
    - Độ bền vững (Sustainability).
- **Khung chuyển dịch đám mây (AWS CAF)**: Phân chia làm 2 nhóm góc nhìn chính:
    - **Nhóm Kinh doanh** (Business, People, Governance) tập trung vào chiến lược và con người
    - **Nhóm Kỹ thuật** (Platform, Security, Operations) tập trung vào nền tảng và vận hành.
- **Mô hình trách nhiệm chia sẻ (Shared Responsibility Model)**:
    - AWS chịu trách nhiệm bảo mật "Cho đám mây" gồm: hạ tầng vật lý, phần cứng, mạng, phần mềm ảo hóa
    - Khách hàng chịu trách nhiệm bảo mật "Trong đám mây" gồm: dữ liệu, cấu hình IAM, hệ điều hành, tường lửa ứng dụng, mã hóa.

#### Quản Lý Rủi Ro Vận Hành Và Cam Kết Chất Lượng Dịch Vụ 
- **Thực tế công việc tại NOC/SOC**: Môi trường Network Operation Center đòi hỏi giám sát liên tục 24/7 trên nhiều màn hình, theo dõi tín hiệu cảnh báo chủ động để ứng phó sự cố tức thì.
- **Khái niệm & Vai trò của SLA**: Là cam kết chính thức về mức độ dịch vụ giữa nhà cung cấp và khách hàng. SLA đóng vai trò quan trọng trong việc giúp minh bạch kỳ vọng , quy trách nhiệm dịch vụ, quản lý rủi ro và đo lường hiệu năng. Vi phạm SLA có thể dẫn đến khoản phạt tài chính đền bù rất lớn cho doanh nghiệp.
- **Vòng lặp quản lý rủi ro**: Giám sát nằm trong tiến trình quản lý rủi ro giúp phát hiện sớm nguy cơ trước khi ảnh hưởng đến SLA. Quy trình gồm 4 bước: Nhận diện rủi ro → Giám sát tín hiệu → Ứng phó → Cải tiến.

#### Kim Tự Tháp Giám Sát Và Luồng Cảnh Báo Sự Cố Realtime
- **Cạm bẫy "Green Dashboard" (Healthy Infrastructure ≠ Healthy User Experience)**: Dashboard hiển thị các chỉ số hạ tầng "xanh" ví dụ như EC2 CPU 18%, ALB Healthy Host 2/2, HTTP 200 OK không đồng nghĩa với việc người dùng đang có trải nghiệm tốt. <br>
Ví dụ: Khi kết nối RDS Database bị lỗi, tiến trình app vẫn sống (Pass Health Check) nhưng đường dẫn `/login` thất bại khiến tỷ lệ đăng nhập rớt từ 100% xuống 0%.
- **Cấu trúc kim tự tháp giám sát**: Giám sát phải đi từ tầng thấp đến tầng cao, trọng tâm nằm ở đỉnh tháp:
  - *Cloud Provider / Infrastructure*: CPU, Memory, Disk, Network.
  - *Application*: Latency, Error Rates, Request Counts.
  - *Business*: Tỷ lệ đăng nhập thành công, Số lượng đơn hàng, Doanh thu.
  - *Customer Experience*: Người dùng có thể đăng nhập được không? Có thể thanh toán/mua hàng được không?
- **Luồng thiết lập cảnh báo tự động**: Đẩy chỉ số tùy chỉnh (ví dụ: Custom Metric như `LoginFailure`) vào CloudWatch → Kích hoạt CloudWatch Alarm khi vượt ngưỡng → Đẩy thông báo ra SNS Topic → Gửi cảnh báo tức thì qua Email hoặc Slack cho đội ngũ vận hành.
- **Tư duy vận hành hiện đại**: Áp dụng triết lý của Tiến sĩ Werner Vogels: *"Everything fails all the time, so plan for failure and nothing fails"*.

#### Tự Động Hóa An Ninh Mạng Với AWS Security Agent
- **Nút thắt an ninh mạng truyền thốn**: Kiểm thử thủ công tốn nhiều tuần, chi phí đắt đỏ ($5.000 - $20.000/đợt pentest), chất lượng không đồng đều tùy thuộc vào kỹ năng của nhân viên.
- **Kiến trúc AWS Security Agent**: Sử dụng mô hình Multi-agent chạy trên nền Amazon Bedrock, có khả năng tự chủ suy luận, bao phủ toàn bộ vòng đời phát triển ứng dụng và đưa ra phát hiện có thể xác minh được bằng cách tấn công khai thác thực tế thay vì chỉ đưa ra văn bản dự đoán.
- **Các tính năng kiểm tra tự động**:
  - **Design Security Review**: Tải lên tài liệu Markdown hoặc mã Terraform, rà soát đối chiếu với bộ tiêu chuẩn (Managed Packs như PCI DSS, NIST CSF, AWS Well-Architected). Hỗ trợ Free Tier 200 lượt review/tháng.
  - **Code Security Review**: Tích hợp trực tiếp vào Pull Request GitHub/GitLab, tự động nhận xét từng dòng code và đề xuất kịch bản sửa lỗi tự động. Quét triệt để ngăn chặn lộ API Keys hoặc Database Keys lên GitHub. Hỗ trợ Free Tier 1.000 PR reviews/tháng.
  - **Threat Modeling**: Đánh giá chuyên sâu các mối đe dọa tiềm ẩn và điểm yếu kiến trúc trong tương lai dựa trên tài liệu hệ thống.

#### Quy Trình Kiểm Thử Xâm Nhập Và Các Hạn Chế Kỹ Thuật Trong Thực Tế
- **Cơ chế Pentesting tự động**: Thực hiện chuỗi khai thác đa bước (Multi-step exploit chains như IDOR → XSS), tự động xác thực như người dùng thật và xuất biểu đồ tấn công chi tiết kèm bằng chứng thực tế.
- **Mô hình chi phí & Task-Hours**:
  - Chi phí $5/Task-Hour tính theo thời gian thực thi của agent. Cung cấp Free Trial 2 tháng tương đương khoảng 400 Task-Hours/tháng.
  - Một dự án thực tế chạy kiểm thử tốn 6-10 tiếng theo thời gian thực nhưng tiêu tốn khoảng 30-50 Task-Hours, tương đương $1.500 - $2.500 do agent chạy song song nhiều tác vụ. Rẻ hơn rất nhiều so với chi phí thuê đội pentest với chi phí nhân lực rơi vào khoảng $10.000+.
- **Quy trình triển khai Demo thực tế**: <br>
  1\. **Verify Target Domain**: Phải xác minh quyền sở hữu domain bằng DNS TXT record thông qua việc thêm Record Name và Verification Token trước khi cho phép agent tấn công. <br>
  2\. **Setup Integrations & Agent Space**: Cài đặt ứng dụng Security Agent trên GitHub/GitLab repository. <br>
  3\. **Configure Out-of-Scope & Access URLs**: Khai báo các URL quan trọng không được tấn công hoặc các dịch vụ xác thực ngoài. <br>
  4\. **Provide Credentials**: Cung cấp tài khoản thử nghiệm thông qua AWS Secrets Manager hoặc cấu hình đường dẫn đăng nhập để agent tự động truy cập.
- **Rào cản & Hạn chế kỹ thuật**:
  - **Rào cản xác thực Auth Blocks**: Agent hoàn toàn bất lực và không thể bypass nếu ứng dụng bắt buộc xác thực MFA, Biometrics, mTLS hoặc OTP/SSO.
  - **Cơ chế xác thực mTLS**: Xác thực hai chiều yêu cầu cài đặt Certificate trên cả Client/Browser lẫn Server, agent không thể vượt qua nếu không có certificate hợp lệ.
  - **Lỗi gian lận logic nghiệp vụ**: Khó phát hiện các lỗi gian lận logic kinh doanh phức tạp nếu không cung cấp đủ ngữ cảnh tài liệu.
  - **Tốc độ tiêu tốn Task-Hours**: Ứng dụng phức tạp có thể đốt Task-Hours rất nhanh, đòi hỏi phải giám sát chặt chẽ tiến trình chạy.

### Những Gì Học Được

#### Tư Duy An Ninh Mạng Và Tự Động Hóa DevSecOps

- **Kiểm thử dựa trên hành vi**: Chuyển dịch từ việc chỉ dùng công cụ quét mã tĩnh như SAST hoặc SonnarQube sang sử dụng Multi-agent AI để mô phỏng hành vi tấn công thực tế Pentesting và kiểm tra cả Front-end lẫn Back-end.
- **Tích hợp an ninh vào CI/CD Pipeline**: Áp dụng tính năng Code Security Review tự động trên Pull Requests nhằm ngăn chặn triệt để rò rỉ Credential hoặc API Key và sửa lỗi ngay từ khâu lập trình.
- **Hiểu giới hạn của AI Agent**: AI Agent hỗ trợ đắc lực nhưng không thể thay thế hoàn toàn con người, đặc biệt ở các bài toán xác thực mTLS, MFA hoặc logic nghiệp vụ đặc thù.

#### Tư Duy Vận Hành Hạ Tầng, Giám Sát Hệ Thống SLA Và Observability

- Chuyển dịch sang **User-Centric Monitoring**: Loại bỏ tư duy phụ thuộc vào "Green Dashboard", thiết lập hệ thống đo đạc dựa trên hành trình khách hàng Customer Journey bao gồm các chỉ số Login, Checkout, Payment success rate.
- Học cách **Chủ động ứng phó rủi ro** với  việc xây dựng quy trình tự động hóa cảnh báo sự cố từ Custom Metrics qua CloudWatch Alarms và SNS đến các kênh làm việc như Slack hay Email trước khi khách hàng phàn nàn.
- **Quản trị SLA theo góc nhìn kinh doanh**: Thấu hiểu mối liên hệ trực tiếp giữa gián đoạn hệ thống, vi phạm cam kết SLA và đền bù tài chính trong doanh nghiệp.

#### Phương Pháp Học Tập Và Đạt Chứng Chỉ AWS

- **Tư duy Keyword Mapping**: Gắn khái niệm lý thuyết với các bài toán, use case thực tế để ghi nhớ sâu.
- **Chiến lược làm bài** thi trắc nghiệm chuẩn quốc tế: loại trừ đáp án vô lý, tối ưu hóa thời gian và giữ tâm lý bình tĩnh khi làm bài.

### Ứng Dụng Vào Công Việc

- **Trial AWS Security Agent Free Tier**: Tận dụng 2 tháng dùng thử với hạn mức 400 Task-Hours mỗi tháng để thực hiện rà soát Security Review và Pentesting cho các dự án cá nhân hoặc đồ án môn học.
- **Integrate PR Security Scanning**: Cài đặt GitHub App của AWS Security Agent vào repository để tự động quét code và phát hiện Secret Leakage trên mỗi Pull Request.
- **User-centric CloudWatch Metrics**: Đẩy các custom metric theo dõi tỷ lệ đăng nhập và giao dịch thành công vào AWS CloudWatch thay vì chỉ đo CPU hay Memory.
- **Automated Alerting Flow**: Cấu hình CloudWatch Alarm kết hợp Amazon SNS nhằm gửi thông báo khẩn cấp qua Slack hoặc Email khi tỷ lệ lỗi ứng dụng tăng bất thường.

### Trải nghiệm trong event

Tham gia sự kiện là một trải nghiệm học thuật vô cùng giá trị và ấn tượng, giúp tôi củng cố toàn diện tư duy an ninh mạng tự động, phương pháp vận hành giám sát SLA chuẩn mực và lộ trình cũng như các mẹo ôn chứng chỉ AWS hữu ích.

#### Học hỏi từ các diễn giả có chuyên môn cao
- Diễn giả Ngo Le Tan Huy đã chia sẻ lộ trình ôn thi chứng chỉ vô cùng thiết thực và súc tích.
- Diễn giả Thịnh Nguyễn đem đến phần demo sinh động về AWS Security Agent cùng với với cách tiếp cận DevSecOps rất thực tế.
- Diễn giả Nguyen Huynh Son cũng mang đến một góc nhìn khác trong việc vận hành NOC/SOC và câu chuyện SLA chân thực từ trải nghiệm làm việc tại tập đoàn của bản thân.

#### Trải nghiệm kỹ thuật thực tế
- Được quan sát trực tiếp giao diện console và các bước cấu hình verify domain, cài đặt integration và đọc báo cáo lỗ hổng bảo mật chi tiết từ AWS Security Agent.
- Tiếp thu cách phân tích cạm bẫy "Green Dashboard" thông qua mô hình tháp giám sát và kịch bản lỗi kết nối RDS thực tế.

#### Tác Động Về Tư Duy & Định Hướng Nghề Nghiệp
- Thay đổi nhận thức về an ninh mạng, nhận ra sự cần thiết của việc tự động hóa pentest bằng AI trong thời đại lập trình bằng AI hiện nay.
- Nhận thức sâu sắc hơn về trách nhiệm đối với trải nghiệm người dùng trong công việc vận hành hạ tầng.

#### Kết nối và trao đổi
- Sự kiện mang không khí cởi mở, tạo cơ hội trao đổi, học hỏi trực tiếp với các chuyên gia trong ngành.

#### Bài học rút ra
- Giám sát hạ tầng phải luôn song hành với trải nghiệm thực tế của người dùng.
- Làm chủ công nghệ tự động hóa mới như AI Agent hay Pentesting cần đi đôi với việc thấu hiểu các rào cản kỹ thuật bản chất như MFA, mTLS hay Logic flaws.

#### Một số hình ảnh khi tham gia sự kiện
![](/static/images/4-EventParticipated/Pic1-2026-07-11.jpg)
![](/static/images/4-EventParticipated/Pic2-2026-07-11.jpg)

> Cuối cùng, sự kiện mang đến những kinh nghiệm và kiến thức giá trị, đặc biệt là các giải pháp bảo mật hệ thống cùng việc giới thiệu công cụ AI tự động hóa rất bổ ích.
