# QA 30 claim — Derived CỬU CHÂU LOẠN THẾ (báo cáo ghi theo phần)

## Phương pháp lấy mẫu
- Parser Python (`parse.py`) trích mọi dòng bảng có cột Source Type hợp lệ (2.270 dòng); `sample.py` dùng `random.seed(20261003)`, lấy phân tầng: mỗi file 10 dòng, mỗi dải Ch01–07 / 08–13 / 14–18 / 19–22 (theo chương đầu tiên trong cột Source) 2 dòng + 2 dòng tự do; chỉ tiêu loại (belief/suspicion, unknown, planning, inference, before→after) được gán vào các ô tầng rồi bốc ngẫu nhiên trong từng ô. Loại trừ: dòng APPEARANCE và dòng chú giải (đã là dòng "dễ").
- Phân bổ thực tế: belief/suspicion = 6; unknown = 5; planning = 6 (trong đó 1 dòng nguồn CB/PB); inference = 5; before→after = nhiều dòng (CB mục (b), Registry mục C, Timeline A).

## PHẦN 1. DANH SÁCH 30 DÒNG ĐÃ BỐC (seed 20261003)

| # | File | Dòng | Dải (theo Source đầu tiên) | Source Type (Derived) | Source (Derived) |
|---|---|---|---|---|---|
| 1 | CHARACTER_BIBLE_DERIVED.md | 60 | Ch01–07 | CANON_BELIEF | Ch04 §III |
| 2 | CHARACTER_BIBLE_DERIVED.md | 1070 | Ch01–07 | CANON_FACT | Ch01 §I.10 |
| 3 | CHARACTER_BIBLE_DERIVED.md | 1441 | Ch08–13 | CANON_UNKNOWN | Ch10 §I.35, I.37, §II |
| 4 | CHARACTER_BIBLE_DERIVED.md | 224 | Ch08–13 | CANON_FACT | Ch08 §III (Nghe/thuật lại) |
| 5 | CHARACTER_BIBLE_DERIVED.md | 432 | Ch14–18 | CANON_SUSPICION | Ch14 §VI |
| 6 | CHARACTER_BIBLE_DERIVED.md | 574 | Ch14–18 | CANON_FACT | Ch18 §I.17–I.18; Ch18 §I.20 |
| 7 | CHARACTER_BIBLE_DERIVED.md | 987 | Ch19–22 | CANON_INFERENCE | Ch21 §III (Vân Chương); Ch21 §I.4 |
| 8 | CHARACTER_BIBLE_DERIVED.md | 1208 | Ch19–22 | PLANNING_NON_CANON | Ch21 §II-B; Ch22 §II-B |
| 9 | CHARACTER_BIBLE_DERIVED.md | 1238 | Ch08–13 | CANON_UNKNOWN | Ch08 §III (Ôn) |
| 10 | CHARACTER_BIBLE_DERIVED.md | 282 | Ch08–13 | CANON_SUSPICION | Ch12 §III (Dịch/Vân Chương) |
| 11 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 608 | Ch01–07 | PLANNING_NON_CANON | Ch06 §V |
| 12 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 118 | Ch01–07 | CANON_FACT | Ch07 §I.2–5, §V; Ch11 §I.20–21, §V |
| 13 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 355 | Ch08–13 | CANON_UNKNOWN | Ch09 §IX; Ch10 §II; Ch11 §IX; Ch12 §IX; Ch13 §IX; Ch19 §IX; Ch22 §II-A |
| 14 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 461 | Ch08–13 | CANON_FACT | Ch11 §VI |
| 15 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 513 | Ch14–18 | CANON_SUSPICION | Ch14 §VI |
| 16 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 698 | Ch14–18 | PLANNING_NON_CANON | Ch16 §V; Ch17 §V |
| 17 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 439 | Ch19–22 | CANON_UNKNOWN | Ch21 §II-A; Ch22 §II-A |
| 18 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 255 | Ch19–22 | CANON_FACT | Ch19 §V |
| 19 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 134 | Ch08–13 | CANON_INFERENCE | Ch09 §V |
| 20 | SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md | 769 | — (CB/PB) | PLANNING_NON_CANON | CB Ch29 |
| 21 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 159 | Ch01–07 | CANON_INFERENCE | Ch03 §VIII.2 |
| 22 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 90 | Ch01–07 | CANON_FACT | Ch04 §I.5–9 |
| 23 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 185 | Ch08–13 | CANON_BELIEF | Ch11 §I.20, §I.28, §III |
| 24 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 267 | Ch08–13 | CANON_UNKNOWN | Ch13 §II |
| 25 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 431 | Ch14–18 | CANON_INFERENCE | Ch17 §VII; Ch17 §VII (ghi chú); Ch17 §I.6 |
| 26 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 290 | Ch14–18 | CANON_FACT | Ch15 §I.1–I.9; Ch15 §VII (ghi chú) |
| 27 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 333 | Ch19–22 | CANON_BELIEF | Ch20 §I.1–4 |
| 28 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 397 | Ch19–22 | PLANNING_NON_CANON | Ch22 §0 |
| 29 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 392 | Ch08–13 | PLANNING_NON_CANON | Ch08 §VII |
| 30 | MASTER_TIMELINE_DERIVED_Ch1-Ch22.md | 424 | Ch01–07 | CANON_INFERENCE | Ch04 §V |

