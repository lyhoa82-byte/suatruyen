# PASS N2A AUDIT — TÀN CỤC

**Loại:** chỉ chẩn đoán. Không sửa tập nào, không viết lại, không nén, không audio polish, không đổi canon, không đề xuất cốt truyện mới.

**Bản thảo được audit:** bản văn xuôi hiện hành (`EP1.txt`–`EP4.txt`, `ep5.txt`–`ep9.txt`), nhánh `claude/lucid-darwin-ut6g7s`, sau commit `8ce0b7f`. Đã đọc toàn bộ chín tập, `MASTER_STORY_BIBLE.md`, `EDITING_PROTOCOL.md`, `STORY HANDBOOK.txt`, `MASTER_TIMELINE.md`, `KNOWLEDGE_MAP.md`, `PASS_B1_REPORT.md`, `B1_VERIFICATION_REPORT.md`, `PASS_N1A_REPORT.md`, `PASS_N1B_REPORT.md`. `AUTHOR_DECISIONS.md` chỉ dùng để đối chiếu AD-01..04.

**Quy ước định vị.** Bản văn xuôi không còn nhãn cảnh. Mỗi mục ghi **số cảnh theo kịch bản gốc** (EP1–EP4: commit `ba4cc5a`; EP5–EP9: commit `740e338`, cùng cách đánh số mà B1/N1A/N1B đã dùng) và **số dòng của bản hiện hành** (`file:dòng`). Số dòng là dòng của câu thoại đầu tiên của cảnh, nên lệch vài dòng so với đầu cảnh. Số liệu độ dài là ký tự không tính khoảng trắng, đo bằng script.

**Công khai nguồn gốc của một số vấn đề.** Một phần các vấn đề audio ở mục 4 do chính lượt chuyển N1B tạo ra (công thức "không nói gì" thay `“…”`, thẻ "X nói:" thay nhãn người nói, các câu mở đầu "Cùng lúc ấy…" thay tiêu đề cảnh). Những chỗ đó được gắn `[N1B]` để người duyệt biết đó là sản phẩm của chuyển đổi, không phải vấn đề của kịch bản gốc.

---

## 1. Executive Summary

**Quy mô.** 475 cảnh nguồn (EP1–EP4: 111; EP5–EP9: 364), 214.406 ký tự (không khoảng trắng), khoảng 279.000 ký tự thô. Mốc tham chiếu của Bible là 90.000–140.000 ký tự, nhưng Bible và Protocol đều nói độ dài không phải KPI; audit này không đặt mục tiêu giảm.

**Bức tranh chung.** EP1–EP4 vững về cấu trúc: mỗi cảnh có thay đổi về thông tin, quan hệ hoặc lựa chọn. Các vấn đề tập trung từ **EP6 trở đi** và nặng nhất ở **EP7–EP9**, nơi vòng điều tra lặp, câu luận đề lặp, và số lượng tên riêng tăng vọt.

| Nhóm | HIGH | MEDIUM | LOW | Tổng |
|---|---|---|---|---|
| Cấu trúc (mục 2) | 5 | 7 | 3 | 15 |
| Audio (mục 4) | 4 | 6 | 4 | 14 |
| Setup/payoff (mục 3) | — | — | — | 13 mục được hỏi + 11 mục phát sinh (phân loại A/B/C/D) |

**Năm phát hiện nặng nhất:**

1. **EP8 là chuỗi khoảng mười vòng điều tra cùng một khuôn** (tìm mã → tìm người → thẩm vấn → mã kế tiếp), nhiều đoạn 8–11 cảnh liền không đổi quan hệ hay tình thế (S-01). Kèm các đoạn tóm tắt lặp (S-06).
2. **Luận đề "không có chủ mưu, chỉ có một hệ thống" được phát biểu thẳng ít nhất 12 lần** trong EP6–EP9, từ miệng Chiêu Ninh, Hoài Xuyên, Chu Tử Dung, Tĩnh An, Phùng Mậu, cả người kể (S-02). Bible §6 và §11 cấm giải thích/phát biểu bài học trực tiếp.
3. **Nút then chốt của vụ án, Bùi Tấn và Nhị hoàng tử, lần đầu có tên ở EP8 (dòng 2927, 2951)**, tức cảnh 108/123 (khoảng 88% tập), không có hiện diện trước đó ngoài chiếc nhẫn (S-05; E1 ở mục 3.2).
4. **Quá tải mã và tên khi nghe** (K7, D2, N4, N-4, BT-3, PM-6, HX-4, H4, Nam 4, Nam tứ, Ninh Tứ, Kho Bốn, Hạng bốn, Hòm số bốn, Tôn Tứ, Tứ gia) và ít nhất 19 tên riêng mới chỉ riêng EP8 (AU-01, AU-02). Bốn chuỗi thoại không thẻ dài 16–19 đoạn (AU-03).
5. **Nhiều setup nằm im từ EP3–EP4 mà không có dấu hiệu "cố ý để mở"** (Từ Kính, Mã Tam, chủ Tấn Ký, bản năm mục năm LK20, người áo nâu, em gái Hàn Dực), cộng ba chi tiết đạo cụ chỉ xuất hiện một lần (dấu X Thanh Trạch, con dấu mẻ góc, vết xước tủ).

**Về nén.** SAFE: khoảng 4.700 ký tự (2,2% toàn bộ). POSSIBLE: khoảng 54.200 ký tự (25,3%); đây là **phạm vi văn bản cần xem lại**, phần lớn chỉ nên được gộp hoặc rút phần trùng, không phải xóa cả cảnh. RISKY: khoảng 38.200 ký tự trong EP5–EP9 (mục 5). Không có mục tiêu giảm.

**Audit này không làm:** không đo văn chương, không chọn câu hay hơn, không đánh giá lại canon (AD-01..04, EP7 LOCK, EP8–EP9 LOCK đều giữ nguyên), không sửa các mâu thuẫn continuity còn mở ở B1/N1A/N1B (xem mục "Ghi chú ngoài phạm vi" cuối mục 2).

---

## 2. Structure Findings

### 2.1 Bản đồ chức năng theo khối cảnh

Cột "Đổi gì" dùng đúng định nghĩa của yêu cầu: thông tin, quan hệ, tình thế, nhận thức, cảm xúc, lựa chọn, hệ quả. "—" là cảnh không tạo thay đổi mới.

**EP1** (17 cảnh, 25.609 ký tự)

| Cảnh (dòng) | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1 (5) | Cái chết kiếp trước | thông tin, cảm xúc | cốt lõi |
| 2–3 (135, 209) | Tỉnh dậy; ôm mẹ | tình thế, cảm xúc | cốt lõi |
| 4 (303) | Bữa ăn; hồ sơ Lạc Thủy; Trần Quảng | thông tin | cốt lõi |
| 5 (415) | Hành lang A Lục | nhận thức (nhẹ) | gần như gag |
| 6 (483) | Danh sách ngày; Tử Khiêm | thông tin, cảm xúc | gag chen vào phần cốt lõi |
| 7–9 (583, 625, 649) | Ba mốc đúng: kho cháy, Hoàng hậu, Triệu Ngạn | nhận thức | ba lần "đúng" liên tiếp |
| 10–11 (691, 781) | Cha "đừng đụng"; Hoài Xuyên hoãn hôn | quan hệ, thông tin | cốt lõi |
| 12–14 (925, 1111, 1133) | Quán mì; mục tiêu; bến Phúc An | thông tin, lựa chọn, tình thế | cốt lõi |
| 15–17 (1353, 1371, 1469) | Hệ quả: Trần Quảng sang Binh bộ; đêm; Tử Khiêm mượn tiền | hệ quả, nhận thức | cảnh 17 một nửa là gag |

