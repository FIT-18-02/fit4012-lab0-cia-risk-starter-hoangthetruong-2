# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Thế Trường  
**MSSV:** 1871020599  
**Lớp/Nhóm:** Cntt18-02  

---

## 1. Assets
- Asset 1: Cơ sở dữ liệu thông tin cá nhân của sinh viên và giảng viên.
- Asset 2: Hệ thống máy chủ lưu trữ tài liệu bài giảng và bài tập.
- Asset 3: Mã nguồn của hệ thống quản lý học tập.

---

## 2. Mapping CIA
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

---

## 3. Phân tích sự cố B
- Threat: Hacker thay đổi điểm bằng SQL Injection.
- Vulnerability: Không kiểm tra dữ liệu đầu vào.
- Mitigation: Sử dụng parameterized query và kiểm tra phân quyền.

---

## 4. Reflection
Qua bài lab này, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào hệ thống thực tế. Em nhận ra rằng việc xác định tài sản và phân tích rủi ro là rất quan trọng để bảo vệ hệ thống. Ngoài ra, việc hiểu rõ các lỗ hổng giúp em đưa ra giải pháp phù hợp. Đây là kiến thức nền tảng quan trọng trong an toàn thông tin.

---

## 5. Bonus Flag
FIT4012{A-Confidentiality-B-Integrity-C-Availability}
