# Portfolio CV - Ngô Khánh Hưng

Trang CV cá nhân và portfolio Frontend Developer của Ngô Khánh Hưng, sinh viên lớp CNTT-20-01. Website giới thiệu thông tin, kỹ năng, dự án tiêu biểu và biểu mẫu liên hệ bằng HTML, CSS và JavaScript thuần.

## Tính năng

- Thiết kế responsive theo hướng mobile-first.
- Giao diện Dark Green với CSS variables.
- Điều hướng đến các phần giới thiệu, kỹ năng, dự án và liên hệ.
- Hiển thị 4 dự án tiêu biểu cùng hình ảnh minh họa.
- Hiệu ứng xuất hiện, hover và chuyển động nhẹ.
- Form liên hệ thu thập email, số điện thoại và nội dung.
- Thông báo gửi form ngay trên trang, không cần backend.
- Hỗ trợ sử dụng bàn phím và `prefers-reduced-motion`.

## Công nghệ

- HTML5
- CSS3: Flexbox, CSS Grid và custom properties
- JavaScript thuần
- Unsplash cho ảnh minh họa dự án

## Cấu trúc thư mục

```text
CV/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    └── img/
        ├── avatar.jpg
        └── cat-meme.png
```

## Chạy website local

Trong thư mục dự án, chạy:

```bash
python3 -m http.server 4173
```

Sau đó mở `http://localhost:4173` trên trình duyệt.

## Form liên hệ

Form liên hệ đang chạy hoàn toàn phía client. Khi người dùng bấm gửi, trang kiểm tra các trường bắt buộc, hiển thị thông báo xác nhận và đặt lại nội dung đã nhập. Dữ liệu chưa được lưu hoặc gửi đến email/server.

Để nhận dữ liệu thực tế, cần kết nối form với backend hoặc dịch vụ form bên thứ ba.

## Thông tin liên hệ

- Email: [hungngo28012007@gmail.com](mailto:hungngo28012007@gmail.com)
- GitHub: [hungngo28012007-design](https://github.com/hungngo28012007-design)
