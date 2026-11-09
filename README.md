Đề bài / Yêu cầu
1. Mục tiêu
Áp dụng mô hình IPO và kỹ năng kiểm chứng thông tin khi làm việc với AI.
2. Bối cảnh
Bạn hỏi AI cách sửa lỗi "Path not found" khi cài đặt Python. AI đưa ra một câu lệnh gạch đầu dòng bảo bạn dán vào Terminal, nhưng lệnh này trông rất lạ và có thể can thiệp sâu vào hệ thống.
3. Ràng buộc & Bẫy dữ liệu
AI có thể bị hiện tượng AI Hallucination (đưa ra lệnh không có thật hoặc sai phiên bản hệ điều hành).
4. Yêu cầu đầu ra
•	Báo cáo phân tích (IPO): Xác định Input (Câu trả lời của AI), Process (Quy trình kiểm chứng bằng toán tử site:stackoverflow.com hoặc trang chủ phần mềm),
Output (Xác nhận lệnh an toàn/không an toàn).
Input (Đầu vào): Câu lệnh lạ do AI cung cấp dùng để sửa lỗi "Path not found" khi cài đặt Python.
Process (Xử lý & Kiểm chứng):
Trích xuất các từ khóa chính và các tham số có trong câu lệnh.
Sử dụng công cụ tìm kiếm với toán tử nâng cao để đối chiếu dữ liệu: "<câu_lệnh_của_AI>" site:stackoverflow.com hoặc tra cứu trực tiếp trên trang chủ tài liệu (Documentation) của Python.
Đọc phản hồi từ cộng đồng để kiểm tra xem lệnh đó có đúng phiên bản hệ điều hành không và có ai cảnh báo về rủi ro của nó hay không.
Output (Đầu ra): Kết luận rõ ràng về độ tin cậy: Xác nhận lệnh an toàn (cho phép thực thi) hoặc Lệnh không an toàn/Sai lệch do AI ảo tưởng (từ chối thực thi và tìm giải pháp khác).
•	Thiết kế một câu lệnh (Prompt) "hỏi ngược lại" AI để yêu cầu nó giải thích độ an toàn của câu lệnh trước khi bạn thực thi.
"Tôi thấy câu lệnh bạn vừa đưa ra có can thiệp sâu vào hệ thống. Trước khi tôi thực thi, hãy giải thích rõ: từng tham số trong lệnh này có chức năng gì?
Lệnh này có thay đổi vĩnh viễn file hệ thống hay quyền truy cập của máy không? Có rủi ro nào gây lỗi hệ điều hành nếu tôi chạy nó không?"
