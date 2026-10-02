# N2B — POST-EXECUTION MICRO-REPAIR REPORT — TÀN CỤC

**Phạm vi:** chỉ kiểm hệ quả trực tiếp của commit `a75a03c` (thực thi AD-N2-01…11). Không phải N2B tổng thể. Không mở lại quyết định, không nén, không tái cấu trúc, không sửa continuity, không tạo canon.

**Kết luận ngắn:** 3 micro-repair (2 tập), 0 dependency bị chặn (BLOCKED), 0 khôi phục nội dung đã cắt. Hai trong ba micro-repair là lỗi do chính các dòng tôi thêm ở lượt thực thi (AD-N2-01) gây ra, không phải do phần cắt.

## 1. Cảnh đã kiểm

| Mục | Vị trí | Kết quả |
|---|---|---|
| 1 | `ep7.txt` sc.35 (~dòng 1081–1103) | **MICRO-REPAIR** |
| 2 | `ep8.txt` sc.118 (~dòng 3190–3210) | **SAFE**, không sửa |
| 3 | `ep5.txt` sc.8, 19, 20, 22, 24, 26, 27 và mọi cảnh sau | **SAFE**, không BLOCKED |
| 4 | Tìm kiếm toàn bản thảo cho AD-N2-03/05/07/09/11 | Xem mục 4 |
| (phát sinh) | `ep9.txt` sc.30 (dòng thêm cho AD-N2-01) | **MICRO-REPAIR** |
| (phát sinh) | `ep7.txt` sc.61 (dòng thêm cho AD-N2-08), `ep8.txt` sc.101 (dòng sửa cho AD-N2-02) | **SAFE** |

## 2. Micro-repair đã làm (3 chỗ)

### R-1. `ep7.txt` sc.35: câu đùa của Lục Trầm

- **Vấn đề:** sau khi bỏ lượt "Có manh mối / Không nói", câu "Ngài ấy với cô thật sự rất hợp." đứng ngay sau "Vẫn mất tích." / "Có thể." mà không có mồi. Mồi cũ chính là sự giấu giếm "Không nói".
- **Trước:** `Lục Trầm quay sang Chiêu Ninh. “Ngài ấy với cô thật sự rất hợp.”`
- **Sau:** `Lục Trầm nhìn hai người hỏi đáp, rồi quay sang Chiêu Ninh. “Ngài ấy với cô thật sự rất hợp.”`
- **Lý do:** neo câu đùa vào điều đang có ngay trên trang (Chiêu Ninh và Hoài Xuyên trao đổi bằng câu cụt, như cả cảnh). Giữ nguyên chữ câu đùa, nhịp "Ngươi muốn bị đuổi không?" và beat quan hệ. Không khôi phục lượt đã bỏ, không thêm thông tin.

### R-2. `ep9.txt` sc.30: người nói liền nhau do dòng AD-N2-01 (hai chỗ)

- **Vấn đề:** bốn dòng thoại Tây Uyển tôi thêm ở lượt thực thi tạo ra hai chỗ cùng một người nói hai lượt liên tiếp không có dấu hiệu: (a) Chiêu Ninh "Ừ." rồi lập tức Chiêu Ninh "Còn Tây Uyển?"; (b) Hoài Xuyên "Cùng một cách, chưa chắc cùng một người." rồi lập tức Hoài Xuyên "Cô thất vọng?". Khi nghe, dễ nhầm người nói.
- **Trước:** `“Ừ.” / “Còn Tây Uyển?”` và `“Cùng một cách, chưa chắc cùng một người.” / “Cô thất vọng?”`
- **Sau:** thêm `Nàng im một lúc.` giữa (a), và `Chiêu Ninh gật.` giữa (b).
- **Lý do:** chỉ là nhịp hành động đổi lượt nói, không thêm thông tin; lời thoại của AD-N2-01 không đổi.

## 3. Kiểm chi tiết

### 3.1 `ep8.txt` sc.118: "Ngài không có câu khác?": SAFE

Cảnh hiện tại: "Cô thất vọng?" / "Không." / "Vậy?" / "Ta từng nghĩ người hại nhà ta phải rất lớn." / "Ừ." / *Nàng nhìn hắn.* "Ngài không có câu khác?" / "Có." / "Gì?" / "Chưa xong."

Câu hỏi vẫn có chỗ dựa: Chiêu Ninh vừa nói một câu nặng và chỉ nhận một "Ừ." cụt, đúng thói quen đối đáp của hai người suốt truyện. Hiệu ứng "ba lần Ừ" yếu đi nhưng câu không mồ côi. Không sửa, theo đúng yêu cầu "chỉ sửa nếu cần".

