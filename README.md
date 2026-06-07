# [Tên Dự Án]

> **BẮT BUỘC ĐỌc:** Agent AI khi bắt đầu phiên làm việc **PHẢI** đọc file này
> và tất cả các file trong thư mục `NhatKy/` trước khi thực hiện bất kỳ thay đổi nào.

---

## Thông Tin Dự Án

| Mục | Chi tiết |
|:---|:---|
| **Tên dự án** | [Nhập tên dự án] |
| **Mô tả** | [Mô tả ngắn gọn] |
| **Ngày bắt đầu** | [DD/MM/YYYY] |
| **Thiết bị chính** | [PLC, HMI, Biến tần, Servo...] |
| **Repository** | [Link GitHub] |

---

## Phương Án Kỹ Thuật Đã Thống Nhất

*(Ghi lại phương án đã được khách hàng duyệt. Cập nhật mỗi khi có thay đổi lớn.)*

---

## Các Quyết Định Kỹ Thuật Quan Trọng

| # | Quyết định | Ngày | Trạng thái |
|:---:|:---|:---:|:---:|
| 1 | [Mô tả quyết định] | [DD/MM] | ✅ Đã duyệt / ⏳ Chờ |

---

## Cấu Trúc Thư Mục

```
DuAn/
├── README.md                        ← File này (Tổng quan + Hướng dẫn agent)
├── TaiLieu/                         ← Tài liệu kỹ thuật chi tiết
│   └── *.md
└── NhatKy/                          ← Nhật ký phiên làm việc (bắt buộc đọc)
    └── YYYY-MM-DD_PhienX_MoTa.md
```

---

## Danh Sách Vấn Đề Chưa Giải Quyết

*(Xem tab **Issues** trên GitHub để theo dõi chi tiết)*

- [ ] [Vấn đề 1]
- [ ] [Vấn đề 2]

---

## Hướng Dẫn Cho Agent Mới

### Khi bắt đầu phiên làm việc:
1. **Đọc `README.md`** (file này) để nắm tổng quan dự án và các quyết định đã thống nhất
2. **Đọc tất cả file trong `NhatKy/`** theo thứ tự thời gian để hiểu quá trình ra quyết định
3. **Kiểm tra GitHub Issues** (đang mở) để biết các vấn đề tồn đọng
4. **Đọc các file trong `TaiLieu/`** nếu cần hiểu chi tiết kỹ thuật

### Khi kết thúc phiên làm việc:
1. **Tạo file nhật ký mới** trong `NhatKy/` theo format: `YYYY-MM-DD_PhienX_Mo_Ta.md`
2. **Nội dung nhật ký bắt buộc gồm:**
   - Yêu cầu của khách hàng trong phiên này
   - Các quyết định đã thống nhất (cập nhật bảng tích lũy)
   - File đã tạo / thay đổi
   - Vấn đề chưa giải quyết
3. **Cập nhật `README.md`** nếu có quyết định mới
4. **Push lên GitHub** và tạo/đóng Issues tương ứng

### Quy tắc vàng:
- **KHÔNG** thay đổi thiết kế đã được duyệt mà không hỏi lại khách hàng
- **LUÔN** ghi nhật ký trước khi kết thúc phiên
- **LUÔN** đọc nhật ký cũ trước khi bắt đầu làm việc