**EP2** (22 cảnh, 15.591)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–3 (5, 55, 113) | Danh sách ký ức; cầu Thanh Bình; về phủ | nhận thức | lần "thử ký ức" thứ nhất |
| 4 (155) | Thư phòng cha | thông tin (nhẹ) | trùng cấu trúc EP1 sc.10 |
| 5–9 (241–503) | Đại Lý Tự: Chu Tử Dung, Lục Trầm mất tích | thông tin, quan hệ | cốt lõi |
| 10–11 (549, 597) | Cửa Nam (thử ký ức thứ hai); bảng ba cột | nhận thức | lần thử thứ hai |
| 12 (627) | Trần Quảng thấy tên Tĩnh An | thông tin | cốt lõi |
| 13–16 (657–825) | Quán mì, thư Lục Trầm, Đại Lý Tự | thông tin | cốt lõi |
| 17–19 (891–1027) | Bữa cơm: cha thừa nhận "vật liệu có vấn đề" | quan hệ, thông tin | cốt lõi |
| 20–22 (1047–1109) | Lục Trầm ở trạm; Hoài Xuyên; Chiêu Ninh đêm | tình thế, nhận thức | cốt lõi |

**EP3** (32 cảnh, 20.849)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–6 (5–247) | Sáng, chờ ở quán trà, Hoài Xuyên cho người nhìn đường, xe đoàn đi qua | tình thế | lần "thử ký ức" thứ ba; cảnh chờ dài |
| 7 (337) | Tin Tây Uyển lệch địa điểm | thông tin | cốt lõi |
| 8–13 (413–665) | Tử Khiêm; Từ Kính khai; khách sảnh | thông tin | cốt lõi, có gag chen |
| 14–20 (703–1045) | Hàn Dực; Mã Tam; Trần Quảng/Chu Tử Dung | thông tin | cốt lõi |
| 21–27 (1105–1419) | Mã Tam khai; "kiếp trước" lỡ miệng; Hàn Dực khai | thông tin, quan hệ | cốt lõi |
| 28–32 (1467–1571) | Sổ Chiêu Ninh; sổ Hoài Xuyên; Trần Quảng; Tử Khiêm; sổ kết | nhận thức | năm cảnh ghi chú/độc thoại liền cuối tập |

**EP4** (40 cảnh, 20.296)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–2 (5, 85) | Bữa sáng; hành lang | quan hệ (nhẹ) | gag mở đầu |
| 3–11 (133–489) | Tủ hồ sơ; cha kể Lạc Thủy; thỏa hiệp | thông tin, quan hệ | cốt lõi (ngăn thứ ba) |
| 12–19 (531–791) | Đại Lý Tự: chuyến mười bảy, mũi tên, Chu Tử Dung | thông tin | cốt lõi |
| 20–25 (841–1057) | Kho Tấn Ký; Mã Tam mất tích | thông tin, hệ quả | cốt lõi |
| 26–29 (1095–1219) | Bản đối chiếu bốn mục; Tử Khiêm | quan hệ | cốt lõi |
| 30–35 (1277–1473) | Hoài Xuyên: bản năm mục, "ba năm" | thông tin, quan hệ | cốt lõi |
| 36–40 (1503–1581) | Trần Quảng; sổ; thư phòng cha; thư thứ ba | thông tin | cảnh 36 là cầu nối A Lục |

**EP5** (41 cảnh, 19.299)

| Cảnh (dòng) | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–4 (5–200) | Phong thư gửi Lục Trầm | thông tin, quan hệ | cốt lõi |
| 5 (201) | Chạy sang Đại Lý Tự | — | cầu nối |
| 6–8 (225–368) | Hàn Dực mất tích lần nữa; sổ ký ức | thông tin | |
| 9–10 (369–424) | Lễ cầu phúc không sự cố | nhận thức | lần thử ký ức thứ tư |
| 11–13 (423–584) | Binh bộ chữ ký ghép; Tử Khiêm về Trịnh Hành | thông tin | gag mặc cả |
| 14–20 (585–826) | Tin Lục Trầm, Thanh Trạch, chị không đi; Trịnh Hành khỏe; đơn nặc danh | thông tin, lựa chọn | |
| 21–27 (891–1078) | Thanh Trạch kho trống; Trịnh Hành chết sai ngày | tình thế, nhận thức | cốt lõi |
| 28 (1079) | Sổ "không còn đo thời điểm" | nhận thức | trùng 36, 41 |
| 29–31 (1109–1228) | Chuỗi Lương Thất → Trịnh Hành → thư | thông tin | cốt lõi |
| 32–36 (1229–1414) | "Tra thứ đang có"; Lục Trầm bị giữ; cha giao thư; sổ "TƯ LIỆU CŨ" | lựa chọn, quan hệ | 36 trùng 28 |
| 37–41 (1415–1562) | Trần Quảng sợ; cáo thị; hộp niêm; Lục Trầm; sổ mới | hệ quả, cảm xúc | |

**EP6** (56 cảnh, 24.097)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1 (5) | A Lục "Mai đi đâu?" | — | lặp điểm kết EP5 |
| 2–3 (39, 105) | Đại Lý Tự bắt đầu lại | thông tin | hai cảnh cùng chỗ |
| 4–9 (157–318) | Trần Quảng chạy khỏi Binh bộ; tới Thẩm phủ; số 720 | tình thế, thông tin | sc.6 gag cầu nối |
| 10–15 (319–614) | Cha và Trần Quảng: 720 là số cân sổ | thông tin | giải thích "cân sổ" lần 1 |
| 16–22 (615–832) | Lục Trầm; hộ vệ; muối; kho; Thanh Trạch | tình thế, hệ quả | |
| 23–28 (833–1116) | Cha thú nhận ký tạm, che cho Trần Quảng | quan hệ, cảm xúc | cốt lõi |
| 29–33 (1117–1200) | Lục Trầm trên xe; kho trống; thư | tình thế, lựa chọn | |
| 34–37 (1201–1354) | Trần Quảng kể lại việc chuyển khoản | thông tin | kể lại sc.24–27 |
| 38–42 (1355–1496) | Lục Trầm thoát; nửa tờ sổ; "Bù" | tình thế, thông tin | cốt lõi |
| 43–44 (1497, 1541) | Tử Khiêm báo tin; Chu Tử Dung | — / thông tin | 43 gag |
| 45–49 (1577–1720) | Gặp Lục Trầm; thư của cha hắn; sổ cân chênh; "không có một gương mặt" | cảm xúc, nhận thức | cốt lõi, câu luận đề đầu tiên |
| 50–56 (1721–1908) | Cha dùng sổ bù; Tử Khiêm; sổ; Hoài Xuyên; Chu Tử Dung; kết | cảm xúc, thông tin | 50–51 lặp sc.36 |

**EP7** (78 cảnh, 28.644)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–3 (5–126) | Tính khoảng chênh; Tử Khiêm sổ chi tiêu | thông tin (nhẹ) | sc.3 gag |
| 4–7 (127–266) | Bản năm mục; Hoài Xuyên từng nghi cha | thông tin, quan hệ | cốt lõi |
| 8–9 (267, 299) | Chiêu Ninh kể dàn ý án | thông tin | đọc lại ở sc.33 |
| 10–13 (321–424) | Cha–con; hồi ức; "trách người vì việc hắn chưa làm" | quan hệ, cảm xúc | 12 tái dùng EP1; 13 trùng 29–31 |
| 14–17 (425–540) | Hoài Xuyên kể nỗ lực LK20 | thông tin | trùng sc.26 |
| 18–21 (541–648) | Tam hoàng tử, Hàn Dực; Trần Quảng–Lục Trầm | thông tin | 20–21 nhẹ |
| 22–28 (649–908) | Hàn Dực khai; "rồi ta dừng"; thuốc độc | thông tin, quan hệ, cảm xúc | cốt lõi (EP7 LOCK) |
| 29–31 (909–996) | Cha–con lần hai về Hoài Xuyên | cảm xúc | trùng sc.11, 13 |
| 32–36 (997–1148) | Bắc Tam; Chu Tử Dung nhận thư | thông tin | 33 trùng 8–9 |
| 37–44 (1149–1410) | Lão Ngô; dấu tam giác; chọn An Bình | thông tin | 41–42 kể lại 38–40 |
| 45–52 (1411–1606) | Đường đi; An Bình; chờ ngoài kho | tình thế | 45–48, 51 nhẹ |
| 53–58 (1607–1784) | Kho giấy; HX-4; về kinh | thông tin, quan hệ | cốt lõi |
| 59–64 (1785–1962) | Hòm Xét số bốn; danh sách người chết; Trịnh Hành gửi bản | thông tin | |
| 65–74 (1963–2256) | Sổ bốn ô; Chu Tử Dung tới Đại Lý Tự; Phùng Mậu | thông tin, quan hệ | cốt lõi |
| 75–78 (2241–2330) | Ba dòng về Hoài Xuyên; Phùng Mậu chạy Nam; chim | cảm xúc, thông tin | |

