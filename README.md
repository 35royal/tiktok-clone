## tiktok-clone : Lưu trữ video, có xây dựng Base_URL để thay thế đường dẫn, không cần sửa logic xử lý, chỉ cần sửa các BASE_URL

</br>

## Đây là code base, dùng để xây dựng các chương trình mới
 **Mỗi lần truy cập, xem video sẽ lưu vào cache để lướt lại không cần tải từ server. Mỗi lần thoát ra và truy cập thì tiến trình lặp lại**

</br>

## giải thích:
            // - BASE_URL_VIDEO: Đường dẫn gốc đến thư mục chứa video.
            // - VIDEOS_JSON_URL: Đường dẫn đến file JSON chứa thông tin video.
            // - REPOSITORY_PROJECT_ROOT: Đường dẫn gốc của dự án, dùng để đăng ký Service Worker.
            // - Nếu đang chạy trên GitHub Pages, sử dụng đường dẫn từ kho lưu trữ.
            // - Nếu đang chạy trên localhost, sử dụng đường dẫn cục bộ.
            // - Nếu đang chạy trên một tên miền khác, sử dụng đường dẫn tương ứng.
            // - Đảm bảo các đường dẫn này được cấu hình đúng để tải video và JSON từ đúng nguồn.