### 3.2 `ep5.txt` AD-N2-07: không BLOCKED

Các điểm kiểm sau khi cắt bản sớ, đơn nặc danh, đứa trẻ đưa thư:

| Cảnh | Hiện trạng | Đánh giá |
|---|---|---|
| sc.8 | "Một Ngự sử ngũ phẩm, không quá nổi bật." rồi "Chiêu Ninh nhìn ngày…" | Liền mạch. Lý do nàng ghi mốc Trịnh Hành bị bớt đi (trước đây là bản sớ), nhưng mốc "Mùng ba tháng Tám — Trịnh Hành chết" vẫn nằm trong sổ ngay trước đó. |
| sc.19 | "Ai giao?" / "Không ai." rồi ngắt cảnh | Liền mạch; không còn câu thừa. |
| sc.20 | Bỏ "Có biết ai gửi đơn?" | Liền mạch ("Cha chắc?" / "Ừ." / "Cha có định cảnh báo ông ấy?"). |
| sc.22 | Thư "hỏi Bắc lộ" còn nguyên; người hầu: "Có người gửi thư." / "Ai?" / "Không biết." | Còn đủ: nguồn thư vẫn "không biết". |
| sc.24 | Chỉ còn "Nghe nói bệnh cấp." / "Thật?" / "Ta không biết." rồi Hoài Xuyên nhìn cửa nhà | Liền mạch. |
| sc.26 | "Thư?" / "Có." / "Đâu?" / "Không thấy." / "Ngươi đọc?" / "Không." rồi vết hằn "…Bắc…, …mười bảy…" | Liền mạch. Vết hằn và thư vẫn đủ cho sc.27 và sc.33. |
| sc.27 | "Không phải bệnh?" / "Chưa biết." / "Giống kiếp trước." / "Có một khác biệt." | Đọc được: "Giống kiếp trước" chỉ còn nói việc cái chết lập lờ như "bệnh cấp". Nghĩa hơi hẹp hơn nhưng không vỡ. |
| Các cảnh sau | sc.28–41; `ep7` sc.62–63 (Trịnh Hành gửi bản) | Không cảnh nào dùng bản sớ, đơn nặc danh hay đứa trẻ. Mọi dependency còn lại (chuỗi Lương Thất, "Và Bắc lộ", sổ bốn thứ, `ep7` sc.63) chỉ dựa vào thư và vết hằn. |

Tìm kiếm `sớ`, `nặc danh`, `đứa trẻ`, `ai gửi`, `gửi đơn`, `người gửi` trong `ep5`–`ep9`: không còn tham chiếu mồ côi. (`ep5:177` "Người đưa thư nói…" là Lương Thất/sổ cũ, việc khác; `ep8:273`, `ep8:1347` là "người gửi bạc/hiệu bạc", việc khác.)

**Kết luận: không có dependency bị phá.** Thư "hỏi Bắc lộ" và vết hằn đủ cho mọi cảnh sau.

## 4. Kiểm toàn cục