**EP8** (123 cảnh, 37.653)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–3 (5–136) | Phùng Mậu chạy; gag chim | thông tin | 3 gag |
| 4–14 (137–466) | Lý Khâm; sổ phụ; mã K7/D2/N4; ba thương hộ | thông tin | 11 cảnh điều tra liền |
| 15–19 (467–612) | Bữa cơm; chủ Nam Hưng chết | thông tin (ít) | đầu mối bị loại |
| 20–28 (613–870) | K7/D2 xác nhận; Ninh Tứ; Cao Nhị | thông tin | 9 cảnh điều tra liền |
| 29–35 (871–1046) | Mạnh Thành bị lộ, bị hỏi | thông tin | |
| 36–40 (1047–1144) | Bắt Tôn Tứ, hắn thoát, thẻ Nam 4 | tình thế | cốt lõi |
| 41–51 (1145–1450) | Nam tứ; Giang Châu; bến Hà Nam | thông tin | 11 cảnh điều tra liền |
| 52–61 (1451–1760) | Hứa Nghiêm; Cố Văn Lâm | thông tin | |
| 62–70 (1761–2002) | Hứa Nghiêm khai; Tề Phương; tóm tắt | thông tin | sc.70 tóm tắt |
| 71–82 (2003–2270) | Tin giả về Trần Quảng; phiếu khẩn; tài khoản | lựa chọn, hệ quả | cốt lõi |
| 83–94 (2271–2542) | Bắt lại Tôn Tứ; Phùng Mậu khai; H4 | thông tin | cốt lõi |
| 95–100 (2543–2692) | Bẫy lời Cố Văn Lâm | quan hệ, nhận thức | cốt lõi, 99–100 tóm tắt |
| 101–107 (2693–2894) | Bảng; Phùng Mậu cung; nhẫn | thông tin | 101 tóm tắt |
| 108–118 (2895–3258) | Bùi Tấn | thông tin, cảm xúc | cốt lõi |
| 119–123 (3259–3360) | Tờ đề nghị; gia đình; sổ; kết | hệ quả, cảm xúc | |

**EP9** (66 cảnh, 22.368)

| Cảnh | Chức năng | Đổi gì | Ghi chú |
|---|---|---|---|
| 1–5 (5–182) | Sáng thường; sổ cũ; cuộc tra; ba tầng; chim | nhận thức | |
| 6–10 (183–350) | Cố Văn Lâm; Bùi Tấn; Nhị hoàng tử | thông tin | |
| 11–14 (351–458) | Cha–con; chim; chợ vải; sổ | cảm xúc, nhận thức | 13–14 lặp sc.2 |
| 15–19 (459–610) | Hủy hồ sơ; trà lạnh; truy tố | hệ quả, quan hệ | cốt lõi |
| 20–25 (611–798) | Trần Quảng, Hàn Dực, cha đình chức | hệ quả, quan hệ | |
| 26–31 (795–962) | Túi; công văn Lạc Thủy; sổ; cha tưới cây; Tết | cảm xúc, hệ quả | 27 là payoff AD-03 |
| 32–37 (963–1080) | Đếm ngược tới 17/10 | cảm xúc | sáu cảnh |
| 38–44 (1081–1260) | Giỏ quýt | cảm xúc, quan hệ | payoff |
| 45–51 (1261–1388) | Kết luận sơ bộ; túi vá; Trần Quảng; Chu Tử Dung; Hàn Dực; bánh | hệ quả | năm cảnh nhỏ |
| 52–62 (1385–1648) | Hoài Xuyên "có vài thứ"; mẹ hỏi hôn sự; "Lễ."; cầu Thanh Bình | quan hệ | chín cảnh |
| 63–66 (1649–1718) | Chim; sổ "không có ai bị bắt"; kết | cảm xúc | |

### 2.2 Phát hiện cấu trúc

**S-01 — HIGH — Vòng điều tra lặp một khuôn trong EP8** (cảnh 4–14, 20–28, 41–51, 55–61, 83–100)

Khoảng mười vòng cùng cấu trúc: một mã hoặc tên được nêu → đi tìm → hỏi → "Có thể." / "Chưa." → mã kế tiếp. Các vòng: Lý Khâm và K7/D2/N4; Ninh Tứ và Cao Nhị; Mạnh Thành; Tôn Tứ; Nam tứ; Hứa Nghiêm; Cố Văn Lâm; Tề Phương; Phùng Mậu; Bùi Tấn. Có những đoạn 8–11 cảnh liền (cảnh 4–14, 20–28, 41–51) chỉ thêm dữ kiện hoặc loại trừ một đầu mối mà không đổi quan hệ, tình thế hay cảm xúc. Bible §7: "Không để nhiều cảnh liên tiếp chỉ gồm điều tra, suy luận hoặc giải thích." Mỗi vòng riêng lẻ đều có thông tin mới; vấn đề là khuôn lặp và mật độ.

**S-02 — HIGH — Luận đề "không có chủ mưu, là một hệ thống" bị nói thẳng nhiều lần**

Các câu phát biểu (hoặc gần như phát biểu) luận đề, theo thứ tự: EP6 sc.13 ("Không một nha môn nào…"), sc.49 ("Không có một gương mặt"); EP7 sc.56 ("Mạng lưới sống được vì nó trộn thật với giả"), sc.62 ("tạo ra một âm mưu không tồn tại"), sc.70 (Chu Tử Dung: "Ta không nghĩ có một người… Bọn họ không cần cùng ngồi một bàn"); EP8 sc.61 ("Chỉ cần mỗi người bảo vệ phần mình"), sc.90 (Phùng Mậu: "Vì nó có ích… Khi có án, nó tạo giấy"), sc.99 (người kể: "Nút thứ tư không phải đồng phạm"), sc.100 ("Hệ thống chỉ cần đưa hồ sơ tới đúng người tin"), sc.101 ("Không có một vua cờ"), sc.116 ("Không phải vua của toàn hệ thống"), sc.118 ("một hệ thống vốn đã bẩn"); EP9 sc.6 ("Một hệ thống có thể lừa được người cẩn thận…"). Từ lần thứ hai trở đi, không câu nào thêm thông tin. Bible §6 ("Narrator không… moralize") và §11 ("Bài học không được phát biểu trực tiếp") áp dụng; Handbook §10 #3 đưa luận đề này làm core theme, nên vấn đề là cách nói (phát biểu thay vì để cảnh nói), không phải nội dung.

**S-03 — HIGH — Món nợ Chiêu Ninh–Hoài Xuyên bị suy lại nhiều lần trong EP7**

Cùng kết luận ("hắn tin chứng cứ; hắn đã đưa; hắn đã dừng; người có thể vừa cố cứu vừa làm chết") được dẫn ra ở: sc.11 (với cha), sc.12 (hồi ức), sc.13 (cha–con), sc.26–27 (Hoài Xuyên "rồi ta dừng"; "Kiếp trước… Kiếp này…"), sc.28 (thuốc độc), sc.29–31 (cha–con lần hai), sc.58 (xe về), sc.75 (ba dòng trong sổ). Các cảnh 11, 13, 29–31 gần như cùng một cuộc nói chuyện hai lần (B1 mục B đã ghi). Sc.28 và sc.75 là hai đỉnh cảm xúc thật sự và không bị tính vào mục này.

**S-04 — HIGH — Điểm kết tập lặp**

Bốn trong năm tập EP5–EP9 kết bằng cùng một nhịp: Chiêu Ninh một mình với sổ, A Lục ngoài cửa ("Có phải chạy không?" / "Mai dậy rồi tính"), và một câu nói về việc không còn tương lai biết trước (EP5 sc.41: "không có ngày mai nào được viết sẵn"; EP6 sc.56: "không còn tương lai để hỏi nữa"; EP8 sc.123: "chưa có gì để chạy"; EP9 sc.66: "nàng không cần biết"). EP9 còn lặp nhịp này trong tập ở sc.14, 28, 32, 55–56, 64–65. Thiết bị "viết → gạch → viết lại" thuộc về tính cách Chiêu Ninh (Handbook mục 11: "kết luận quá sớm rồi tự sửa") nên không vấn đề riêng; vấn đề là tần suất ở điểm kết tập.

