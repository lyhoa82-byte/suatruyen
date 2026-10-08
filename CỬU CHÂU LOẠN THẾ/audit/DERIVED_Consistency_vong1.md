# CONSISTENCY REPORT — 3 file DERIVED, CỬU CHÂU LOẠN THẾ (Ch01–Ch22)

Phạm vi: CB = CHARACTER_BIBLE_DERIVED.md (1580 dòng), REG = SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md (886), TL = MASTER_TIMELINE_DERIVED_Ch1-Ch22.md (518). Không sửa file nào trong repo. Mọi đề xuất chỉ nhằm vào Derived.

Giới hạn trung thực của lần kiểm này:
- Mục 1 (chuỗi before→after) và mục 3 (chéo file) chỉ kiểm bằng script heuristic cộng đọc mẫu. Chưa đọc hết khối Bàng, Ôn, Phùng, Tô và các mục 4.1/4.2 của CB. Danh sách mục 3 vì vậy không đầy đủ (không nên coi là "hết lỗi").
- Số liệu script: `scratchpad/work/*.json` (src_issues, quote_issues, st_issues, cb_cmp).

## TÓM TẮT SỐ LỖI

| Loại | BLOCKER | SỬA ĐƯỢC NGAY | GHI NHẬN |
|---|---|---|---|
| 1. Chuỗi before→after (CB) | 0 | 2 mẫu | 70 điểm cần rà (23 không có hàng trước, 47 so sánh được) |
| 2. Nguồn `ChNN §…` | 0 | ~6 (số mục sai) | 314 tham chiếu có phần chú thích không khớp tiêu đề |
| 3. Mâu thuẫn chéo file | 3 | 6 | 3 |
| 4. Planning rò rỉ | 1 | 3 | 12 dòng nhắc kế hoạch trong bảng canon |
| 5. Source Type / ID / "resolved" | 1 | 21 ô | — |
| 6. Số liệu header/ghi chú | 0 | 1 | đã khớp phần lớn |

---
## BLOCKER

### B-1. Cùng một claim, hai nhãn Source Type khác nhau giữa CB và REG (thư riêng đã tới tay người giữ chức)
- CB:1549 (L-20) giữ claim là mâu thuẫn "CHƯA QUYẾT" và staging gắn CANON_INFERENCE theo ma trận Ch21 §III.
- REG:430 (OP-115) ghi cùng claim là `CANON_FACT`, "ĐÓNG MỘT PHẦN" (Ch21 §I.4; §0).
- Hệ quả: Derived tự chọn một phía của mâu thuẫn Canon, vi phạm "Derived không giải quyết mâu thuẫn".
- Sửa Derived: REG:430 đổi ô trạng thái thành "CHƯA QUYẾT — xem CB L-20", Source Type tách hai dòng (FACT theo §I.4, INFERENCE theo §III) hoặc ghi nhãn đúng nhất theo cách CB đã làm. Không gộp.

### B-2. Mâu thuẫn Canon bị giải quyết ngầm bằng việc gộp khối nhân vật
- CB:92 và CB:75 gộp "Phùng thúc" vào khối PHÙNG BẢO; CB:1296 tự thừa nhận "Canon Update không nêu rõ Phùng thúc = Phùng Bảo"; CB:1530 (L-01) vẫn để "CHƯA QUYẾT".
- CB:80 và CB:90 gộp "Ôn" với "Thứ sử"; CB:1555 (L-26) vẫn "CHƯA QUYẾT".
- Hệ quả: lịch sử của hai danh xưng trộn thành một chuỗi liền, người đọc Derived sẽ coi đó là đã giải quyết.
- Sửa Derived: tách riêng hai khối con trong CB (mỗi cái chỉ giữ nhãn gốc), hoặc gắn cờ ⟦chưa xác nhận đồng nhất, L-01⟧ / ⟦L-26⟧ ngay đầu mỗi hàng gộp; chuỗi "Nối chuỗi" không được nối qua ranh giới này. CB:1571 (ghi chú "Đồng nhất nhân vật") đã nói đúng nguyên tắc, nhưng bảng không làm theo.

### B-3. Bảng (a) trạng thái cuối của Dịch còn hàng UNKNOWN cũ, REG đã ghi là đã đóng
- CB:171 (Ch20 KNOWLEDGE): "chưa biết chiếu nêu tên mình" gắn `CANON_UNKNOWN`.
- REG:422 (OP-110a): "ĐÓNG MỘT PHẦN: Dịch đã đọc tên mình ở Ch22 §I.30–31", `CANON_FACT`.
- CB 3.1 có hàng KNOWLEDGE(thuyền) Ch22 ở CB:383 nhưng hàng đứng ngay trước trong cùng khóa là CB:364 (Ch20), after vẫn là "chưa biết chiếu nêu tên mình"; không có hàng Ch22 nào đóng điều này. (Chưa kiểm phần (a) có sửa hay không.)
- Sửa Derived: ở (a), ghi trạng thái cuối theo Ch22 và chuyển hàng Ch20 sang lịch sử (b); thêm cột "Nối chuỗi" trỏ tới Ch22 §I.30–31.

