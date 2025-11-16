# Cấu trúc thư mục Playwright Framework

## 1. `tests/` -- Testcase theo module/page

Cấu trúc **module → page → file .spec.ts**.

    tests/
    ├── login/
    │   └── login.spec.ts
    ├── dashboard/
    │   ├── home.spec.ts
    │   └── update.spec.ts
    └── logout/
        └── logout.spec.ts

## 2. `fixtures/` -- Khởi tạo dữ liệu và context dùng chung

    fixtures/
    ├── login/
    │   └── login.fixture.ts
    ├── product/
    │   └── product.fixture.ts
    └── user/
        └── user.fixture.ts

## 3. `utils/` -- Hàm dùng chung

    utils/
    ├── dateUtils.ts
    └── apiHelper.ts

## 4. `pom/` -- Page Object Model

    pom/
    ├── login/
    │   └── Login.page.ts
    ├── dashboard/
    │   ├── Home.page.ts
    │   └── Update.page.ts
    └── logout/
        └── Logout.page.ts

**Ghi chú**: 

- Mỗi module trong tests/ sẽ có module tương ứng trong pom/.

- Mỗi file .spec.ts trong tests/ sẽ có file .page.ts tương ứng trong pom/.

- Chỉ khác biệt duy nhất: đổi hậu tố *.spec.ts → *.page.ts.
## 5. `playwright.config.ts` -- File config chính

## 6. `.env` -- Biến môi trường

## 7. `.gitignore` -- Ignore file trong Git

## 8. `.github/` -- CI/CD Workflow