**S-05 — HIGH — Bùi Tấn và Nhị hoàng tử xuất hiện muộn, không có nền**

`ep8.txt:2927` ("Nhị hoàng tử") và `:2951` ("Bùi Tấn") là lần đầu hai cái tên xuất hiện trong toàn bộ bản thảo (EP1–EP7: 0 lần). Chiếc nhẫn (EP7:663, EP8:2839) là manh mối duy nhất trước đó và không mang tên. Người dựng vụ án giả được nêu tên ở cảnh 108–109 trên 123 cảnh (khoảng 88% EP8), rồi bị bắt và khai ở cảnh 113–118. Bible §5: "Manh mối phải gieo trước." AD-04 cho phép không có Final Boss, nhưng không nói người nối thẳng với việc dựng hồ sơ Thẩm gia có thể xuất hiện lần đầu ở phần cuối của vụ án. Liên quan E1 (mục 3.2).

**S-06 — MEDIUM — Tóm tắt lặp ở EP8–EP9**

Cảnh sc.70 (Chiêu Ninh tóm tắt ba người đã nhận phần), sc.99–100 (người kể rồi Chiêu Ninh cùng nói Cố Văn Lâm không phải đồng phạm, là "cửa"), sc.101 (bảng cuối), sc.116 (danh sách "Cố Văn Lâm? Không. Tề Phương? Không…"), EP9 sc.4 (ba tầng), sc.7 (Chiêu Ninh–Hoài Xuyên nói lại về Cố Văn Lâm), sc.19 (danh sách truy tố). Cùng một bảng phân vai được lập lại 6–7 lần trong khoảng 60 cảnh.

**S-07 — MEDIUM — EP6: một sự kiện LK19 được kể ba lần, một khái niệm được giải thích hai lần**

Tĩnh An ký xác nhận tạm, dùng bù khoản, che cho Trần Quảng được kể bởi cha (sc.24–27), kể lại bởi Trần Quảng (sc.34–37), rồi cha lại (sc.50–51). Cả hai nhân vật dùng cùng câu "nếu quay lại, không biết" (sc.36, sc.51, và sc.51 nói rõ "Trần Quảng cũng nói vậy"). Cơ chế sổ bù được giải thích ở sc.11–13 rồi lại ở sc.47–48. Mỗi lần có chi tiết mới, nhưng ba lần kể và hai lần giải thích cho cùng một kết luận.

**S-08 — MEDIUM — EP7: trùng ý trong tập**

Dàn ý án của Chiêu Ninh (sc.8–9) được Hoài Xuyên đọc lại (sc.33). "Ta xin tra tiếp" ở sc.15 và sc.26 (B1 mục B). Sc.41 kể lại điều Tử Khiêm vừa nghe ở sc.38–40 trước khi tới một đoạn gag. Sc.12 dựng lại EP1 sc.1.

**S-09 — MEDIUM — EP9: hậu quả dài sau điểm ngoặt**

Điểm ngoặt của EP9 là hồ sơ bị hủy (sc.15–19). Từ sc.20 đến sc.66 còn 47 cảnh (khoảng 68% độ dài tập, tính từ điểm truy tố). Phần lớn là payoff có lý (túi vá, giỏ quýt, "Lễ."), và Bible §7 cho phép khoảng lặng sau payoff lớn. Vấn đề là cùng một nhịp bị lặp: ấm áp của cha (sc.17, 25, 29, 46, 51); Chiêu Ninh–Hoài Xuyên chậm nóng qua chín cảnh (sc.16, 43–44, 52–53, 57–59, 61–62); sáu cảnh đếm ngược tới 17/10 (sc.32–37) cho một nhịp chờ; chim "Không!" trong sc.5, 12, 18, 37, 63.

**S-10 — MEDIUM — Vòng cảnh cha–con (kể, hỏi, đối chiếu)**

Khoảng 21 khối: EP5 sc.2–4, 20, 29–31, 35; EP6 sc.10–13, 23–27, 50–51; EP7 sc.10–11, 13, 29–31, 63–64; EP8 sc.15–16, 41–42, 60–61, 71, 93, 108–109, 120; EP9 sc.11–12, 17, 24–25, 29, 46, 51. Nhiều khối mang thông tin thật; nhiều khối chỉ truyền lại điều khán giả vừa thấy và nhận "Ừ."

**S-11 — MEDIUM — Cảnh "thử ký ức, ký ức hụt" lặp**

EP2 sc.2–3 (cầu), sc.10 (cửa Nam), EP3 sc.2–6 (Tây Uyển), EP5 sc.9–10 (lễ cầu phúc), sc.23 (Trịnh Hành). Từ lần thứ ba trở đi mỗi lần chỉ nhắc lại ý "ký ức mất giá trị"; EP5 sc.9–10 có nâng thêm ("ngay cả kết quả cũng không còn") và EP5 sc.23 là bước ngoặt thật. Handbook EP5 đã giao nhiệm vụ này cho tập đó, nên các lần trước là tích lũy hợp lý; vấn đề ở mật độ.

**S-12 — MEDIUM — Đồng hồ và áp lực lên Thẩm gia hiện ra muộn**

Áp lực trên trang rơi vào các nhân vật phụ (Lục Trầm, Trần Quảng, Hàn Dực, Mã Tam, Trịnh Hành). Từ EP6 sc.44 ("Thẩm gia… Chưa.") đến EP9 sc.32 (ngày 17/10 lần đầu được nêu thành hạn), khoảng 240 cảnh, không có cảnh nào cho thấy một hành động cụ thể nhắm thẳng vào nhà Thẩm; mối đe dọa với họ chỉ là hồ sơ Hạng bốn "chưa trình", và người nghe không có hạn chót. EP7–EP8 vận hành chủ yếu bằng suy luận.

**S-13 — LOW — Công thức "Chiêu Ninh tới Đại Lý Tự không được mời"**

EP2, EP3, EP4 (hai lần), EP5, EP6, EP7, EP9: hầu hết bắt đầu bằng "Cô lại tới" / "Có chuyện?" và kết bằng "Ngài học cha ta". Mỗi lần có nội dung mới; công thức lặp.

**S-14 — LOW — Cảnh gag/cầu nối không đổi gì (tích lũy)**

EP5 sc.5; EP6 sc.1, 6, 43; EP7 sc.3, 41–42, 51, 71; EP8 sc.3, 31–32, 80; EP4 sc.36. Mỗi cảnh một chi tiết nhỏ; cộng lại khoảng 4.700 ký tự (mục 5). Chuỗi chim của Tử Khiêm (EP1, EP7 sc.77, EP8 sc.3, EP9 sc.5, 12, 18, 63) có payoff và callback thật nên không tính chung.

**S-15 — LOW — Tần suất thiết bị sổ tay**

Số lần "gạch" theo tập (EP1→EP9): 3, 4, 6, 2, 5, 2, 1, 4, 3 (tổng 30). Đã nêu ở S-04.

### 2.3 Ghi chú ngoài phạm vi (continuity còn mở, chỉ nêu lại, không phải đối tượng N2A)

Các mục này đã được B1/N1A/N1B ghi nhận và vẫn còn nguyên trong bản hiện hành: `EP1.txt:37` ("Hai ngày trước anh trai bị chém", sau cha ba ngày) so với `EP1.txt:573` ("Tử Khiêm chết đầu tiên"); mốc "còn mười ngày" so với 23/7 ở EP5; hai mốc đình chức ở EP9 sc.24 và sc.28; kênh thông tin của Chiêu Ninh tới nhà an toàn (EP6 sc.34) và về "nhẫn" (EP7 sc.29); cảnh Chiêu Ninh nói ngày 17/10 với Hoài Xuyên chưa xuất hiện trước EP9 sc.33/43. Chuyển cho B2.

---

## 3. Setup/Payoff Findings

**Phân loại:** A = ACTIVE SETUP (đã gieo, chưa trả, không có dấu hiệu cố ý để mở); B = ALREADY PAID OFF; C = DELIBERATELY UNRESOLVED (có căn cứ trên trang hoặc trong tài liệu canon); D = POSSIBLE REMOVAL (chi tiết đơn lẻ không có hệ quả, bỏ được mà không đụng mạch chính).