### B-4. (Planning rò rỉ) REG:442 OP-124 ghi `CANON_UNKNOWN` cho "mối nối Lạc Kinh Chapter Bible Ch22 ↔ Ch28"
- Hàng nằm trong bảng canon (mục B), nhưng nội dung là so sánh kế hoạch Chapter Bible; cột "Chuyển sang" trỏ D3-21 (PLANNING).
- Sửa Derived: giữ ở mục B chỉ phần canon ("Ch22 §0: Lạc Kinh không lên trang") và chuyển câu về CB Ch22/Ch28 sang D3/D5 (D5-03 đã có, REG:824).

### B-5. Dải ID L-xx trùng tên giữa ba file nhưng khác nghĩa
- CB:1530 L-01 = Phùng thúc ↔ Phùng Bảo; REG:835 L-01 = chương gieo motif "cửa"; TL:455 L-01 = Lạc Kinh thất thủ.
- Tương tự L-02 (CB:1531 / REG:836 / TL:456) và L-20 (CB:1549 / REG:854 / TL:478).
- Các ghi chú chéo file (ví dụ REG:860 L-26, CB:1555 L-26) dễ bị đọc nhầm.
- Sửa Derived: đổi tiền tố, ví dụ CB-L-xx, REG-L-xx, TL-L-xx, và sửa mọi chỗ trỏ chéo.

(Ghi chú: bảng tóm tắt đếm B-1, B-3 là chéo file, B-2 là gộp ngầm, B-4 planning, B-5 ID; số trong bảng là ước lượng.)

---
## SỬA ĐƯỢC NGAY

### S-1. 21 ô Source Type có phần chú thích trong ngoặc, không đúng 6 giá trị chuẩn (script `st_issues.json`)
Chú thích: legend quy định "đúng 6 giá trị" cho ô Source Type; CB dùng ⟦ST gốc⟧, REG và TL thì viết trực tiếp trong ô.
- REG: 84, 112, 153, 502, 513 (ví dụ `CANON_BELIEF (Tạ Vân Chương)`); REG:842 là ô `—` (không có Source Type; hàng L-08 trong bảng E).
- TL: 124, 168, 169, 185, 190, 202, 227, 234, 237, 243, 250, 293, 333, 337, 394.
- Sửa Derived: ô chỉ ghi giá trị chuẩn; đưa phần trong ngoặc sang cột ghi chú hoặc ⟦ST gốc⟧ như CB. TL:394 `PLANNING_NON_CANON (Chapter Bible Ch14)` hợp lệ vì ở mục B.P, chỉ cần bỏ ngoặc.

### S-2. Tham chiếu mục sai/mơ hồ
- TL:294 (T-153): "Về sau 'không ai đuổi'" trích Ch15 §I.14, nhưng câu đó là Ch15 §I.23 (Ch15:57). Sửa thành `Ch15 §I.14; §I.23; §VII`.
- TL:328 (T-180): nguồn ghi "Ch19 IV" (thiếu §), trong khi nội dung "Giá chợ cũ" (Ch19 §I.15) và "Tôi ăn rồi" (Ch19 §V) không thuộc §IV. Sửa thành `Ch19 §I.15; §V`.
- Hai ví dụ này đến từ mẫu đọc, chưa quét toàn bộ để tìm cả loại "số mục tồn tại nhưng nội dung khác".

### S-3. Tham chiếu có chú thích trong ngoặc không khớp tiêu đề (20 ví dụ đầu; tổng 314: CB 48, REG 249, TL 17)
Không có tham chiếu nào trỏ tới mục không tồn tại. Các chú thích sau không phải số mục:
CB:118 `III (dòng Dịch, …)`, CB:128 `III (Dịch, Chiêu, …)`, CB:129 `III (Dịch…)`, CB:251, CB:276, CB:278 `III (cột INFERENCE)`, CB:288, CB:311 `II (mục 1)`, CB:339, CB:340 `I.1–22 (I.21)`, CB:391, CB:412 (`1C`), CB:425 `0 (Sync Ch14)`, CB:472 (`1C`), CB:476, CB:511, CB:530, CB:563 `III (Uyển, …)`, CB:585, CB:653.
Phần lớn là chú thích người đọc, nhưng:
- `1C` (CB:412, CB:472, TL cùng loại) là mục của Gate, mà quy tắc cấm dùng Gate làm nguồn. Sửa Derived: đổi thành mục Canon Update tương ứng hoặc bỏ.
- `…` và `(Dịch…)` nên bỏ, để nguồn chỉ còn `ChNN §III`.
- REG: 249 hàng có chú thích dạng (trong dấu ngoặc) ở cột Gieo; không phải lỗi nguồn, nhưng nên tách cột.

