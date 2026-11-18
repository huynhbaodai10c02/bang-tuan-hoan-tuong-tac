# Bảng Tuần Hoàn Hóa Học — 118 Nguyên Tố IUPAC

Ứng dụng web tĩnh (React + TypeScript + Vite + Tailwind CSS + Framer Motion) tra cứu 118 nguyên tố hóa học, cấu hình electron, mô hình Bohr, sơ đồ ô orbital (quy tắc Hund) và bộ chuyển đổi cấu hình electron. Không cần backend hay API key.

## Đưa lên GitHub Pages

1. Đẩy toàn bộ mã nguồn lên repository GitHub (nhánh `main` hoặc `master`).
2. Trên GitHub, vào **Settings → Pages → Build and deployment → Source** và chọn **GitHub Actions**.
3. Workflow `.github/workflows/deploy.yml` sẽ tự động kiểm tra kiểu, chạy unit test, build `dist/` và phát hành lên địa chỉ `https://<ten-tai-khoan>.github.io/<ten-repo>/`.

## Chạy và build cục bộ

```bash
npm install
npm run dev     # Chạy môi trường phát triển tại http://localhost:3000
npm run lint    # Kiểm tra kiểu TypeScript
npm run build   # Xuất bản tĩnh vào thư mục dist/
```
