# Ôn phỏng vấn Sea Soul

Trang ôn tập cho vị trí **Marketing Executive** tại Sea Soul Hotel Nha Trang. Có hai bản, mỗi bản là một file HTML, không cần build:

- `index.html`: bản đầy đủ, hợp với màn hình lớn.
- `mobile.html`: cùng nội dung, trình bày cho điện thoại. Mở bằng nút **Bản cho điện thoại** ở đầu `index.html`.

## Xem trang

- Mở trực tiếp `index.html` hoặc `mobile.html` bằng trình duyệt, hoặc
- Bật GitHub Pages: **Settings → Pages → Deploy from a branch → `master` / root**, sau đó vào `https://daycd1905.github.io/sea-soul/` (bản điện thoại: `https://daycd1905.github.io/sea-soul/mobile.html`).

## Nội dung

| Tab | Có gì |
| --- | --- |
| Tổng quan | Số liệu chính, các tầng chức năng, 6 hạng phòng, review, 84 bài viết theo chủ đề |
| Lỗi website | 11 điểm, mỗi điểm có bằng chứng, lý do quan trọng và cách nói khi phỏng vấn |
| Khớp JD | Đối chiếu tin tuyển dụng của Sea Soul (HotelJob, 04/2026) với hồ sơ |
| Giới thiệu | Kịch bản 60 giây tiếng Việt và tiếng Anh, bảng nối kinh nghiệm cũ |
| Câu hỏi | 45 câu hay gặp, lọc theo nhóm |
| Kế hoạch | 3 ý tưởng có cách đo, kế hoạch 30–60–90 ngày |
| Kiến thức ngành | OCC, ADR, RevPAR, kênh trực tiếp và OTA, mùa vụ |
| Chuẩn bị | Checklist (trình duyệt tự nhớ), câu nên hỏi lại, bài test, nguồn |

## Bản cho điện thoại

- Cùng 8 mục như bảng trên. Thanh dưới đáy màn hình có nút ‹ › để đọc lần lượt, nút ở giữa mở danh sách mục.
- 11 điểm website và các câu hỏi gập sẵn, chạm để mở. Bảng hạng phòng và bảng khớp JD chuyển thành danh sách, không phải kéo ngang.
- Nút chuyển giữa hai bản giữ nguyên mục đang xem.
- Khi xem qua GitHub Pages, checklist ở mục Chuẩn bị dùng chung giữa hai bản trên cùng trình duyệt.
- **Nội dung nằm ở cả hai file.** Khi sửa, ví dụ điền 11 chỗ tô vàng, nhớ sửa cả `index.html` và `mobile.html`. Bản mobile ghi "mục" ở chỗ bản gốc ghi "tab".

## Thư mục khác

Bài về nhà sau buổi phỏng vấn, độc lập với hai trang trên. Mỗi thư mục có README riêng.

| Thư mục | Có gì |
| --- | --- |
| [`tim-hieu/`](tim-hieu/) | Dữ liệu công khai về Sea Soul và phân tích: 4 file md, 84 bài web và 241 bài Fanpage dạng CSV |
| [`de-xuat/`](de-xuat/) | Đề xuất chiến dịch 20/10, Halloween, Giáng sinh, bài học từ Fanpage. Thư mục con chứa hình mẫu, logo và file gốc của hình |
| [`bao-cao/`](bao-cao/) | 2 bản PDF đang dùng và file gốc HTML |
| [`luu-tru/`](luu-tru/) | Bản cũ và bản backup, không sửa tiếp |

## Dùng với Claude Project

Tải lên **các file nằm ngay trong** `tim-hieu/`, `de-xuat/` và `bao-cao/`, không lấy thư mục con. Tổng cộng 14 file:

- `tim-hieu/`: `README.md`, `1-da-lam.md`, `2-san-pham.md`, `3-phan-tich.md`, `4-facebook.md`, `bai-viet.csv`, `bai-facebook.csv`
- `de-xuat/`: `README.md`, `1-20-10-halloween.md`, `2-giang-sinh.md`, `3-bai-hoc-va-dieu-chinh.md`
- `bao-cao/`: `README.md`, `bao-cao-chuong-trinh-da-chay.pdf`, `bao-cao-mua-le-hoi-2026.pdf`

Ba file `README.md` trùng tên nhưng khác nội dung, dòng tiêu đề đầu file cho biết file nào là của thư mục nào. Không tải `luu-tru/`, `index.html`, `mobile.html` và các thư mục `hinh/`, `nguon/`, `cach-lam/`. Khi sửa file trên máy, xoá bản cũ trong Project rồi tải lại.

Đoạn dán vào mục **Instructions** của Project:

```
Bối cảnh: Kim Huệ ứng tuyển Marketing Executive tại Sea Soul Hotel Nha Trang.
File trong project gồm dữ liệu công khai (web seasoulhotel.vn cào ngày 12/10/2026,
2 Fanpage quét ngày 12–13/10/2026), phân tích, và đề xuất chiến dịch mùa lễ hội 2026–2027.

- Trả lời bằng tiếng Việt, ngắn gọn.
- Khi nêu số liệu, ghi rõ lấy từ file nào.
- Chưa có số liệu nội bộ (doanh thu, công suất phòng, tỷ lệ đặt trực tiếp/OTA), giá OTA,
  TikTok, Instagram. Không tự đoán; nói rõ là chưa có dữ liệu.
- Số liệu gốc nằm trong bai-viet.csv (web) và bai-facebook.csv (Fanpage).
  Nếu PDF và CSV lệch nhau thì theo CSV.
- Giá, ngân sách và KPI trong các đề xuất đều chưa được khách sạn duyệt.
```

## Ghi chú

- Điểm review và tin tuyển dụng là ảnh chụp ngày 06/10/2026.
- Trang có thẻ `noindex` để Google không lập chỉ mục. Tuy vậy, GitHub Pages bản miễn phí chỉ chạy với repo public, nên ai có link vẫn xem được.
- Trang có thông tin cá nhân của Kim Huệ và liệt kê điểm yếu trên website của khách sạn. Cân nhắc kỹ trước khi để public.
