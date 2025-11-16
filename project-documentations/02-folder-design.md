# Cấu trúc thư mục dự án Playwright Framework


## 1. `tests/` – Quản lý testcase theo từng page/module  
Mỗi **page** = một **folder**. Trong folder đó, chia nhỏ theo từng tính năng (search, add, edit, delete...).  
- Nếu test ngắn, có thể viết chung trong một file, ví dụ `ProductPage.spec.ts`.  
- Nếu logic dài, tách ra nhiều file trong folder `product` tương ứng với từng tính năng.

Ví dụ:
```
tests/
├── login/
│   └── login.spec.ts
├── product/
│   ├── productpage.spec.ts        # test ngắn, gom chung
│   ├── search.spec.ts             # test dài, tách riêng
│   ├── add.spec.ts
│   └── edit.spec.ts
└── logout/
    └── logout.spec.ts
```

---

## 2. `fixtures/` – Setup dữ liệu test  
Mỗi module có thể có fixture riêng để chuẩn bị dữ liệu, login, inject Page Object vào test.  
Ví dụ:
```
fixtures/
├── login/
│   └── login.fixture.ts
├── product/
│   └── product.fixture.ts
└── user/
    └── user.fixture.ts
```

---

## 3. `utils/` – Hàm dùng chung  
Chứa các hàm tiện ích không liên quan UI, dùng lại nhiều nơi (random data, format, gọi API...).  
```
utils/
├── dateUtils.ts
└── apiHelper.ts
```

---

## 4. `pom/` – Page Object Model theo module  
Mỗi module có một folder riêng, bên trong là file class đại diện cho trang đó.  
Ví dụ:
```
pom/
├── login/
│   └── LoginPage.ts
├── product/
│   └── ProductPage.ts
└── logout/
    └── LogoutPage.ts
```

---

## 5. `playwright.config.ts` – File config chính  

## 6. `.env` – Biến môi trường  
Lưu `BASE_URL`, `USERNAME`, `PASSWORD` để dễ thay đổi theo môi trường.

## 7. `.gitignore` – File Git  
Chặn các file/folder không cần thiết khỏi việc push lên GitHub.

## 8. `.github/` – CI/CD  
Chứa workflow GitHub Actions để chạy test tự động.