Không có mục nào được đề xuất payoff mới. Cột "Quyết định cần của tác giả" chỉ nêu câu hỏi.

### 3.1 Mười ba mục được hỏi

| # | Mạch | Phân loại | Gieo / lần cuối nhắc | Trạng thái |
|---|---|---|---|---|
| 1 | **Tây Uyển** | **C** (với một điều kiện) | EP2:1113 → `ep7.txt:567` ("Từ sau Tây Uyển, ngươi đứng gần ta hơn") | AD-04 và B1 mục A.6 khóa việc không gán kẻ tổ chức. Nhưng các mảnh con đều bị bỏ lửng từ EP4: tiểu thái giám báo "đường chính kẹt" (EP3:577, 775–777), xe gỗ chắn đường chính "chưa rõ" (EP3:345–353), tiếng chim khách hai lần (EP3:549), mũi tên cấm quân ba loại lông đuôi (EP3:1377; EP4:551–683), xe thật bị tráo (EP3:1105–1167). EP8–EP9 không nhắc lại. Trên trang không có gì cho thấy đây là "cố ý để mở", chỉ đọc là bị bỏ. Cần quyết định: có thêm một dấu hiệu công nhận hay không. |
| 2 | **Từ Kính** | **A** | EP3:497–811 (cứu sống, "siết tay" ở :599, :625) → không còn xuất hiện (EP4–EP9: 0 lần) | Handbook mục 5 liệt kê "Từ Kính sống" là setup đang mở. "Siết tay" khi nghe tên Hàn Dực chưa giải thích. |
| 3 | **Mã Tam** | **A** | EP3:897–1167; EP4:827–867 (mất tích sáng, nhà mẹ trống, có người hỏi Tử Khiêm); `ep7.txt:549, 721` | Biến mất không giải thích; người lấy xe của hắn chưa lộ. EP7:721 chỉ nối "cùng một cách" dọa. EP8–EP9: 0 lần. |
| 4 | **Trịnh Hành** | **C** (phần nguyên nhân chết) / **A** (các mảnh phụ) | EP5 (29 lần), `ep7.txt` (4 lần, gồm danh sách người chết ở sc.62 và "gửi bản" ở sc.63), EP8–EP9: 0 lần | EP7 sc.62 chủ động không gom ("Nếu gom sai… sẽ tạo ra một âm mưu không tồn tại") nên nguyên nhân chết để mở là có căn cứ. Các mảnh phụ không có căn cứ đó: bản sớ, đơn nặc danh, và người gửi thư "hỏi Bắc lộ" (EP5 sc.19, 22). |
| 5 | **Chủ Tấn Ký** | **A** | EP4:959–973 ("đi Lạc Thủy nửa tháng trước"); `ep5.txt:663`; `ep7.txt:1097–1101` ("Có manh mối." / "Không nói."); EP9: `ep9.txt:613` ("Một số người của Tấn Ký bị gọi") | Hoài Xuyên có một lời hứa manh mối chưa được trả. Chủ hiệu không bao giờ được truy tiếp. |
| 6 | **HX-4** | **B** (nhận dạng) / **A** (phần còn lại) | `ep7.txt:1625–1660` (ghi chú sổ), `1785–1850` (Hòm Xét số bốn; bốn người giữ chìa), `1899–1940`; `ep8.txt:2447–2540` (H4 khác HX-4) | Đã trả: HX-4 là Hòm Xét số bốn; bốn người giữ chìa; H4 là Hạng bốn, tách riêng. Chưa trả: ai ghi "Đã kiểm — HX-4" vào sổ buôn lậu (`ep7.txt:1657`). Viên lại già (người giữ chìa thứ tư, EP7 sc.60) không còn được nhắc. |
| 7 | **Dấu X Thanh Trạch** | **D** | `ep6.txt:1629` (một lần) | Sơ đồ bến Thanh Trạch có dấu X trong thư của cha Lục Trầm; không cảnh nào hỏi X chỉ gì. EP8 gần như không quay lại Thanh Trạch. |
| 8 | **Con dấu mẻ góc** | **D** | `EP4.txt:259` (một lần, trong danh sách vật trong ngăn thứ ba) | Không dùng lại. Con dấu ở kho An Bình (`ep7.txt:1607`) là vật khác. |
| 9 | **Vết xước tủ** | **D** | `EP4.txt:209` (một lần) | Gợi ý có người từng tháo ngăn; không có hệ quả. |
| 10 | **Người áo nâu** | **A** | EP1:1181–1265; EP2:829–837 ("Chưa") | Không còn nhắc từ EP3. Có ba mô tả "người đàn ông bình thường" chưa được nối: áo xám 30–40 tuổi ở quán mì (EP2:675–699); giọng kinh thành khoảng bốn mươi, bắt Lục Trầm (`ep6.txt:1461`) và xuất hiện ở An Bình (`ep7.txt:1523–1527`); áo nâu ở bến. |
| 11 | **Người đốt xe giúp Tôn Tứ** | **A** (nhẹ; D khả dĩ) | `ep8.txt:1089`, `2273` | Xuất hiện một lần, không bao giờ được xác định; EP9 sc.19 không có tội danh nào cho hành vi này. |
| 12 | **Người trói Hàn Dực** | **A** | EP3:1329–1347 ("Không biết") | Hàn Dực bị trói trong kho thuyền sau giờ Dậu ngày 3/7. EP7–EP8 xác lập việc ép Hàn Dực học lời khai (Bùi Tấn/Tôn Tứ) nhưng không nối với vụ trói. |
| 13 | **Em gái Hàn Dực** | **A** (nhẹ) | `ep7.txt:705–729` (đe dọa; Hoài Xuyên ghi tên làng, gấp lại, đưa sai dịch); `ep7.txt:915` | Việc bảo vệ nàng không được nhắc lại. EP9 sc.22 và sc.50 (Hàn Dực rời đi) không đề cập. Việc bắt Bùi Tấn/Tôn Tứ có thể được hiểu là gỡ mối đe dọa nhưng không được nói ra. |

### 3.2 Các mạch phát sinh trong quá trình audit

| # | Mạch | Phân loại | Chi tiết |
|---|---|---|---|
| E1 | **Nguồn gốc bản năm mục năm LK20** (nặc danh bỏ vào Hòm Xét) | **A** (nặng nhất trong nhóm này) | Gieo ở `EP4.txt:1309–1380`, dùng ở `ep7.txt` sc.4–7 (Hoài Xuyên từng nghi cha). Bùi Tấn khai mua sổ bù "đầu năm nay" và tạo "phần giả" (EP8 sc.116) nên không giải thích một bản năm mục tồn tại từ LK20. B1 mục A.7-01 đã ghi đây là câu hỏi mới. |
| E2 | **Kẻ bắt Lục Trầm: "giọng kinh thành, khoảng bốn mươi"** | **A** | Xuất hiện ở `ep6.txt:1461` (lời Lục Trầm) và ở quán cơm An Bình (`ep7.txt:1523–1547`, Lục Trầm nhận ra). Sau khi kho An Bình bị khám, không ai được nêu là hắn. |
| E3 | **Thẩm phu nhân: "Năm đó ông giấu ta"** | **A** | `EP4.txt:1607` (dòng kết). Không bao giờ giải thích bà biết gì. |
| E4 | **"Bắc môn có động!" và "Phía trên đã có lệnh"** | **A** (hook EP1) | `EP1.txt:23, 123`. Không còn nhắc. Handbook không giải thích; AD-04 không khóa riêng. |
| E5 | **Kho số ba: ai trả tiền thuê, chủ Vạn Hưng** | **A** (nhẹ) | `ep6.txt` sc.2 ("Đó là câu hỏi." / "Đang.") |
| E6 | **Chủ hiệu Vĩnh Thái (nhà họ Vệ); "bốn hiệu bạc"** | **A / C** | `ep8.txt:1181` và Tôn Tứ ở sc.85 ("Bốn"). Mạng lưới còn dư "bốn hiệu" nhưng chỉ ba tên xuất hiện; EP9 sc.19 ("không xử cả mạng như một khối") đóng gần như mặc nhiên. |
| E7 | **Dấu Ty Thông hành "nét khuyết"** (EP2:1099) | **B / A** | Một phần được nối vào kho giấy/con dấu ở An Bình (`ep7.txt:1607`) nhưng không có câu nối nào. |
| E8 | **Hai mốc ký ức không bao giờ được kiểm**: Phùng Chiêu làm rơi ngọc bội 27/6 (EP2:13); Hộ bộ đổi chủ sự kho Đông 22/7 (`ep5.txt` sc.8) | **D** | B1 mục C đã ghi. Không có hệ quả. |
| E9 | **Chu Tử Dung: "Thẩm gia… Có xử lý? Không. Chưa."** (`ep6.txt:1565`) | **B** | Được trả bằng EP7 sc.67–73 (hợp tác) và EP9 sc.49 (nhận lỗi). |
| E10 | **Vết thương trán Lục Trầm; ai truy hắn ở trạm** (EP2:1045–1073) | **A** (nhẹ) | Không có lời giải thích. Mối nối khả dĩ là nhóm của kẻ bắt, nhưng bản thảo không nói. |
| E11 | **Nhị hoàng tử tiếp tục bị tra riêng** (EP9 sc.30) | **C** | "Không dừng tra… không gắn vào vụ hồ sơ nhà cô" là một lựa chọn có chủ ý. |

