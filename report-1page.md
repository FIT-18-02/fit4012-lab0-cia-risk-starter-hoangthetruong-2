# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Hiểu mô hình CIA
- Xác định tài sản cần bảo vệ
- Phân tích rủi ro và đề xuất giải pháp

---

### 2. Kết quả chính

**Assets:**
- Cơ sở dữ liệu sinh viên và giảng viên
- Hệ thống lưu trữ bài giảng

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Hacker sử dụng SQL Injection để sửa điểm
- Vulnerability: Không validate input
- Mitigation: Dùng parameterized query và phân quyền

---

### 3. Kết luận
Bài lab giúp em hiểu rõ mô hình CIA và cách áp dụng trong thực tế. Từ đó, em có thể nhận diện rủi ro và đưa ra giải pháp bảo vệ hệ thống hiệu quả hơn.