Phủ dải theo file (số dòng): CB Ch01–07=2; CB Ch08–13=4; CB Ch14–18=2; CB Ch19–22=2; REG Ch01–07=2; REG Ch08–13=3; REG Ch14–18=2; REG Ch19–22=2; REG — (CB/PB)=1; TL Ch01–07=3; TL Ch08–13=3; TL Ch14–18=2; TL Ch19–22=2

Phủ loại: CANON_BELIEF=3; CANON_FACT=8; CANON_INFERENCE=5; CANON_SUSPICION=3; CANON_UNKNOWN=5; PLANNING_NON_CANON=6; belief+suspicion=6

Dòng thuộc chuỗi before → after (CB mục (b); Registry mục C; Timeline A): #2, #4 (có 'Nối chuỗi ← Ch07'), #7, #9, #10, #14, #15, #22.

## PHẦN 2. KẾT QUẢ ĐỐI CHIẾU 30 DÒNG

Ký hiệu file: CB = CHARACTER_BIBLE_DERIVED.md; REG = SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md; TL = MASTER_TIMELINE_DERIVED_Ch1-Ch22.md. "Dòng" = số dòng trong file Derived. Trích dẫn Canon <= 25 từ.

| # | File:Dòng | Source Type (Derived) | Claim (rút gọn) | Source (Derived) | Phán | Trích Canon (<=25 từ) và ghi chú |
|---|---|---|---|---|---|---|
| 1 | CB:60 | CANON_BELIEF | Vân Chương tin Dịch là con trai Thẩm chiêu nghi, chưa xác nhận | Ch04 §III | MATCH | Ch04 §III, mục "TIN RẤT CAO — CHƯA XÁC NHẬN": "Dịch chính là con trai của Thẩm chiêu nghi (Thất hoàng tử)." Đúng loại, đúng mục. |
| 2 | CB:1070 | CANON_FACT | Chu Hạc: phó tướng Hoắc gia quân, lo thành phòng bắc, xin 30 bộ áo bông (chuỗi (b), đầu dải) | Ch01 §I.10 | MATCH | Ch01 §I.10: "Chu Hạc: phó tướng Hoắc gia quân, lo thành phòng mặt bắc, ngày nào cũng đi tuần tường thành." Các dòng kế tiếp của chuỗi STATE Chu Hạc (Ch01 §I.9; Ch02; Ch03; Ch06) nối đúng. |
| 3 | CB:1441 | CANON_UNKNOWN | Tướng trẻ vô danh: muốn đánh qua sông, quay mặt đi; tên OPEN | Ch10 §I.35, I.37, §II | MATCH (lưu ý) | I.35 "Tướng trẻ muốn đánh qua sông."; I.37 "Tướng trẻ và vài người cạnh hắn quay mặt đi."; §II "Tên tướng trẻ" (OPEN). Lưu ý: dòng UNKNOWN lặp nguyên phần hành vi (vốn là FACT) do tách ô kép; chỉ phần "tên" là UNKNOWN. Đã được ⟦⟧ chú thích. |
| 4 | CB:224 | CANON_FACT | Dịch NGHE: tung tích Thất hoàng tử "đã tìm được" (nguồn/thật-giả OPEN); Nối chuỗi ← Ch07 KNOWLEDGE | Ch08 §III (Nghe/thuật lại) | TYPE_WRONG | Ch08 §III, mục "NGHE / THUẬT LẠI (không xác nhận)": "Luồng tin phía tây: đã tìm được tung tích Thất hoàng tử." Canon xếp vào nhóm không xác nhận, không phải "BIẾT". Cùng nhóm "NGHE (lời đồn, chưa kiểm chứng)" ở Ch07 §III thì Derived gắn CANON_BELIEF (CB:215), còn Ch08 gắn CANON_FACT (CB:224, CB:225): chuỗi nối hai dòng cùng loại nhưng khác Source Type. Dòng "Lời đồn Tam Lang tử trận" Ch08 (CB:229, cùng nhóm NGHE/THUẬT LẠI) cũng gắn CANON_FACT. Nối chuỗi trỏ chung "Ch07 KNOWLEDGE" (nhiều dòng), không nói trỏ dòng nào. |
| 5 | CB:432 | CANON_SUSPICION | Chỉ: "nghi rò tin" (Debt "Chính hắn (nghi rò tin)", hai dòng "Kha Trọng") | Ch14 §VI | MATCH | Ch14 §VI: "Chỉ | Chính hắn (nghi rò tin) | Hai dòng "Kha Trọng" | ACTIVE". Sao chép sát chữ, giữ nguyên nhãn "(nghi rò tin)". Lưu ý: Canon không nói "Chính hắn" là ai. |
| 6 | CB:574 | CANON_FACT | Uyển: không hỏi chuyện mũ, không xác nhận/phủ nhận, gật cho thủ lĩnh râu rậm đọc luật, Tu Bặc Cốt chết | Ch18 §I.17–18; §I.20 | MATCH | I.17: "Ta không hỏi ngươi chuyện mũ. Ta hỏi ngươi chuyện người chết." I.18 "nàng gật"; I.20 "Tu Bặc Cốt đã chết." |
| 7 | CB:987 | CANON_INFERENCE | Vân Chương: "thư riêng đã tới tay người giữ chức" (narration nêu như dữ kiện; Knowledge Matrix ghi INFERENCE một mức) | Ch21 §III (Vân Chương); Ch21 §I.4 | MATCH (lưu ý, đã gắn L-20) | I.4: "thư riêng đã tới tay người giữ chức (narration nêu như dữ kiện)". §III: cùng ô Vân Chương liệt kê câu này ở cả cột FACT lẫn "INFERENCE (một mức)"; §0: "xác nhận OPEN Ch20 'tới tay ai', chỉ ở mức Hổ Lao". Derived chọn INFERENCE và mô tả L-20 chỉ nhắc nhãn INFERENCE, bỏ sót việc cùng ô §III còn liệt kê ở FACT và §0 dùng chữ "xác nhận". |
| 8 | CB:1208 | PLANNING_NON_CANON | Bàng "học quá kỹ" từ Dĩnh Xuyên, sai một điểm; tự ra lệnh mở cổng; không điều khiển G | Ch21 §II-B; Ch22 §II-B | MATCH | Ch21 §II-B: "sai đúng một điểm: thuyền lần này thật sự chỉ chở lương." và "Bàng tự ra lệnh mở cổng (mở ≠ đầu hàng)". Đúng là author-truth, không lên trang. |
| 9 | CB:1238 | CANON_UNKNOWN | Ôn tin Dịch hay không: OPEN, không được biểu lộ | Ch08 §III (Ôn) | MATCH | Ch08 §III, mục ÔN THỨ SỬ: "Tin: OPEN (không được biểu lộ)." |
| 10 | CB:282 | CANON_SUSPICION | Dịch: Vân Chương không nhìn chỗ Uyển–Tam Lang "như người đã quen" (phạm vi 2/3 của ô kép) | Ch12 §III (Dịch/Vân Chương) | TYPE_WRONG | Ch12 §III, bảng Dịch, cột INFERENCE: "Chàng không nhìn chỗ Uyển – Tam Lang 'như người đã quen'". Nhãn Canon là INFERENCE, và cùng mục Canon dùng chữ "Nghi, chưa xác nhận" (Vân Chương) khi muốn nói suspicion; Derived gắn SUSPICION cho cột INFERENCE (7 dòng, cả Uyển dòng 278), nhưng gắn CANON_INFERENCE cho nhãn y hệt ở Ch21 (#7). Quy tắc ánh xạ không nhất quán. Source đúng mục. |
| 11 | REG:608 | PLANNING_NON_CANON | S-073 "A Quy bị quy là nội ứng": PLAN Ch11, Ch26 | Ch06 §V | MATCH | Ch06 §V bảng Seed→Payoff: "A Quy bị quy là nội ứng | Major | Ch11, Ch26". |
| 12 | REG:118 | CANON_FACT | S-079 "Cửa mở từ bên trong. Hai người khiêng then.": gieo Ch07; Core; payoff một phần ở Ch11 | Ch07 §I.2–5, §V; Ch11 §I.20–21, §V | MATCH (lưu ý nhỏ) | Ch11 §V: "Payoff một phần: nói ra với Chỉ". Ch07 §V: "Đã gieo (nhắc lại một lần ở S4)", mức Core. Nhỏ: nhãn "(Dịch nghe/thấy)" - Canon Ch07 §I.3 ghi Dịch "không nghe được gì vì tiếng pháo", chỉ thấy. |
| 13 | REG:355 | CANON_UNKNOWN | OP-050 Chu Hạc trong bộ máy Hoắc; động cơ riêng: CÒN MỞ tới Ch22 | Ch09 §IX; Ch10 §II; Ch11 §IX; Ch12 §IX; Ch13 §IX; Ch19 §IX; Ch22 §II-A | MATCH (lưu ý nhỏ) | Ch09 §IX: "Chu Hạc trong bộ máy Hoắc, 'người đưa ra lời khuyên từ phía sau'." Ch10 §II: "Động cơ riêng của Chu Hạc (author-truth Gate D, không dựng)." Nhỏ: Ch19 §IX và Ch22 §II-A chỉ ghi "Chu Hạc" giữ OPEN, không có chữ "động cơ"; dòng gom vào ngoặc "động cơ riêng:" cả hai nguồn này. |
| 14 | REG:461 | CANON_FACT | D-03 Dịch → A Quy: món nợ Ch7 "chạm tới" qua "Ngươi còn sống."; ACTIVE, không nói ra; không cập nhật sau Ch11 | Ch11 §VI | MATCH | Ch11 §VI: "Món nợ Ch7 (không quay lại) chạm tới qua 'Ngươi còn sống.', không nói ra | ACTIVE". Quét Ch12–Ch22 §VI: không có dòng Dịch → A Quy nào nữa, "không cập nhật sau Ch11" đúng. |
| 15 | REG:513 | CANON_SUSPICION | D-54b Chỉ → chính hắn: hai dòng "Kha Trọng" — "đối tượng bị nghi (nghi rò tin)" | Ch14 §VI | OVERSTATED | Ch14 §VI chỉ ghi: "Chính hắn (nghi rò tin) | Hai dòng 'Kha Trọng' | ACTIVE". Cụm "đối tượng bị nghi" là chú giải của Derived, gắn Kha Trọng với nghi rò tin. Canon tách hai thread: Ch14 §II G-1 (nguồn rò) OPEN, G-2 (Kha Trọng) OPEN "liên quan..." chưa kết luận; §III Chỉ "Không biết: Ai rò"; §I.25 Chỉ trả lời "Có thể." với "trùng tên". Derived đang nối G-1 và G-2 mà Canon chưa nối (Ch15 §0 còn ghi "không chữ nào nối rò Ch14…"). |
| 16 | REG:698 | PLANNING_NON_CANON | S-186 Dĩnh Xuyên: PLAN Ch17 (Ch16 §V); PLAN Ch19 (Ch17 §V) | Ch16 §V; Ch17 §V | MATCH | Ch16 §V: "Dĩnh Xuyên ... Core | Đã gieo | Ch17 (Gate)". Ch17 §V: "Payoff (vị trí/chức năng); vì sao Dịch chắc còn OPEN | Ch19". |
| 17 | REG:439 | CANON_UNKNOWN | OP-121b "Ai ra lệnh neo thuyền; phó tướng biết gì về ý đồ": CÒN MỞ | Ch21 §II-A; Ch22 §II-A | OVERSTATED | Ch22 §II-A: "Ai ra lệnh thuyền neo ngang sông..." chỉ OPEN theo điểm nhìn Dịch/trên trang Ch22. Nhưng Ch21 §I.12 ghi trên trang Vân Chương dặn phó tướng: "Tới bến thì neo ngang sông. Một đêm."; Ch22 §III: "nguồn lệnh neo — Ch21 lời miệng của Vân Chương; Dịch không biết". Registry tự ghi D-69 (REG:528) "Vân Chương → thủy quân: Đặt thuyền neo ngang sông", mâu thuẫn với OP-121b. Ch21 §II-A cũng chỉ nêu phần "phó tướng biết gì về ý đồ", không nêu "ai ra lệnh". Dòng thiếu phạm vi "OPEN với Dịch / trong Ch22". |
| 18 | REG:255 | CANON_FACT | S-202 tờ giấy dán trên cổng (Dĩnh Xuyên), chữ ký trong tay người khác; Supporting; đã gieo | Ch19 §V | MATCH | Ch19 §V: "Tờ giấy dán trên cổng, chữ ký trong tay người khác | Ch19 | Supporting | Đã gieo | Ch28". Ch19 §I.20 xác nhận cảnh. |
| 19 | REG:134 | CANON_INFERENCE | S-092b "~1.000" (1.200 suất / ~1.000 ký nhận) "do Canon Update tự ghi" | Ch09 §V | TYPE_WRONG | Ch09 §I.12: "danh sách ký nhận ... chỉ tính cho chừng 1.000 người." (con số CÓ trên trang). Ch09 §V: "Đã payoff (1.200 suất / ~1.000 ký nhận; 300 ngựa thật)". Chú giải CANON_INFERENCE yêu cầu "không có trên trang"; chính dòng này thừa nhận "trang chỉ ghi 'chừng 1.000 người'", và S-092a (REG:133) đã giữ phần trên trang là FACT. Dòng 134 tự mâu thuẫn; nên là CANON_FACT (xấp xỉ) hoặc gộp vào S-092a, và Source phải thêm Ch09 §I.12. |
| 20 | REG:769 | PLANNING_NON_CANON | D2-20 Chapter Bible Ch29 "Chu Hạc": Chiêu bắt nhưng không giết ngay; "không phải đại phản diện"; trốn thoát bán mình triều đình mới; hook mang thông tin bố trí quân Hoắc | CB Ch29 | MATCH | bible/CHAPTER_BIBLE_32_CHUONG.txt, CHƯƠNG 29: "DECISION: Chiêu bắt Chu Hạc nhưng không giết ngay." "POWER SHIFT: Chu Hạc trốn thoát và bán mình cho triều đình mới." ENDING HOOK khớp. |
| 21 | TL:159 | CANON_INFERENCE | T-035 chuyến lương 11 "rơi vào khoảng ngày 12" (nhịp ~12 ngày/chuyến), Canon đặt câu hỏi, chưa khóa | Ch03 §VIII.2 | MATCH | Ch03 §VIII.2: "Tính theo nhịp khoảng 12 ngày một chuyến, chuyến 11 rơi vào khoảng ngày 12." Ch04 §I.17 "hàng 11 đủ" khớp tham chiếu T-040. |
| 22 | TL:90 | CANON_FACT | N3-03 Ch04 §I.5–9: Tạ Diên tầng cao từ năm -21; Vân Chương theo cha vào cung; kiến thức công khai năm -21; tên chiêu nghi chứa "Huệ"; Dịch được dạy khuyết nét | Ch04 §I.5–9 | MATCH | Ch04 §I.5: "Tạ Diên ở tầng cao triều đình từ năm -21." I.9: "Dịch từng được dạy khuyết một nét khi viết chữ 'Huệ'." Cột Before ghi "(không ghi)": không phải chuỗi thật, chỉ là dòng nâng lên Production Bible. |
| 23 | TL:185 | CANON_BELIEF (Bùi Chỉ) | T-061 đêm trừ tịch: A Quy nói "tên lính trực mở cửa"; kết luận mười năm "một người"; Chỉ mang tiếng nội ứng | Ch11 §I.20, §I.28, §III | MATCH (lưu ý nhỏ) | Ch11 §I.20: "Ta không mở cửa Bắc. Kẻ mở là tên lính trực đêm ấy." §III: "Kết luận cũ 'một người' không còn đứng vững". Dòng ghi "(kết luận cũ)" nên đúng; thiếu §I.22 và §VI trong Source cho "chỉ đếm tới một" và "mang tiếng nội ứng". T-060 (FACT) tách riêng đúng quy ước. |
| 24 | TL:267 | CANON_UNKNOWN | T-131 nguồn người để câu "không văn thư" lọt ra: chưa xác định | Ch13 §II | MATCH | Ch13 §II: "Người rò tin bên trong (ai, đoàn nào): OPEN tới Gate Ch14." Ch13 §VII: "Đêm ngày 2 (ngoài trang) có người để câu 'không văn thư' lọt ra ngoài." |
| 25 | TL:431 | CANON_INFERENCE | C.2 Ch17: ngày 30; ngày 34; thuyền rời Lạc Thủy rạng ngày 35 | Ch17 §VII; Ch17 §VII (ghi chú); Ch17 §I.6 | MATCH (lưu ý nhỏ) | Ch17 §VII ghi chú: "Thuyền rời Lạc Thủy rạng ngày 35 là lời Dịch ở I; ngày 34 là suy ra." Lưu ý nhỏ: "ngày 30 suy từ 'hạn còn hai' tới ngày 31" nằm ở cột "Ghi chú (theo Canon Update)" nhưng là phép suy của chỉ mục (Canon không giải thích ngày 30); mục C có tuyên bố riêng rằng phép cộng/trừ ngày là của chỉ mục. |
| 26 | TL:290 | CANON_FACT | T-149 hội minh Lạc Thủy: ba cột hội Hổ Lao, bến trên, nghi binh, bốn thời hạn; mốc "đầu xuân năm 1, ngày 1" là INFERRED | Ch15 §I.1–I.9; Ch15 §VII (ghi chú) | MATCH (lưu ý) | Ch15 §VII: "Văn bản không nêu tháng; 'đầu xuân năm 1' là suy ra theo 'băng tan'." Cột Nhãn (mốc) = INFERRED, cột Source Type (sự kiện) = FACT, theo quy ước bảng B. Lưu ý: Ch15 §I.1 vẫn ghi "Đầu xuân năm 1." trong Canon mới (đã vào L-12). |
| 27 | TL:333 | CANON_BELIEF (Tạ Vân Chương) | T-185 ~Ngày 44: Vân Chương suy "một bộ, không phải nhiều" từ thư Uyển | Ch20 §I.1–4 | MATCH | Ch20 §I.4: "Chàng đọc hai lần; suy: một bộ, không phải nhiều." Ch20 §VII: "Mọi số ngày là suy ra" (mốc INFERRED đúng). |
| 28 | TL:397 | PLANNING_NON_CANON | P-11 Scene Bible Ch22: bộ Hàn đi đê ~58, điều chỉnh Production Check thành ~59 | Ch22 §0 | MATCH | Ch22 §0: "Scene Bible ghi bộ đi đê ~58 là lệch một nhịp"; "bộ Hàn đi đê, thuyền tới, cổng bến mở, trận = cùng đêm ~59". |
| 29 | TL:392 | PLANNING_NON_CANON | P-06 ngày 6–9 tin tới đồn Tây Lương ở biên (author-truth) | Ch08 §VII | MATCH | Ch08 §VII: "Ngày 6–9 | Tin tới đồn Tây Lương ở biên (author-truth)". |
| 30 | TL:424 | CANON_INFERENCE | C.2 Ch04 "Khoảng ngày 31" thư nhà kế tiếp, suy từ nhịp mười ngày | Ch04 §V | MATCH | Ch04 §V: "Khoảng 31 | Thư nhà định kỳ kế tiếp (suy từ nhịp mười ngày; nội dung không Canon)". Ch04 §I.21: gửi thư mười ngày một lần. |

## PHẦN 3. TỔNG HỢP

### 3.1 Tỷ lệ MATCH

| Chỉ số | Kết quả |
|---|---|
| MATCH (kể cả "MATCH có lưu ý" nhỏ) | 25/30 = 83,3% |
| MATCH sạch (không lưu ý nào: bỏ #3, #7, #12, #13, #23, #25, #26) | 18/30 = 60% |
| TYPE_WRONG | 3 (#4, #10, #19) |
| OVERSTATED | 2 (#15, #17) |
| SOURCE_WRONG / UNSUPPORTED / BEFORE_AFTER_WRONG | 0 / 0 / 0 |

Theo file: CB 8/10 (lỗi #4, #10); REG 7/10 (lỗi #15, #17, #19); TL 10/10.
Theo loại: PLANNING_NON_CANON 6/6; CANON_UNKNOWN 4/5 (#17); CANON_BELIEF + SUSPICION 4/6 (#10, #15); CANON_INFERENCE 4/5 (#19); nhóm before → after (#2, #4, #7, #9, #10, #14, #15, #22) 5/8.
Theo dải: Ch01–07 và Ch19–22 không có lỗi; lỗi dồn ở Ch08–13 (#4, #10, #19) và Ch14–22 (#15, #17).
Mọi mục Canon được trích (số §, số dòng đánh số, tên mục) đều tồn tại và đúng nghĩa; không dòng nào bịa. Lỗi nằm ở nhãn Source Type và ở lời chú giải của Derived, không phải ở việc trỏ sai chương.
Giới hạn: n=30 nên khoảng tin cậy rộng (xấp xỉ ±13 điểm phần trăm); #28 dựa vào Canon Update Ch22 §0 (Scene Bible không đọc trực tiếp); #20 đối chiếu bible/CHAPTER_BIBLE_32_CHUONG.txt.

### 3.2 Danh sách lỗi (xếp theo mức nghiêm trọng)

| Hạng | # | File:Dòng | Loại lỗi | Mô tả ngắn |
|---|---|---|---|---|
| 1 | 17 | REG:439 (OP-121b) | OVERSTATED | "Ai ra lệnh neo thuyền" ghi UNKNOWN tuyệt đối, trong khi Ch21 §I.12 trên trang cho thấy Vân Chương ra lệnh miệng "Tới bến thì neo ngang sông. Một đêm."; chỉ OPEN theo điểm nhìn Dịch (Ch22 §II-A, §III). Mâu thuẫn với D-69 (REG:528) ngay trong Registry. Người viết Ch23+ có thể coi việc "ai ra lệnh" còn mở cho cả truyện. |
| 2 | 15 | REG:513 (D-54b) | OVERSTATED | Thêm chú giải "đối tượng bị nghi" gắn Kha Trọng với "nghi rò tin". Canon Ch14 giữ nguồn rò (G-1) và Kha Trọng (G-2) là hai thread OPEN riêng; Chỉ "Không biết: Ai rò"; Ch15 §0 ghi chưa nối. Derived đang nối hộ Canon. Cùng gốc: CB:432 và CB:523 (chép sát chữ nên nhẹ hơn). |
| 3 | 4 | CB:224 (+ CB:225, CB:229) | TYPE_WRONG | Tin đồn "tung tích Thất hoàng tử đã tìm được" nằm ở Canon mục "NGHE / THUẬT LẠI (không xác nhận)" nhưng dòng nội dung gắn CANON_FACT; cùng nhóm ở Ch07 lại gắn CANON_BELIEF (CB:215). Nối chuỗi "← Ch07 KNOWLEDGE" nối hai dòng khác Source Type. Đụng bí mật trung tâm (Thất hoàng tử). |
| 4 | 19 | REG:134 (S-092b) | TYPE_WRONG | Gắn CANON_INFERENCE cho con số "chừng 1.000 người" vốn có trên trang (Ch09 §I.12); dòng tự thừa nhận "trang chỉ ghi chừng 1.000 người". Source thiếu §I.12. |
| 5 | 10 | CB:282 (+ CB:278, CB:281, CB:283) | TYPE_WRONG | Cột INFERENCE của Ch12 §III gắn CANON_SUSPICION trong khi cùng nhãn ở Ch21 §III gắn CANON_INFERENCE (CB:987). |

Các lưu ý nhẹ (vẫn tính MATCH): #3 (nội dung FACT bị lặp trong dòng UNKNOWN), #7 (L-20 bỏ sót việc Ch21 §III còn liệt kê câu này ở cột FACT và §0 dùng chữ "xác nhận"), #12 ("Dịch nghe/thấy" trong khi Ch07 §I.3 ghi không nghe được), #13 (Ch19 §IX và Ch22 §II-A không có chữ "động cơ"), #23 (Source thiếu Ch11 §I.22 và §VI), #25 (phép suy "ngày 30" là của chỉ mục nhưng nằm ở cột "theo Canon Update"), #26 (cột Nhãn INFERRED, cột Source Type FACT theo quy ước bảng B; Ch15 §I.1 vẫn ghi "Đầu xuân năm 1.").

### 3.3 Lỗi hệ thống (mẫu hình chung)

1. Ánh xạ Source Type không nhất quán cho hai nhóm Canon ở "vùng xám": (a) Knowledge Matrix "NGHE / THUẬT LẠI" (hearsay): Ch07 gắn BELIEF (CB:215), Ch08 gắn FACT (CB:224, 225, 229), Ch14 gắn FACT (CB:426, 521); (b) Knowledge Matrix "INFERENCE": Ch12 gắn SUSPICION (CB:168, 278, 282), Ch22 gắn SUSPICION (CB:169, 383; nhãn Canon có thêm chữ "nghi"), Ch21 gắn INFERENCE (CB:892, 987). Đã gặp ở #4, #7, #10. Hậu quả: lọc theo Source Type sẽ cho kết quả khác nhau cho cùng một loại thông tin.
2. Chú giải của chỉ mục chèn vào ô claim như thể thuộc Canon: #15 ("đối tượng bị nghi"), #25 (phép suy ngày 30 ở cột "theo Canon Update"), #12 ("nghe/thấy"), #13 (gộp "động cơ riêng" cho Ch19/Ch22). Mẫu hình: chú giải "giúp đọc" nới rộng hơn câu Canon, nguy hiểm nhất khi nó nối hai thread OPEN mà Canon chưa nối (#15).
3. Mất phạm vi điểm nhìn của OPEN (#17): Canon đánh dấu "OPEN trên trang" theo từng chương/POV; Registry gộp thành UNKNOWN tuyệt đối dù chương khác đã đưa câu trả lời lên trang. Nên rà các OP-xxx dạng "Ai ra lệnh... / ai biết..." xuyên chương.
4. Ô kép tách k/n lặp nguyên văn cả ô vào mỗi dòng (#3, #4, #10): dòng UNKNOWN chứa nội dung FACT, dòng FACT chứa nội dung tin đồn. Có chú thích ⟦⟧ nhưng người lọc theo cột Source Type sẽ không thấy chú thích.
5. "Nối chuỗi" chỉ nối theo tên trường: 82/82 con trỏ trong CB mục (b) đều trỏ tới dòng có tồn tại (quét tự động), nhưng nội dung nhiều dòng được nối không cùng chủ đề (ví dụ CB:224 ← "Ch07 KNOWLEDGE" chung chung; Ôn Ch15 KNOWLEDGE(không biết) "thái độ Ôn sau thất bại" ← Ch12 KNOWLEDGE "chưa biết chuyện bảo chứng A Quy"). Chuỗi before → after ở những chỗ này là chuỗi cơ học, không phải chuỗi ngữ nghĩa. Không dòng nào trong mẫu bị sai theo nghĩa "after không khớp before", nhưng một số dòng before → after có cột Before ghi "(không ghi)"/"(đầu dải)" nên không kiểm được chuỗi (#2, #9, #22).

### 3.4 Khuyến nghị sửa Derived (không sửa Canon)

1. REG:439 (OP-121b): tách hai ý. "Ai ra lệnh neo thuyền" -> ghi "OPEN với Dịch / trong Ch22 (Ch22 §II-A); trên trang Ch21 §I.12 Vân Chương dặn phó tướng 'Tới bến thì neo ngang sông. Một đêm.'" (kèm tham chiếu D-69, REG:528, và Ch22 §III). Chỉ giữ CANON_UNKNOWN cho "phó tướng biết gì về ý đồ" (Ch21 §II-A). Rà các OP khác cùng dạng.
2. REG:513 (D-54b): bỏ cụm "đối tượng bị nghi"; chép đúng Canon "Chính hắn (nghi rò tin) | Hai dòng 'Kha Trọng'"; thêm ghi chú "Canon không nói 'Chính hắn' là ai; G-1 (nguồn rò) và G-2 (Kha Trọng) chưa được nối (Ch14 §II; Ch15 §0)". Đồng bộ CB:432 và CB:523.
3. CB:224, 225, 229 (và CB:215, 426, 521): thống nhất quy tắc hearsay. Đề nghị: dòng "Dịch đã nghe tin X" -> CANON_FACT (bỏ nội dung tin đồn ra khỏi ô, hoặc ghi "nội dung không xác nhận"); dòng nội dung tin đồn -> CANON_BELIEF/UNKNOWN. Đổi "Nối chuỗi" của CB:224 thành trỏ cụ thể tới dòng CB:215.
4. REG:134 (S-092b): đổi sang CANON_FACT (xấp xỉ) hoặc gộp vào S-092a (REG:133); bỏ cụm "do Canon Update tự ghi"; thêm Source Ch09 §I.12.
5. CB:168, 278, 281–283 và CB:892, 987 (CB:169, 383 có chữ "nghi" trong nhãn Canon nên có thể giữ SUSPICION): chọn một quy tắc duy nhất cho nhãn "INFERENCE" trong Knowledge Matrix (đề xuất: nhãn Canon "INFERENCE" -> CANON_INFERENCE; chỉ khi Canon dùng "nghi/đoán" -> CANON_SUSPICION) và ghi quy tắc vào chú giải; sau đó đổi các dòng lệch.
6. CB:1549 (L-20) và CB:987/892: bổ sung vào L-20 rằng Ch21 §III liệt kê câu "thư riêng đã tới tay người giữ chức" ở cả cột FACT và "INFERENCE (một mức)", và Ch21 §0 ghi "xác nhận ... chỉ ở mức Hổ Lao"; theo quy ước của chính Derived cho trường hợp Canon mâu thuẫn, nên giữ hai dòng (FACT và INFERENCE) thay vì chọn một.
7. TL:431: chuyển phần "ngày 30 suy từ 'hạn còn hai' tới ngày 31" ra khỏi cột "Ghi chú (theo Canon Update)" hoặc gắn "(phép của chỉ mục)".
8. REG:355 (OP-050): ghi "động cơ riêng" chỉ cho Ch10 §II, Ch11–Ch13 §IX; Ch19 §IX và Ch22 §II-A ghi "Chu Hạc (nói chung, giữ OPEN)".
9. REG:118 (S-079): đổi "Dịch nghe/thấy" thành "Dịch thấy (không nghe được vì pháo)". TL:185 (T-061): thêm Ch11 §I.22 và §VI vào Source.
10. Rà các dòng cùng mẫu hình đã nêu ở 3.3 (grep "cột INFERENCE", "NGHE", "đối tượng bị nghi", "Ai ra lệnh") trước khi đưa các file Derived vào dùng làm tham chiếu viết Ch23+.

### 3.5 Ghi chú phương pháp và tệp tạm
- Script: parse.py, sample.py trong thư mục scratchpad; rows.json (2.270 dòng claim) và chosen.json (30 dòng bốc). Không sửa bất kỳ file nào trong repo.
- Loại trừ khi bốc: dòng APPEARANCE và dòng chú giải Source Type (là dòng dễ). Mỗi ô tầng (file x dải) được bốc ngẫu nhiên bằng random.choice với random.seed(20261003) trong tập dòng đủ điều kiện về loại; thứ tự bốc cố định theo script.
