# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Thế Trường

**MSSV:** 1871020599

**Lớp/Nhóm:** Cntt18-02

---
## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu thông tin cá nhân của sinh viên và giảng viên.
- Asset 2: Hệ thống máy chủ lưu trữ tài liệu bài giảng và bài tập.
- Asset 3 (nếu có): Mã nguồn của ứng dụng quản lý học tập trực tuyến.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality (Tính bảo mật - Dữ liệu bị rò rỉ ra ngoài)
- Sự cố B -> Integrity (Tính toàn vẹn - Dữ liệu bị chỉnh sửa trái phép)
- Sự cố C -> Availability (Tính khả dụng - Hệ thống bị treo không truy cập được)

---

## 3. Phân tích sự cố B
- Threat: Kẻ tấn công thực hiện thay đổi điểm số trên hệ thống bằng SQL Injection.
- Vulnerability: Ứng dụng chưa kiểm tra kỹ dữ liệu đầu vào từ phía người dùng.
- Mitigation: Sử dụng tham số hóa truy vấn (Parameterized queries) và kiểm tra phân quyền chặt chẽ.

---

## 4. Reflection
Viết 5-7 dòng.

Qua bài lab này, em đã nắm vững kiến thức về mô hình bảo mật CIA và cách áp dụng vào thực tế. Em hiểu rằng việc xác định đúng tài sản (Assets) là bước đầu tiên và quan trọng nhất trong quản trị rủi ro. Việc phân tích các mối đe dọa giúp em có cái nhìn đa chiều về các lỗ hổng bảo mật tiềm ẩn. Từ đó, em có thể đề xuất các biện pháp giảm thiểu rủi ro phù hợp để bảo vệ hệ thống. Bài học này rất hữu ích cho lộ trình học tập về an toàn thông tin của em.

---

## 5. Bonus Flag
Flag của em: FIT4012{A-Confidentiality-B-Integrity-C-Availability}