### 3.3 Tóm lại

- Hai hướng đã được trả khá gọn: chuỗi thư (Lục Trầm → Lương Thất → Trịnh Hành → Tĩnh An → Đại Lý Tự, B) và công văn Lạc Thủy (AD-03, B).
- Điểm đáng nói nhất không phải một mạch cụ thể mà là **mật độ im lặng sau EP4**: Tây Uyển, Từ Kính, Mã Tam, người áo nâu, người trói Hàn Dực và bản năm mục LK20 đều gieo ở EP1–EP4 và rơi khỏi EP8–EP9 mà trang không ghi dấu "cố ý". Theo Protocol §7, setup không được bị bỏ quên mà không có lý do rõ ràng; bản thảo hiện tại không cho thấy lý do đó cho các mạch A.
- Ba mục D (dấu X, con dấu mẻ góc, vết xước tủ) là chi tiết đạo cụ một lần, có hệ quả bằng không; bỏ hay giữ đều không đụng mạch chính.

---

## 4. Audio Findings

Phương pháp: đọc theo hướng nghe, cộng đo bằng script (chuỗi thoại không thẻ, độ dài câu kể, tần suất cụm). Các mục gắn `[N1B]` do chuyển đổi tạo ra.

### 4.1 HIGH

**AU-01 — Quá tải mã và con số "bốn/tứ/4"** (EP7–EP8)

K7, D2, N4, N-4, BT-3, PM-6, HX-4, H4, "Nam 4" (thẻ), "Nam tứ" (chi nhánh), "Ninh Tứ" (trấn), "Kho Bốn", "Hạng bốn", "Hòm số bốn", "Tôn Tứ" (tên người), "Tứ gia" (biệt danh). Tai nghe phân biệt khó giữa "bốn / tứ / 4" và giữa "HX-4 / H4" (hai vật khác nhau). Vị trí nặng nhất: `ep7.txt:1625–1660`, `ep8.txt:415–466, 543–680, 983–1050, 2289–2330, 2447–2540`. Thêm: "mười bảy" mang hai nghĩa (chuyến mười bảy, EP2–EP7; ngày 17/10, EP9).

**AU-02 — Số lượng tên riêng mới và tên gần âm** (EP8)

Chỉ riêng EP8 có ít nhất 19 tên mới: Lý Khâm, Khang Ký, Đồng Phát, Nam Hưng, Cao Bính, Cao Nhị, Tôn Tứ, Mạnh Thành, Hứa Nghiêm, Cố Văn Lâm, Tề Phương, Thịnh Nguyên, Bùi Tấn, Nhị hoàng tử, Ninh Tứ, Giang Châu, Hà Nam, Doanh hai, Hạng bốn (so với EP5: khoảng 5). Cặp gần âm: Phùng Chiêu (EP2) / Phùng Mậu; Tấn Ký / Tấn Bắc; Trịnh Hành / Triệu Ngạn / Trần Quảng; Từ Kính / Tôn Tứ; Cố Văn Lâm / Cao Bính / Cao Nhị; Hàn Dực / Hứa Nghiêm; Lý Khâm / Lục Trầm.

**AU-03 — Chuỗi thoại không thẻ rất dài**

Số đoạn thoại liên tiếp không tag: EP8 có bốn chuỗi 16–19 đoạn (`ep8.txt:3163` Bùi Tấn liệt kê tên, 19 đoạn; `:1935` Tề Phương, 17; `:1525` Hoài Xuyên–Chiêu Ninh về Cố Văn Lâm, 17; `:2807` Phùng Mậu về nhẫn, 16); EP6:1019 (Tĩnh An–Chiêu Ninh, 14); EP9:185 (13); EP4:943, 661 (12). Các lượt rất ngắn ("Ừ." / "Không." / "Có.") làm người nghe mất dấu nếu hai người cùng giọng.

**AU-04 — Cảnh nhiều người nói câu ngắn, đại từ "hắn/ông" mơ hồ**

EP7 sc.1–9 (Chiêu Ninh, Hoài Xuyên, Lục Trầm, Trần Quảng; `ep7.txt:5–320`), sc.32–35 (cùng bốn người; `:997–1116`); EP8 sc.4–10; EP6 sc.38–42 (Lục Trầm và Hoài Xuyên đều là "hắn", `ep6.txt:1355–1496`); EP9 sc.4. Cả bốn người nói bằng cùng loại câu "Ừ." / "Có thể." / "Chưa."

### 4.2 MEDIUM

**AU-05 — Chữ viết/ghi chép trong lời kể không có dấu hiệu nghe**

Dòng sổ, thư, bảng và nhãn hồ sơ giờ nằm lẫn trong câu kể, không ngoặc kép. Đáng chú ý: lá thư của cha Lục Trầm (`ep6.txt:1629–1660`, một beat cảm xúc), bảng bốn ô (`ep7.txt` sc.65), ba dòng về Hoài Xuyên (sc.75), bảng cuối (`ep8.txt` sc.101), dòng ghi ở EP8 sc.121, "Thứ nhất." Có sai phạm… (`ep9.txt` sc.4), kết luận sơ bộ (sc.45), hai dòng sổ cuối (sc.55–56, 64). Kết quả của việc bỏ in đậm ở N1A/N1B. `[N1B]`

**AU-06 — Mở cảnh bằng cụm thời gian không có điểm neo** `[N1B]`

Số cụm "Cùng lúc ấy / Cùng đêm ấy / Sau đó, / Cùng ngày…" đầu đoạn: EP5 6, EP6 12, EP7 10, EP8 16, EP9 10. Chuỗi cảnh một dòng liền nhau ở EP8 sc.75–77 (ba nơi khác nhau, mỗi nơi vài câu). Cụm nhảy ngày: "Hai ngày sau" ở `ep8.txt:1221, 2271, 2471` và EP9 sc.13; EP8 có tổng cộng 10 mốc nhảy ngày ("Hai ngày sau", "Sáng hôm sau", "Hôm sau", "Ngày hôm sau"); người nghe không biết "sau" so với cảnh nào khi cảnh trước là ban đêm.

**AU-07 — Chuỗi địa điểm nhỏ và vị trí người nghe**

- `ep7.txt:649–770` (sc.22–29): phủ Tam hoàng tử → ngoài phủ → hành lang → sân, trong khi Chiêu Ninh lúc ở ngoài (không nghe), lúc nghe kể lại; người nghe không rõ nàng nghe được gì.
- `ep8.txt:1221` (sc.43): câu mở nêu Nam lộ, nhưng đoạn thoại diễn ra ở kinh; chỉ có "Nàng ở lại kinh" đặt lại vị trí.
- `ep8.txt:1789` (sc.63–64): câu mở "Sáng ở Đại Lý Tự" nhưng cảnh diễn ra ở nhà trọ của Hứa Nghiêm.

**AU-08 — Công thức phản ứng và "không nói gì"** `[N1B]` một phần