### S-4. Hàng "PLAN" trong bảng E của REG lộ kế hoạch ở cột Canon (12 dòng: REG:841, 843, 847, 849, 857, 858, 859, 860, 861)
- Ví dụ REG:841 L-07 dẫn "Ch05 §IV: 'Payoff dự kiến Ch6'", REG:857 L-23 dẫn "Ch14 §V: Payoff 'Ch15–Ch17 (tìm), Ch26, Ch29'".
- Đây là chính Canon Update nhắc kế hoạch, nên hợp lệ nếu có nhãn PLAN. Phát hiện này chỉ là rủi ro: người đọc thấy chương payoff dự kiến như dữ kiện.
- Sửa Derived: mỗi ô kế hoạch thêm nhãn `(PLANNING_NON_CANON)` ngay trong ô.

### S-5. REG:861 (L-27) trích câu "Hook CB Ch25" trong cột canon
- Nội dung là hook của Chapter Bible Ch25 (kế hoạch), không có số mục Canon. Sửa Derived: chuyển hẳn sang D-section, giữ trong E chỉ dòng Ch22 §0.

### S-6. Nhóm lỗi nhỏ cùng loại về chuỗi before→after (mục 1)
- CB:1200 (Ch19 KNOWLEDGE Dịch về Bàng): before `"Lương của ngài đi nhanh hơn sổ của ta"` trong khi after dòng trước (CB:1198) chỉ là `Ch19`, nghĩa là ô after bị cắt/dán nhầm.
- CB:507 (Ch13 RELATION Chiêu): after dòng trước (CB:499) là `A Quy)` — mảnh vỡ của ô.
- CB:219 (Ch07 RELATION Phùng thúc): before "(như Ch1)" trỏ về CB:186 nhưng hàng trung gian (Ch03–Ch04) bị bỏ.
- Sửa Derived: khôi phục ô after đúng; thêm cột "Nối chuỗi" khi bỏ qua một hàng.

### S-7. Header REG:289
- 249 dòng / 232 ID seed / 58 + 174 + 17: ĐÃ KIỂM bằng script, đúng (58 "other" gồm đóng/payoff, 174 "Canon chưa đặt", 17 OPEN), nên không phải lỗi.
- Nhưng 58 + 174 + 17 = 249 chỉ đúng nếu mọi hàng thuộc một trong ba nhóm; cần ghi thêm "(đếm theo dòng, không theo ID)" ở cùng câu vì 232 là số ID, dễ bị hiểu nhầm là tổng ba nhóm.

---
## GHI NHẬN

### G-1. Mục 2: số nguồn không tồn tại
Kiểm 6230 tham chiếu `ChNN §…` đối với `canon/CCLT_Canon_Update_ChNN.md`: 0 tham chiếu trỏ tới chương hoặc mục không tồn tại (cấp tiêu đề). Việc kiểm cấp mục con (ví dụ `§I.21` nằm trong khoảng 1..N của mục I) cũng không phát hiện lỗi ngoài các ví dụ ở S-2. Kiểm trích dẫn nguyên văn (305 trích dẫn không tìm thấy trong chương được dẫn, `quote_issues.json`) phần lớn do Derived tóm tắt/viết lại, không phải lỗi; ví dụ đáng rà: CB:60 (`Dịch chính là con trai Thẩm chiêu nghi (Thất hoàng tử)` dẫn Ch04 §III nhưng không có trong Ch04), CB:67.

### G-2. Mục 5: không có contradiction nào được ghi "resolved"
Không có trạng thái "resolved/đã giải quyết" cho bảng mâu thuẫn; mọi mục đều "CHƯA QUYẾT". Rủi ro nằm ở việc gộp ngầm (B-2). Không phát hiện: hàng claim thiếu Source (script), ID `S-`/`OP-`/`D-` trùng hoặc khuyết (S: 249 hàng/249 key, không khuyết; OP: 151 hàng/131 số, các hậu tố a/b hợp lệ; D: 77 hàng, không trùng), L-xx liên tục (REG L-01..L-27).

### G-3. Mục 1: 23 điểm "NOPREV"
Không có hàng trước để so (CB:176, 244, 380, 439, 453, 492, 499, 594, 627, 639, 727, 899, 934, 971, 981, 1017, 1068, 1126, 1191, 1234, 1252, 1289, 1333). Phần lớn là hàng đầu dải của từng nhân vật, hợp lệ. Các hàng RELATION(...) mới xuất hiện (CB:244, 380, 453, 492, 499, 639, 934, 971, 981, 1252) nên kiểm tay xem có hàng bị bỏ mất.

### G-4. Mục 1: 47 so sánh before/after; độ tương đồng thấp nhất (xem thêm S-6)
Tương đồng thấp không đồng nghĩa với lỗi (ô before thường diễn đạt lại). Các trường hợp đáng đọc lại bằng tay: CB:751 (Ch06 STATE: before "Tam Lang (nam theo cách gọi trước)" khác after CB:749), CB:456 (Ch03 "bị trói" so với after trước là tên "A Quy"), CB:235, CB:527, CB:479, CB:378 (Ch22 RELATION Hàn: before "Dịch" khác after trước "Hàn tự chọn").

### G-5. Tên gọi cùng một số liệu trên REG và TL
Số "58/174/17" chỉ xuất hiện ở REG:289; TL và CB không lặp lại nên không thể chéo.