| Quyết định | Tìm | Kết quả | Phân loại |
|---|---|---|---|
| **AD-N2-03** (siết tay Từ Kính) | `siết tay`, `Từ Kính` trong EP3–EP9 | Còn cử chỉ "Từ Kính siết tay" ở `EP3:~599` (tự trách khi nói về đổi tuyến), là cử chỉ khác, không thuộc quyết định. `EP3:~727` "Vì hôm qua cô nghe Từ Kính sống thì phản ứng" nói về Chiêu Ninh. Các "siết tay" khác ở EP4/EP7/EP8 là nhân vật khác. | **SAFE** |
| **AD-N2-05** (chủ Tấn Ký "Có manh mối") | `manh mối`, `Không nói`, `chủ Tấn Ký` | `EP4:959`, `ep5:663`, `ep7:1097` còn, không dựa vào lượt đã bỏ. Không có tham chiếu tới "Có manh mối" hay "Không nói" về chủ hiệu. | **SAFE** (một hệ quả đã sửa ở R-1) |
| **AD-N2-07** (Trịnh Hành) | `sớ`, `nặc danh`, `đứa trẻ`, `ai gửi` | Mục 3.2 | **SAFE** |
| **AD-N2-09** (con dấu mẻ) | `con dấu`, `mẻ`, `dấu riêng`, `ngăn thứ ba` | Ngăn thứ ba còn bọc giấy dầu, hai phong thư, sổ mỏng, không cảnh sau nào nhắc "con dấu" của ngăn. "Con dấu" ở `EP4:1531` (kiểu sửa số "không động tới con dấu") và `ep7:1599` (kho An Bình) là vật khác. "Bản kê có dấu riêng" (`ep7:287`, `:1029`) giữ nguyên là ký ức kiếp trước, đúng lựa chọn (a). | **SAFE** |
| **AD-N2-11** (câu luận đề) | `hệ thống`, `mạng lưới`, `vua cờ`, `nút`, `đáng sợ`, `bảo vệ phần mình`, `ngồi một bàn`, `có ích`, `âm mưu không tồn tại` | Không có callback tới câu đã bỏ. `ep9:219` (câu kết giữ lại) đứng độc lập. `ep7:1719` "Có chứng cứ về hệ thống" và `ep8:1995` "nút thứ tư" nằm trước hoặc ngoài các câu bị bỏ. Đọc lại từng chỗ cắt (`ep7` sc.56, 62, 70; `ep8` sc.61, 90, 99, 100, 101, 116, 118): đều liền mạch. | **SAFE** |
| **AD-N2-01** (dòng thêm) | `ep9` sc.30 | Hai chỗ trùng người nói | **MICRO-REPAIR** (R-2) |
| **AD-N2-02, 08** (dòng thêm/sửa) | `ep8` sc.101; `ep7` sc.61 | Đọc lại: luân phiên người nói đúng; dòng bảng đọc được. Lưu ý nhẹ: ẩn dụ "cửa" xuất hiện ở `ep7` sc.61 ("cùng một cửa") và `ep8` sc.100 ("hắn là cửa") với hai nghĩa khác nhau. Không sửa (không phải hệ quả của việc cắt). | **SAFE** |

**BLOCKED:** không có.

## 5. Tài liệu có thể đã cũ (chỉ ghi nhận, không cập nhật)

| Tệp | Chỗ cũ |
|---|---|
| `MASTER_TIMELINE.md` | Dòng "3/8 | Trịnh Hành chết… mất bản sớ" (dòng 67) và tuyến Trịnh Hành "sau một đơn nặc danh" (dòng 147): hai chi tiết đã bỏ khỏi `ep5`. |
| `KNOWLEDGE_MAP.md` | Không nhắc trực tiếp các chi tiết đã bỏ; mục R15 (Trịnh Hành) vẫn đúng. |
| `AUTHOR_DECISIONS.md` | Dòng EP3 "Từ Kính khẽ siết tay" (dòng 335) đã bỏ khỏi `EP3`. |
| `STORY HANDBOOK.txt` | Không nhắc các chi tiết đã bỏ. Vẫn chưa đồng bộ các khóa B1 như ghi ở B1/N2A. |
| `PASS_B1_REPORT.md`, `PASS_N2A_AUDIT.md`, `PASS_N2A_AUTHOR_DECISION_PREP.md`, `PASS_N1B_REPORT.md` | Mô tả các mảnh đã bỏ (đơn nặc danh, bản sớ, con dấu mẻ, siết tay, "Có manh mối") như đang tồn tại. Là hồ sơ lịch sử nên có thể giữ nguyên. |
| `N2B_DECISION_EXECUTION_REPORT.md` | Báo cáo thực thi trước đó chưa nêu hai chỗ trùng người nói ở `ep9` sc.30 (đã sửa ở R-2). |

## 6. Xác nhận

- **Không quyết định đã khóa nào thay đổi.** AD-N2-01…11 giữ đúng như khóa. Micro-repair chỉ là nhịp hành động và một mệnh đề neo.
- **Không canon mới.** Ba chỗ sửa không thêm sự kiện, thông tin, manh mối hay cách hiểu. "Nàng im một lúc", "Chiêu Ninh gật", "nhìn hai người hỏi đáp" chỉ là hành vi nhìn thấy được.
- **Không khôi phục nội dung đã cắt.** Lượt "Có manh mối / Không nói", bản sớ, đơn nặc danh, đứa trẻ, con dấu mẻ, cử chỉ siết tay và các câu luận đề vẫn đã bỏ.
- **Phạm vi tệp:** chỉ `ep7.txt` (một dòng) và `ep9.txt` (hai dòng) cộng báo cáo này. CRLF giữ nguyên (kiểm nhị phân: không có LF/CR lẻ).
- Không bắt đầu N2B tổng thể. Dừng ở đây.
