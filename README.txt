Worklog - Ngày [08/07/2026]
📅 Thông tin cơ bản
Ngày: 08/07/2026

Thứ: Thứ tư

Tuần thực tập: Tuần thứ 1/8

Thời gian làm việc: 8:00 - 17:00

Mood: 😊 + Ngày đầu đi làm rất háo hức, môi trường năng động.

🎯 Mục tiêu ngày hôm nay
[x] Mục tiêu 1: Hoàn thành được 2 module bài học đầu tiên về hạ tầng Cloud đám mây.

[x] Mục tiêu 2: Thiết lập thành công tài khoản AWS cá nhân và cấu hình bảo mật cơ bản.

[x] Mục tiêu 3: Tạo repository trên GitHub để quản lý và lưu trữ tài liệu daily log thực tập.

💼 Công việc đã thực hiện
1. First Cloud Journey Bootcamp - 2025 ⏱️ [9:10 am - 2:00 pm]
Mô tả: Xem video hướng dẫn, tìm hiểu tổng quan về điện toán đám mây và cách sử dụng giao diện quản trị AWS Console.

Kết quả: Nắm vững lý thuyết cốt lõi về AWS (Region, Availability Zone). Biết cách phân biệt tài khoản Root và IAM User để đảm bảo an toàn hệ thống.

Tools/Tech: AWS Console

2. Viết dailylog & Quản lý Source Code ⏱️ [2:30 pm - 4:30 pm]
Mô tả: Khởi tạo kho lưu trữ (repository) trên GitHub cá nhân và viết tài liệu daily log cho ngày làm việc đầu tiên.

Kết quả: Hoàn thành cấu trúc thư mục quản lý công việc hàng ngày mượt mà.

Tools/Tech: Git, GitHub, Markdown

📚 Kiến thức học được
🔧 Technical Skills
AWS Services: Tìm hiểu về IAM (Identity and Access Management), AWS Billing, AWS Budgets (hiểu cơ chế hoạt động của Cost Budget, Usage Budget).

Architecture: Hiểu về mô hình chia nhỏ tài nguyên mạng theo khu vực địa lý của Amazon (Regions & Availability Zones).

💡 Concepts & Theory
New Concepts: Khái niệm về Cloud Computing, mô hình BaaS (Backend as a Service) của Firebase so sánh với hệ sinh thái Cloud khổng lồ của AWS.

Best Practices: Nguyên tắc bảo mật "Least Privilege" (quyền tối thiểu) - sử dụng IAM User thay cho Root Account để thao tác hàng ngày; cách đặt Billing Alarm để tránh mất tiền oan khi học Cloud.

🤝 Soft Skills
Problem Solving: Biết cách tra cứu, phân tích nguyên nhân lỗi và tìm giải pháp thay thế khi gặp lỗi đồng bộ dữ liệu hệ thống (lỗi load Dropdown trên AWS Budget).

Time Management: Sắp xếp thời gian hợp lý giữa việc học lý thuyết qua video và thực hành trực tiếp trên Lab.

🚧 Khó khăn và giải pháp
Vấn đề 1: Lỗi "Usage type groups cannot be empty" khi tạo AWS Budget
Mô tả: Khi cấu hình Custom Budget theo dạng Usage, ô lựa chọn thả xuống bị trống rỗng và hiển thị "No data to display", không thể bấm Tiếp tục (Next).

Impact: Làm gián đoạn quá trình thực hành thiết lập cảnh báo chi phí.

Root Cause: Tài khoản AWS mới khởi tạo (chưa quá 24h) nên hệ thống Billing chưa đồng bộ xong dữ liệu nền tảng; đồng thời tài khoản chưa phát sinh dữ liệu sử dụng thực tế khiến AWS chưa thể phân loại nhóm tài nguyên.

Solution: Chuyển hướng sang sử dụng tính năng Use a template và chọn Zero spend budget để điền thủ công mức cảnh báo $0. Cách này bỏ qua bước quét dữ liệu tự động nên không bị lỗi.

Result: Tạo thành công Budget cảnh báo chi phí đầu tiên để bảo vệ tài khoản.

Lesson: Đối với tài khoản mới tinh, cần đợi từ 12 - 24 tiếng để các dịch vụ bổ trợ của AWS kích hoạt hoàn toàn. Khi làm Budget ban đầu nên ưu tiên chọn Cost Budget bằng Template thay vì Custom Usage Budget.

💭 Reflection & Insights
What went well today?
Tinh thần học hỏi cao, nắm bắt giao diện AWS khá nhanh dù đây là dịch vụ lớn và phức tạp.

Khắc phục và tự giải quyết được lỗi phát sinh ngay trong ngày đầu tiên tiếp cận công nghệ mới.

What could be improved?
Cần đọc kỹ tài liệu hướng dẫn của AWS (Documentation) song song với việc xem video để hiểu sâu hơn bản chất các thông số cấu hình.

Key Insights
Học Cloud quan trọng nhất là tư duy vận hành hệ thống và khả năng kiểm soát chi phí, không nên nóng vội cấu hình những dịch vụ nâng cao khi chưa vững nền tảng.

📋 Kế hoạch ngày mai
Priority Tasks
[ ] High: Chờ tài khoản AWS đồng bộ đủ 24h, kiểm tra lại giao diện Custom Budget xem đã hiển thị đầy đủ chưa.

[ ] Medium: Bắt đầu Module tiếp theo: Tìm hiểu về máy chủ ảo Amazon EC2 (Cách khởi tạo instance t2.micro thuộc gói Free Tier).

[ ] Low: Tìm hiểu sơ bộ về dịch vụ lưu trữ Amazon S3.

Learning Goals
[ ] Học cách kết nối SSH vào máy chủ Linux trên EC2 bằng Key Pair.

[ ] Tìm hiểu cách cấu hình Security Group (tường lửa đám mây) để mở port cho ứng dụng.

📊 Self Assessment
Productivity
Score: 8/10

Reason: Hoàn thành đúng tiến độ các đầu việc đề ra, phân bổ thời gian hiệu quả.

Learning
Score: 9/10

New Knowledge: Tiếp thu được một lượng lớn kiến thức mới về hạ tầng Cloud và tích lũy được kinh nghiệm xử lý lỗi thực tế của tài khoản AWS mới.

Collaboration
Score: 8/10

Interactions: Tương tác tốt, chủ động tìm kiếm giải pháp và học hỏi kinh nghiệm.

Overall Satisfaction
Score: 9/10

Highlights: Ngày đầu tiên thực tập rất trọn vẹn, vượt qua bỡ ngỡ ban đầu và làm quen tốt với nhịp độ công việc.

📎 Attachments & Links
Code & Projects
GitHub commits (Bạn tự thay link repo của bạn vào đây nhé)

Learning Resources
[Videos watched]: First Cloud Journey Bootcamp Video Guide.

📝 Notes for tomorrow:
Luôn nhớ "Stop" hoặc "Terminate" các tài nguyên máy chủ sau khi thực hành xong để tránh phát sinh chi phí ngoài ý muốn.

🎯 Week Progress:
Đã hoàn thành 30% mục tiêu học tập của tuần đầu tiên.

Worklog created by: [Điền tên của bạn vào đây]

Next review: 09/07/2026