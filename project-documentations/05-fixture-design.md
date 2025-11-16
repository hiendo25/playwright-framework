## Fixtures

**Mục đích:** Quản lý cấu trúc folder `tests`, `pom`, `fixtures` đồng bộ theo module.  
Mỗi module sẽ có 3 phần tương ứng:

- `*.page.ts` trong **POM** → thao tác UI
- `*.spec.ts` trong **tests** → test case
- `*.fixture.ts` trong **fixtures** → dữ liệu, context, setup

---

### storefront/

- `home.fixture.ts` -> Fixture cho trang chủ
- `single-post.fixture.ts` -> Fixture cho trang chi tiết bài viết
- `category.fixture.ts` -> Fixture cho trang lọc theo danh mục
- `archive-by-month.fixture.ts` -> Fixture cho trang lọc theo tháng đăng

### dashboard/

#### login/

- `login.fixture.ts` -> Fixture cho dữ liệu đăng nhập

##### dashboard/

- `home.fixture.ts` -> Fixture cho trang chính sau khi đăng nhập
- `update.fixture.ts` -> Fixture cho trang cập nhật WordPress, plugin, theme

##### posts/

- `all-post.fixture.ts` -> Fixture cho danh sách bài viết
- `add-post.fixture.ts` -> Fixture cho dữ liệu thêm bài viết mới
- `categories.fixture.ts` -> Fixture cho dữ liệu danh mục bài viết
- `tags.fixture.ts` -> Fixture cho dữ liệu tag

##### media/

- `library.fixture.ts` -> Fixture cho thư viện hình ảnh mẫu
- `add-media.fixture.ts` -> Fixture cho dữ liệu thêm hình ảnh

##### pages/

- `all-pages.fixture.ts` -> Fixture cho danh sách trang tĩnh
- `add-page.fixture.ts` -> Fixture cho dữ liệu tạo trang mới

##### comments/

- `comments.fixture.ts` -> Fixture cho dữ liệu bình luận mẫu

##### appearance/

- `themes.fixture.ts` -> Fixture cho dữ liệu theme
- `patterns.fixture.ts` -> Fixture cho dữ liệu pattern
- `customize.fixture.ts` -> Fixture cho dữ liệu tuỳ chỉnh theme
- `widgets.fixture.ts` -> Fixture cho dữ liệu widget
- `menus.fixture.ts` -> Fixture cho dữ liệu menu
- `theme-file-editor.fixture.ts` -> Fixture cho dữ liệu file theme

##### plugins/

- `installed-plugins.fixture.ts` -> Fixture cho danh sách plugin đã cài
- `add-plugin.fixture.ts` -> Fixture cho dữ liệu thêm plugin mới
- `plugin-file-editor.fixture.ts` -> Fixture cho dữ liệu file plugin

##### Users/

- `all-users.fixture.ts` -> Fixture cho danh sách người dùng
- `add-user.fixture.ts` -> Fixture cho dữ liệu thêm người dùng
- `profile.fixture.ts` -> Fixture cho dữ liệu profile cá nhân

##### tools/

- `availble-tools.fixture.ts` -> Fixture cho danh sách công cụ
- `import.fixture.ts` -> Fixture cho dữ liệu import
- `export.fixture.ts` -> Fixture cho dữ liệu export
- `site-health.fixture.ts` -> Fixture cho dữ liệu kiểm tra hệ thống
- `export-personal-data.fixture.ts` -> Fixture cho dữ liệu xuất thông tin cá nhân
- `erase-personal-data.fixture.ts` -> Fixture cho dữ liệu xóa thông tin cá nhân
- `network-setup.fixture.ts` -> Fixture cho dữ liệu cấu hình mạng

##### settings/

- `general.fixture.ts` -> Fixture cho dữ liệu cài đặt chung
- `writing.fixture.ts` -> Fixture cho dữ liệu cài đặt viết bài
- `reading.fixture.ts` -> Fixture cho dữ liệu cài đặt hiển thị
- `discussion.fixture.ts` -> Fixture cho dữ liệu cài đặt bình luận
- `media.fixture.ts` -> Fixture cho dữ liệu cài đặt media
- `permalinks.fixture.ts` -> Fixture cho dữ liệu cài đặt URL
- `privacy.fixture.ts` -> Fixture cho dữ liệu cài đặt bảo mật

##### miniOrange API Authentication/

- `miniOrange-api-authentication.fixture.ts` -> Fixture cho dữ liệu plugin miniOrange

##### header/

- `header.fixture.ts` -> Fixture cho dữ liệu thao tác header (comment, profile, logout)

##### footer/

- `footer.fixture.ts` -> Fixture cho dữ liệu thao tác footer (link WordPress)
