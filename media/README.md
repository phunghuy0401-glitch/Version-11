# Thư mục media

Đặt video MP4 / WebM chính thức tại đây. Ví dụ:

- `19-11-chuyen-ha-long.mp4`
- `poster-19-11.webp` (nếu có ảnh poster)

Cấu hình nguồn video nằm trong `video-config.js`, không nằm trong `data.js`.

## Dùng YouTube

Mở website với `?media-admin=1`, dán link video và chọn **Kiểm tra link**. Sau đó tải file cấu hình và thay `video-config.js`.

## Dùng MP4 / WebM

Mở website với `?media-admin=1`, kéo thả hoặc chọn tệp. Sau khi kiểm tra xong, tải cấu hình. Đặt video vào đúng thư mục `media/` với đúng tên đường dẫn trong file cấu hình; ví dụ `media/clip-1911.mp4`.

## Quan trọng

Trình duyệt không thể tự tải tệp video lên web hosting khi website không có backend. Công cụ quản trị chỉ xem thử trên máy hiện tại và tạo file cấu hình. Bạn vẫn cần tải video cùng website lên hosting / CDN. Không nên dùng MP4 dung lượng rất lớn trên hosting yếu; ưu tiên YouTube Unlisted hoặc CDN video.
