# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
Assets (Tài sản):
• Dữ liệu điểm số (Data): Bảng điểm của sinh viên lưu trữ trong cơ sở dữ liệu.
• Cơ sở hạ tầng (Infrastructure): Máy chủ lưu trữ (Server) và giao diện nhập điểm của giáo viên.
CIA mapping:
• Sự cố A (Rò rỉ bảng điểm): Vi phạm tính Confidentiality (Tính bảo mật) do thông tin riêng tư bị lộ cho người không có thẩm quyền.
• Sự cố B (Sinh viên tự sửa điểm): Vi phạm tính Integrity (Tính toàn vẹn) do dữ liệu bị thay đổi trái phép, không còn chính xác.
• Sự cố C (Hệ thống sập vào giờ cao điểm): Vi phạm tính Availability (Tính khả dụng) do người dùng hợp pháp không thể truy cập dịch vụ khi cần.
Phân tích sự cố B (Sinh viên tự sửa điểm):
• Threat (Mối đe dọa): Sinh viên có kỹ năng kỹ thuật hoặc kẻ tấn công bên ngoài cố tình can thiệp vào cơ sở dữ liệu để trục lợi.
• Vulnerability (Lỗ hổng): Hệ thống kiểm soát truy cập yếu (mật khẩu đơn giản) hoặc thiếu cơ chế kiểm tra tính hợp lệ của dữ liệu đầu vào (Input validation).
• Mitigation (Biện pháp khắc phục): Triển khai xác thực đa yếu tố (MFA), phân quyền chặt chẽ (Role-based Access Control) và ghi nhật ký (Logging) mọi thao tác thay đổi dữ liệu.
4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về cách áp dụng mô hình CIA để phân loại các rủi ro bảo mật trong thực tế thay vì chỉ học lý thuyết suông. Phần khó nhất là phân biệt giữa Threat (nguồn gây hại) và Vulnerability (điểm yếu nội tại), vì chúng thường có mối liên hệ mật thiết. Điều quan trọng nhất khi phân tích một sự cố là phải xác định đúng tài sản trọng yếu để từ đó đưa ra các biện pháp giảm thiểu (mitigation) phù hợp và tối ưu về chi phí.
