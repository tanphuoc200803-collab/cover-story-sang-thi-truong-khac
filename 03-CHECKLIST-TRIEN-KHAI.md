# Checklist triển khai 2 kênh (DE + PL)

## 0. Việc cần bạn bổ sung (mình không lấy được do YouTube chặn crawl)
- [ ] Export danh sách video kênh gốc + view/CTR/AVD (YouTube Studio → Analytics → Content → Export CSV)
- [ ] Gửi mình top 20 video theo view → mình xếp vào 3 nhóm (bê nguyên / viết lại / bỏ) và viết full script

## 1. Setup kênh
| | Đức | Ba Lan |
|---|---|---|
| Tên kênh | Dr. Berger Gesundheit | dr Kowalczyk — Zdrowie po 50 |
| Ngôn ngữ kênh | de-DE | pl-PL |
| **Impressum trong "About"** | BẮT BUỘC (luật DE) | không bắt buộc |
| Disclaimer y tế cố định | có, mọi mô tả video | có, mọi mô tả video |
| Lịch đăng | 3/tuần, 18:00 CET | 4/tuần + 5 Shorts, 19:00 CET |

## 2. Pipeline sản xuất 1 video
1. Chọn kịch bản gốc → 2. Dịch bản địa hóa theo ma trận (file 00) → 3. **Người bản xứ soát** (bắt buộc với PL) → 4. TTS chất lượng cao (ElevenLabs, giọng nam 50+) → 5. B-roll + on-screen text theo ngôn ngữ đích (không để chữ tiếng Anh trong hình) → 6. Thumbnail riêng từng thị trường → 7. Đăng + ghim comment câu hỏi.

## 3. Rủi ro & phòng ngừa
- **DE / HWG:** không hứa chữa khỏi; tránh nêu tên thuốc kèm khuyến nghị ngừng thuốc. Xem bảng "từ ngữ cấm" ở file 01.
- **YouTube medical misinformation policy:** không phủ nhận điều trị chuẩn, không chống vaccine → mất kiếm tiền cả kênh.
- **Persona bác sĩ hư cấu:** khai rõ trong About là kênh giáo dục sức khỏe, nội dung do đội ngũ biên soạn, hoặc dùng tên thương hiệu thay vì học vị "dr. med." — ở Đức mạo danh chức danh bác sĩ có rủi ro pháp lý thực sự.
- **AI disclosure:** bật "altered/synthetic content" nếu dùng giọng/hình AI.

## 4. KPI 90 ngày
| | DE | PL |
|---|---|---|
| CTR | ≥ 5% | ≥ 7% |
| AVD | ≥ 45% | ≥ 40% |
| Tốc độ đạt 4.000h | chậm hơn ~35% | nhanh nhất |
| RPM kỳ vọng | 8–20 USD | 2–5 USD |

## Files
- `00-PHAN-TICH-THI-TRUONG.md` — phân tích khán giả + ma trận bản địa hóa
- `01-KICH-BAN-DUC.md` — 2 kịch bản DE + thư viện tiêu đề + từ cấm HWG
- `02-KICH-BAN-BA-LAN.md` — 2 kịch bản PL + Shorts + checklist lỗi dịch
