## 1. Naming

- camelCase: biến, hàm
- PascalCase: class, Page Object
- kebab-case: tên file
- Hàm phải bắt đầu bằng động từ (get, set, update, validate…)

## 2. Formatting

- Dùng **Prettier** để format code cho gọn và sạch

## 3. POM

- File: `*.page.ts`
- Mỗi hàm = 1 action
- **Không assert trong POM**, chỉ assert trong file test

## 4. Test

- File: \*.spec.ts
- 1 test = 1 test case
- Test suite = describe() để gom nhóm các logic chung thành 1 bộ test
- Bên trong 1 describe() có thể chứa nhiều test

## 5. Folder Structure

- `tests/`, `pom/`, `fixtures/` giữ cấu trúc **y chang nhau**
- Chỉ đổi đuôi file:
  - `.spec.ts` → `.page.ts` (POM)
  - `.spec.ts` → `.fixture.ts` (Fixtures)