"… không nói gì" thay thoại im lặng `“…”` xuất hiện 12 / 20 / 10 / 19 / 13 lần ở EP5–EP9 (tổng 74), trong khi EP1–EP4 do N1A chuyển dùng nhiều cách nói hơn (chỉ 2 lần trong bốn tập). Thêm các nhịp phản ứng: "khựng lại / cứng người / lạnh người / lạnh sống lưng" 5, 5, 6, 12, 9, 7, 13, 11, 6 lần theo tập; "bật cười / cười khẽ" 3–6 lần mỗi tập; "nhìn" 67–123 lần mỗi tập.

**AU-09 — Thẻ người nói và độ dày câu "Ừ."** `[N1B]` một phần

Đoạn bắt đầu bằng "X nói/hỏi/đáp:" tăng từ 9 (EP1) và 12 (EP2) lên 92 (EP7), 161 (EP8). "Ừ." đứng một mình: 20, 21, 20, 41, 58, 45, 60, 93, 55 theo tập. Tăng phần do chuyển nhãn người nói (`Tên:`) thành thẻ, phần do EP7–EP9 vốn nhiều người cùng nói; kết quả là nhịp thẻ + "Ừ." dày.

**AU-10 — Chuỗi câu rất ngắn và độ dài câu kể giảm dần**

Độ dài câu kể trung bình (không kể thoại): 30,6 ký tự (EP1) → 27,3 → 26,2 → 24,6 → 27,3 → 24,2 → 23,2 → 22,3 (EP8) → 24,2 (EP9). Số đoạn có ít nhất bốn câu liền ≤22 ký tự: EP1 3, EP2 2, EP3 5, EP4 5, EP5 1, EP6 4, EP7 7, EP8 10, EP9 15 (ví dụ `ep9.txt:965`, `1045`; `ep8.txt:2271`; `ep7.txt:915`, `2321`). Mật độ câu cụt tăng từ EP7. N1A đã nêu hiện tượng này cho EP1–EP4.

### 4.3 LOW

**AU-11 — Người kể xen vào và POV** — `ep8.txt:249` ("Trần Quảng nếu có mặt chắc sẽ hiểu."), `:3029` ("Chiêu Ninh không có mặt nhưng nếu nghe chắc sẽ biết là mình."), và POV bên ngoài ở EP7 sc.22–23. Giữ nguyên chữ nguồn (N1B H-8, H-7).

**AU-12 — Đại từ mơ hồ ở các cảnh hai nữ và nhiều nam** — ví dụ `EP3.txt:7` ("Nàng hé mắt" chỉ A Lục, câu kế là Chiêu Ninh); "hắn" cho nhiều người trong cùng đoạn; "ông" cho Tĩnh An, Chu Tử Dung, Nhị hoàng tử.

**AU-13 — Đoạn liệt kê dài** — `ep9.txt:611` (đoạn 395 ký tự liệt kê tội danh), bảng cuối EP8 (sc.101). Đọc to dễ đứt.

**AU-14 — Cảnh kiếp trước mở không nhãn** — `EP1.txt:5–131` (N1A ghi ở mục 5.6). EP7 sc.12 đã có tín hiệu "Ký ức kiếp trước. Trở lại hiện tại." nên không phải vấn đề.

---

## 5. Compression Candidates

**Nhắc lại:** đây là danh sách để xem xét, không phải kế hoạch cắt. Không có mục tiêu giảm. Bible và Protocol: độ dài không phải KPI; không cắt nếu làm giảm nhịp cảm xúc hoặc logic. Kích cỡ là ký tự không khoảng trắng, đo trên ranh giới cảnh; "POSSIBLE" gồm cả phần chỉ cần rút phần trùng, không phải xóa cả đoạn.

**SAFE** = có thể bỏ với ảnh hưởng tối thiểu: không thông tin riêng, không phụ thuộc phía sau. **POSSIBLE** = cần xem. **RISKY** = chạm chức năng truyện.

### 5.1 SAFE (≈ 4.700 ký tự, 2,2% toàn bộ)

| Vị trí | Dòng | Ký tự | Lý do |
|---|---|---|---|
| EP5 sc.5 | ~201–224 | 234 | A Lục chạy theo, cầu nối, không thông tin |
| EP6 sc.1 | ~5–38 | 521 | Lặp "Mai đi đâu? / Không biết." đã có ở điểm kết EP5 |
| EP6 sc.6 | ~199–238 | 282 | Tử Khiêm ngủ, A Lục báo "áo quan rách"; sc.7 mở lại bằng cảnh khác, không phụ thuộc |
| EP6 sc.43 | ~1497–1540 | 489 | Báo "người sống rồi" khán giả đã biết từ sc.40–42; phần còn lại là gag hộ vệ |
| EP7 sc.3 | ~87–126 | 393 | Tử Khiêm xem sổ chi tiêu, gag |
| EP7 sc.41–42 | ~1271–1342 | 845 | Tử Khiêm kể lại điều vừa nghe ở sc.38–40; cha "tiến bộ" |
| EP7 sc.51 | ~1565–1590 | 295 | Chờ ngoài kho, "Em có bánh" |
| EP7 sc.71 | ~2117–2144 | 257 | A Lục ngái ngủ |
| EP8 sc.3 | ~97–136 | 438 | Tử Khiêm đuổi chim |
| EP8 sc.31–32 | ~909–954 | 471 | Tin về Mạnh Thành đã thấy ở sc.29–30; Tử Khiêm than không được đi |
| EP8 sc.80 | ~2201–2234 | 254 | "Ta từng định bỏ nhà"; thông tin cảng có ở sc.83 |
| EP4 sc.36 | ~1503–1522 | 228 | A Lục "Có phải chạy không?" |

### 5.2 POSSIBLE (≈ 54.200 ký tự là phạm vi xem xét, 25,3% toàn bộ)

Các lý do được rút gọn; "trùng với" nghĩa là chức năng bị lặp bởi cảnh nêu tên.

| Tập | Cảnh | Ký tự | Lý do xem xét |
|---|---|---|---|
| EP5 | 10; 12–13; 18; 28; 38–39 | 3.123 | Trùng cảnh 9; gag mặc cả; Trịnh Hành khỏe; sổ trùng 36/41; cáo thị |
| EP6 | 2–3; 12–13; 14–15; 17; 19–20; 28; 34–37; 45; 50–52; 53–56 | 10.042 | Hai cảnh cùng chỗ; giải thích cân sổ lần 1 (lặp ở sc.47–48); cầu nối hộ vệ; kể lại sc.24–27 (S-07); túi; sc.50–52 lặp sc.36; năm cảnh kết |
| EP7 | 1–2; 8–9; 12; 13; 15–17; 20–21; 25–26; 30–31; 33–35; 45–48; 64; 77–78 | 8.603 | Tính chênh; dàn ý (đọc lại sc.33); EP1 tái dùng; trùng sc.29–31; "xin tra tiếp" ×2; Ty Độ Chi nhắc lại (có chi tiết Phùng Mậu về quê); đường đi An Bình; sc.64 loại Hoài Xuyên khỏi vụ gửi bản |
| EP8 | 11–12; 13–14; 15–16; 17–19; 20–22; 24; 33–35; 42; 43; 54; 70; 75–77; 92; 99–101; 116; 120; 121–123 | 9.817 | Đoán mã (B1 mục E); K7/D2 xác nhận; chủ Nam Hưng chết (đầu mối loại); tóm tắt (S-06); ba cảnh một dòng; H4 lặp sc.91/94 |
| EP9 | 2; 5; 12; 13–14; 20–21; 24–25; 28–30; 32–37; 41–42; 46; 47–51; 54–56; 60; 63–66 | 10.215 | Sổ ngày 16/8 và 18/8 trùng; chim; đếm ngược sáu cảnh; năm cảnh hậu quả nhỏ; ba cảnh sổ kết |
| EP1–EP4 | EP1 sc.4, sc.6 (phần mượn tiền), sc.7–9, sc.17 (phần mượn tiền); EP2 sc.1, 3, 4, 5; EP3 sc.1–2, 12–13, 31; EP4 sc.1–2, 3 | 12.367 | Gag mượn tiền ×2; ba mốc "đúng"; A Lục cầu nối; cảnh chờ dài; gag trước phần tiết lộ |

Một vài cảnh trong 5.2 mang beat nhỏ cần giữ nếu giữ cảnh phía sau, ví dụ EP9 sc.60 (mua hạt dẻ, dùng ở sc.62), EP9 sc.5/12 (chim "Không!" là callback), EP8 sc.43 (lựa chọn của Chiêu Ninh không đi). Đây là lý do chúng là POSSIBLE chứ không SAFE.

