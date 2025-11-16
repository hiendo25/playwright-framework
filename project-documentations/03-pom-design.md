## POM/

### storefront/

- `home.page.ts` -> Trang chủ, hiển thị danh sách bài viết mới nhất
- `single-post.page.ts` -> Trang chi tiết bài viết, có phần comment
- `category.page.ts` -> Trang lọc bài viết theo danh mục
- `archive-by-month.page.ts` -> Trang lọc bài viết theo tháng đăng

### dashboard/

#### login/

- `login.page.ts` -> Trang đăng nhập

##### dashboard/

- `home.page.ts` -> Trang chính sau khi đăng nhập
- `update.page.ts` -> Trang xem và cập nhật phiên bản WordPress, plugin, theme

##### posts/

- `all-post.page.ts` -> Quản lý danh sách bài viết
- `add-post.page.ts` -> Thêm mới bài viết
- `categories.page.ts` -> Quản lý danh mục bài viết
- `tags.page.ts` -> Quản lý thẻ (tag) bài viết

##### media/

- `library.page.ts` -> Quản lý thư viện hình ảnh
- `add-media.page.ts` -> Thêm mới hình ảnh vào thư viện

##### pages/

- `all-pages.page.ts` -> Quản lý danh sách các trang
- `add-page.page.ts` -> Tạo mới trang

##### comments/

- `comments.page.ts` -> Quản lý bình luận của người dùng

##### appearance/

- `themes.page.ts` -> Quản lý theme đang sử dụng
- `patterns.page.ts` -> Quản lý pattern hiển thị
- `customize.page.ts` -> Tuỳ chỉnh giao diện theme
- `widgets.page.ts` -> Quản lý widget hiển thị
- `menus.page.ts` -> Quản lý menu điều hướng
- `theme-file-editor.page.ts` -> Chỉnh sửa trực tiếp file theme

##### plugins/

- `installed-plugins.page.ts` -> Quản lý plugin đã cài đặt
- `add-plugin.page.ts` -> Cài đặt plugin mới
- `plugin-file-editor.page.ts` -> Chỉnh sửa trực tiếp file plugin

##### Users/

- `all-users.page.ts` -> Quản lý danh sách người dùng
- `add-user.page.ts` -> Thêm mới người dùng
- `profile.page.ts` -> Quản lý và chỉnh sửa thông tin cá nhân

##### tools/

- `availble-tools.page.ts` -> Danh sách công cụ có sẵn
- `import.page.ts` -> Nhập dữ liệu
- `export.page.ts` -> Xuất dữ liệu ra file
- `site-health.page.ts` -> Kiểm tra tình trạng hệ thống
- `export-personal-data.page.ts` -> Xuất dữ liệu cá nhân
- `erase-personal-data.page.ts` -> Xóa dữ liệu cá nhân
- `network-setup.page.ts` -> Cấu hình thiết lập mạng

##### settings/

- `general.page.ts` -> Cài đặt chung cho website
- `writing.page.ts` -> Cài đặt liên quan đến việc viết bài
- `reading.page.ts` -> Cài đặt hiển thị trang chủ và bài viết
- `discussion.page.ts` -> Cài đặt liên quan đến bình luận
- `media.page.ts` -> Cài đặt kích thước ảnh và xử lý media
- `permalinks.page.ts` -> Cài đặt cấu trúc đường dẫn (URL)
- `privacy.page.ts` -> Cài đặt chính sách bảo mật

##### miniOrange API Authentication/

- `miniOrange-api-authentication.page.ts` -> Quản lý plugin bảo mật miniOrange và theo dõi API truy cập

##### header/

- `header.page.ts` -> Quản lý các thao tác trên header như: click icon comment để điều hướng sang `comments.page.ts`, click vào avatar để điều hướng sang `profile.page.ts`, thao tác logout, chuyển sang giao diện người dùng (view site)

##### footer/

- `footer.page.ts` -> Quản lý các thao tác ở footer như điều hướng liên kết sang trang WordPress
