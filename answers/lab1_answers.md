# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Thế Trường

**MSSV:** 1871020599

**Lớp/Nhóm:** Cntt18-02

---

1. Assets
Asset 1: Dữ liệu điểm của sinh viên
Asset 2: Tài khoản đăng nhập của giảng viên và sinh viên
Asset 3: Máy chủ lưu trữ hệ thống
2. Mapping CIA
Sự cố A → Confidentiality (Lộ thông tin điểm sinh viên)
Sự cố B → Integrity (Điểm số bị thay đổi trái phép)
Sự cố C → Availability (Hệ thống bị lỗi hoặc bị tấn công nên không truy cập được)
3. Phân tích sự cố B
Threat: Hacker hoặc người dùng cố ý sửa điểm.
Vulnerability: Hệ thống phân quyền chưa chặt chẽ hoặc thiếu kiểm tra thay đổi dữ liệu.
Mitigation: Áp dụng phân quyền truy cập, ghi log thay đổi dữ liệu và sao lưu dữ liệu định kỳ.
4. Reflection

Qua bài tập này em hiểu rõ hơn về mô hình CIA trong bảo mật hệ thống thông tin. Ba yếu tố Confidentiality, Integrity và Availability đều rất quan trọng trong việc bảo vệ dữ liệu. Đặc biệt với hệ thống lưu điểm sinh viên, nếu dữ liệu bị lộ hoặc bị thay đổi sẽ ảnh hưởng lớn đến tính công bằng. Vì vậy cần áp dụng các biện pháp bảo mật phù hợp để bảo vệ hệ thống.

5. Bonus Flag
FIT4012{A-Confidentiality-B-Integrity-C-Availability}
