# EDUAI Reports – Hệ thống AI tạo báo cáo giáo dục

Dự án này được xây dựng bằng **Google Apps Script** và Google Sheets để:
- Tự động tạo báo cáo cho từng trường
- Phân tích dữ liệu 2 giai đoạn
- Sinh nhận xét bằng AI
- Tạo file so sánh giai đoạn

## Cấu trúc mã nguồn

- `ai.gs` – Các hàm giao tiếp với UI và xử lý AI
- `report.gs` – Tạo báo cáo cho từng giai đoạn
- `reportComparison.gs` – So sánh dữ liệu giữa 2 giai đoạn
- `reportGenerator.gs` – Hàm xử lý chính để tạo báo cáo
- `upload.gs` – Nhận file dữ liệu từ UI
- `web.gs` – Điều khiển Web App + API đầu ra
- `ui.html` – Giao diện HTML của Web App
- `appsscript.json` – Manifest cấu hình Apps Script

## Cách triển khai

1. Tạo Google Spreadsheet mới
2. Mở **Extensions → Apps Script**
3. Copy toàn bộ code từ repo này vào
4. Deploy Web App để sử dụng

> Repo này được tạo để chia sẻ với giáo viên nhằm minh bạch quy trình xử lý và tạo báo cáo AI.
