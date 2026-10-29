# 💌 Hồng Phước & Ngọc Hân - Thiệp cưới nhà trai

Thiệp cưới online của nhà trai, lễ cưới ngày **29.11.2026** (tức ngày 21 tháng 10 năm Bính Ngọ), 11:00 tại 209 Nguyễn Chí Thanh, Hòa Thành, Tây Ninh.
Web tĩnh (HTML/CSS/JS thuần, không có bước build), chạy trên GitHub Pages: <https://hongphuocngochan.github.io>

Thiệp nhà gái (28.11.2026): <https://ngochanhongphuoc.github.io>

## Tính năng

- Hiệu ứng mở phong bì, nhạc nền, tự cuộn qua từng phần
- Thông tin lễ cưới, "Hành trình của chúng mình" (4 mốc, giống thiệp nhà gái)
- Album ảnh coverflow 12 ảnh + xem ảnh lớn (phóng to, vuốt)
- Đếm ngược, lịch tháng 11, thêm vào Google Calendar, bản đồ chỉ đường
- Xác nhận tham dự (RSVP) và sổ lưu bút, lưu vào Google Sheet
- Giao diện riêng cho điện thoại và máy tính

## Cấu trúc thư mục

```
hongphuocngochan.github.io/
├── index.html        # Thiệp cưới (kèm toàn bộ JavaScript ở cuối file)
├── styles.css        # Giao diện thiệp (điện thoại + máy tính)
├── thumbnail.jpg     # Ảnh xem trước khi chia sẻ link (1200×630)
├── assets/
│   ├── couple.webp, envelope-*.webp, flower.webp, paper.webp, castle-background.webp
│   ├── wedding-01.webp … wedding-12.webp   # Album ảnh
│   ├── vi-phuoc-han.mp3                    # Nhạc nền
│   └── fonts/        # Cormorant Garamond, Montserrat, Lora, Be Vietnam Pro (kèm giấy phép OFL)
├── LICENSE
└── README.md
```

## Xem thử trên máy

```
npx serve .
```

## Bản quyền và watermark

© 2026 Lê Hồng Phước & Võ Trương Ngọc Hân. Bảo lưu mọi quyền (All rights reserved).

Thiệp có watermark ghi tên tác giả, **không được xóa hoặc sửa**:

- Dưới ảnh cưới phần đầu thiệp: `THIỆP CƯỚI ĐƯỢC THỰC HIỆN BỞI HỒNG PHƯỚC & NGỌC HÂN`
- Cuối trang (footer): `Thiệp cưới được thực hiện bởi Hồng Phước & Ngọc Hân`

Ảnh cưới, nhạc, nội dung và thiết kế thiệp thuộc về cô dâu chú rể. Không sao chép, chỉnh sửa hoặc dùng lại cho thiệp khác khi chưa được đồng ý. Muốn tham khảo code, vui lòng liên hệ và giữ nguyên watermark trên.

Font chữ trong `assets/fonts/` dùng giấy phép SIL Open Font License 1.1 (xem các file `*-OFL.txt`), không thuộc phạm vi bản quyền trên.

Chi tiết: xem file [LICENSE](LICENSE).