### 5.3 RISKY (≈ 38.200 ký tự trong EP5–EP9; không nén)

| Tập | Cảnh | Ký tự | Lý do giữ nguyên |
|---|---|---|---|
| EP5 | 1–4; 23–27; 29–31; 34; 40 | 6.730 | Phong thư; cái chết sai ngày; chuỗi Lương Thất; Lục Trầm bị giữ |
| EP6 | 24–27; 38–42; 46–49 | 5.606 | Thú nhận của cha; Lục Trầm thoát; thư của cha hắn, luận đề đầu tiên |
| EP7 | 4–7; 22–28; 53–61; 67–73 | 10.906 | Bản năm mục; Hàn Dực và EP7 LOCK (thuốc độc); kho An Bình và HX-4; Chu Tử Dung |
| EP8 | 36–40; 88–91; 95–98; 108–119 | 7.833 | Bắt Tôn Tứ; Phùng Mậu; bẫy lời Cố Văn Lâm; Bùi Tấn và tờ đề nghị (chức năng EP8–EP9 LOCK) |
| EP9 | 1; 15–17; 22–23; 27; 31; 38–40; 43; 52–53; 57–58; 61–62 | 7.158 | Hủy hồ sơ; Hàn Dực; payoff AD-03; giỏ quýt; hôn sự; cầu Thanh Bình |
| EP1–EP4 | Cảnh mở EP1 sc.1–4; EP2 dài bữa cơm sc.17–19; EP3 Hàn Dực sc.21–27; EP4 sc.3–11, 26–35, 40 | — | Nền của toàn bộ setup |

---

## 6. Priority Ranking

Xếp theo mức độ ảnh hưởng tới người nghe, rồi theo rủi ro nếu sửa. Hạng 1 đều cần quyết định của tác giả hoặc đụng setup, nên theo Protocol §7 không nên xử lý một mình.

| Hạng | Mục | Mức | Ghi chú |
|---|---|---|---|
| 1 | E1 bản năm mục LK20 (mục 3.2); #5 chủ Tấn Ký ("Có manh mối"); #2 Từ Kính; #3 Mã Tam; #1 Tây Uyển (có/không một dấu công nhận) (mục 3.1) | A / C cần quyết định | Quyết định giữ mở, trả hay bỏ; các mạch A không có dấu "cố ý" |
| 2 | S-05 Bùi Tấn, Nhị hoàng tử xuất hiện muộn | HIGH | Cần nền hoặc chấp nhận có chủ ý (liên quan AD-04) |
| 3 | S-01 vòng điều tra EP8 + S-06 tóm tắt lặp | HIGH + MEDIUM | Khối lớn nhất (≈ 9.800 ký tự POSSIBLE ở EP8) |
| 4 | S-02 luận đề phát biểu ≥ 12 lần | HIGH | Giữ lần đầu (EP6 sc.49), xem xét các lần sau |
| 5 | S-03 EP7 món nợ Hoài Xuyên suy lại | HIGH | Giữ sc.28 và sc.75 |
| 6 | AU-01, AU-02 mã và tên | HIGH | EP7–EP8; cần quy ước đọc thống nhất |
| 7 | AU-03, AU-04 chuỗi thoại không thẻ; đại từ mơ hồ | HIGH | EP7–EP8, EP6 sc.38–42 |
| 8 | S-04 điểm kết tập lặp; S-09 EP9 hậu quả dài | HIGH + MEDIUM | |
| 9 | S-07, S-08 EP6/EP7 trùng nội bộ | MEDIUM | |
| 10 | AU-05, AU-06, AU-07 chữ viết, thời gian, địa điểm | MEDIUM | Một phần sinh từ N1B |
| 11 | AU-08, AU-09, AU-10 công thức, thẻ, câu cụt | MEDIUM | Một phần sinh từ N1B |
| 12 | S-10..S-12 vòng kể cho cha, thử ký ức, đồng hồ | MEDIUM | |
| 13 | #7, #8, #9 (mục 3.1) và E8 (mục 3.2): chi tiết đạo cụ/mốc chỉ xuất hiện một lần (D) | D | Rủi ro thấp |
| 14 | S-13..S-15; AU-11..AU-14; SAFE ở mục 5.1 | LOW / SAFE | |

---

## 7. Recommended N2B Scope

Đây là đề xuất phạm vi, không phải chỉ thị sửa. Mọi bước giữ canon (AD-01..04, EP7 LOCK, EP8–EP9 LOCK) và knowledge map nguyên; không tạo setup/payoff mới; không đổi chức năng RISKY.

**N2B-0. Quyết định của tác giả (trước mọi sửa chữa).** Với mỗi mạch phân loại A hoặc D ở mục 3 (đặc biệt E1, #5, #2, #3, #1 và ba mục D #7–#9), tác giả chọn: để mở có chủ ý, trả bằng chất liệu sẵn có, hay bỏ chi tiết. Cho đến khi có quyết định, N2B không xóa hay thêm setup nào. Cũng cần quyết: Bùi Tấn/Nhị hoàng tử (S-05) giữ như hiện tại hay cần dấu hiệu sớm hơn.

**N2B-1. Dọn trùng cấu trúc, giới hạn ở EP6–EP9.**
- EP6: S-07 (ba lần kể một sự kiện, hai lần giải thích cân sổ); các cảnh SAFE.
- EP7: S-03, S-08.
- EP8: S-01, S-06, các cảnh SAFE.
- EP9: S-09, S-04 (điểm kết), các cảnh SAFE.
- Mỗi tập: đối chiếu từng setup còn lại sau khi dọn (mục 3) trước khi sang tập kế, đúng quy trình một-tập-một-lần của Protocol §1.
- Không đụng các khối RISKY (mục 5.3). Không nhắm mức giảm cụ thể.

**N2B-2. Làm giảm tải khi nghe, ở EP7–EP8 (và EP6 sc.38–42, EP9 sc.4).**
- AU-01/02: thống nhất cách gọi mã và tên, giảm số tên chỉ xuất hiện một lần nếu chúng thuộc cảnh được dọn ở N2B-1.
- AU-03/04: gắn thẻ người nói tại các chuỗi dài nhất; đại từ rõ ở cảnh nhiều người.
- AU-05/06/07: thêm dấu hiệu nghe cho chữ viết, neo thời gian và địa điểm ở các chỗ đã nêu.
- AU-08/09: các công thức do N1B sinh ra (`không nói gì`, thẻ, nhịp phản ứng) cần xem lại như một nhóm.
- Phần này gần với "audio polish" (một pass riêng theo thứ tự công việc); nếu tác giả muốn giữ N2B thuần cấu trúc, tách N2B-2 thành pass sau.

**N2B-3. Chỉ EP1–EP4 ở mức nhẹ.** Các cảnh SAFE/POSSIBLE ở mục 5 (gag mượn tiền, A Lục cầu nối, ba mốc "đúng"). EP1–EP4 không có vấn đề cấu trúc HIGH. Giữ nguyên các cảnh gieo setup.

**Ngoài phạm vi N2B (chuyển B2/N3).** Continuity còn mở (mục 2.3); đồng bộ Handbook, `MASTER_TIMELINE.md`, `KNOWLEDGE_MAP.md`, `AUTHOR_DECISIONS.md`; quyết định về độ dài so với mốc tham chiếu 90.000–140.000 của Bible.

**Điều kiện kiểm tra sau mỗi tập (đề xuất):** (1) không mất thông tin mà cảnh sau còn dùng; (2) các setup A đã được tác giả quyết định giữ nguyên hoặc không bị làm yếu; (3) không thêm thông tin mới; (4) AD-01..04 và các LOCK không đổi; (5) báo cáo số liệu độ dài chỉ để tham khảo.

---

## Kiểm tra dừng N2A

1. Không tập nào bị sửa (`git status` trước khi tạo báo cáo này sạch).
2. Không viết lại, gộp, cắt, nén, audio polish hay đổi canon.
3. Không đề xuất payoff hay cốt truyện mới.
4. Chỉ tạo `PASS_N2A_AUDIT.md`.
5. Dừng. Chưa bắt đầu N2B.
