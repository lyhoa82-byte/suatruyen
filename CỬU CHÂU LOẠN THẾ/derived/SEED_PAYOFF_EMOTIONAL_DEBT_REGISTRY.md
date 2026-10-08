# SEED → PAYOFF · OPEN THREADS · EMOTIONAL DEBT — REGISTRY (CỬU CHÂU LOẠN THẾ)

> **DERIVED / NON-CANON.** DERIVED files have zero canon authority. They are convenience indexes only.
> Thứ tự ưu tiên: LOCKED / Canon Update → Bible quy định → Derived → Draft.
> Nếu Derived sai: sửa/xóa Derived; KHÔNG BAO GIỜ sửa Canon để làm Derived khớp.
> Derived Registry không bao giờ được giải quyết một mâu thuẫn Canon; chỉ được chỉ ra mâu thuẫn đó (mục "MÂU THUẪN / LỆCH").
> Trạng thái: dựng từ Canon Update Ch01–Ch22 (cuối Ch22). Đã Consistency Check + QA 30 claim (vòng 1) + sửa vòng 1.

## CHÚ GIẢI

**Source Type (đúng 6 giá trị; mỗi dòng/claim đúng 1 giá trị):**

| Source Type | Nghĩa |
|---|---|
| `CANON_FACT` | Fact đã có trên trang / đã khóa canon trong Canon Update (mục "Canon mới", Canon Change, fact khách quan). |
| `CANON_BELIEF` | Điều một nhân vật TIN chắc (cột "Tin"/"Niềm tin" của Canon Update; có thể sai). Ghi rõ ai tin trong cột nội dung. |
| `CANON_SUSPICION` | Điều một nhân vật NGHI/đoán, chưa xác nhận; gồm cả cột "INFERENCE"/"suy luận" của Knowledge Matrix về một nhân vật (ghi ai đoán), và lời đồn / "NGHE / THUẬT LẠI (không xác nhận)" / tin chưa xác nhận (đầu nội dung ghi "(lời đồn)" hoặc "(nghe thuật lại)"). |
| `CANON_INFERENCE` | Chỉ dành cho suy ra cấp tác giả / Canon Update (số ngày "~", "suy ra", ước tính), không có trên trang. Không dùng cho suy luận của một nhân vật. |
| `CANON_UNKNOWN` | Canon Update ghi rõ OPEN / chưa biết / không biết / chưa trả lời. Nếu OPEN chỉ theo điểm nhìn một nhân vật mà Canon đã cho thấy ở chương khác: nội dung ghi "OPEN với <ai> / trên trang POV <ai>; Canon đã có ở ChNN §…". |
| `PLANNING_NON_CANON` | Kế hoạch, author-truth (không lên trang), "Chapter Bible dự kiến", "ràng buộc Ch+", đề xuất chưa duyệt. Chỉ nằm ở mục D (và các dòng bị tách có ghi rõ). |

**Cách đọc Source:** `Ch12 §I.7` = Canon Update Ch12, mục I, dòng đánh số 7. `Ch22 §II-A` = mục II-A. `Ch08 §V` = Seed→Payoff Registry của Canon Update Ch08 (các chương đặt số mục khác nhau: Ch01–Ch05 là §IV, Ch06 trở đi là §V; §VI/§VII = Emotional Debt / Timeline tùy chương — luôn ghi đúng số mục của file đó). Planning ghi `CB Ch28` (Chapter Bible) / `PB Seed 3` (Production Bible).

**Quy ước của file này**
- Mọi dòng lấy từ staging do các agent trích từ `canon/CCLT_Canon_Update_ChNN.md` (Ch01–Ch22). Không có claim mới; riêng mục D có thêm kế hoạch đọc từ `bible/CHAPTER_BIBLE_32_CHUONG.txt` và `bible/PRODUCTION_BIBLE.txt`.
- **Bảng A–C không chứa planning.** Mọi `PLAN: ChX` do Canon Update ghi ở cột Payoff dự kiến đã được tách sang **D1** (khóa theo ID seed).
- Cột "Payoff theo canon" chỉ có: payoff đã xảy ra theo Canon Update (Ch + Source), hoặc `OPEN`, hoặc `Canon chưa đặt`. Registry này **không tự đặt deadline/payoff**.
- ID `S-nnn` = seed (mục A). Hậu tố `a`/`b` = dòng bị tách vì staging gắn 2 Source Type trong một ô (vd FACT / UNKNOWN). `OP-nnn` = OPEN thread (mục B). `D-nn` = nợ cảm xúc theo cặp (mục C). `RG-L-nn` = mâu thuẫn/lệch (mục E); `CB-L-nn` / `TL-L-nn` = mâu thuẫn ghi ở CHARACTER_BIBLE_DERIVED.md / MASTER_TIMELINE_DERIVED_Ch1-Ch22.md.
- Ô Source Type chỉ chứa đúng một trong 6 giá trị; người tin/nghi và chú thích nằm ở cột nội dung. Claim đang là mâu thuẫn CHƯA QUYẾT ở bất kỳ file Derived nào: dòng dùng claim đó ghi "⚠ xem RG-L-xx" và không gắn CANON_FACT cho phía đang tranh chấp.
- Bí danh chưa được Canon xác nhận (Phùng thúc ↔ Phùng Bảo; Ôn ↔ Thứ sử; Uyển ↔ Khả đôn…) không gộp: mỗi dòng giữ nhãn gốc, gắn "[BÍ DANH CHƯA XÁC NHẬN — xem RG-L-xx]" khi dòng chạm tới cả hai nhãn. Hoắc Tam Lang = Hoắc Chiêu được Canon xác nhận (Ch12 §III) nên được gộp.
- "Mức" (Core/Major/Supporting/Minor) chép nguyên nhãn Canon Update; nếu hai chương ghi mức khác nhau thì ghi cả hai.
- Trạng thái nợ (UNPAID / ACTIVE / Mới / Ẩn / …) giữ nguyên chữ từng Canon Update; các chương không dùng chung một bộ nhãn nên **không quy đổi** giữa các nhãn.
- "Không cập nhật sau ChNN" = Canon Update các chương sau không có dòng cho mục đó; không suy diễn thêm.

---

## A. SEED → REINFORCE → PAYOFF

| ID | Seed (tên theo Canon Update) | Gieo | Reinforce | Payoff theo canon | Mức | Trạng thái cuối Ch22 | Source Type | Source |
|---|---|---|---|---|---|---|---|---|
| S-001 | Bắc Môn / "cửa mở từ bên trong" (motif cửa; Ch19 §V gọi "biểu tượng Danh") | Ch01 §IV | Ch06 §V ("nàng tự tay đóng lại", Major); Ch19 §V; Ch21 §V (hook "Cổng thành mở."); Ch22 §V (cổng bến mở, "không ai hô") | Canon chưa đặt | Core | Đã gieo, được gieo thêm Ch06, Ch19, Ch21, Ch22; chưa payoff (xem RG-L-01) | CANON_FACT | Ch01 §IV; Ch06 §V; Ch19 §V; Ch21 §V; Ch22 §V |
| S-002 | Then mới (sồi bọc sắt, hai người khiêng, bôi dầu) | Ch01 §IV; Ch01 §I.9 | Ch06 §I.41, §I.48 (then nguyên vẹn, cài lại "êm như chưa từng được kéo ra"); Ch11 §V, §I.28 (lệnh "thanh then nặng bao nhiêu, mấy người mới khiêng nổi"; nhãn "Được gọi lại") | Canon chưa đặt | Major (Ch01 §IV); Core (Ch11 §V) | Được gọi lại ở Ch11; chưa payoff (xem RG-L-02) | CANON_FACT | Ch01 §I.9, §IV; Ch06 §I.41, §I.48; Ch11 §I.28, §V |
| S-003 | Chu Hạc | Ch01 §IV | Ch02 §IV; Ch03 §IV; Ch06 §I.25–28 | Canon chưa đặt | Core | Đang tăng cường (Ch03 §IV, Ch06); thread Chu Hạc giữ OPEN ở Ch22 (xem OP-050) | CANON_FACT | Ch01 §IV; Ch02 §IV; Ch03 §IV; Ch06 §I.25–28 |
| S-004 | Hụt lương có quy luật / số tồn không đáng tin | Ch01 §IV | Ch04 §I.16–17 (Dịch dựng lại lượng tồn: hàng 3, 5, 7, 9 hụt hai, hàng 11 đủ); Ch04 §IV | Canon chưa đặt | Major | Còn mở; Ch04 §VI: tuyến lương không đổi, tám xe hụt, chuyến 11 đủ (xem OP-001, OP-002) | CANON_FACT | Ch01 §IV; Ch04 §I.16–17, §IV, §VI |
| S-005 | Thiếu giấy báo hao | Ch01 §IV | — | Canon chưa đặt | Supporting | Đã gieo; không nhắc lại trong staging | CANON_FACT | Ch01 §IV |
| S-006 | Bao lương dây mới (xe "Thất", bao thứ ba) | Ch01 §IV, §VI | — | Canon chưa đặt ("chưa khóa payoff, chưa khóa giả thuyết" — Ch01 §IV) | Supporting | Đã gieo; không nhắc lại Ch2–Ch7 (xem OP-005) | CANON_FACT | Ch01 §IV, §VI |
| S-007 | Người mặc áo lính hỏi thăm Dịch | Ch01 §IV | Ch03 §IV ("Giữ mở") | Canon chưa đặt ("chưa khóa danh tính" — Ch01 §IV) | Supporting | Còn mở (xem OP-003) | CANON_FACT | Ch01 §IV; Ch03 §IV |
| S-008 | Bàn cờ chín hàng bị bỏ lại ("Hắn không dọn") — phần quân cờ xem S-029 | Ch01 §IV (tiền seed) | Ch03 §III–§IV; Ch07 §V | Ch07 §V "Đã payoff (đóng tuyến Quyển I)"; Ch07 §I.9 | Core (Ch01 §IV); Supporting (Ch07 §V) | Phần bàn cờ bị bỏ lại: đóng ở Ch07 (xem RG-L-03) | CANON_FACT | Ch01 §IV; Ch03 §III–§IV; Ch07 §I.9, §V |
| S-009 | Hoắc Tam Lang (các clue thân phận) | Ch01 §IV (clue Ch01 §I.14) | Ch06 §I.20–21 (cha gọi "A Chiêu"; narration gọi "nàng") | Canon chưa gắn nhãn payoff (sự kiện trên trang: Ch06 §I.20–21) | Core | Ch06 đưa thân phận nữ lên trang; Canon Update không ghi payoff | CANON_FACT | Ch01 §IV; Ch06 §I.20–21 |
| S-010 | Uyển: nhường đường, giữ đội hình | Ch01 §IV | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch01 §IV |
| S-011 | Tiếng ho của Tạ phó sứ → Sức khỏe Vân Chương (Seed 9) | Ch01 §IV | Ch03 §IV; Ch04 §IV, §I.32; Ch05 §I.27, §I.33; Ch20 §V (chuỗi Ch4 → Ch13 → Ch20); Ch21 §V (ho nặng, bút rơi, thư lại ghi thay) | Canon chưa đặt | Major | Nặng hơn; chưa máu (Ch21 §V, §IV) | CANON_FACT | Ch01 §IV; Ch03 §IV; Ch04 §I.32, §IV; Ch05 §I.27, §I.33; Ch20 §V; Ch21 §IV, §V |
| S-012 | Phùng thúc cúi quá thấp (thân phận Dịch) | Ch01 §IV (Ch01 §I.13) | Ch03 §IV, §I.34 ("Người trong kinh."); Ch04 §IV, §I.13–14 (Vân Chương thấy dáng cúi, không nhận ra danh tính); Ch07 §V | Canon chưa đặt | Major | Đang tăng cường (theo Ch07 §V); chưa payoff theo nhãn Canon Update | CANON_FACT | Ch01 §IV; Ch03 §IV; Ch04 §IV; Ch07 §V |
| S-013 | Đoàn hòa thân mắc lại vì Hắc Sơn tắc tuyết | Ch01 §IV (Ch01 §I.2) | Ch04 §I.23 (thư Vân Chương: ải Hắc Sơn dự kiến thông vào tháng Hai) | Canon chưa đặt | Major | Còn mở (xem OP-014) | CANON_FACT | Ch01 §IV; Ch04 §VIII.4; Ch05 §VIII.1 |
| S-014 | Tuyết | Ch01 §IV | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch01 §IV |
| S-015 | Lời hứa áo bông ("Ngày mai tôi sẽ nói") | Ch01 §VII | Ch02 §VII ("Vẫn treo từ Ch1") | Ch03 §IV "Đã payoff (một phần, 26/30)"; Ch03 §VII: đóng | Supporting | Đóng (xem RG-L-04) | CANON_FACT | Ch01 §VII; Ch02 §VII; Ch03 §IV, §VII |
| S-016 | Chu Hạc biết mặt Chỉ | Ch02 §IV | Ch06 §I.27 (lời Chu Hạc về A Quy; Canon Ch06 không gắn nhãn payoff) | Canon chưa đặt | Major | Đã gieo; Ch06 có lời Chu Hạc nhưng Canon Update không ghi payoff | CANON_FACT | Ch02 §IV; Ch06 §I.27 |
| S-017 | Hoắc giữ Chỉ ngoài sổ | Ch02 §IV | Ch03 §III (lính hậu doanh biết A Quy là kẻ đột nhập, làm theo lệnh không hỏi, không đánh) | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch02 §IV; Ch03 §III |
| S-018 | Vết bớt sau tai Chỉ | Ch02 §IV (Ch02 §II) | — | Canon chưa đặt | Core | Đã gieo (chưa gọi tên, chưa được nói ra trong truyện) | CANON_FACT | Ch02 §II, §IV |
| S-019 | Cửa sau phủ Bùi / "Ta ở đó" | Ch02 §IV | Ch03 §IV ("Giữ mở": cửa sau) | Canon chưa đặt | Core | Đã gieo; Canon Update Ch06 không nhắc | CANON_FACT | Ch02 §IV; Ch03 §IV |
| S-020 | "Có người kéo hắn ra" | Ch02 §II, §IV | — | Canon chưa đặt | Major | Đã gieo; danh tính chưa khóa (xem OP-008) | CANON_FACT | Ch02 §II, §IV |
| S-021 | Tam Lang–Chỉ chạm mặt lần đầu | Ch02 §IV | Ch06 §I.14–15 (giao thủ một đòn) | Canon chưa gắn nhãn payoff | Major | Đã gieo | CANON_FACT | Ch02 §IV; Ch06 §I.14–15 |
| S-022 | Hoắc thức ở thư phòng | Ch02 §IV | Ch06 §I.4 (Hoắc về thư phòng; Canon Ch06 không gắn nhãn) | Canon chưa đặt | Supporting | Đã gieo; nguyên nhân author-truth: xem D3 | CANON_FACT | Ch02 §II, §IV; Ch06 §I.4 |
| S-023 | Chỉ biết nhìn thời tiết, chờ tuyết | Ch02 §IV | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch02 §IV |
| S-024 | Vết thương tay Tam Lang | Ch02 §IV | Ch03 §I.45, §VI (băng tay lộ hai lần) | Canon chưa đặt ("không bắt buộc, không thành subplot" — Ch02 §IV) | Minor | Đã gieo | CANON_FACT | Ch02 §IV; Ch03 §I.45, §VI |
| S-025 | Bát cháo / bó chân | Ch02 §IV | Ch03 §VII (giữ mạng, bó chân, đặt tên cho Chỉ là một phần món nợ của Hoắc, "không được giải thích"); Ch03 §I.12 | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch02 §IV; Ch03 §I.12, §VII |
| S-026 | Thanh đao trong phòng ngủ | Ch02 §II, §IV | — | Đóng (chỉ tả cảnh; Ch02 §II: không gán chức năng) | Minor | Đóng | CANON_FACT | Ch02 §II, §IV |
| S-027 | Lòng thù Hoắc của Chỉ | Ch02 → Ch03 §IV | Ch03 §VII (Chỉ vẫn thù Hoắc) | Canon chưa đặt | Core | Đang tăng cường; Canon Update Ch06 ghi Hoắc đã chết (Ch06 §I.20) nhưng không cập nhật seed này | CANON_FACT | Ch03 §IV, §VII; Ch06 §I.20 |
| S-028 | Khoảng cách một cây thương | Ch02 → Ch03 §IV | — | Canon chưa đặt | Supporting | Đang tăng cường | CANON_FACT | Ch03 §IV |
| S-029 | Quân trắng (Seed 1) — năm quân trắng, mỗi người một quân | Ch03 §IV (§I.30–31, §I.43) | Ch04 §VI; Ch05 §V; Ch07 §V (Quân trắng trong túi Dịch, "Ch3 → Ch7, đang tăng cường"), §I.10, §I.31 | Canon chưa đặt | Core | Đang tăng cường; Dịch giữ quân trắng trong túi áo (Ch07 §IV); không cập nhật sau Ch07; "quân trắng của năm người" giữ OPEN (OP-061) | CANON_FACT | Ch03 §IV; Ch04 §VI; Ch05 §V; Ch07 §I.10, §I.31, §IV, §V |
| S-030 | Quân của A Quy, hắn tự nhặt | Ch03 §IV (Ch03 §I.13) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch03 §IV |
| S-031 | Quân của Tam Lang để lại trên bàn | Ch03 §IV (Ch03 §I.50) | Ch04 §I.26 (nằm sáu ngày không ai đụng) | Ch04 §IV "Đã payoff (Ch4 S4)" — Đóng | Supporting | Đóng | CANON_FACT | Ch03 §I.50, §IV; Ch04 §I.26, §IV |
| S-032 | Tên A Quy | Ch03 §IV (Ch03 §I.4) | Ch06 §I.27, §I.47 (lệnh "A Quy. Bắt sống."); Ch07 §I.27 | Canon chưa đặt | Core | Đang tăng cường | CANON_FACT | Ch03 §IV; Ch06 §I.27, §I.47; Ch07 §I.27 |
| S-033 | Tay áo Dịch | Ch03 §IV (Ch03 §I.32) | — | Ch04 §IV "Đã payoff → phép thử" — Đóng | Major (seed nhỏ) | Đóng | CANON_FACT | Ch03 §IV; Ch04 §IV |
| S-034 | Hắc Hà đóng băng | Ch03 §IV (Ch03 §I.3) | Ch04 §IV, §I.31 (báo cáo Tam Lang: băng dày ngang một bàn tay) | Ch06 §V liệt "P-20 Hắc Hà (Gate)" vào "Payoff đã trả" | Major | Đã trả theo Ch06 §V | CANON_FACT | Ch03 §IV; Ch04 §I.31, §IV; Ch06 §V |
| S-035 | Tam Lang không bỏ quân | Ch03 §IV (Ch03 §I.49) | — | Canon chưa đặt ("Không foreshadow lộ" — Ch03 §IV) | Supporting (seed tính cách) | Đã gieo | CANON_FACT | Ch03 §IV |
| S-036 | Vọng Hương (lầu Vọng Hương / vọng bái) | Ch03 §IV (Ch03 §I.28) | Ch05 §IV ("Motif Vọng Hương / vọng bái", đang tăng cường), §I.11, §I.27 | Canon chưa đặt ("Không bắt buộc" — Ch03 §IV) | Supporting | Đang tăng cường | CANON_FACT | Ch03 §IV; Ch05 §I.11, §I.27, §IV |
| S-037 | Bàn cờ gấp của Vân Chương | Ch03 §IV (Ch03 §I.38) | — | Canon chưa đặt ("Không bắt buộc") | Supporting | Đã gieo | CANON_FACT | Ch03 §IV |
| S-038 | Uyển–Vân Chương | Ch03 §IV | Ch04 §IV (than, thuốc sắc); Ch05 §I.27–28 | Canon chưa đặt | Major | Đang tăng cường (theo Ch05); các tuyến sau xem S-056, S-159 và mục C | CANON_FACT | Ch03 §IV; Ch04 §IV; Ch05 §I.27–28 |
| S-039 | Uyển tự cưỡi ngựa | Ch03 §I.40; Ch04 §I.32 | — | Ch05 §IV "Đã payoff" — Đóng; Ch05 §I.26 | Supporting | Đóng | CANON_FACT | Ch03 §I.40; Ch04 §I.32; Ch05 §I.26, §IV |
| S-040 | Uyển xin học ngựa / con ngựa hồng | Ch03, Ch05 (theo Ch12 §V) | Ch12 §I.26 | Ch12 §V "Payoff (bước 2 nhận diện)" | Supporting | Đã payoff | CANON_FACT | Ch12 §I.26, §V |
| S-041 | Luật giữ lượt (Canon Ch3) | Ch03 (theo Ch10 §V) | Ch10 §I.38–39 (quân cờ trắng đặt lên mép bàn; nàng nhớ luật ở Vân Trung) | Ch10 §V "Payoff một phần (quân cờ trên mép bàn)" | Core | Payoff một phần | CANON_FACT | Ch10 §I.38–39, §V |
| S-042 | A Quy ngồi quay lưng vào tường | Ch03 (theo Ch12 §V) | Ch12 §I.20; Ch13 §I.24 (ký ức: ngồi sát tường; không ai bảo ngồi chỗ khác) | Canon chưa đặt (nhãn "Tiếng vọng" — Ch12 §V) | Supporting | Tiếng vọng | CANON_FACT | Ch12 §I.20, §V; Ch13 §I.24 |
| S-043 | Vết sẹo trên tay Chiêu | Ch03 (theo Ch13 §V) | Ch13 §I.12 | Canon chưa đặt (nhãn "Tiếng vọng" — Ch13 §V) | Supporting | Tiếng vọng | CANON_FACT | Ch13 §I.12, §V |
| S-044 | Vải bông trong tờ kê (áo bông Ch3) | Ch03 (theo Ch13 §V) | Ch13 §I.4 | Canon chưa đặt (nhãn "Tiếng vọng" — Ch13 §V) | Supporting | Tiếng vọng | CANON_FACT | Ch13 §I.4, §V |
| S-045 | "Sông đóng thì ngựa qua được" (Ch3) → đục băng | Ch03 (theo Ch10 §V) | — | Ch10 §V "Payoff (tiếng vọng)" — Đóng | Supporting | Đã payoff | CANON_FACT | Ch10 §V |
| S-046 | Vân Chương tin về thân phận Dịch | Ch04 §IV | Ch05 §III ("Vẫn tin rất cao, chưa xác nhận"); Ch07 §III (Vân Chương không chắc Dịch sống hay chết) | Canon chưa đặt | Core | Đã gieo (niềm tin của Tạ Vân Chương, chưa xác nhận) | CANON_BELIEF | Ch04 §III, §IV; Ch05 §III; Ch07 §III |
| S-047 | Chữ "Huệ" / khuyết bút | Ch04 §IV (Ch04 §I.9, §I.19) | — | Canon chưa đặt | Major | Đã gieo (xem RG-L-05 về nhãn "Phùng Bảo") | CANON_FACT | Ch04 §IV |
| S-048 | Vân Chương giấu cha (đốt thư) | Ch04 §IV (Ch04 §I.22) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch04 §IV |
| S-049 | Vân Chương biết Dịch dựng lại lượng tồn kho | Ch04 §IV | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch04 §IV |
| S-050 | Thư Tạ Diên, "một chỗ chỉ hai cha con biết đọc" | Ch04 §IV (Ch04 §I.34) | — | Ch05 §IV "Đã payoff một phần (giải mã)"; Ch05 §I.1–5 (mười chữ) | Core | Payoff một phần | CANON_FACT | Ch04 §IV; Ch05 §I.1–5, §IV |
| S-051 | Dịch không tránh Vân Chương | Ch04 §IV (Ch04 §I.28) | — | Canon chưa đặt ("Căng thẳng; chưa xác nhận hai bên hiểu nhau" — Ch04 §IV) | Supporting | Đã gieo | CANON_FACT | Ch04 §IV |
| S-052 | Uyển: "không giống thư lại" | Ch04 §IV (Ch04 §I.25) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch04 §IV |
| S-053 | Uyển thấy tro giấy | Ch04 §IV (Ch04 §I.24) | — | Canon chưa đặt ("Không bắt buộc") | Minor | Đã gieo | CANON_FACT | Ch04 §IV |
| S-054 | Tay áo ở S4 (P-11) | Ch04 §IV (Ch04 §I.29) | — | Canon chưa đặt ("ý nghĩa không xác định" — Ch04 §I.29) | Minor / watch | Mơ hồ (xem OP-016; RG-L-06 về nhãn P-11) | CANON_FACT | Ch04 §I.29, §IV |
| S-055 | Cái liếc xuống chân trái | Ch04 (theo Ch11 §V; Ch11 §I.14) | — | Ch11 §V "Payoff (nhận diện)" — Đóng | Supporting | Đã payoff | CANON_FACT | Ch11 §I.14, §V |
| S-056a | Thuốc vỏ quýt → thư ngắn + gói vỏ quýt đi sau (Uyển → Vân Chương) — phần fact | Ch04 (theo Ch13 §V, Ch18 §V) | Ch13 §I.17, §V ("Tiếng vọng"); Ch18 §I.23–24, §IV, §V (thư và gói đã gửi); Ch20 §I.4, §I.19, §I.21 (tới Kim Lăng, Vân Chương nhận, không đáp); Ch21 §V ("Gói vỏ quýt còn một nắm") | Canon chưa đặt | Supporting (Ch13, Ch20, Ch21 §V); Major (Ch18 §V) | Thư và gói đã gửi; Vân Chương đã nhận; gói còn một nắm (Ch21 §V) | CANON_FACT | Ch13 §I.17, §V; Ch18 §I.23–24, §IV, §V; Ch20 §I.4, §I.19, §I.21; Ch21 §V |
| S-056b | Thuốc vỏ quýt → thư ngắn + gói vỏ quýt — phần phản ứng / đáp | Ch18 §II; Ch20 §V | Ch21 §V | OPEN (Ch20 §V; Ch21 §V) | Supporting | Đã nhận, không đáp; còn mở (xem OP-106b) | CANON_UNKNOWN | Ch18 §II; Ch20 §V; Ch21 §V |
| S-057 | Lá thư viết dở gửi Hoắc (thêm một dòng) | Ch05 §IV (Ch05 §I.7–10) | — | Canon chưa đặt | Major | Đã gieo; vị trí cuối ghi nhận: trong tay Vân Chương (Ch05 §V); Ch06, Ch07 không nhắc | CANON_FACT | Ch05 §IV, §V |
| S-058 | Bảy ngày giữ kín | Ch05 §IV | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch05 §IV |
| S-059 | Bộ sử 12 quyển / mật mã cha con | Ch05 §IV (Ch05 §I.1–4) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch05 §IV |
| S-060 | Lời mời hai lần | Ch05 §IV (Ch05 §I.20–22) | Ch07 §V (đêm trừ tịch Dịch ở nhà sát Bắc Môn, đúng điều Vân Chương sợ; Dịch không nhớ lại lời mời trong Ch7) | Ch07 §V "Payoff một phần" ("chỉ nằm ở phía người nghe") | Major | Đã gieo (scope limit); payoff một phần | CANON_FACT | Ch05 §I.20–22, §IV; Ch07 §V |
| S-061 | Phu xe đoàn ở lại dịch quán | Ch05 §IV (Ch05 §I.14) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch05 §IV |
| S-062 | A Quy không được mời | Ch05 §IV (Ch05 §I.23) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch05 §IV |
| S-063 | Lệnh "không được vào" | Ch05 §IV (Ch05 §I.28) | — | Canon chưa gắn nhãn payoff | Major | Đã gieo | CANON_FACT | Ch05 §IV |
| S-064 | Tùy tùng ở ngoài Nam Môn | Ch05 §IV (Ch05 §I.31) | — | Canon chưa đặt | Supporting | Đã gieo, "chỉ là khả năng"; Ch06, Ch07 không nhắc | CANON_FACT | Ch05 §IV |
| S-065 | Câu hỏi về pháo | Ch05 §IV (Ch05 §I.25) | — | Ch06 §V "Payoff đã trả" ("chỉ nhắc lại, chưa có ý nghĩa với Chiêu"); Ch06 §I.6 | Minor | Đã trả theo Ch06 §V | CANON_FACT | Ch05 §IV; Ch06 §I.6, §V |
| S-066 | Âm thanh phía bắc | Ch05 §IV (Ch05 §I.35) | — | Ch07 §V "Đã payoff (hai POV nghe cùng một âm thanh)" — Đóng; Ch07 §I.7 | Core (hook) | Đóng theo Ch07 §V (xem RG-L-07 về chương payoff) | CANON_FACT | Ch05 §IV; Ch07 §I.7, §V |
| S-067 | Chu Hạc công khai trao chính danh | Ch06 §V (Ch06 §I.28) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch06 §V |
| S-068 | Tướng kỳ họ Hoắc | Ch01 (chỉ theo Ch06 §V; Canon Update Ch01 không có mục này — xem RG-L-08) | — | Ch06 §V "Payoff đã trả" ("tướng kỳ họ Hoắc (Ch1)"); Ch06 §I.30 | (không ghi) | Đã trả theo Ch06 §V | CANON_FACT | Ch06 §I.30, §V |
| S-069 | "A Chiêu" | Ch06 §V (Ch06 §I.20–21) | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch06 §V |
| S-070 | Xác lính gác trẻ; "trực ở đây"; áo bông kép | Ch06 §V (Ch06 §I.42, §I.44) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch06 §V |
| S-071 | Phòng củi trống, khóa mở | Ch06 §V (Ch06 §I.32) | — | Canon chưa đặt | Major | Đã gieo; ai mở khóa là OPEN (Ch06 §II; xem OP-027) | CANON_FACT | Ch06 §II, §V |
| S-072 | Xác thích khách Bắc Nhung; "có gì đó không khớp" | Ch06 §V (Ch06 §I.19) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch06 §V |
| S-073 | A Quy bị quy là nội ứng | Ch06 §V (Ch06 §I.26–27; Ch06 §II) | Ch07 §V (lời đồn A Quy không khớp nhau) | Canon chưa đặt | Major | Đã gieo (người tin: Chu Hạc — "cách nhìn"; Hoắc Chiêu — "niềm tin"; Ch06 §II) | CANON_BELIEF | Ch06 §II, §V; Ch07 §V |
| S-074 | "Bắt sống" | Ch06 §V (Ch06 §I.47) | Ch07 §I.27 (lệnh lan tới nửa nam) | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch06 §V; Ch07 §I.27 |
| S-075 | "…quân…" (lời cha Chiêu) | Ch06 §V (Ch06 §I.20) | — | OPEN (Ch06 §V; Ch06 §II) | Supporting | OPEN (xem OP-029) | CANON_UNKNOWN | Ch06 §II, §V |
| S-076 | Tiểu Tứ không quay lại | Ch06 §V (Ch06 §I.12; Ch06 §0A) | — | OPEN (Ch06 §V; Ch06 §0A) | Minor | OPEN (Ch10 §II giữ OPEN; xem OP-028) | CANON_UNKNOWN | Ch06 §0A, §V; Ch10 §II |
| S-077 | Lời mùng một "ra đồn phía tây" | Ch06 §V (Ch06 §I.3) | — | Canon chưa đặt | Minor | Đã gieo | CANON_FACT | Ch06 §V |
| S-078 | Tù và ("lính gác say rồi") | Ch06 (Ch06 §I.7) | Ch07 §V ("Lặp lại có chủ ý") | Canon chưa đặt | Minor | Lặp lại có chủ ý | CANON_FACT | Ch06 §I.7; Ch07 §V |
| S-079 | "Cửa mở từ bên trong. Hai người khiêng then." (Dịch thấy, Ch7 S1; Ch07 §I.3: Dịch "không nghe được gì vì tiếng pháo") | Ch07 §V (Ch07 §I.2–5) | Ch07 §V (nhắc lại một lần ở S4); Ch11 §I.20–21 | Ch11 §V "Payoff một phần: nói ra với Chỉ" | Core | Payoff một phần | CANON_FACT | Ch07 §I.2–5, §V; Ch11 §I.20–21, §V |
| S-080 | "Không ai bắt. Nàng tự đi." (Dịch tận mắt thấy) | Ch07 §V (Ch07 §I.22–25) | Ch12 §V (nhãn "Chưa chạm") | Canon chưa đặt | Major | Chưa chạm (Ch12 §V); Ch13 §V không có dòng cập nhật; không cập nhật sau Ch12 | CANON_FACT | Ch07 §I.22–25, §V; Ch12 §V |
| S-081 | Thứ tự: ngừng đốt → thả dân → nàng đi | Ch07 §V (Ch07 §I.20–22) | — | Canon chưa đặt | Supporting | Đã gieo; Dịch chưa kết luận | CANON_FACT | Ch07 §V |
| S-082 | (lời đồn) Lời đồn A Quy không khớp nhau | Ch07 §V (Ch07 §II, §III) | — | Canon chưa đặt | Major | Đã gieo; Ch07 §III: Dịch "NHẬN RA: các lời kể về A Quy không khớp nhau. Chưa ai nói mình thấy tận mắt." | CANON_SUSPICION | Ch07 §III, §V |
| S-083 | Bọc vải của Phùng thúc | Ch07 §V (Ch07 §I.8) | — | Ch08 §V "Đã payoff (khóa trường mệnh)"; "Đóng tuyến 'nội dung bọc'"; Ch08 §I.15 | Supporting | Đóng ở Ch08 (Ch08 §I.15 chép nguyên: "Phùng Bảo mở bọc vải xám (Canon Ch7)"; [BÍ DANH CHƯA XÁC NHẬN Phùng thúc ↔ Phùng Bảo — xem RG-L-05 (= CB-L-01)]) | CANON_FACT | Ch07 §I.8, §V; Ch08 §I.15, §V |
| S-084 | Ba câu của Phùng thúc ("trong kinh", "lật sổ", "nhà cháy") | Ch07 §V (Ch07 §I.30) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch07 §V |
| S-085 | "Thẩm thư lại" mất tích/chết | Ch07 §V (Ch07 §I, mục P-09) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch07 §V |
| S-086 | Lính xét ở Nam Môn không hỏi tên | Ch07 §V (Ch07 §I.33) | — | Canon chưa đặt | Minor | Đã gieo | CANON_FACT | Ch07 §V |
| S-087 | "Vân Chương về Kim Lăng" (chuyển từ Ch7, P-13) | Ch07 §V | — | Ch08 §V "Đã payoff (tin trạm)"; Ch08 §I.6 | (không ghi) | Đã payoff ở Ch08 | CANON_FACT | Ch07 §V; Ch08 §I.6, §V |
| S-088 | Khóa trường mệnh: chứng xuất thân ≠ chứng danh tính; "Không có cách nào." | Ch08 §V (Ch08 §I.15–16, §I.21) | Ch09 §IV (khóa vẫn trong tay Dịch) | Canon chưa đặt (Ch09 §V không có dòng cho seed này) | Core | Đã gieo | CANON_FACT | Ch08 §I.15–16, §I.21, §V; Ch09 §IV |
| S-089a | Hai cây quế; cành gãy buộc dây gai vẫn ra hoa — phần gieo | Ch08 §V (Ch08 §I.23; §0 mục 1a) | — | Canon chưa đặt; hiện chỉ chứng Phùng Bảo từng ở cung Thẩm chiêu nghi (Ch08 §V) | Minor | Đã gieo | CANON_FACT | Ch08 §I.23, §V |
| S-089b | Hai cây quế — phần payoff | Ch08 §V | — | OPEN ("Nếu dùng lại, chỉ ở dạng hình ảnh; không biến thành bằng chứng danh tính" — Ch08 §V) | Minor | Payoff OPEN | CANON_UNKNOWN | Ch08 §V |
| S-090 | Ba người trong phòng kín; tin lọt | Ch08 §V (Ch08 §I.17, §I.33) | — | Ch09 §V "Đã payoff (Hàn tự nhận)"; Ch09 §I.19 (Hàn tự nhận nhắn ải Tây) | Major | Đã payoff (xem RG-L-09 về đường tin lọt) | CANON_FACT | Ch08 §I.17, §I.33, §V; Ch09 §I.19, §V |
| S-091a | Bất thường thương mại ải Tây; "Hàng đi qua ải?" — phần phủ thành | Ch08 §V (Ch08 §I.4) | Ch09 §I.10–17 (nhà Đỗ, hai cặp số, gian kho thứ chín, sổ trọ) | Ch09 §V "Đã payoff"; "Đóng phần phủ thành" | Major | Payoff phần phủ thành | CANON_FACT | Ch08 §I.4, §V; Ch09 §I.10–17, §V |
| S-091b | Bất thường thương mại ải Tây — phần ở ải | Ch08 §V | Ch09 §V | OPEN ("phần ở ải OPEN" — Ch09 §V) | Major | OPEN (xem OP-040b) | CANON_UNKNOWN | Ch08 §V; Ch09 §V |
| S-092a | Số khai của ải Tây (1.200 quân, 300 ngựa) — phần trên trang | Ch08 §V (Ch08 §II) | Ch09 §I.12–13 (1.200 suất lương; ký nhận và hồ sơ khác chỉ cho chừng 1.000 người; cỏ theo 500 ngựa, vật tư chuồng chỉ vừa chừng 300) | Ch09 §V "Đã payoff"; Đóng | Supporting | Đã payoff | CANON_FACT | Ch08 §II, §V; Ch09 §I.12–13, §V |
| S-092b | Số khai của ải Tây — số ký nhận "~1.000" (Ch09 §V) = "chừng 1.000 người" trên trang (Ch09 §I.12); con số xấp xỉ có trên trang, không phải suy ra | Ch09 §V | — | Ch09 §V: "1.200 suất / ~1.000 ký nhận; 300 ngựa thật" | Supporting | Đã payoff (xem S-092a) | CANON_FACT | Ch09 §I.12, §V |
| S-093a | Viên quản lương biết họ "Trình" — phần fact | Ch08 §V (Ch08 §I.5) | Ch09 §I.17, §I.20 (trọ nhà Đỗ; là mắt xích Hàn nhờ nhắn, không nói tên) | Ch09 §V "Payoff một phần (y là mắt xích; không nói tên)" | Supporting | Payoff một phần | CANON_FACT | Ch08 §I.5, §V; Ch09 §I.17, §I.20, §V |
| S-093b | Viên quản lương biết họ "Trình" — số phận y | Ch09 §II | Ch11 §IX (giữ OPEN) | OPEN (Ch09 §V, §II) | Supporting | OPEN (xem OP-045) | CANON_UNKNOWN | Ch09 §II, §V; Ch11 §IX |
| S-094a | (nghe thuật lại) Luồng tin phía tây về "tung tích Thất hoàng tử" — phần gieo (Ch08 §I.11: "Tô thuật lại"; Ch08 §III xếp vào "NGHE / THUẬT LẠI (không xác nhận)") | Ch08 §V (Ch08 §I.11) | Ch09 §II; Ch11 §IX; Ch12 §IX | Canon chưa đặt | Major | Đã gieo | CANON_SUSPICION | Ch08 §I.11, §III, §V |
| S-094b | Luồng tin phía tây — nguồn / thật-giả | Ch08 §III | Ch09 §II; Ch11 §IX; Ch12 §IX (giữ OPEN: nguồn luồng tin cũ "Thất hoàng tử") | OPEN (Ch09 §II) | Major | OPEN (xem OP-041) | CANON_UNKNOWN | Ch08 §III; Ch09 §II; Ch11 §IX; Ch12 §IX |
| S-095a | Sứ của Hạ Hầu ở ải Tây — phần fact | Ch08 §V (Ch08 §I.9) | Ch09 §I.20 (Hàn: sứ Hạ Hầu ở ải), §II | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch08 §I.9, §V; Ch09 §I.20 |
| S-095b | Sứ của Hạ Hầu ở ải Tây — liên hệ sứ Hạ Hầu – Bàng | Ch09 §II | Ch11 §IX | OPEN (Ch09 §II) | Supporting | OPEN (xem OP-044b) | CANON_UNKNOWN | Ch09 §II; Ch11 §IX |
| S-096 | Lời đồn sai "Tam Lang tử trận" | Ch08 §V (Ch08 §I.13) | Ch09 §I.32 (tin trạm: "Hoắc Tam Lang vẫn giữ Hắc Hà" = đính chính) | Ch10 §V "ĐÃ PAYOFF (Ch8 gieo → Ch9 đính chính → Ch10 sự thật)" | Supporting | Đã payoff | CANON_FACT | Ch08 §I.13, §V; Ch09 §I.32, §V; Ch10 §V |
| S-097 | Dịch nghe tên Tạ Vân Chương | Ch08 §V (Ch08 §I.7) | — | Canon chưa đặt (Ch12 §V không có dòng riêng; Ch12 §I.8 ghi Dịch và Vân Chương cùng có mặt tại đình) | Supporting | Canon chưa đặt payoff | CANON_FACT | Ch08 §I.7, §V; Ch12 §I.8 |
| S-098 | "Tại hạ" → "ta" | Ch08 §V (Ch08 §I.18) | Ch09 §0 (A-1: ba chỗ đổi "tại hạ" sang "ta"; "Ta" không đồng nghĩa với tự xưng Thất điện hạ) | Canon chưa đặt ("Theo dõi xưng hô của Dịch" — Ch08 §V) | Supporting | Đã gieo | CANON_FACT | Ch08 §I.18, §V; Ch09 §0 |
| S-099 | Quyền kho hành chính có giới hạn | Ch08 §V (Ch08 §I.25) | Ch09 §I.30 (quyền kiểm kê kho ba huyện); Ch12 §0B (CC-2: quyền điều phối vận lương, tuyến vận, đội hộ tống, đại diện có điều kiện) | Canon chưa ghi payoff; được mở rộng bằng Ch09 §I.30 và Ch12 §0B (CC-2) | Major | Đã mở rộng (Ch12 CC-2) | CANON_FACT | Ch08 §I.25, §V; Ch09 §I.30; Ch12 §0B |
| S-100 | Ôn nghiêng người (ambiguity) | Ch08 §V (Ch08 §I.34) | Ch09 §V ("Giữ nguyên ambiguity": Ôn lặp lại kiểu hành xử, không tự tay cầm thư); Ch09 §IV; Ch12 §0B | Canon chưa đặt (Ch09 §II: lý do Ôn nghiêng người là author-truth, không diễn giải) | Supporting | Giữ nguyên ambiguity; Ôn "chọn trì hoãn" (Ch09 §IV), "đặt cược có điều kiện" (Ch12 CC-2) | CANON_FACT | Ch08 §I.34, §V; Ch09 §II, §IV, §V; Ch12 §0B |
| S-101 | Phong thư chưa mở | Ch08 §V (Ch08 §I.35) | — | Ch09 §V "Đã payoff": Dịch mở, đọc to (Ch09 §I.3) | Hook | Đã payoff | CANON_FACT | Ch08 §I.35, §V; Ch09 §I.3, §V |
| S-102 | Dịch không biết Tam Lang là nữ | Ch12 §V (Canon Update ghi nguồn gieo "Gate Ch8") | — | Ch12 §V "Payoff" | Major | Đã payoff | CANON_FACT | Ch12 §0C, §V |
| S-103 | U — Dịch biết gì về Uyển | Ch12 §V (Canon Update ghi nguồn gieo "Gate Ch8") | — | Ch12 §V "Payoff một phần (thấy mức ảnh hưởng)" | Major | Payoff một phần | CANON_FACT | Ch12 §V |
| S-104 | "Hoắc Tam Lang vẫn giữ Hắc Hà." (hook Ch9) | Ch09 §V (Ch09 §I.32) | — | Canon Update không có dòng payoff riêng; Ch10 §V xử lý qua dòng "Lời đồn 'Tam Lang tử trận'" = ĐÃ PAYOFF (xem GHI CHÚ ĐỘ TIN CẬY) | Hook | Đã dẫn tới Ch10 (qua dòng lời đồn) | CANON_FACT | Ch09 §I.32, §V; Ch10 §V |
| S-105 | Hàn: đồng minh quân sự rạn; "Chưa." | Ch09 §V (Ch09 §I.28) | Ch09 §VI (Dịch ↔ Hàn hai chiều ACTIVE) | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch09 §I.28, §V, §VI |
| S-106 | "Không ai ăn được huyết thống." | Ch09 §V (Ch09 §I.27) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch09 §I.27, §V |
| S-107 | Người thật ở ải Tây được cấp đủ lương | Ch09 §V (Ch09 §I.26) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch09 §I.26, §V |
| S-108 | Hai câu mồi trong thư | Ch09 §V (Ch09 §I.3, §II) | Ch09 §I.7 (Phùng Bảo: "Có người ấy thật, thì họ đã viết tên người ấy ra.") | Canon chưa đặt | Supporting | Đã gieo; (người đoán: Dịch; Phùng Bảo) trên trang chỉ là điều Dịch và Phùng Bảo đoán | CANON_SUSPICION | Ch09 §I.3, §I.7, §II, §V |
| S-109 | Thư Bàng / hồi âm chỉ lương gửi Bàng ("Bàng không nhận hồi âm" → "Bàng nghĩ bằng lương" → "Hồi âm Bàng chưa đáp") | Ch09 §V (Ch09 §I.29); Ch15 §I.30, §V | Ch16 §I.22–24, §I.27, §V (hồi âm chỉ lương gửi ngày 14; toàn văn đọc công khai ở Ch16 §I.23); Ch17 §I.2, §V (đội trưởng báo "chỉ nói lương"; "Chưa đáp") | Ch15 §V "Payoff một phần"; Ch16 §V "Payoff một phần (gửi)"; Ch19 §V "Đã đáp bằng thư lương Ch19" | Major | Đã đáp (Ch19 §V) | CANON_FACT | Ch09 §I.29, §V; Ch15 §I.30, §V; Ch16 §I.22–24, §I.27, §V; Ch17 §I.2, §V; Ch19 §V |
| S-110a | Tiết tướng quân (cùng Hàn đi lính từ mười sáu tuổi) — phần fact | Ch09 §V (Ch09 §I.20) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch09 §I.20, §V |
| S-110b | Tiết tướng quân — phản ứng của Tiết | Ch09 §II | Ch11 §IX (giữ OPEN); Ch19 §IX; Ch22 §II-A | OPEN (Ch09 §II) | Supporting | OPEN (xem OP-045, OP-108) | CANON_UNKNOWN | Ch09 §II; Ch11 §IX; Ch19 §IX; Ch22 §II-A |
| S-111 | Quyền kiểm kê ba huyện | Ch09 §V (Ch09 §I.30) | Ch12 §0B (CC-2) | Canon chưa đặt | Supporting | Đã gieo; mở rộng bởi CC-2 | CANON_FACT | Ch09 §I.30, §V; Ch12 §0B |
| S-112 | Hạ Hầu đọc thói quen hậu cần qua giao dịch lâu năm (Hàn xác nhận fact giao dịch) | Ch09 → Ch15 → Ch16 §I.2, §I.4, §V | — | Ch16 §V "Payoff một phần (fact giao dịch)" | Core | Payoff một phần; "có rò tin hay không" xem OP-086 | CANON_FACT | Ch16 §I.2, §I.4, §V |
| S-113a | Tờ nhất thư Bàng / "Việc kia" (Thứ sử đã xem) — phần fact | Ch09 → Ch16 §I.22, §V; Ch19 §V | Ch19 §I.5 ("Tờ thứ nhất, ta vẫn chờ"); Ch16 §II (GR16-15: không giải thích thêm) | Canon chưa đặt riêng | Supporting (Ch16 §V); Major (Ch19 §V) | Chưa đáp (Ch19 §V) | CANON_FACT | Ch16 §I.22, §II, §V; Ch19 §I.5, §V |
| S-113b | Tờ nhất thư Bàng / "Việc kia" — payoff | Ch16 §V | Ch22 §II-A | OPEN (Ch16 §V ô Payoff) | Supporting | Giữ OPEN (Ch22 §II-A; xem OP-092) | CANON_UNKNOWN | Ch16 §V; Ch22 §II-A |
| S-114 | Quân cờ trắng của Khả đôn trên mép bàn | Ch10 §V (Ch10 §I.38–40) | Ch12 §II (quân cờ trắng không xuất hiện trong Ch12) | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch10 §I.38–40, §V; Ch12 §II |
| S-115 | Quan hệ Chiêu–Uyển (qua trung gian) | Ch10 §V | Ch12 §I.26–27 (Uyển rót nước cho Tam Lang trước; ngồi sát; ngựa hồng) | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch10 §V; Ch12 §I.26–27 |
| S-116 | Thư Chu Hạc: lời khuyên từ phía sau, số liệu đúng | Ch10 §V (Ch10 §I.22) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch10 §I.22, §V |
| S-117 | Bắc Nhung chia phe | Ch10 §V | Ch12 §I.24 ("Ta không nói thay Hách Liên. Ta không nói thay cả Bắc Nhung."), §IV | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch10 §V; Ch12 §I.24, §IV |
| S-118 | Khương lão tướng muốn lui; tướng trẻ muốn đánh; rạn nội bộ | Ch10 §V (Ch10 §I.21, §I.35–37) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch10 §I.21, §I.35–37, §V |
| S-119 | Mũ trụ lông đen được trả lại (gãy lông, vết lõm) | Ch06 → Ch10 §V | Ch17 §I.10, §I.20 (xem S-125) | Canon chưa đặt | Supporting | "Đang tăng cường" (Ch10 §V) | CANON_FACT | Ch10 §V |
| S-120 | Đoàn buôn da đi từ trưa | Ch10 §V (Ch10 §I.18) | — | Ch10 §V "Payoff chéo với Ch8" — Đóng | Minor | Đã payoff | CANON_FACT | Ch10 §I.18, §V |
| S-121 | Hách Liên Chước có cớ, tập hợp quân | Ch10 → Ch18 §I.26, §V | — | Canon chưa đặt | Core | Đã gieo (hook) | CANON_FACT | Ch18 §I.26, §V |
| S-122 | Luật mùa cỏ, giếng, chợ biên | Ch10 → Ch18 §I.6, §I.10, §V | — | Ch18 §V "Payoff một phần" | Major | Payoff một phần; luật còn hiệu lực, giếng có bàn đăng sổ (Ch18 §IV) | CANON_FACT | Ch18 §I.6, §I.10, §IV, §V |
| S-123 | "Khả đôn nói thay người Hán" (mũ, quân cờ trắng) | Ch10 → Ch18 §I.17, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch18 §I.17, §V |
| S-124 | Ông già sứ ngồi ngoài vòng lửa | Ch10 → Ch18 §I.22, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch18 §I.22, §V |
| S-125 | Chiêu làm mồi bằng mũ trụ | Ch10 → Ch17 §I.10, §I.20, §V | Ch17 §I.22 (trinh sát Hạ Hầu nhìn chùm lông đen), §I.26 (họ nhắm vào chùm lông) | Ch17 §V "Payoff" | Core | Payoff (Ch17) | CANON_FACT | Ch17 §I.10, §I.20, §I.22, §I.26, §V |
| S-126 | Câu khóa "hai người… chỉ có một" (Dạ Kiêu nói: người khiêng then cửa Bắc có hai người, ngươi chỉ có một) | Ch11 §V (Ch11 §I.21) | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch11 §I.21, §V |
| S-127 | Kết luận "một người" của Dạ Kiêu sụp | Ch11 §V (Ch11 §III) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch11 §III, §V |
| S-128 | "Ta không thấy mặt." (Dịch dừng ở một dữ kiện) | Ch11 §V (Ch11 §I.23) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch11 §I.23, §V |
| S-129a | Không có tiếng gọi lính — hiện tượng | Ch11 §V (Ch11 §I.17) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch11 §I.17, §V |
| S-129b | Không có tiếng gọi lính — động cơ để trống | Ch11 §II | Ch12 §II (còn nhắc "vì sao Dịch không gọi lính") | OPEN (Ch11 §V "động cơ: OPEN") | Major | OPEN; Ch13 không nhắc lại (xem OP-056) | CANON_UNKNOWN | Ch11 §II, §V; Ch12 §II |
| S-130 | Bạc khuôn vảy cá; tiền bị trả | Ch11 §V (Ch11 §I.5, §I.26) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch11 §I.5, §I.26, §V |
| S-131 | "Sẽ có người khác tới" | Ch11 §V (Ch11 §I.24) | — | Canon chưa đặt; Canon Update Ch12–13 không có dòng cập nhật | Supporting | Đã gieo | CANON_FACT | Ch11 §I.24, §V |
| S-132a | Chỉ phá nguyên tắc 2, 3 với đơn này — phần fact | Ch11 §V (Ch11 §0C) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch11 §0C, §V |
| S-132b | Chỉ phá nguyên tắc 2, 3 với đơn này — payoff | Ch11 §V | — | OPEN ("Payoff cụ thể: OPEN, cần Gate" — Ch11 §V) | Supporting | Payoff OPEN | CANON_UNKNOWN | Ch11 §V |
| S-133a | Người dò tin bị bắt — phần fact | Ch11 §V (Ch11 §I.10) | Ch13 §IX | Canon chưa đặt | Minor | Treo (Ch11 §V) | CANON_FACT | Ch11 §I.10, §V |
| S-133b | Người dò tin bị bắt — số phận | Ch11 §II, §V | Ch13 §IX (giữ OPEN) | OPEN ("Treo" — Ch11 §V) | Minor | OPEN (xem OP-059) | CANON_UNKNOWN | Ch11 §II, §V; Ch13 §IX |
| S-134 | Sổ trực gác (một hướng trong nhiều hướng) | Ch01 → Ch11 §V (Ch11 §I.29) | — | Canon chưa đặt | Major | Chỉ là gợi ý, không phải đích (Ch11 §V) | CANON_FACT | Ch11 §I.29, §V |
| S-135 | Hook "Ai đã có mặt ở Bắc Môn đêm ấy?" | Ch11 §V (Ch11 §I.30) | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch11 §I.30, §V |
| S-136 | Thỏa thuận thăm dò Lạc Thủy (qua mùa đông, không văn thư) | Ch12 §V (Ch12 §I.24–25) | Ch13 §I.1–5 (Dịch đưa lương mẫu; Chiêu ký tờ kê), §IV (tuyến lương Ích Châu → Hoắc quân đã ký) | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch12 §I.24–25, §V; Ch13 §I.1–5, §IV |
| S-137 | "Người hứa là Hoắc Chiêu." | Ch12 §V (Ch12 §I.29) | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch12 §I.29, §V |
| S-138 | Thư gửi Ôn giữ chữ "Hoắc quân" | Ch12 §V (Ch12 §I.32) | Ch13 §I.6 (Chiêu hỏi thư ghi thế nào — "Hoắc quân.") | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch12 §I.32, §V; Ch13 §I.6 |
| S-139 | "Hết cuộc gặp này." | Ch12 §V (Ch12 §I.19) | Ch13 §I.10 (Chiêu: "Lệnh bắt sống ngươi vẫn còn" / "Mùa đông này, Hoắc quân không truy…") | Canon chưa đặt | Major | Đã gieo; Ch13 ghi: lệnh bắt còn, treo qua mùa đông (Ch13 §IV) | CANON_FACT | Ch12 §I.19, §V; Ch13 §I.10, §IV |
| S-140 | A Quy nói lời của Dạ Kiêu; lý do thật không nói | Ch12 §V (Ch12 §I.13–15) | Ch13 §I.11 (A Quy "mở miệng như định nói thêm, rồi không nói") | Canon chưa đặt (lý do thật là author-truth, không lên trang — Ch12 §II; xem D3) | Major | Đã gieo | CANON_FACT | Ch12 §I.13–15, §II, §V; Ch13 §I.11 |
| S-141 | Người lạ đếm thuyền (không phe) | Ch12 §V (Ch12 §I.14) | Ch13 §I.20–23 (Chỉ: ba mắt xích; tin giả); Ch13 §III | Canon Update Ch13 §V không gắn nhãn "payoff" cho dòng này | Major | Chỉ biết đầu dây phía Hạ Hầu (Knowledge Matrix Ch13 §III, nhãn FACT, "theo Chỉ") | CANON_FACT | Ch12 §I.14, §V; Ch13 §I.20–23, §III |
| S-142 | "Kim Lăng chưa công nhận ai." / Kim Lăng "đợi thấy việc" | Ch12 §V (Ch12 §I.24); Ch12 → Ch15 §I.7 (theo Ch15 §V) | Ch13 §I.30 (thư Vân Chương: "Kim Lăng chưa công nhận ai. Người ở Ích Châu vẫn là người tự nhận."); Ch16 §I.13 (thuyền chở lương, ghi sổ); Ch17 §IV (thuyền chở bộ lần đầu; "chưa công nhận ai") | Canon chưa đặt (chuỗi sau: xem S-204 "chiếu nêu sứ Ích Châu") | Major | Chưa công nhận ai (Ch17 §IV) | CANON_FACT | Ch12 §I.24, §V; Ch13 §I.30; Ch15 §I.7, §V; Ch16 §I.13, §IV; Ch17 §IV |
| S-143 | Uyển vắng Bắc cảnh | Ch12 §IV; Ch12 §V (Canon Update ghi nguồn gieo "Gate R3") | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch12 §IV, §V |
| S-144 | Mức ảnh hưởng của Uyển (Dịch thấy một phần) | Ch12 §V (Ch12 §I.9) | Ch13 §I.16 ("Giữ được những người theo ta.") | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch12 §I.9, §V; Ch13 §I.16 |
| S-145 | Uyển bị cô lập (trướng quân + kỵ các bộ theo nàng) | Ch12 → Ch18 §I.21, §IV, §V | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch18 §I.21, §IV, §V |
| S-146 | Lời hứa mùa đông của Khả đôn hết khi băng tan | Ch12 → Ch15 §I.7 (theo Ch15 §V) | Ch16 §0 (không nhắc thành lời), §II; Ch17 §IX; Ch18 §I.1 (băng Hắc Hà tan hẳn) | Canon chưa đặt (Canon Update Ch18 không ghi payoff cho seed này) | Major | Đã gieo | CANON_FACT | Ch15 §I.7, §V; Ch16 §II; Ch18 §I.1 |
| S-147 | Dịch hiểu Ch12 ("mỗi bên đứng một mình") | Ch12 → Ch15 (theo Ch15 §V; Ch15 §0: không nhắc lại câu ấy) | — | Ch15 §V "Payoff ngầm" | Major | Payoff ngầm | CANON_FACT | Ch15 §0, §V |
| S-148 | Hoắc quân rút nửa, hạn ba tuần; Hạn Chiêu (hết trận, tối đa ngày 42) | Ch12 → Ch15 → Ch16 §I.12, §V | Ch17 §I.11 ("Hạn ngày 31 bỏ"), §V; Ch18 §VII (ghi chú: không nối số ngày với tuyến Dĩnh Xuyên) | Canon chưa đặt cho nửa kỵ nhẹ còn lại sau trận | Major | Đã gieo; hạn mới tối đa ngày 42 (Ch17 §V); Ch18 không nối số ngày; xem RG-L-10 | CANON_FACT | Ch16 §I.12, §V; Ch17 §I.11, §V; Ch18 §VII |
| S-149 | Ôn đóng ấn có mức tối đa → món nợ muối vượt trần Ôn; "ấn tới sau" | Ch12 → Ch16 §I.31, §V | Ch17 §IX (nợ muối; chưa biết thêm chi phí Dĩnh Xuyên); Ch19 §I.9, §I.13, §V; Ch22 §IX | Canon chưa đặt | Major | Đã gieo; nợ muối vượt trần ACTIVE (Ch22 §VI); xem RG-L-11 (= CB-L-26) về "Ấn Thứ sử" — Ôn ↔ Thứ sử chưa xác nhận đồng nhất | CANON_FACT | Ch16 §I.31, §V; Ch17 §V, §IX; Ch19 §I.9, §I.13, §V; Ch22 §IX |
| S-150 | Kim Lăng ghi "chở lương đường sông cho liên quân" | Ch12 → Ch16 §I.13, §V | Ch17 §V (bảy chuyến → chở bộ) | Canon chưa đặt riêng | Supporting | Đã gieo | CANON_FACT | Ch16 §I.13, §V; Ch17 §V |
| S-151 | Bảy chuyến thuyền đỏ chở lương → chở bộ (chỗ đọc sai duy nhất) | Ch12 → Ch16 → Ch17 §I.6, §I.34, §V | — | Ch17 §V "Payoff" | Core | Payoff (Ch17) | CANON_FACT | Ch17 §I.6, §I.34, §V |
| S-152 | "Không văn thư" → rò tin bên trong | Ch13 §V (Ch13 §I.21–23) | Ch14 §V ("T5 xác nhận có lỗ trên tuyến"); Ch15 §0 (không nối) | Ch14 §V "Payoff một phần (T5 xác nhận có lỗ trên tuyến)" | Core | Payoff một phần; Ch15–Ch18 không mở rộng | CANON_FACT | Ch13 §I.21–23, §V; Ch14 §V; Ch15 §0 |
| S-153 | Đường dây quán nước → người bán củi → Lạc Kinh | Ch13 §V (Ch13 §I.20) | Ch14 §V ("Giữ"; chưa chạm trong Ch14) | Canon chưa đặt | Major | Giữ | CANON_FACT | Ch13 §I.20, §V; Ch14 §V |
| S-154 | Hai con ngựa về Kim Lăng | Ch13 §V (Ch13 §I.28, §I.33) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch13 §I.28, §I.33, §V |
| S-155 | "Người tự nhận" trong thư Vân Chương | Ch13 §V (Ch13 §I.30) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch13 §I.30, §V |
| S-156a | Viên quan Kim Lăng gửi không hỏi (K2) — phần fact | Ch12 → Ch13 §V (Ch13 §I.28–29) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch13 §I.28–29, §V |
| S-156b | Viên quan Kim Lăng gửi không hỏi (K2) — gửi cho ai | Ch13 §II | Ch19 §IX; Ch22 §II-A (K2 giữ OPEN) | OPEN (Ch13 §V, §II) | Major | OPEN (xem OP-071) | CANON_UNKNOWN | Ch13 §II, §V; Ch19 §IX; Ch22 §II-A |
| S-157a | Lệnh bắt A Quy (hạn "qua mùa đông") → "Lệnh còn." — phần fact | Ch13 §V (Ch13 §I.10, §IV); Ch14 §IV (Còn; hoãn qua mùa đông) | Ch15 §V; Ch17 §I.1 ("Lệnh còn."), §V ("Nhắc, không giải") | Canon chưa đặt hành động | Major | "Lệnh còn." — không hành động (Ch17 §V) | CANON_FACT | Ch13 §I.10, §IV, §V; Ch14 §IV; Ch15 §V; Ch17 §I.1, §IV, §V |
| S-157b | Lệnh bắt A Quy — A Quy ở đâu / Chiêu làm gì khi gặp | Ch15 §II | Ch16 §II; Ch17 §II (toàn bộ, không nối Dĩnh Xuyên); Ch19 §IX; Ch22 §II-A | OPEN (Ch15 §V; Ch16 §II) | Major | OPEN; giữ OPEN ở Ch22 (xem OP-089) | CANON_UNKNOWN | Ch15 §II, §V; Ch16 §II; Ch17 §II; Ch19 §IX; Ch22 §II-A |
| S-158 | "Đêm ấy…" (Dịch không nói tiếp) | Ch13 §V (Ch13 §I.7) | Ch15 §VI ("Đêm ấy…" chưa nói) | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch13 §I.7, §V; Ch15 §VI |
| S-159 | Câu Vân Chương không hỏi Uyển | Ch13 §V (Ch13 §I.18) | Ch18 §II; Ch20 §II; Ch22 §IX | Canon chưa đặt | Major | Đã gieo; giữ OPEN ở Ch22 (xem OP-107) | CANON_FACT | Ch13 §I.18, §V |
| S-160 | Dạ Kiêu báo cho không bốn bên | Ch13 §V (Ch13 §I.25) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch13 §I.25, §V |
| S-161 | Chapter Bible Ch13 hook: tin giả + người phản ứng ngay (nhãn do Canon Update gán) | Ch13 §V | — | Ch13 §V "Payoff" — "Đóng (chức năng hook)" | Core | Đã payoff | CANON_FACT | Ch13 §V |
| S-162a | New info: Vân Chương có thể phải phản bội Dịch — phần fact | Ch13 §V | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch13 §V |
| S-162b | New info: Vân Chương có thể phải phản bội Dịch — "chưa quyết" | Ch13 §V | Ch20 §II; Ch21 §II-A | "Đã gieo (chưa quyết)" (Ch13 §V) | Core | Chưa quyết (theo Ch13 §V; xem OP-066b) | CANON_UNKNOWN | Ch13 §V |
| S-163 | Nợ lương của Dịch với Hoắc quân (hai xe, sổ hội minh) | Ch13 → Ch15 §I.27, §V | Ch16 §V ("Tăng": nuôi kỵ nhẹ ba tuần), §VI; Ch17 §VI (nợ lương + đã kéo nàng làm mồi) | Canon chưa đặt | Major | ACTIVE, tăng (Ch17 §VI; xem mục C) | CANON_FACT | Ch15 §I.27, §V; Ch16 §V, §VI; Ch17 §VI |
| S-164 | Mua lương dân bằng muối/vải/phiếu | Ch13 → Ch16 §I.15–17, §V | Ch17 §V ("Đã gieo") | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch16 §I.15–17, §V; Ch17 §V |
| S-165 | Muối trả ngay làm nền cho Danh | Ch13 → Ch16 → Ch19 (theo Ch19 §V) | — | Ch19 §V "Payoff Ch19" (làng trưởng "Tôi ăn rồi.", Ch19 §I.15) | Major | Payoff (Ch19) | CANON_FACT | Ch19 §I.15, §V |
| S-166 | Kha Trọng (sổ Nam Môn cũ ↔ sổ thuê ngựa hiện tại) | Ch14 §V (Ch14 §I.8, §I.23–24) | Ch15 §0 (không có "Kha"); Ch16 §II, §IX; Ch17 §II, §IX; Ch18 §II, §IX (không chạm) | Canon chưa đặt | Core | Đã gieo (G-2): Chỉ ra lệnh tìm, không bắt, không lại gần (Ch14 §I.28); Ch15–Ch18 không chạm; xem OP-077 | CANON_FACT | Ch14 §I.8, §I.23–24, §I.28, §V |
| S-167 | (lời đồn) Lời đồn lão Kha / phủ lớn họ Tạ (Ch14 §I.26: "ba tầng miệng") | Ch14 §V (Ch14 §I.26–27) | — (Canon Update Ch15–18 không nhắc riêng) | Canon chưa đặt | Core | Đã gieo, chưa xác nhận (Ch14 §V) | CANON_SUSPICION | Ch14 §I.26–27, §V |
| S-168 | Đường văn thư – trạm ngựa Kim Lăng có lỗ (G-1) → "Đường trạm hở dùng có chủ ý" | Ch14 §V (Ch14 §I.18); Ch14 → Ch20 §V | Ch15 §0 (K-2: không nối "văn thư", "trạm ngựa", "Dạ Kiêu", "Kha"); Ch16 §0; Ch17 §0; Ch18 §II; Ch21 §V (lệnh lương T2 đi trạm) | Canon chưa đặt | Core (Ch14 §V); Major (Ch20 §V) | Đã gieo; Dịch không biết lỗ văn thư (Ch15 §III); đường trạm hở được dùng (Ch21 §V); nguồn rò xem OP-076 | CANON_FACT | Ch14 §I.18, §V; Ch15 §III; Ch20 §V; Ch21 §V |
| S-169 | Hoắc quân chờ lời đáp của Chỉ | Ch14 §V (Ch14 §I.21; Ch14 §IV) | — | Canon chưa đặt (Chỉ vắng Ch15–Ch18) | Major | Đã gieo (chưa trả) | CANON_FACT | Ch14 §I.21, §IV, §V |
| S-170 | Vân Chương nhận hai chỗ hẹn | Ch14 §V (Ch14 §I.20) | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch14 §I.20, §V |
| S-171 | Hai người lạ ở miếu / trạm Thạch Kiều | Ch14 §V (Ch14 §I.14, §I.22–23) | Ch15 §0 (không chữ nào nối Ch14 với Hổ Lao) | Canon chưa đặt | Major | Đã gieo; danh tính xem OP-078 | CANON_FACT | Ch14 §I.14, §I.22–23, §V |
| S-172 | Cơ chế "năm điểm hẹn" (kiểm đường truyền) | Ch14 §V (Ch14 §I.2) | — | Ch14 §V "Dùng xong" | Supporting | Dùng xong | CANON_FACT | Ch14 §I.2, §V |
| S-173 | Câu "Kênh này mới dựng ba hôm" | Ch14 §V (Ch14 §I.4) | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch14 §I.4, §V |
| S-174 | Chapter Bible Ch14 hook: "Một cái tên từ mười năm trước xuất hiện" (nhãn do Canon Update gán) | Ch14 §V | Ch14 §I.24 (hai tờ giấy cạnh nhau) | Ch14 §V "Payoff (Kha Trọng)"; ô Payoff ghi "Mở rộng" | Core | Payoff (chức năng hook); thread Kha Trọng xem S-166 | CANON_FACT | Ch14 §I.24, §V |
| S-175 | Hạ Hầu đánh đường, không đánh thành | Ch15 §V (Ch15 §I.16; mục Nguyên tắc ghi) | Ch16 §I.8, §I.30 (Hạ Hầu thêm quân, thêm người giữ tuyến cỏ); Ch17 §V (xem S-190) | Canon chưa đặt riêng | Core | Đã gieo | CANON_FACT | Ch15 §I.16, §V; Ch16 §I.8, §I.30; Ch17 §V |
| S-176 | Dịch cần đổi cách đánh (tờ giấy trắng) | Ch15 §I.35, §V | Ch16 §I.1, §I.28 (tờ giấy vẫn trắng) | Ch16 §V "Đóng; hành động tiếp ở Ch17"; Ch16 §I.33 (đường than tới "Dĩnh Xuyên") | Core | Đóng (Ch16 §V) | CANON_FACT | Ch15 §I.35, §V; Ch16 §I.1, §I.28, §I.33, §V |
| S-177 | "Người trước, lương sau" | Ch15 §I.17, §V | — (Ch16–Ch18 Canon Update không nhắc riêng) | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch15 §I.17, §V |
| S-178 | Nghi "ai biết cột đi hướng nào" / "nhà buôn tin" (nghi "ai báo tin") | Ch15 §I.31, §V | Ch16 §I.10 (phó tướng Hoắc: "kẻ báo tin"; Dịch: "Có hay không, đường lương cũng phải đổi"), §V; Ch17 §V ("Không đụng ở Ch17") | Canon chưa đặt | Major | Đã gieo; không đụng ở Ch17. Người nghi: phó tướng Hoắc quân (Ch15 §III: Nghi "ai biết cột đi hướng nào"; nghi "nhà buôn tin"); Ch16 §IV: hội minh còn nghi "ai báo tin", chưa giải | CANON_SUSPICION | Ch15 §I.31, §III, §V; Ch16 §I.10, §IV, §V; Ch17 §V |
| S-179 | Hàn bị thương | Ch15 §I.19, §V | Ch16 §I.28 (vai đỡ nhưng băng chưa tháo); Ch17 §I.13 (vai chưa nâng nổi cung) | Canon chưa đặt | Supporting | Vai còn băng (Ch17 §IV) | CANON_FACT | Ch15 §I.19, §V; Ch16 §I.28; Ch17 §I.13, §IV |
| S-180 | Nghi binh không ai đuổi | Ch15 §I.23, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch15 §I.23, §V |
| S-181 | Hai bến / vòng chỉ chạm cả hai bến | Ch15 §I.32–33, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch15 §I.32–33, §V |
| S-182 | Chapter Bible Ch15 hook: "Dịch nhìn bản đồ và nhận ra mình đã đánh nhầm thứ" (nhãn do Canon Update gán) | Ch15 §I.34 | — | Ch15 §V "Đóng (chức năng hook)" | Core | Đóng | CANON_FACT | Ch15 §I.34, §V |
| S-183 | Sĩ quan Ích Châu xin về (chi phí nhân lực) | Ch15 → Ch16 §I.26, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch16 §I.26, §V; Ch16 §0 (GR16-17) |
| S-184 | "Có hay không, đường lương cũng phải đổi" | Ch15 → Ch16 §I.10, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch16 §I.10, §V |
| S-185 | Lão phu đầu (cắt dây) hiện diện | Ch15 §I.17 → Ch16 §I.14, §V | — | Ch16 §V "Không cần payoff" | Supporting | Đã gieo | CANON_FACT | Ch16 §I.14, §V |
| S-186 | Dĩnh Xuyên (tên + đường lương tới đó; chợ cũ của làng) | Ch16 §I.20, §I.33, §V | Ch17 §I.3–4 (Dịch mang cuộn giấy; kế hoạch) | Ch17 §V "Payoff (vị trí/chức năng)" | Core | Payoff vị trí/chức năng; "vì sao Dịch chắc họ sẽ cứu" xem OP-096b | CANON_FACT | Ch16 §I.20, §I.33, §V; Ch17 §I.3–4, §V |
| S-187 | Hạ Hầu cũng mua lương dân (một phần ba) → "mua lương dân → mua ngựa" (cùng mạch bạc) | Ch16 §I.18, §V; Ch16 → Ch18 §I.2, §V | Ch17 §V | Ch18 §V "Đóng một phần" | Major | Đã gieo (fact thuần); Ch18 đóng một phần (trên trang Ch18 không nêu "Hạ Hầu"/"Tây Lương" — Ch18 §0; xem RG-L-12) | CANON_FACT | Ch16 §I.18, §V; Ch17 §V; Ch18 §I.2, §0, §V |
| S-188 | Từ chối thắng nhỏ bằng số (200 người) | Ch16 §I.9, §V | — (Ch17 §V có dòng) | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch16 §I.9, §V; Ch17 §V |
| S-189 | Dịch nói "Không" / "Ta không biết"; im ở "vì sao họ sẽ cứu" | Ch17 §I.7–8, §V | — | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch17 §I.7–8, §II, §V |
| S-190 | Hạ Hầu chuyển từ chủ động sang phản ứng (đi đêm, đi gấp, hiệu muộn, hàng đứt) | Ch17 §I.24, §I.29, §I.34–35, §V | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch17 §I.24, §I.29, §I.34–35, §V |
| S-191 | Hàn nhận trách nhiệm gửi bộ | Ch16 → Ch17 §I.13, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch17 §I.13, §V |
| S-192 | Tháp hiệu (Chiêu thấy, tự quyết) | Ch17 §I.17–18, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch17 §I.17–18, §V |
| S-193 | Nén hương / ống hương (Tiểu Thất → Chiêu) | Ch17 §I.14, §I.30, §I.37, §V | — | Canon chưa đặt (Ch18 Canon Update không nhắc) | Supporting | Đã gieo | CANON_FACT | Ch17 §I.14, §I.30, §I.37, §V |
| S-194 | Nén bạc có dấu trong tay áo Uyển | Ch18 §I.2, §V | — | Canon chưa đặt | Supporting | Chưa dùng | CANON_FACT | Ch18 §I.2, §V |
| S-195 | Bộ nhỏ nhận nửa giá (oán) | Ch18 §I.19, §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch18 §I.19, §V |
| S-196 | "Ai mở cửa, không bị hỏi tội" | Ch19 §I.11, §V | Ch20 §I.5, §I.10 (chiếu); Ch22 §I.14, §0 (sĩ quan hô tờ "Hàng binh không giết, có ăn!"; quan cũ trích câu tờ) | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch19 §I.11, §V; Ch20 §I.5, §I.10; Ch22 §I.14, §0 |
| S-197 | Thư Bàng: "đo bằng xe", tự viết sổ mình chậm hơn lương | Ch09 → Ch16 → Ch19 (theo Ch19 §V) | Ch19 §I.7 | Ch19 §V "Payoff GR17-1" | Core | Bàng không lên trang ở Ch22 (Ch22 §IV); "Bàng đổi cách đo": Canon chưa đặt trên trang | CANON_FACT | Ch19 §I.7, §V; Ch22 §IV |
| S-198 | Lời hứa vượt quyền (ân xá làm trước) | Ch19 §V | Ch20 §V | Ch20 §V "Đã nhận (hợp thức hóa hậu quả)" | Major | Đã nhận (Ch20 §V) | CANON_FACT | Ch19 §V; Ch20 §V |
| S-199 | Hàng binh sống (Hàn / tờ văn) | Ch19 §V | — | Ch22 §V "PAYOFF Ch22" (hàng đông, hàng theo tờ văn; dập kho) | Supporting (Ch19 §V); Major (Ch22 §V) | PAYOFF Ch22 | CANON_FACT | Ch19 §V; Ch22 §V |
| S-200 | Chiêu không ký; kỵ nhẹ ngoài thành / Chiêu vắng; Dịch nợ Chiêu | Ch19 §V; Ch17–19 (theo Ch22 §V) | Ch22 §V (gò thấp phía đông trống) | Canon chưa đặt (xem OP-103) | Supporting | ACTIVE; Ch22 không là nguồn về Chiêu/Hoắc (Ch22 §0) | CANON_FACT | Ch19 §V; Ch22 §0, §V |
| S-201 | "Để hắn có một con số" | Ch16 → Ch19 §I.7 (theo Ch19 §V) | Ch19 §I.7 | Ch19 §V "Payoff Ch19" | Supporting | Ch21 §0: "Vân Chương gửi một lời — và lời ấy là thật" (xem RG-L-13) | CANON_FACT | Ch19 §I.7, §V; Ch21 §0 |
| S-202 | Tờ giấy dán trên cổng (Dĩnh Xuyên), chữ ký trong tay người khác | Ch19 §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch19 §V |
| S-203 | Ấu đế đặt tay lên ấn theo thủ tục | Ch20 §V (Ch20 §I.15) | — | Canon chưa đặt | Core | Đã gieo (Ch21–22 vắng — Ch21 §IV) | CANON_FACT | Ch20 §I.15, §V; Ch21 §IV |
| S-204 | Chiếu nêu "sứ Ích Châu Trình Dịch" (nhận việc, không nhận người) | Ch20 §V | Ch22 §V (chiếu lên trang; Dịch đọc tên mình, Ch22 §I.30) | Canon chưa đặt | Core | Chiếu lên trang (Ch22 §V) | CANON_FACT | Ch20 §V; Ch22 §I.30, §V |
| S-205 | Ấn tước phải có người chứng; Vân Chương không rời | Ch20 §V | Ch21 §IV (Vân Chương không rời) | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch20 §V; Ch21 §IV |
| S-206a | Thư xin hàng Hổ Lao — phần fact | Ch20 §V | Ch21 §I.2, §V (ba điều lên trang; thư đã đáp) | Ch21 §V "Đã đáp" | Core | Đã đáp (Ch21 §V) | CANON_FACT | Ch20 §V; Ch21 §I.2, §V |
| S-206b | Thư xin hàng Hổ Lao — thật/trá chưa rõ trên trang | Ch20 §II | Ch21 §II-A; Ch22 §II-A | OPEN (xem OP-113b) | Core | Chưa rõ trên trang (Ch21 §II-A, Ch22 §II-A) | CANON_UNKNOWN | Ch20 §II; Ch21 §II-A; Ch22 §II-A |
| S-207 | Hạn "kể từ ngày chiếu tới" (chỗ hở) | Ch20 §V | — | Canon chưa đặt (Ch21 §IX, Ch22 §IX không ghi payoff) | Major | Canon chưa đặt payoff | CANON_FACT | Ch20 §V; Ch21 §IX; Ch22 §IX |
| S-208a | Quan huyện đọc chiếu rồi bị xử ("hai dòng quan huyện bị đè dưới ống tre") — phần fact | Ch20 §V; Ch20 → Ch21 §V | Ch21 §V (hai dòng dưới ống tre, không nối nhân quả); Ch22 §I.29 (thư lại Hổ Lao giấu chiếu "từ ngày huyện bên bị treo") | Canon chưa đặt | Major (Ch20 §V); Supporting (Ch21 §V) | Giữ | CANON_FACT | Ch20 §V; Ch21 §V; Ch22 §I.29 |
| S-208b | Quan huyện đọc chiếu rồi bị xử — động cơ | Ch20 §II | Ch21 §II-A; Ch22 §II-A | OPEN (Ch21 §V; động cơ vẫn OPEN) | Major | OPEN (xem OP-114) | CANON_UNKNOWN | Ch20 §II, §V; Ch21 §II-A, §V; Ch22 §II-A |
| S-209 | Ông áo tía không hài lòng (ấn tước) | Ch20 §V | — | Canon chưa đặt | Major | Vắng ở Ch21 (Ch21 §IV); xem OP-116 | CANON_FACT | Ch20 §V; Ch21 §IV |
| S-210 | Hôn thư tướng râu quai nón – ngoại thích | Ch20 §V | — | Canon chưa đặt | Supporting | Đã gieo | CANON_FACT | Ch20 §V |
| S-211a | Thư riêng theo chức (tới tay ai) — phần gieo | Ch20 §V | — | Canon chưa đặt riêng | Supporting | Đã gieo (Ch20 §V: "không biết tới tay ai") | CANON_FACT | Ch20 §V |
| S-211b | Thư riêng theo chức — "thư riêng đã tới tay người giữ chức" (Vân Chương suy: Ch21 §III "INFERENCE (một mức)") ⚠ xem RG-L-28 (= CB-L-20) | Ch20 §V | Ch21 §V ("Xác nhận mức Hổ Lao") | CHƯA QUYẾT — Ch21 §V ghi "Xác nhận mức Hổ Lao"; cùng claim bị Ch21 §III xếp thêm vào INFERENCE; Registry không chọn bên | Supporting | Tranh chấp FACT / INFERENCE, ⚠ xem RG-L-28 | CANON_SUSPICION | Ch21 §III, §V |
| S-212 | Tờ xin ra tuyến trước trong ngăn kéo | Ch20 → Ch21 §V | Ch21 §I.21 (tay đặt lên ngăn kéo, không kéo) | Canon chưa đặt | Major | Giữ | CANON_FACT | Ch21 §I.21, §V |
| S-213 | Điều (2): nhận bằng chữ "binh không giao người ngoài", không nói liên quân | Ch21 §V | — | Canon chưa đặt | Core | Đã gieo (xem Ch22 §IX) | CANON_FACT | Ch21 §V; Ch22 §IX |
| S-214 | Thư đáp ngoài sổ, dấu riêng, không ai chứng | Ch21 §V | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch21 §V |
| S-215 | Lịch lương (ngày–lương–đường) + lời miệng "neo ngang sông" → Dịch tự đọc | Ch21 §V | Ch22 §I.2–4 | Ch22 §V "Lịch lương → Dịch tự đọc" (PAYOFF Ch22) | Core | PAYOFF Ch22 | CANON_FACT | Ch21 §V; Ch22 §I.2–4, §V |
| S-216 | Lương thật xuất kho (số suất gấp ba; sổ gạch nửa tháng) | Ch21 §V | — | Canon chưa đặt (Ch22 §V không có dòng riêng) | Major | Đã gieo | CANON_FACT | Ch21 §V |
| S-217 | "Một lời" vs "năm lời" (Vân Chương vs Chỉ) | Ch21 §V | — | Canon chưa đặt | Major | Đã gieo; xem OP-076 về G-1 | CANON_FACT | Ch21 §V |
| S-218 | "Nghỉ một đêm ở nhà trạm của quân" | Ch21 §V | — | Canon chưa đặt | Major | Đã gieo (dữ kiện, chưa nghĩa — Ch21 §V) | CANON_FACT | Ch21 §V |
| S-219 | Thuyền neo ngang sông; Hổ Lao dồn quân ra phía bến | Ch21 §V | — | Ch22 §V "PAYOFF Ch22" (Dịch thấy, không giải thích) | Core | PAYOFF Ch22 | CANON_FACT | Ch21 §V; Ch22 §V |
| S-220 | "Cổng thành mở." (hook Ch21) | Ch21 §V | — | Ch22 §V ghi payoff Ch22 (cổng bến mở, không ai hô) | Core | Hook (Ch21); Ch22 chỉ có cổng bến (Ch22 §0); xem RG-L-14 | CANON_FACT | Ch21 §V; Ch22 §0, §V |
| S-221 | Hạn "ba đêm" / thư đáp đúng hạn | Ch21 §V | — | Ch21 §V "Đã dùng" | Supporting | Đã dùng | CANON_FACT | Ch21 §V |
| S-222 | Lời hứa C1 / chiếu "xác nhận" | Ch19 → Ch20 (theo Ch22 §V) | Ch22 §V (chiếu lên trang) | Canon chưa đặt | Core | Chiếu lên trang | CANON_FACT | Ch22 §V |
| S-223 | Danh: "sứ Ích Châu" / "họ Tiêu" | Ch19 → Ch20 (theo Ch22 §V) | Ch22 §V (quan cũ hỏi "họ Tiêu?", Dịch không đáp; ký sổ kho) | Canon chưa đặt | Core | Đã gieo | CANON_FACT | Ch22 §V |
| S-224 | Phó tướng nhận công; sổ kho một bản cho Kim Lăng (có ký Dịch) | Ch22 §V | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch22 §V |
| S-225 | "Thuyền sao không vào bến?" — "Lương còn nguyên." | Ch22 §V | — | Canon chưa đặt | Major | Đã gieo (nghi không đáp) | CANON_FACT | Ch22 §V |
| S-226 | Cột bại quân + nhóm đi bờ phía tây (có kỵ che) | Ch22 §V | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch22 §V |
| S-227 | Ai "hợp lệ" cai trị Hổ Lao | Ch19 (tờ) → Ch22 §V | — | Canon chưa đặt | Major | Đã gieo (không ai đáp) | CANON_FACT | Ch22 §V |
| S-228 | Tướng giữ thành Hổ Lao "không thấy" | Ch22 §V | — | Canon chưa đặt | Major | Đã gieo; xem OP-125 | CANON_FACT | Ch22 §V |
| S-229 | "Quá mềm" (sĩ quan Ích Châu): để đi, cho cầm xô | Ch22 §V | — | Canon chưa đặt | Major | Đã gieo | CANON_FACT | Ch22 §V |
| S-230 | Hàn tự chọn; sổ người chết | Ch16–19 → Ch22 §V | — | Canon chưa đặt | Supporting | Giữ | CANON_FACT | Ch22 §V |
| S-231 | Thuyền Kim Lăng chở bộ ở Dĩnh Xuyên (Ch17) / "Ngoài lương?" | Ch17 → Ch21 → Ch22 §V | Ch22 §V (Dịch hỏi, không đáp) | Canon chưa đặt | Major | Dịch hỏi, không đáp | CANON_FACT | Ch22 §V |
| S-232 | Chiếu có ấn / Dịch chỉ có chữ ký | Ch20 → Ch22 §V | — | Canon chưa đặt | Core | Chiếu có ấn (đối lập "không ấn" của Dịch) | CANON_FACT | Ch22 §V |

**Trạng thái cuối Ch22 (tóm tắt mục A):** 250 dòng (232 ID seed; các ID có hậu tố a/b là một seed tách hai dòng). Đếm theo dòng (không theo ID), theo đầu ô cột "Payoff theo canon": 175 dòng "Canon chưa đặt" (hoặc "chưa gắn nhãn"), 17 dòng OPEN, 1 dòng CHƯA QUYẾT (S-211b, ⚠ RG-L-28), 57 dòng còn lại mở đầu bằng ghi nhận của Canon Update (đóng / payoff / payoff một phần / đã dùng / đã nhận / đã đáp…; trong đó S-104, S-141, S-162b ghi Canon Update không gắn nhãn payoff hoặc "Đã gieo (chưa quyết)"). 175 + 17 + 1 + 57 = 250. Đây là số đếm theo chữ trong ô, không phải đánh giá chất lượng payoff; từng seed xem cột "Trạng thái cuối Ch22".

---

## B. OPEN THREADS — TRẠNG THÁI CUỐI CH22

**Cách đọc.** Chỉ liệt kê trạng thái **trên trang** theo Canon Update (CANON_UNKNOWN = còn mở; CANON_FACT = đã đóng bởi chương nào). OPEN bị đóng một phần được tách `a` (phần đã đóng, CANON_FACT) / `b` (phần còn mở, CANON_UNKNOWN). **Author-truth / ràng buộc kế hoạch KHÔNG nằm ở đây** — cột "Author-truth đi kèm" chỉ trỏ sang mục D3 (PLANNING_NON_CANON). "Còn mở" = Canon Update các chương sau không ghi đóng; không suy diễn. OPEN chỉ theo điểm nhìn một nhân vật (Canon đã đưa câu trả lời lên trang ở chương/POV khác) vẫn ghi CANON_UNKNOWN nhưng nội dung ghi rõ phạm vi "OPEN với <ai> / trên trang POV <ai>; Canon đã có ở ChNN §…".

| ID | OPEN | Mở từ | Trạng thái cuối Ch22 (đóng bởi / cập nhật gần nhất) | Author-truth đi kèm | Source Type | Source |
|---|---|---|---|---|---|---|
| OP-001 | Ai đứng sau việc hụt lương; mục đích là gì | Ch01 §III | CÒN MỞ (Ch04 §III: Vân Chương cũng không biết "ai rút lương"); không cập nhật sau Ch07 | D3-04 | CANON_UNKNOWN | Ch01 §III; Ch04 §III |
| OP-002 | Việc hụt lương có liên hệ gì với Bắc Môn không | Ch01 §III | CÒN MỞ (Ch04 §VIII.1) | D3-04 | CANON_UNKNOWN | Ch01 §III; Ch04 §VIII.1 |
| OP-003 | Người mặc áo lính hỏi thăm Dịch thuộc phe nào; danh tính | Ch01 §III, §IV | CÒN MỞ (Ch03 §IV "Giữ mở") | — | CANON_UNKNOWN | Ch01 §III, §IV; Ch03 §IV |
| OP-004 | Lượng tồn thực tế trong kho | Ch01 §III, §VI | CÒN MỞ (Ch04 §I.16: Dịch xin số gạo đoàn nhận "để ước lượng"; Canon Update không ghi kết quả) | — | CANON_UNKNOWN | Ch01 §III, §VI; Ch04 §I.16 |
| OP-005 | Bao lương dây mới có gì bất thường không | Ch01 §III, §IV | CÒN MỞ | — | CANON_UNKNOWN | Ch01 §III, §IV |
| OP-006 | Ai nuôi Bùi Chỉ; ai dạy võ; Dạ Kiêu hình thành từ khi nào; ai trả tiền nuôi Chỉ những năm đầu; thư phòng Hoắc–Chỉ | Ch01 §IX (Ch10 §IX nhắc lại) | CÒN MỞ (nhắc lại: Ch02 §II; Ch03 §VIII; Ch10 §IX; Ch11 §II, §IX; Ch13 §IX; Ch15 §IX; Ch18 §IX) | D3-14 | CANON_UNKNOWN | Ch01 §IX; Ch02 §II; Ch03 §VIII; Ch10 §IX; Ch11 §II, §IX; Ch13 §IX; Ch15 §IX; Ch18 §IX |
| OP-007 | Người gia nhân năm ấy còn sống hay đã chết | Ch02 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch02 §II |
| OP-008 | Danh tính người đã kéo Chỉ ra khỏi chỗ nhìn trộm đêm phủ Bùi | Ch02 §II | CÒN MỞ (seed S-020) | — | CANON_UNKNOWN | Ch02 §II, §IV |
| OP-009 | Hoắc nhận ra Chỉ chính xác bằng cách nào (Canon chỉ ghi ông nhìn chỗ sau tai và im lặng lâu hơn thường) | Ch02 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch02 §II |
| OP-010 | Lý do Hoắc thức ở thư phòng đêm Ch2 (trên trang) | Ch02 §II | CÒN MỞ (truyện chưa nói) | D3-03 | CANON_UNKNOWN | Ch02 §II |
| OP-011 | Tin có thích khách vào phủ tướng quân có lan ra ngoài hay không (mặc định: tin không chính thức) | Ch02 §III | CÒN MỞ (Ch03 §III: Dịch "Không biết: A Quy là Bùi Chỉ, là thích khách") | — | CANON_UNKNOWN | Ch02 §III; Ch03 §III |
| OP-012 | Người giữ dao của Chỉ; ai nhặt dây móc sắt | Ch02 §VI ("chưa xác định", "chưa rõ ai nhặt") | ĐÃ ĐÓNG bởi Ch03 §VI: người giữ là Tam Lang | — | CANON_FACT | Ch02 §VI; Ch03 §VI |
| OP-013a | Logistics chu kỳ tiếp tế mùa đông — phần đã đóng | Ch03 §VIII | ĐÓNG MỘT PHẦN bởi Ch04 §I.17, §III: hàng/chuyến 11 đủ (Dịch thấy trên giấy) | — | CANON_FACT | Ch03 §VIII; Ch04 §I.17, §III |
| OP-013b | Logistics chu kỳ tiếp tế mùa đông — xe lương còn chạy không; nếu thiếu Dịch biết cách nào; vì sao Ch3 không nêu chuyến xe | Ch03 §VIII | CÒN MỞ (Canon Update không ghi đóng các câu hỏi còn lại) | — | CANON_UNKNOWN | Ch03 §VIII; Ch04 §I.17 |
| OP-014 | Kỵ binh Bắc Nhung đi đường Hắc Hà đóng băng tới Bắc Môn: quân số, thời gian hành quân, điểm tập kết; phe Bắc Nhung và quân số ("OPEN, bắt buộc chốt") | Ch04 §VIII.4; Ch05 §II, §VIII.1 | CÒN MỞ (Ch06, Ch07 Canon Update không ghi) | — | CANON_UNKNOWN | Ch04 §VIII.4; Ch05 §II, §VIII.1 |
| OP-015a | Nội dung thư Tạ Diên và phương pháp đọc — phần đã đóng | Ch04 §II, §VIII.2 | ĐÃ ĐÓNG (nội dung/phương pháp) bởi Ch05 §I.1–5: mười chữ giải được (xem RG-L-15) | — | CANON_FACT | Ch04 §II, §VIII.2; Ch05 §I.1–5 |
| OP-015b | Tạ Diên có tìm Dịch hay không; thư có nhắc tìm Dịch không | Ch04 §VIII.3 | CÒN MỞ (Ch05 §III: Vân Chương không biết Tạ Diên có tìm Dịch hay không) | D3-26 | CANON_UNKNOWN | Ch04 §VIII.3; Ch05 §III |
| OP-016 | Ý nghĩa việc Dịch đỡ tay áo ở S4; Vân Chương có cố ý thua hay không | Ch04 §I.29–30, §II | CÒN MỞ | — | CANON_UNKNOWN | Ch04 §I.29–30, §II |
| OP-017 | Động cơ cuối cùng khiến Vân Chương giữ im lặng | Ch04 §II, §VII ("chưa xác định") | CÒN MỞ | — | CANON_UNKNOWN | Ch04 §II, §VII |
| OP-018 | Mẹ của Vân Chương | Ch04 §II ("Không có thông tin") | CÒN MỞ | — | CANON_UNKNOWN | Ch04 §II |
| OP-019 | Nội dung dòng Vân Chương viết thêm vào lá thư gửi Hoắc | Ch05 §I.9, §II | CÒN MỞ (Ch06, Ch07 không nhắc lá thư) | — | CANON_UNKNOWN | Ch05 §I.9, §II |
| OP-020 | Vị trí/việc đốt thư của Tạ Diên | Ch05 §V ("Không khóa") | CÒN MỞ | — | CANON_UNKNOWN | Ch05 §V |
| OP-021 | Dịch có cảnh giác/nghi gì sau lời mời (ngoài POV, scope limit) | Ch05 §II | CÒN MỞ (Ch07 §V: Dịch không nhớ lại lời mời trong Ch7) | — | CANON_UNKNOWN | Ch05 §II; Ch07 §V |
| OP-022 | Tùy tùng có về miếu báo hay không | Ch05 §II, §V | CÒN MỞ (Ch06, Ch07 Canon Update không nhắc) | — | CANON_UNKNOWN | Ch05 §II, §V |
| OP-023 | Dịch đêm trừ tịch ở đâu (chỉ có lời Dịch ở Ch5; chưa xác minh bằng POV) | Ch05 §III, §V | ĐÃ ĐÓNG bởi Ch07 §I.1–11 (POV Dịch: đốt pháo ở đầu ngõ, về nhà, ra đầu bên kia) | — | CANON_FACT | Ch05 §III, §V; Ch07 §I |
| OP-024 | Người khiêng then Bắc Môn: hai người, Chu Hạc và ai; danh tính hai người khiêng then (Ch11 §II: "người thứ hai khiêng then") | Ch05 §VIII.2; Ch07 §II, §III; Ch11 §II | CÒN MỞ (Ch07 §III: Dịch không thấy mặt; Ch13 §IX giữ OPEN; Ch15 §IX, Ch18 §IX trong danh sách giữ OPEN) | — | CANON_UNKNOWN | Ch05 §VIII.2; Ch07 §II, §III; Ch11 §II; Ch13 §IX; Ch15 §IX; Ch18 §IX |
| OP-025 | Bùi Chỉ vào trướng/thư phòng Hoắc vì sao đêm ấy, bằng cách nào; chuyện thật trong thư phòng; ai giết người Bắc Nhung; A Quy đã làm gì | Ch05 §VIII.3; Ch06 §II, §III | CÒN MỞ | — | CANON_UNKNOWN | Ch05 §VIII.3; Ch06 §II, §III |
| OP-026 | Ai mở Bắc Môn; người lính dưới vòm cổng đã làm gì | Ch06 §II, §III | CÒN MỞ | — | CANON_UNKNOWN | Ch06 §II, §III |
| OP-027 | Ai mở khóa phòng củi; số phận người lính trông phòng củi | Ch06 §II | CÒN MỞ (Ch10 §II giữ OPEN "người lính trẻ trông phòng củi") | — | CANON_UNKNOWN | Ch06 §II; Ch10 §II |
| OP-028 | Số phận Tiểu Tứ (thân binh Tam Lang sai tới thư phòng) | Ch06 §0A | CÒN MỞ (Ch10 §II) | — | CANON_UNKNOWN | Ch06 §0A; Ch10 §II |
| OP-029 | Nghĩa của "…quân…" | Ch06 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch06 §II |
| OP-030 | Chu Hạc ở đâu lúc chính Tý | Ch06 §III; Ch07 §III | CÒN MỞ | — | CANON_UNKNOWN | Ch06 §III; Ch07 §III |
| OP-031 | Uyển: có quay vào thành không, vì sao, cơ chế nàng tự đi; vì sao công chúa quay lại thành; điều kiện của Uyển | Ch05 §VIII.5; Ch07 §II, §III | CÒN MỞ (Ch07 §I.22–25 chỉ có cảnh nàng tự đi; Canon không nêu lý do) | — | CANON_UNKNOWN | Ch05 §VIII.5; Ch07 §I.22–25, §II, §III |
| OP-032 | Cảnh trao đổi Uyển (để cho Ch7) | Ch06 §II | ĐÓNG MỘT PHẦN bởi Ch07 §I.20–25 (từ POV Dịch; "Dịch không thấy mặt"); Canon Update không chỉ rõ phần còn lại | — | CANON_FACT | Ch06 §II; Ch07 §I.20–25 |
| OP-033 | Dịch đêm ấy: thức hay ngủ; nhìn thấy gì (P-07 scope limit) | Ch05 §VIII.8 | ĐÃ ĐÓNG bởi Ch07 §I.1–15 (POV Dịch) | — | CANON_FACT | Ch05 §VIII.8; Ch07 §I |
| OP-034 | Vân Chương ở đâu đêm ấy; có gặp Uyển đêm ấy không | Ch06 §III; Ch07 §IX | CÒN MỞ trên trang (Ch07 §IV, §IX có author-truth đã khóa) | D3-05 | CANON_UNKNOWN | Ch06 §III; Ch07 §IV, §IX |
| OP-035 | Dịch từ Vân Trung tới Ích Châu thế nào (mức khung cho Ch8) | Ch07 §IX | CÒN MỞ | — | CANON_UNKNOWN | Ch07 §IX |
| OP-036 | Nội dung bọc vải xám của Phùng thúc | Ch07 §I.8, §II, §IX | ĐÃ ĐÓNG bởi Ch08 §I.15–16, §V (khóa trường mệnh; "đóng tuyến 'nội dung bọc'"; Ch08 §I.15: "Phùng Bảo mở bọc vải xám (Canon Ch7)") [BÍ DANH CHƯA XÁC NHẬN Phùng thúc ↔ Phùng Bảo — xem RG-L-05 (= CB-L-01)] | — | CANON_FACT | Ch07 §I.8, §II, §IX; Ch08 §I.15–16, §V |
| OP-037 | Bàn cờ và căn nhà của Dịch có thật sự cháy hay không (Dịch không tận mắt thấy) | Ch07 §II (xem RG-L-03) | CÒN MỞ | — | CANON_UNKNOWN | Ch07 §II |
| OP-038 | Ai để lộ tin (một trong Ôn, Tô, Hàn, qua mắt xích trong Ích Châu) | Ch08 §IX | ĐÃ ĐÓNG bởi Ch09 §I.19–20, §V (Hàn tự nhận nhắn ải Tây) | — | CANON_FACT | Ch08 §IX; Ch09 §I.19–20, §V |
| OP-039 | Nội dung phong thư Tây Lương | Ch08 §III, §IX | ĐÃ ĐÓNG bởi Ch09 §I.3 (thư Bàng) | — | CANON_FACT | Ch08 §III, §IX; Ch09 §I.3 |
| OP-040a | Việc bán lương, cỏ ải Tây; quân số, ngựa thật của ải — phần phủ thành | Ch08 §IX, §II | ĐÃ ĐÓNG (phần phủ thành) bởi Ch09 §V | — | CANON_FACT | Ch08 §II, §IX; Ch09 §V |
| OP-040b | Việc bán lương, cỏ ải Tây có phải đường dây trực tiếp của Tây Lương không — phần ở ải | Ch08 §IX | CÒN MỞ | — | CANON_UNKNOWN | Ch08 §IX; Ch09 §V |
| OP-041 | Nguồn và độ thật của luồng tin "tung tích Thất hoàng tử"; có người giả danh không | Ch08 §III, §IX | CÒN MỞ (Ch09 §II; Ch11 §IX; Ch12 §IX giữ OPEN) | — | CANON_UNKNOWN | Ch08 §III, §IX; Ch09 §II; Ch11 §IX; Ch12 §IX |
| OP-042a | Ôn nghiêng người / đứng về phe nào — phần hành xử đã lên trang | Ch08 §III, §IX | ĐÓNG MỘT PHẦN: Ch09 §III–IV (giữ Dịch, không công nhận, không gửi Kim Lăng; "chọn trì hoãn"); Ch12 §0B (CC-2: đặt cược có điều kiện) | — | CANON_FACT | Ch08 §III, §IX; Ch09 §III–IV; Ch12 §0B |
| OP-042b | Ôn nghiêng người vì cớ gì (trên trang) | Ch08 §III, §IX | CÒN MỞ (Ch09 §II: lý do Ôn nghiêng người / không tự tay cầm thư, không diễn giải) | D3-07 | CANON_UNKNOWN | Ch08 §III, §IX; Ch09 §II |
| OP-043 | Đính chính "Tam Lang còn sống" (hook Chapter Bible Ch9) | Ch08 §IX | ĐÃ ĐÓNG bởi Ch09 §I.32 | — | CANON_FACT | Ch08 §IX; Ch09 §I.32 |
| OP-044a | Tên tướng giữ ải Tây; tên tướng Tây Lương ở biên — tên xuất hiện | Ch08 §IX | Ch09 §I.3, §I.20: xuất hiện tên "Bàng" và "Tiết tướng quân" (Canon Update không ghi rõ đã đóng thread tên) | — | CANON_FACT | Ch08 §IX; Ch09 §I.3, §I.20 |
| OP-044b | Liên hệ giữa sứ Hạ Hầu và tướng Tây Lương (Bàng) | Ch08 §IX | CÒN MỞ (Ch09 §II; Ch11 §IX) | — | CANON_UNKNOWN | Ch08 §IX; Ch09 §II; Ch11 §IX |
| OP-045 | Phản ứng của Tiết; kết quả việc Hàn xử lý ải Tây; viên quản lương bị xử thế nào | Ch09 §II, §IV | CÒN MỞ (Ch11 §IX giữ OPEN: "phản ứng của Tiết; viên quản lương"; Ch19 §IX, Ch22 §II-A: Tiết tướng quân giữ OPEN) | — | CANON_UNKNOWN | Ch09 §II, §IV; Ch11 §IX; Ch19 §IX; Ch22 §II-A |
| OP-046 | Bắc Môn mười năm của Dịch: Dịch đã làm gì với ký ức Bắc Môn; có nghi Chu Hạc không | Ch08 §IX; Ch10 §IX | CÒN MỞ trên trang (Ch11 §II: suy luận riêng của Dịch không lên trang, không xác nhận Chu Hạc) | D3-09 | CANON_UNKNOWN | Ch08 §IX; Ch10 §IX; Ch11 §II |
| OP-047a | Dịch biết gì về Uyển (tước vị, quyền lực) — phần đã đóng | Ch08 §IX; Ch10 §IX; Ch11 §IX | ĐÓNG MỘT PHẦN bởi Ch12 §III (Vĩnh Ninh công chúa; Khả đôn; thủ lĩnh đợi nàng ngồi); Ch12 §V "Payoff một phần" | — | CANON_FACT | Ch10 §IX; Ch11 §IX; Ch12 §III, §V |
| OP-047b | Dịch biết gì về Uyển — phần còn lại (số bộ/quân; quan hệ thực với Hách Liên; con của Uyển…) | Ch10 §IX; Ch11 §IX | CÒN MỞ | — | CANON_UNKNOWN | Ch10 §IX; Ch12 §III |
| OP-048 | Trận Hắc Hà: diễn biến thật; nguồn gốc lời đồn Tam Lang tử trận | Ch09 §IX | ĐÃ ĐÓNG bởi Ch10 §I.10–16, §V (cờ đổ, mũ trụ trên giáo; đoàn buôn da) | — | CANON_FACT | Ch09 §IX; Ch10 §I.10–16, §V |
| OP-049a | Uyển trở lại câu chuyện qua quân cờ trắng / tín vật; đình chiến ngắn — phần "trở lại" | Ch09 §IX | ĐÃ ĐÓNG (phần "trở lại") bởi Ch10 §I.25–40 | — | CANON_FACT | Ch09 §IX; Ch10 §I.25–40 |
| OP-049b | Ý nghĩa quân cờ với Uyển | Ch10 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch10 §II |
| OP-050 | Chu Hạc trong bộ máy Hoắc ("người đưa ra lời khuyên từ phía sau"); động cơ riêng của Chu Hạc | Ch09 §IX; Ch10 §II | CÒN MỞ ("động cơ riêng của Chu Hạc": Ch10 §II; "động cơ Chu Hạc": Ch11 §IX, Ch12 §IX, Ch13 §IX; Ch19 §IX, Ch22 §II-A chỉ ghi "Chu Hạc" trong danh sách giữ OPEN, không có chữ "động cơ"). Thư Chu Hạc đã lên trang ở Ch10 §I.22 (xem S-116) | — | CANON_UNKNOWN | Ch09 §IX; Ch10 §II; Ch11 §IX; Ch12 §IX; Ch13 §IX; Ch19 §IX; Ch22 §II-A |
| OP-051 | Bắc Nhung chia phe (phe Uyển / phe Hách Liên) | Ch09 §IX | CÒN MỞ (Ch10 §I.27, §V đã gieo; Ch12 §I.24: Uyển không nói thay Hách Liên) | — | CANON_UNKNOWN | Ch09 §IX; Ch10 §V; Ch12 §I.24 |
| OP-052a | Knowledge của Chiêu về Dịch, Vân Chương, A Quy sau mười năm — phần đã đóng | Ch09 §IX | ĐÓNG MỘT PHẦN: Ch10 §III (không đổi so với đầu chương); Ch12 §III (Chiêu biết Trình Dịch = Thẩm thư lại; A Quy còn sống, nói lời Dạ Kiêu) | — | CANON_FACT | Ch09 §IX; Ch10 §III; Ch12 §III |
| OP-052b | Knowledge của Chiêu về Bắc Môn sau mười năm | Ch09 §IX | CÒN MỞ | — | CANON_UNKNOWN | Ch09 §IX; Ch12 §III |
| OP-053 | Ai giao Dạ Kiêu nhiệm vụ giết Dịch (Chapter Bible Ch11) / người ra lệnh cuối | Ch10 §IX | CÒN MỞ trên trang (Ch11 §III: Chỉ không biết) | D3-10 | CANON_UNKNOWN | Ch10 §IX; Ch11 §II–III |
| OP-054 | Câu khóa Ch11 "Đêm đó ta thấy người khiêng then cửa Bắc có hai người. Ngươi chỉ có một." | Ch10 §IX | ĐÃ ĐÓNG bởi Ch11 §I.21 | — | CANON_FACT | Ch10 §IX; Ch11 §I.21 |
| OP-055 | Thời điểm Ch11 so với Ch8–Ch9 (Dịch đã lộ danh ở Ích Châu) | Ch10 §IX | ĐÃ ĐÓNG bởi Ch11 §I (cuối tháng Năm / đầu tháng Sáu), §VII | — | CANON_FACT | Ch10 §IX; Ch11 §I, §VII |
| OP-056 | Vì sao Dịch không gọi lính (đêm Chỉ vào nhà) | Ch11 §II | CÒN MỞ (Ch12 §II còn nhắc; Ch13 Canon Update không nhắc lại) | — | CANON_UNKNOWN | Ch11 §II; Ch12 §II |
| OP-057 | Trình Dịch có thật là con của Thẩm chiêu nghi không (với Chỉ) | Ch11 §II, §III | CÒN MỞ | — | CANON_UNKNOWN | Ch11 §II, §III |
| OP-058 | Phản ứng của người thuê; quan hệ Dạ Kiêu với trung gian này về sau | Ch11 §II | CÒN MỞ (Ch13 §IX giữ OPEN: "phản ứng của người thuê") | — | CANON_UNKNOWN | Ch11 §II; Ch13 §IX |
| OP-059 | Số phận người dò tin bị bắt | Ch11 §II | CÒN MỞ (Ch13 §IX) | — | CANON_UNKNOWN | Ch11 §II; Ch13 §IX |
| OP-060 | Chỉ biết Tam Lang là nữ hay không | Ch11 §II | ĐÃ ĐÓNG bởi Ch12 §III (A Quy/Chỉ nay biết Tam Lang là Hoắc Chiêu) | — | CANON_FACT | Ch11 §II; Ch12 §III |
| OP-061 | Quân trắng (của Chiêu, của Chỉ, của năm người); người gia nhân | Ch10 §II; Ch11 §II | CÒN MỞ (Ch12 §II: "Quân trắng của năm người" không xuất hiện trong Ch12; Ch13 §IX; Ch15 §IX, Ch18 §IX trong danh sách giữ OPEN) | — | CANON_UNKNOWN | Ch10 §II; Ch11 §II; Ch12 §II; Ch13 §IX; Ch15 §IX; Ch18 §IX |
| OP-062 | Lão Tần; Chiêu có từng tới ngõ cháy không; Khả hãn hiện tại; tên tướng trẻ | Ch10 §II; Ch11 §IX | CÒN MỞ (Ch12 §IX, Ch13 §IX giữ OPEN: Lão Tần; ngõ cháy; Ch15 §IX, Ch18 §IX; Ch19 §IX, Ch22 §II-A: Lão Tần) | — | CANON_UNKNOWN | Ch10 §II; Ch11 §IX; Ch12 §IX; Ch13 §IX; Ch15 §IX; Ch18 §IX; Ch19 §IX; Ch22 §II-A |
| OP-063 | Người lạ đếm thuyền thuộc phe nào — phần đã biết theo Chỉ | Ch12 §II | ĐÓNG MỘT PHẦN: Ch13 §III (Chỉ biết đầu dây phía Hạ Hầu, qua ba mắt xích); Canon Update Ch13 không ghi "đóng" | — | CANON_FACT | Ch12 §II; Ch13 §III |
| OP-064 | Uyển biết Tam Lang là nữ bằng căn cứ nào | Ch12 §II | CÒN MỞ (Ch13 §II, §IX; Ch15 §IX; Ch18 §II) | — | CANON_UNKNOWN | Ch12 §II; Ch13 §II, §IX; Ch15 §IX; Ch18 §II |
| OP-065 | Sau "hết cuộc gặp này", Chiêu làm gì với A Quy | Ch12 §II, §IX | ĐÃ ĐÓNG bởi Ch13 §I.10, §IV (lệnh bắt còn; không truy qua mùa đông; chạy lại khi hết mùa đông hoặc thỏa thuận vỡ). Thread kế tiếp: xem OP-089 | — | CANON_FACT | Ch12 §II, §IX; Ch13 §I.10, §IV |
| OP-066a | Vân Chương sẽ dùng sự công nhận Kim Lăng thế nào — phần đã lên trang | Ch12 §II | ĐÓNG MỘT PHẦN: Ch13 §I.30 (thư "người tự nhận") | — | CANON_FACT | Ch12 §II; Ch13 §I.30 |
| OP-066b | Vân Chương "có thể phải phản bội Dịch" | Ch12 §II; Ch13 §V | CÒN MỞ ("Đã gieo (chưa quyết)" — Ch13 §V) | — | CANON_UNKNOWN | Ch12 §II; Ch13 §V |
| OP-067 | Dịch có báo Ôn chuyện đêm Ch11 không | Ch12 §II | CÒN MỞ (Ch12 §I.31: thư không có tên A Quy) | — | CANON_UNKNOWN | Ch12 §II, §I.31 |
| OP-068 | Khả hãn hiện tại; con của Uyển; quan hệ huyết thống Hoài Nam vương; tên thị trấn/bến; số hộ vệ; người thay quyền của Uyển; Hạ Hầu có biết cuộc gặp không | Ch12 §II | CÒN MỞ (Ch18 §II giữ OPEN: Khả hãn; con của Uyển; huyết thống Hoài Nam vương) | — | CANON_UNKNOWN | Ch12 §II; Ch18 §II |
| OP-069 | Chuỗi suy luận của Vân Chương về Dịch (bằng cách nào chàng biết) | Ch12 §III | CÒN MỞ — ngoài màn (Ch12 §0B CC-1); Ch13 chỉ thể hiện kết quả nhận thức; Dịch vẫn không biết | — | CANON_UNKNOWN | Ch12 §III, §0B; Ch13 §0 |
| OP-070 | Người rò tin bên trong (ai, đoàn nào) | Ch13 §II | CÒN MỞ ("OPEN tới Gate Ch14" — Ch13 §II); xem thêm OP-076 (G-1) | D3-12 | CANON_UNKNOWN | Ch13 §II, §IX |
| OP-071 | Viên quan Kim Lăng gửi cho ai trong triều (K2); triều Kim Lăng phản ứng; con ngựa nào tới trước | Ch13 §II | CÒN MỞ (Ch19 §IX, Ch22 §II-A: K2 giữ OPEN) | — | CANON_UNKNOWN | Ch13 §II; Ch19 §IX; Ch22 §II-A |
| OP-072 | Hạ Hầu làm gì tiếp sau tin giả | Ch13 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch13 §II |
| OP-073 | Dịch định nói gì sau "Đêm ấy…"; A Quy định nói gì với Chiêu; Vân Chương định hỏi Uyển điều gì | Ch13 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch13 §II |
| OP-074 | Các đoàn chưa rời Lạc Thủy ở cuối chương | Ch13 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch13 §II |
| OP-075 | Năm đường của "năm tin giả" (Ch14 POV Chỉ): năm bên hay năm mắt xích; Ch14 diễn ra ở đâu, khi nào; ai bị nghi; cái tên mười năm trước ở hook Ch14 | Ch13 §IX | CÒN MỞ theo staging Ch08–13 ("câu hỏi chuyển sang Gate Ch14"); staging Ch14–18 không có dòng đóng riêng (xem S-174 về hook "cái tên từ mười năm trước") | D3-13 | CANON_UNKNOWN | Ch13 §IX |
| OP-076 | Nguồn rò tuyến văn thư – trạm ngựa Kim Lăng (G-1): chỉ biết "đường có lỗ"; không biết nguồn rò là ai, trong hay ngoài đoàn Kim Lăng | Ch14 §II | CÒN MỞ (Ch15 §II; Ch16 §II; Ch17 §II, §IX; Ch18 §II, §IX; Ch19 §IX K-1/K-2; Ch22 §II-A) | — | CANON_UNKNOWN | Ch14 §II; Ch18 §IX; Ch19 §IX; Ch22 §II-A |
| OP-077 | Kha Trọng (G-2): chưa kết luận cùng một người (sổ cũ = sổ thuê ngựa = lão Kha); còn sống; liên quan Bắc Môn / Chu Hạc / Tạ gia; chủ mưu | Ch14 §II | CÒN MỞ (Ch15 §IX; Ch16 §IX; Ch17 §IX; Ch18 §IX; Ch19 §IX; Ch22 §II-A) | — | CANON_UNKNOWN | Ch14 §II; Ch18 §IX; Ch19 §IX; Ch22 §II-A |
| OP-078 | Hai người lạ ở miếu: họ là ai, ai sai, có thực sự nhận tin qua tờ giấy | Ch14 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch14 §II |
| OP-079 | Vân Chương và hai chỗ hẹn: có làm gì với hai chỗ hẹn; vì sao nhận cả hai; chàng nghĩ gì | Ch14 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch14 §II |
| OP-080 | Ai báo tuyến miệng T1–T3, vì sao "không ai" (tuyến sạch ≠ an toàn tuyệt đối) | Ch14 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch14 §II, §IV |
| OP-081 | Lời đáp cho Hoắc quân (Chỉ chưa trả lời: "Chưa.") | Ch14 §II | CÒN MỞ (Chỉ vắng Ch15–Ch18) | — | CANON_UNKNOWN | Ch14 §II, §I.21 |
| OP-082 | "Phủ lớn họ Tạ" là phủ nào; lão Kha có phải người trong lời đồn (lời đồn ba tầng miệng) | Ch14 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch14 §II |
| OP-083 | Người giữ sổ, người ở trạm, người theo chân, người canh: chưa đặt tên | Ch14 §II | CÒN MỞ (Ch15–Ch18 không nêu) | — | CANON_UNKNOWN | Ch14 §II |
| OP-084 | Chỉ sẽ nói gì với Dịch về phát hiện Ch14 (Ch14 chưa nói với ai ngoài thuộc hạ và Vân Chương) | Ch14 §IX | CÒN MỞ (Ch15–Ch18 không có Chỉ) | — | CANON_UNKNOWN | Ch14 §IX |
| OP-085 | Bàng đọc đường lương bằng cách nào (trên trang Dịch thấy hai đường trùng nhau, không kết luận) | Ch15 §II | CÒN MỞ (Ch17 §II: "cách Bàng đọc liên minh" OPEN) | — | CANON_UNKNOWN | Ch15 §II; Ch17 §II |
| OP-086 | Có rò tin hay không (phía Dịch); giữ OPEN, không nguyên nhân Hổ Lao (K-2) | Ch15 §II | CÒN MỞ (Ch16 §II; Ch17 §IX) | — | CANON_UNKNOWN | Ch15 §II; Ch16 §II; Ch17 §IX |
| OP-087 | Nội dung hồi âm Dịch/Ôn gửi Bàng | Ch15 §II | ĐÃ ĐÓNG bởi Ch16 §I.23 (toàn văn hồi âm đọc công khai) | — | CANON_FACT | Ch15 §II; Ch16 §I.23 |
| OP-088a | Bàng đáp thế nào (hồi âm chỉ lương) | Ch16 §II | ĐÃ ĐÓNG bởi Ch19 §V ("Đã đáp bằng thư lương Ch19"; Ch19 §I.7) | — | CANON_FACT | Ch16 §II; Ch17 §II; Ch19 §I.7, §V |
| OP-088b | Ý đồ thật của hồi âm Bàng; Hạ Hầu/Bàng phản ứng sau Dĩnh Xuyên (đổi cách đo; phản công; đọc bản nào lúc nào); Hạ Hầu mất một phần ngựa | Ch16 §II; Ch17 §II; Ch18 §II; Ch19 §II, §IX; Ch20 §II | CÒN MỞ (Bàng, Hạ Hầu Liệt "không trên trang" ở Ch22 §IV) | — | CANON_UNKNOWN | Ch16 §II; Ch17 §II; Ch18 §II; Ch19 §II, §IX; Ch20 §II; Ch22 §IV |
| OP-089 | Lệnh bắt A Quy: hạn "qua mùa đông" đã hết; Ch17 chỉ "Lệnh còn."; A Quy ở đâu, Chiêu làm gì khi gặp | Ch15 §II (Ch14 §IV) | CÒN MỞ (Ch17 §II: "toàn bộ", không nối Dĩnh Xuyên; Ch19 §IX; Ch22 §II-A) | — | CANON_UNKNOWN | Ch14 §IV; Ch15 §II; Ch17 §II; Ch19 §IX; Ch22 §II-A |
| OP-090 | Thái độ Ôn sau thất bại | Ch15 §II | Canon Update không ghi đóng (Ch16 §I.31 có thư Ôn: ấn tới hết vụ thu; muối 400 bao, vải 200 tấm) | — | CANON_UNKNOWN | Ch15 §II; Ch16 §I.31 |
| OP-091 | Ôn đã quyết gì về "việc kia" | Ch16 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch16 §II |
| OP-092 | "Việc kia" / tờ thứ nhất thư Bàng: nội dung (Ôn, Tô, Hàn, Dịch đã xem; không giải thích; Dịch/Ôn chưa đáp) | Ch16 §II; Ch19 §II | CÒN MỞ (Ch20 §IX; Ch21 §IX; Ch22 §II-A) | — | CANON_UNKNOWN | Ch16 §II; Ch19 §II; Ch22 §II-A |
| OP-093 | Thương vong "nghìn tám" / "bảy trăm" không phân chia (số chết / bị bắt / lạc) | Ch15 §II (G-15-1) | CÒN MỞ một phần: Ch16 §I.5 ghi "Hai trăm bốn mươi người chưa rõ sống chết" | — | CANON_UNKNOWN | Ch15 §II; Ch16 §I.5 |
| OP-094 | Ai ra lệnh trống ba tiếng; thương vong Hạ Hầu | Ch15 §II | CÒN MỞ (Bàng không xuất hiện; không nêu) | — | CANON_UNKNOWN | Ch15 §II |
| OP-095 | Tên bến, chỗ ép, phó tướng các bên (vô danh) | Ch15 §II | CÒN MỞ (Ch16 §II, Ch17 §II vẫn vô danh) | — | CANON_UNKNOWN | Ch15 §II; Ch16 §II |
| OP-096a | Dĩnh Xuyên: vị trí, kho, ai giữ, mục đích — phần đã lên trang | Ch16 §II | ĐÓNG MỘT PHẦN bởi Ch17 §I.4 (chức năng, kho, đê, cổ chai, Đô úy giữ) | — | CANON_FACT | Ch16 §II; Ch17 §I.4 |
| OP-096b | Vì sao Dịch chắc họ (Dĩnh Xuyên) sẽ cứu | Ch16 §II | CÒN MỞ (Ch17 §II → Ch19) | — | CANON_UNKNOWN | Ch16 §II; Ch17 §II |
| OP-097a | Vì sao Hạ Hầu mua lương dân — phần Canon Update ghi "Đóng một phần" | Ch16 §II | ĐÓNG MỘT PHẦN bởi Ch18 §V (seed "mua ngựa, cùng mạch bạc") | — | CANON_FACT | Ch16 §II; Ch18 §V |
| OP-097b | Vì sao Hạ Hầu mua lương dân (chiến lược tiếp tế); trên trang không nêu tên phe | Ch16 §II | CÒN MỞ (Ch18 §0: trên trang không nêu "Hạ Hầu"/"Tây Lương") | — | CANON_UNKNOWN | Ch16 §II; Ch18 §0 |
| OP-098 | Khả đôn / băng tan: phản ứng (lời hứa hết khi băng tan; không nhắc thành lời Ch16) | Ch15 §I.7; Ch16 §II | Canon Update Ch18 không ghi đóng (Ch18 §I.1: Hắc Hà băng tan hẳn) | — | CANON_UNKNOWN | Ch16 §II; Ch17 §IX; Ch18 §I.1 |
| OP-099a | Hạ Hầu "thêm quân" ở Hổ Lao: khả năng đọc bẫy — phần đã lên trang | Ch16 §IX | ĐÓNG MỘT PHẦN: Ch17 §I.34 (chỗ đọc sai bằng hình ảnh) | — | CANON_FACT | Ch16 §IX; Ch17 §I.34 |
| OP-099b | Hạ Hầu "thêm quân" ở Hổ Lao: phản ứng với hồi âm; khả năng đọc bẫy — không giải thích trên trang | Ch16 §IX | CÒN MỞ (Ch17 §II) | — | CANON_UNKNOWN | Ch16 §IX; Ch17 §II |
| OP-100 | Chiêu biết gì về đường than tới Dĩnh Xuyên | Ch16 §IX | ĐÃ ĐÓNG bởi Ch17 §I.3–I.7 (Dịch tới mang giấy) | — | CANON_FACT | Ch16 §IX; Ch17 §I.3–7 |
| OP-101 | Ai chỉ huy viện quân; số quân hai khối; thương vong; Đô úy Dĩnh Xuyên và quan coi kho; số phận Đô úy, quan coi kho, hào chợ, hàng binh sau ngày 41 (vô danh) | Ch17 §II; Ch19 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch17 §II; Ch19 §II |
| OP-102 | Dịch ở đâu trong trận; Dịch nghĩ gì khi kéo Chiêu làm mồi (Chiêu không thấy hắn) | Ch17 §II, §III; Ch19 §II | CÒN MỞ (Ch19 §II: "không ghi") | — | CANON_UNKNOWN | Ch17 §II, §III; Ch19 §II |
| OP-103 | Số phận kỵ nhẹ Hoắc quân sau trận (hạn tối đa ngày 42) / sau ngày 42; Chiêu về biên hay ở lại; có tin phương bắc không | Ch17 §II; Ch19 §II, §IX | CÒN MỞ (Ch18 §VII không nối số ngày; Ch22: gò thấp phía đông trống, không nêu vì sao — Ch22 §II-A, §IX) | — | CANON_UNKNOWN | Ch17 §II; Ch18 §VII; Ch19 §II, §IX; Ch22 §II-A, §IX |
| OP-104 | Hách Liên Chước: quân số, mục tiêu, có sai Tu Bặc Cốt không, quan hệ Hạ Hầu; tập quân (Vân Chương chưa biết) | Ch18 §II; Ch20 §II | CÒN MỞ (Ch22 §IX) | — | CANON_UNKNOWN | Ch18 §II; Ch20 §II; Ch22 §IX |
| OP-105 | Người mua (giọng miền tây, bạc dấu kho): của ai; nén bạc: ai đúc, Lạc Kinh | Ch18 §II, §IX | CÒN MỞ (không nêu tên phe; Uyển không nói "Hạ Hầu") | — | CANON_UNKNOWN | Ch18 §II, §IX |
| OP-106a | Kim Lăng/Vân Chương phản ứng thư ngắn + gói vỏ quýt — phần đã đóng | Ch18 §II; Ch19 §IX | ĐÓNG MỘT PHẦN bởi Ch20 §I.4, §I.19, §I.21 (tới Kim Lăng, Vân Chương nhận, không đáp) | — | CANON_FACT | Ch18 §II; Ch19 §IX; Ch20 §I.4, §I.19, §I.21 |
| OP-106b | Vân Chương đáp / phản ứng thế nào thư + gói vỏ quýt; Uyển nghĩ gì khi nhận lại | Ch18 §II; Ch20 §II | CÒN MỞ (Ch20 §V; Ch21 §II-A, §V) | — | CANON_UNKNOWN | Ch18 §II; Ch20 §II, §V; Ch21 §II-A, §V |
| OP-107 | Câu Vân Chương không hỏi Uyển | Ch13 §II; Ch18 §II; Ch20 §II | CÒN MỞ (Ch21 §II-A; Ch22 §IX) | — | CANON_UNKNOWN | Ch13 §II; Ch18 §II; Ch20 §II; Ch22 §IX |
| OP-108 | Danh sách "giữ OPEN" tích lũy: Tiết tướng quân; K2; Chu Hạc; Khương lão tướng; Lão Tần; quân trắng; người thứ hai khiêng then; Chiêu có từng tới ngõ cháy không; ai trả tiền nuôi Chỉ / thư phòng Hoắc–Chỉ; K-1/K-2 (rò Ch14); Kha Trọng (G-2); lệnh bắt A Quy; Hách Liên Chước | Ch15 §IX | CÒN MỞ (lặp lại Ch16 §IX, Ch17 §IX, Ch18 §IX; Ch19 §II, §IX; Ch22 §II-A) | D3-14 | CANON_UNKNOWN | Ch15 §IX; Ch16 §IX; Ch17 §IX; Ch18 §IX; Ch19 §II, §IX; Ch22 §II-A |
| OP-109 | Kim Lăng/Vân Chương phản ứng lời hứa vượt quyền của Dịch (ân xá làm trước, không ấn) | Ch19 §II | ĐÃ ĐÓNG bởi Ch20 §V ("Đã nhận (hợp thức hóa hậu quả)"), Ch20 §VI ("Kim Lăng đã ôm hậu quả"; Dịch chưa biết; Ch21 §VI không đổi) | — | CANON_FACT | Ch19 §II; Ch20 §V, §VI; Ch21 §VI |
| OP-110a | Phản ứng của Dịch với chiếu nêu tên "sứ Ích Châu Trình Dịch" — phần đã lên trang | Ch20 §II (Dịch chưa biết chiếu ở Ch20) | ĐÓNG MỘT PHẦN: Dịch đã đọc tên mình ở Ch22 §I.30–31 | — | CANON_FACT | Ch20 §II; Ch22 §I.30–31 |
| OP-110b | Phản ứng/giải nghĩa của Dịch, Ôn, Chiêu với chiếu nêu tên "sứ Ích Châu Trình Dịch" | Ch20 §II | CÒN MỞ (Ch22 §II-A: phản ứng/giải nghĩa của Dịch; Ôn, Chiêu còn mở) | — | CANON_UNKNOWN | Ch20 §II; Ch22 §II-A |
| OP-111 | Cách Dịch trả C1 (lời hứa văn bản trong tay dân Dĩnh Xuyên và nơi mở cửa sau) | Ch19 §II | CÒN MỞ | — | CANON_UNKNOWN | Ch19 §II |
| OP-112a | Liên minh vào thành Dĩnh Xuyên ngày đầu ra sao — phần đã lên trang | Ch19 §IX | ĐÓNG MỘT PHẦN bởi Ch20 §I.2 (báo cáo: liên quân đứng ngoài; quan cũ giữ việc) | — | CANON_FACT | Ch19 §IX; Ch20 §I.2 |
| OP-112b | Liên minh vào thành Dĩnh Xuyên; quan coi kho/Đô úy/hào chợ giữ việc thế nào — phần còn lại | Ch19 §IX | CÒN MỞ | — | CANON_UNKNOWN | Ch19 §IX |
| OP-113a | Thư xin hàng Hổ Lao — ba điều kiện | Ch20 §II (không lên trang Ch20) | ĐÓNG: ba điều kiện lên trang ở Ch21 §I.2 | — | CANON_FACT | Ch20 §II; Ch21 §I.2 |
| OP-113b | Thư xin hàng Hổ Lao: thật hay trá; người đưa thư là ai; tướng giữ Hổ Lao là ai | Ch20 §II | CÒN MỞ (Ch21 §II-A; Ch22 §II-A) | D3-15 | CANON_UNKNOWN | Ch20 §II; Ch21 §II-A; Ch22 §II-A |
| OP-114 | Quan huyện: vì sao bị Hạ Hầu xử (Vân Chương chỉ biết hai việc) | Ch20 §II | CÒN MỞ (Ch21 §II-A: không nối nhân quả; Ch22 §II-A: thư lại Hổ Lao giấu chiếu "từ ngày huyện bên bị treo", không giải thích) | — | CANON_UNKNOWN | Ch20 §II; Ch21 §II-A; Ch22 §II-A |
| OP-115a | Thư riêng theo chức: tới tay người giữ chức Hổ Lao — (Vân Chương suy: Ch21 §III "INFERENCE (một mức)") | Ch20 §II | CHƯA QUYẾT ⚠ xem RG-L-28 (= CB-L-20): Ch21 §I.4 (narration nêu như dữ kiện) và Ch21 §0 ("xác nhận OPEN Ch20 'tới tay ai', chỉ ở mức Hổ Lao") đặt claim này ở FACT; Ch21 §III (Vân Chương) liệt kê cùng claim ở cả cột FACT lẫn "INFERENCE (một mức)". Registry không chọn bên, không ghi "đã đóng" | — | CANON_SUSPICION | Ch20 §II; Ch21 §I.4, §0, §III |
| OP-115b | Thư riêng theo chức: tới tay ai — ngoài mức Hổ Lao | Ch20 §II | CÒN MỞ (Ch21 §0 chỉ nêu "mức Hổ Lao"; Canon Update không chỉ rõ phần còn lại) | — | CANON_UNKNOWN | Ch20 §II; Ch21 §0 |
| OP-116 | Ông áo tía; ấn tước; hôn thư (không subplot trừ khi chị quyết) | Ch20 §II | CÒN MỞ (vắng Ch21–22) | — | CANON_UNKNOWN | Ch20 §II; Ch21 §II-A |
| OP-117 | Tờ xin ra tuyến trước; Vân Chương có đi hay không (nằm trong ngăn kéo) | Ch20 §II | CÒN MỞ (Ch21 §II-A) | — | CANON_UNKNOWN | Ch20 §II; Ch21 §II-A |
| OP-118a | Hổ Lao đã đổi chủ chưa — phần đã lên trang | Ch21 §II-A | ĐÓNG MỘT PHẦN: đã đổi chủ (Ch22 §IV: Hạ Hầu "Mất Hổ Lao") | — | CANON_FACT | Ch21 §II-A; Ch22 §IV |
| OP-118b | Cổng thành nào, do ai mở, vì sao, bẫy hay thắng; vì sao cổng bến mở, ai mở | Ch21 §II-A | CÒN MỞ (Ch22 §II-A) | D3-24 | CANON_UNKNOWN | Ch21 §II-A; Ch22 §II-A |
| OP-119 | Thư Hổ Lao có bị chạm trên đường không (trên trang chỉ "một đêm ở nhà trạm của quân") | Ch21 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch21 §II-A |
| OP-120a | Liên quân/Dịch/Hàn/Chiêu có nhận lịch lương không — phần Dịch | Ch21 §II-A | ĐÓNG MỘT PHẦN: Dịch nhận lịch lương (Ch22 §I.2–4) | — | CANON_FACT | Ch21 §II-A; Ch22 §I.2–4 |
| OP-120b | Liên quân/Hàn/Chiêu có nhận lịch lương không, làm gì (Chiêu vắng) | Ch21 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch21 §II-A; Ch22 §I |
| OP-121a | Thuyền Kim Lăng có vào bến/chịu hại không — phần đã lên trang | Ch21 §II-A | ĐÓNG MỘT PHẦN: Ch22 §I.24 "Thuyền chưa dỡ. Lương còn nguyên." | — | CANON_FACT | Ch21 §II-A; Ch22 §I.24 |
| OP-121b | Phó tướng thủy quân biết gì về ý đồ; thuyền chở gì ngoài lương | Ch21 §II-A | CÒN MỞ (Ch21 §II-A: "phó tướng thủy quân biết gì về ý đồ"; Ch22 §II-A: "thuyền chở gì ngoài lương", trên trang chỉ "Thuyền chưa dỡ. Lương còn nguyên.") | — | CANON_UNKNOWN | Ch21 §II-A; Ch22 §II-A |
| OP-121c | Ai ra lệnh thuyền neo ngang sông | Ch22 §II-A | OPEN với Dịch / trên trang POV Dịch Ch22 (Ch22 §II-A; Ch22 §III: "nguồn lệnh neo — Ch21 lời miệng của Vân Chương; Dịch không biết"). Canon đã có ở Ch21 §I.12 (POV Vân Chương): lời miệng cho phó tướng "Tới bến thì neo ngang sông. Một đêm."; xem D-69 | — | CANON_UNKNOWN | Ch21 §I.12; Ch22 §II-A, §III |
| OP-122 | Điều (2): liên quân biết khi nào; "người ngoài" gồm ai | Ch21 §II-A | CÒN MỞ (Ch22 §IX) | — | CANON_UNKNOWN | Ch21 §II-A; Ch22 §IX |
| OP-123 | Thư đáp ngoài sổ triều, không ai chứng: hậu quả | Ch21 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch21 §II-A |
| OP-124 | Lạc Kinh trên trang: cách / lúc Lạc Kinh đổi chủ | Ch21 §II-A, §IX | CÒN MỞ trên trang (Ch21 §II-A: "Ch21 không đụng"; Ch21 §IX: "Ch21 không canon hóa cách Lạc Kinh đổi chủ"; Ch22 §0, §II-A: Lạc Kinh "không đụng trên trang ngoài tiêu đề"). Phần kế hoạch (mối nối Chapter Bible Ch22 ↔ Ch28) đã chuyển sang D5-03 | D3-21 | CANON_UNKNOWN | Ch21 §II-A, §IX; Ch22 §0, §II-A |
| OP-125 | Tướng giữ thành Hổ Lao (Hạ Hầu giữ thành đêm qua): sống/chết/thoát ("Không thấy từ đêm qua", vô danh) | Ch22 §II-A | CÒN MỞ | D3-23 | CANON_UNKNOWN | Ch22 §II-A |
| OP-126 | Hai luồng đi bờ phía tây (nhóm đêm; cột sáng có kỵ che hai bên): thuộc/đi đâu | Ch22 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch22 §II-A |
| OP-127 | Ai hợp lệ cai trị Hổ Lao (không ai đáp) | Ch22 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch22 §II-A |
| OP-128 | Hệ quả sổ kho Hổ Lao (chữ ký Dịch) tới Vân Chương | Ch22 §II-A | CÒN MỞ | — | CANON_UNKNOWN | Ch22 §II-A |
| OP-129 | Vì sao thư lại Hổ Lao dán chiếu lúc này | Ch22 §II-A | CÒN MỞ (không giải thích trên trang) | — | CANON_UNKNOWN | Ch22 §II-A |
| OP-130 | Điều (2) / thư Hổ Lao / Vân Chương làm gì / Bàng đọc gì / số phận người viết thư — Dịch không biết (GR22-H1) | Ch22 §II-A | OPEN với Dịch / trên trang POV Dịch Ch22 (Ch22 §II-A). Canon đã có trên trang POV Vân Chương ở Ch21: thư Hổ Lao ba điều (Ch21 §I.2; xem OP-113a), điều (2) Vân Chương "đã nhận bằng chữ" (Ch21 §II-A), việc Vân Chương làm (Ch21 §I). "Số phận người viết thư" còn OPEN trên trang (Ch21 §II-A); "Bàng đọc gì" chỉ có ở author-truth (D3-17) | D3-22 | CANON_UNKNOWN | Ch21 §I.2, §II-A; Ch22 §II-A |
| OP-131 | Ôn muối trần; "ấn tới sau" | Ch19 §IX | CÒN MỞ (Ch22 §II-A) | — | CANON_UNKNOWN | Ch19 §IX; Ch22 §II-A |

---

## C. EMOTIONAL DEBT — THEO CẶP NHÂN VẬT

**Cách đọc.** Sắp theo cặp `A → B` (chủ nợ/đối tượng đúng như cột "Người | Đối tượng" của Canon Update; không đảo chiều), không theo chương. "Diễn biến" nối before → after qua các chương; "Trạng thái cuối Ch22" = dòng cuối có trong Canon Update (các chương sau không có dòng → ghi "không cập nhật sau ChNN"). Trạng thái giữ nguyên chữ Canon Update (UNPAID / ACTIVE / Mới / Ẩn …), các chương dùng bộ nhãn không đồng nhất và Registry **không quy đổi** (xem GHI CHÚ ĐỘ TIN CẬY). Dòng đầu tiên của một cặp: Canon ghi "Mới" → "(không có dòng trước; Canon ghi 'Mới')"; Canon không ghi "Mới" và không có dòng trước trích được → "(Before chưa trích được)". Registry không nối hai dòng khác đối tượng / khác nội dung khi Canon Update không tự nối. Mọi `PLAN: ChX` gắn với nợ đã chuyển sang D4. Nợ chỉ có tính author-level / planning (Tạ Diên → Vân Chương; cost Chapter Bible Ch6; "Dịch nợ những người đã tin mình") nằm ở D4, không ở đây.

| ID | Cặp (A → B) | Nợ (tên theo Canon Update) | Gốc | Diễn biến (before → after) | Trạng thái cuối Ch22 | Source Type | Source |
|---|---|---|---|---|---|---|---|
| D-01 | Dịch → Tam Lang, A Quy | Dừng ở khúc ngoặt rồi đi tiếp; ở ngã ba, đường lên phía bắc đã thông mà không lên | Ch07 §VI | Ch07: UNPAID (dòng gốc không có cập nhật; các dòng kế tiếp xem D-02, D-03) | UNPAID (Ch07 §VI) | CANON_FACT | Ch07 §VI |
| D-02 | Dịch → Tam Lang / Chiêu | Unresolved attachment / concern ("nợ cũ từ Ch7") | Ch08 §VI (lời đồn tử trận "kích hoạt món nợ cũ từ Ch7") | Ch08: lời đồn kích hoạt (Ch9 đính chính) → Ch09: "được gỡ một phần (vẫn giữ Hắc Hà); món nợ Ch7 vẫn còn", ACTIVE → Ch12: "Nàng trao tên thật trước mặt hắn; hắn bỏ đi đêm Vân Trung (Ch7), chưa nói", ACTIVE, không nói ra → Ch13: "Bỏ đi đêm Vân Trung; 'Đêm ấy…' rồi thôi", ACTIVE, không nói ra | ACTIVE, không nói ra (Ch13 §VI; Ch14–Ch22 không có dòng riêng) | CANON_FACT | Ch08 §VI; Ch09 §VI; Ch12 §VI; Ch13 §VI |
| D-03 | Dịch → A Quy | Món nợ Ch7 (không quay lại) "chạm tới" qua "Ngươi còn sống." (Ch11 §VI nêu gốc "Ch07"; Canon Update không ghi rõ cùng dòng với D-01) | Ch07 (theo Ch11 §VI); Ch11 §VI | Ch11: ACTIVE, không nói ra | ACTIVE, không nói ra (không cập nhật sau Ch11) | CANON_FACT | Ch11 §VI |
| D-04 | Dịch → Hoắc quân / Chiêu | Nhận hai xe lương (sổ hội minh); "Đêm ấy…" chưa nói; nợ lương + nuôi kỵ nhẹ; đã kéo nàng làm mồi | Ch13 (theo Ch15 §V); Ch15 §VI | Ch15: ACTIVE (hai xe; "Đêm ấy…" chưa nói) → Ch16: ACTIVE, tăng (nợ lương + nuôi kỵ nhẹ; hạn còn hai ngày) → Ch17: ACTIVE, tăng (đã kéo nàng làm mồi, nàng bị thương; chưa trên trang) | ACTIVE, tăng (Ch17 §VI) | CANON_FACT | Ch15 §V, §VI; Ch16 §V, §VI; Ch17 §VI |
| D-05 | Dịch → Chiêu | Tiểu Thất (tên ghi); nàng không ký | Ch19 §VI | (Before chưa trích được) → Ch19: ACTIVE, "không gọi tên" → Ch20: "Không đổi" (dòng chung "Các nợ còn lại Dịch/Chiêu/Hàn/Ôn") → Ch22: ACTIVE, "không lên trang" (gò thấp trống) | ACTIVE, không lên trang (Ch22 §VI) | CANON_FACT | Ch19 §VI; Ch20 §VI; Ch22 §VI |
| D-06 | Dịch → Uyển | Đứng nhìn nàng tự đi | Ch07 §VI | Ch07: UNPAID → Ch12: ACTIVE, chưa chạm (Canon Update Ch12 đổi nhãn UNPAID → ACTIVE, không nêu lý do) | ACTIVE, chưa chạm (Ch12 §VI; Ch13–Ch22 không cập nhật) | CANON_FACT | Ch07 §VI; Ch12 §VI |
| D-07 | Dịch → Vân Chương | Không biết Vân Chương sống chết (Ch04 §VII: "Dịch không biết Vân Chương đã giữ im lặng thay mình, nên chưa thể có món nợ này trong nhận thức của Dịch") | Ch04 §VII | Ch04: (chưa ghi) → Ch07: UNPAID | UNPAID (Ch07 §VI; không cập nhật sau) | CANON_FACT | Ch04 §VII; Ch07 §VI |
| D-08 | Dịch → điều mình đã thấy ở Bắc Môn | Im lặng; không làm chứng vì làm chứng phải đứng ra bằng tên | Ch07 §VI | Ch07: ACTIVE | ACTIVE | CANON_FACT | Ch07 §VI |
| D-09 | Dịch → hàng xóm trong ngõ | Không báo | Ch07 §VI (không được gọi tên trong văn bản) | Ch07: Ẩn | Ẩn | CANON_FACT | Ch07 §VI |
| D-10 | Dịch ↔ Phùng thúc [BÍ DANH CHƯA XÁC NHẬN Phùng thúc ↔ Phùng Bảo — xem RG-L-05 (= CB-L-01)] | Được che chở, dìu lão suốt đường (hai chiều) | Ch07 §VI | Ch07: Hai chiều, ACTIVE. Không nối sang D-11 (D-11 mang nhãn gốc "Phùng Bảo"); Ch08 §I.15 chép nguyên: "Phùng Bảo mở bọc vải xám (Canon Ch7)" | ACTIVE (Ch07 §VI) | CANON_FACT | Ch07 §VI; Ch08 §I.15 |
| D-11 | Dịch → Phùng Bảo [BÍ DANH CHƯA XÁC NHẬN — xem RG-L-05 (= CB-L-01); không nối với D-10, D-78] | DEBT thật — Phùng Bảo đứng ra làm chứng, tự đặt mình trở lại trong án cũ | Ch08 §VI | Ch08: ACTIVE → Ch09: ACTIVE ("DEBT thật (Ch8)"); Ch10–Ch13 không cập nhật | ACTIVE | CANON_FACT | Ch08 §VI; Ch09 §VI |
| D-12 | Dịch → Thẩm chiêu nghi | Moral / identity burden | Ch08 §VI | Ch08: ACTIVE, không nói ra → Ch09: ACTIVE; Ch10–Ch22 không cập nhật | ACTIVE (Ch09 §VI) | CANON_FACT | Ch08 §VI; Ch09 §VI |
| D-13 | Dịch ↔ Hàn | Hàn đứng ra nhận; Dịch phải dè chừng; Hàn nghe "Chưa." | Ch09 §VI | Ch09: hai chiều ACTIVE; Ch10–Ch13 không cập nhật | Hai chiều, ACTIVE | CANON_FACT | Ch09 §VI |
| D-14 | Dịch → Hàn | Hàn bị thương ở hậu quân → Hàn ký kèm phiếu và hồi âm, nhận trách nhiệm → Hàn tự chịu quyết gửi bộ | Ch15 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch15: mới (bị thương) → Ch16: mới (ký phiếu + hồi âm, nhận trách nhiệm) → Ch17: ACTIVE (Hàn tự chịu quyết gửi bộ). Ch19 §VI có dòng Dịch → Hàn "Hàn giữ hàng binh" (xem D-15); Canon Update không nêu có nối hai dòng | ACTIVE (Ch17 §VI) | CANON_FACT | Ch15 §VI; Ch16 §VI; Ch17 §VI |
| D-15 | Dịch → Hàn | Hàn giữ hàng binh | Ch19 §VI | (Before chưa trích được) → Ch19: ACTIVE → Ch20: "Không đổi" (dòng chung "Các nợ còn lại Dịch/Chiêu/Hàn/Ôn"); Ch22 không có dòng cùng nội dung (dòng Ch22 khác đối tượng: xem D-79) | ACTIVE (Ch19 §VI; Ch20 §VI không đổi) | CANON_FACT | Ch19 §VI; Ch20 §VI |
| D-16 | Dịch → Ôn / Hàn | Bảo chứng A Quy bằng danh Ích Châu mà không được dặn | Ch12 §VI | Ch12: Mới, ACTIVE | ACTIVE (không cập nhật sau Ch12) | CANON_FACT | Ch12 §VI |
| D-17 | Dịch → Ôn | Làm trước, ấn sau; tối đa 400 bao | Ch16 §VI | Ch16: mới; Ch17–Ch18 không có dòng riêng | Mới (theo dòng cuối Ch16) | CANON_FACT | Ch16 §VI |
| D-18 | Dịch → Ôn | Muối vượt trần | Ch19 §VI | Ch19: Mới ("tự chịu") → Ch22: ACTIVE, không đổi (Canon Update không nối dòng này với D-17) | ACTIVE | CANON_FACT | Ch19 §VI; Ch22 §VI |
| D-19 | Dịch → Ích Châu (Ôn, sĩ quan) | Mất cột và đoàn xe; thư Bàng bị nhắc công khai | Ch15 §VI | Ch15: mới, ACTIVE; Ch16–Ch18 không có dòng riêng | ACTIVE (theo dòng cuối Ch15) | CANON_FACT | Ch15 §VI |
| D-20 | Dịch → sĩ quan Ích Châu / Ích Châu | Để cột bại quân đi; cho kẻ thù cầm xô | Ch22 §VI | Ch22: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch22 §VI |
| D-21 | Dịch → người chết / phu / lạc (Ch15) | Quyết định cắt xe, đổi lương lấy người; danh sách tên người chết / lạc | Ch15 §VI | Ch15: ACTIVE, mới → Ch16: ACTIVE, nặng thêm (240 người chưa rõ; danh sách tên) → Ch17: ACTIVE (danh sách tên) → Ch19: ACTIVE (thêm một tên) → Ch22: ACTIVE (đếm lại hai lần) | ACTIVE | CANON_FACT | Ch15 §VI; Ch16 §VI; Ch17 §VI; Ch19 §VI; Ch22 §VI |
| D-22 | Dịch → làng (làng trưởng) | Phiếu nợ mang tên mình | Ch16 §VI | Ch16: mới; Ch17–Ch18 không có dòng | Mới (theo dòng cuối Ch16) | CANON_FACT | Ch16 §VI |
| D-23 | Dịch → người đã mở cửa; mọi nơi mở cửa sau | Lời hứa C1 (văn bản trong tay họ) | Ch19 §VI | Ch19: Mới, ACTIVE → Ch20: ACTIVE ("nay có ngai đứng tên") | ACTIVE (dòng kế tiếp: D-24) | CANON_FACT | Ch19 §VI; Ch20 §VI |
| D-24 | Dịch → hàng binh Hổ Lao | Lời hứa C1 thành của triều đình; không rút được | Ch22 §VI | Ch22: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch22 §VI |
| D-25 | Dịch → Kim Lăng / Vân Chương | Vượt quyền ân xá | Ch19 §VI | Ch19: Mới, ACTIVE → Ch20: "Chuyển trạng thái": Kim Lăng đã ôm hậu quả (Dịch chưa biết) → Ch21: không đổi (Dịch chưa biết) | ACTIVE (Dịch chưa biết, Ch21 §VI) | CANON_FACT | Ch19 §VI; Ch20 §VI; Ch21 §VI |
| D-26 | Dịch → Kim Lăng | Một nghi vấn không đáp (thuyền; sổ kho) | Ch22 §VI | Ch22: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch22 §VI |
| D-27 | Dịch → danh ("sứ Ích Châu", không "Tiêu"; tên trong chữ người khác) | Không đáp "họ Tiêu?"; chiếu có ấn | Ch22 §VI | Ch22: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch22 §VI |
| D-28 | Dịch → Chu Hạc / lính gác đêm | Lời hứa áo bông ("Ngày mai tôi sẽ nói") | Ch01 §VII | Ch1: chưa trả → Ch2: vẫn treo → Ch3: đã trả một phần (26/30), đóng | Đóng (Ch03 §VII) | CANON_FACT | Ch01 §VII; Ch02 §VII; Ch03 §VII |
| D-29 | Dịch → Tôn Đức | Cam kết lấy số xe Nam Môn | Ch01 §VII | Ch1: đang thực hiện → Ch3: Dịch vẫn ra Nam Môn mỗi tối (kết quả không nêu) | Đang thực hiện (Ch03 §VI; Ch04–Ch07 không cập nhật) | CANON_FACT | Ch01 §VII; Ch03 §VI |
| D-30 | Chiêu → cha (Hoắc Thành Lĩnh) | Chọn giữ quân thay vì chạy tới cha, và tới muộn | Ch06 §VI | Ch6: UNPAID | UNPAID (không cập nhật sau Ch06) | CANON_FACT | Ch06 §VI |
| D-31 | Chiêu → cha | Mũ trụ rơi vào tay giặc, được người khác trả lại | Ch10 §VI | Ch10: ACTIVE, không nói ra | ACTIVE, không nói ra (không cập nhật sau) | CANON_FACT | Ch10 §VI |
| D-32 | Chiêu → Hoắc gia quân | Binh phù, trách nhiệm | Ch06 §VI | Ch6: ACTIVE | ACTIVE (không cập nhật sau Ch06) | CANON_FACT | Ch06 §VI |
| D-33 | Chiêu → Hoắc quân | Người cước, người chết vì dải băng; một phần quân quay mặt đi | Ch10 §VI | Ch10: ACTIVE; Ch11–Ch13 không cập nhật | ACTIVE | CANON_FACT | Ch10 §VI |
| D-34 | Chiêu → Hoắc quân | Kỵ nhẹ hao | Ch17 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch17: mới | Mới | CANON_FACT | Ch17 §VI |
| D-35 | Chiêu → Uyển | Không làm được gì | Ch06 §VI | Ch6: UNPAID | UNPAID (không cập nhật sau Ch06) | CANON_FACT | Ch06 §VI |
| D-36 | Chiêu → Uyển | Nhận ơn từ bên kia sông | Ch10 §VI | Ch10: Mới, UNPAID; Ch12–Ch13 không có dòng cập nhật | UNPAID | CANON_FACT | Ch10 §VI |
| D-37 | Chiêu → Chu Hạc | Nợ chính danh bị hiểu sai (nàng tưởng mình nợ Chu Hạc sự ủng hộ), củng cố bằng niềm tin vào số liệu | Ch06 §VI | Ch6: Ẩn → Ch10: Ẩn | Ẩn | CANON_FACT | Ch06 §VI; Ch10 §VI |
| D-38 | Chiêu → A Quy | Hận bị hiểu sai (song song với nợ của Chỉ với Hoắc) | Ch06 §VI | Ch6: ACTIVE (dòng kế tiếp: D-39; Ch12 §VI không ghi gốc Ch06) | ACTIVE (Ch06 §VI) | CANON_FACT | Ch06 §VI |
| D-39 | Chiêu → A Quy | Kẻ bị truy mười năm ngồi cùng bàn; lời hoãn | Ch12 §VI | Ch12: ACTIVE → Ch13: "Hoãn, không tha; deadline mùa đông", ACTIVE | ACTIVE (Ch13 §VI; không có dòng sau) | CANON_FACT | Ch12 §VI; Ch13 §VI |
| D-40 | Chiêu → Dịch | Nhận vật tư chống rét; cất tờ kê, không nói | Ch13 §VI | Ch13: Mới, UNPAID | UNPAID (không cập nhật sau Ch13) | CANON_FACT | Ch13 §VI |
| D-41 | Chiêu → Dịch | Tin có điều kiện, đã được giữ (đèn lên đúng cọc, trong hương); chưa nói thành lời | Ch17 §VI | (Before chưa trích được; Canon Update không nối với D-40) → Ch17: chuyển động | Chuyển động | CANON_FACT | Ch17 §VI |
| D-42 | Chiêu → hội minh | Lui, quay lại tìm cột; mất bảy trăm → rút nửa quân vì chi phí, ở lại; cho hạn | Ch15 §VI | Ch15: mới, không gọi tên → Ch16: mới, không gọi tên (rút nửa, hạn); Ch17 không có dòng | Mới, không gọi tên (theo dòng cuối Ch16) | CANON_FACT | Ch15 §VI; Ch16 §VI |
| D-43 | Chiêu → Tiểu Thất | Chi phí tác chiến (người giữ hương / hạn chết khi chặn khe) | Ch17 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch17: mới; không dựng nhịp riêng | Mới | CANON_FACT | Ch17 §VI |
| D-44 | Bùi Chỉ → Hoắc Thành Lĩnh | Món nợ bị hiểu sai — niềm tin của Bùi Chỉ: Hoắc nợ Bùi gia một mạng | Ch02 §VII | Ch2: chưa đổi, "từ Ch2 bắt đầu lệch" → Ch3: không đổi, Chỉ vẫn thù Hoắc | Không đổi (Ch03 §VII); người tin: Bùi Chỉ | CANON_BELIEF | Ch02 §VII; Ch03 §VII |
| D-45 | Bùi Chỉ → Hoắc Thành Lĩnh | Món nợ bị hiểu sai — sự thật Canon Update ghi: Hoắc đã cứu Chỉ (xem RG-L-16) | Ch02 §VII | Ch2: chưa đổi → Ch3: không đổi | Không đổi (Ch03 §VII) | CANON_FACT | Ch02 §VII; Ch03 §VII |
| D-46 | Bùi Chỉ → Hoắc Tam Lang | Oán / hiềm (chưa phải nợ): "Kẻ đã bắt mình, mình đã làm bị thương" | Ch02 §VII | Ch2: chỉ ghi nhận, không ép thành subplot | Chỉ ghi nhận | CANON_FACT | Ch02 §VII |
| D-47 | Bùi Chỉ → Hoắc quân / biên bắc | Mười năm mang tiếng nội ứng; biết lời giải cũ thiếu một người | Ch11 §VI | Ch11: hận → nghi, ACTIVE | ACTIVE (không cập nhật sau Ch11) | CANON_FACT | Ch11 §VI |
| D-48 | Bùi Chỉ → Dịch | Dịch nói một điều thật về Bắc Môn; đêm ấy không có tiếng gọi lính; Chỉ "ghi nhận", chưa gọi tên | Ch11 §VI | Ch11: Mới, UNPAID; Ch12–Ch13 không có dòng cập nhật riêng | UNPAID | CANON_FACT | Ch11 §VI |
| D-49 | Chỉ → Dịch | Được cho vào bằng cửa trước, dưới bảo chứng của Ích Châu | Ch12 §VI | Ch12: Mới, UNPAID | UNPAID (không cập nhật sau Ch12) | CANON_FACT | Ch12 §VI |
| D-50 | Bùi Chỉ → Dạ Kiêu | Phá 2/3 nguyên tắc với đơn này; một mình quyết; người của hắn làm theo mà không được biết lý do | Ch11 §VI | Ch11: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch11 §VI |
| D-51 | Chỉ → bốn bên | Báo cho không, cùng một lời | Ch13 §VI | Ch13: Mới, ACTIVE | ACTIVE | CANON_FACT | Ch13 §VI |
| D-52 | Chỉ → Hoắc quân | Chưa trả lời; giữ im vì chưa thể nói chuyện rò | Ch14 §VI | (không có dòng trước; Canon ghi 'mới') → Ch14: ACTIVE, mới; Ch15–Ch22 không có dòng | ACTIVE (theo dòng cuối) | CANON_FACT | Ch14 §VI |
| D-53 | Chỉ → Vân Chương | Nhờ mở hai tuyến; chàng nhận không hỏi | Ch14 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch14: mới, không gọi tên; Ch15–Ch22 không có dòng | Mới, không gọi tên (theo dòng cuối) | CANON_FACT | Ch14 §VI |
| D-54a | Chỉ → Chính hắn (nghi rò tin) | Hai dòng "Kha Trọng" | Ch14 §VI | (Before chưa trích được) → Ch14: ACTIVE; Ch15–Ch22 không có dòng | ACTIVE | CANON_FACT | Ch14 §VI |
| D-54b | Chỉ → Chính hắn (nghi rò tin) | (nghi — hàng của Chỉ) nhãn "(nghi rò tin)" Canon gắn ở cột Đối tượng "Chính hắn"; Canon không nói "Chính hắn" là ai, không nói ai bị nghi rò tin | Ch14 §VI | (Before chưa trích được) → Ch14: nhãn "(nghi rò tin)" | Chưa xác nhận; Ch14 §III: Chỉ "Không biết: Ai rò". Nguồn rò (G-1, OP-076) và Kha Trọng (G-2, OP-077) là hai thread OPEN riêng, Canon chưa nối (Ch14 §II; Ch15 §0) | CANON_SUSPICION | Ch14 §II, §III, §VI; Ch15 §0 |
| D-55 | A Quy → Chiêu | Điều định nói, không nói | Ch13 §VI | Ch13: ACTIVE | ACTIVE (không cập nhật sau Ch13) | CANON_FACT | Ch13 §VI |
| D-56 | Vân Chương → Dịch | Bảo vệ / im lặng / trách nhiệm → [CANON CHANGE] "Ta đã có thể đi tìm để biết ngươi còn sống hay không. Ta đã chọn không đi." → "Viết 'người tự nhận' dù biết; không báo Dịch" | Ch04 §VII | Ch04: UNPAID (giữ thông tin có khả năng liên quan hoàng thất, không gửi về Tạ gia) → Ch05: "Trách nhiệm / bảo hộ chưa hoàn thành", nghĩa vụ tự nhận, Dịch không biết, UNPAID → Ch07: [CANON CHANGE] thay bằng "Ta đã có thể đi tìm… Ta đã chọn không đi." (Ch07 §VI: "Thay cho món nợ 'bảo hộ chưa hoàn thành' ở Ch5"; Dịch không biết; UNPAID) → Ch08: UNPAID, không đổi → Ch09: UNPAID, không đổi → Ch12: ACTIVE, không nói ra ("Chọn không tìm (Gate VC); nay chọn chưa công nhận") → Ch13: Mới, ACTIVE ("Viết 'người tự nhận' dù biết; không báo Dịch") → Ch14: ACTIVE, không đổi | ACTIVE (Ch14 §VI; không có dòng sau trong Ch15–Ch18) | CANON_FACT | Ch04 §VII; Ch05 §VII; Ch07 §VI; Ch08 §VI; Ch09 §VI; Ch12 §VI; Ch13 §VI; Ch14 §VI |
| D-57 | Vân Chương → Dịch | Chiếu nêu tên Dịch, không báo trước | Ch20 §VI | Ch20: Mới, ACTIVE → Ch21: ACTIVE, không đổi ("Không báo", D20-11) | ACTIVE | CANON_FACT | Ch20 §VI; Ch21 §VI |
| D-58 | Vân Chương → chính mình | Trách nhiệm đạo đức (đã chọn im lặng) | Ch04 §VII (động cơ cuối cùng chưa xác định) | Ch04: UNPAID | UNPAID (không cập nhật sau Ch04) | CANON_FACT | Ch04 §VII |
| D-59 | Vân Chương → chính mình | Không rời Kim Lăng | Ch20 §VI | Ch20: Mới, ACTIVE → Ch21: ACTIVE, nặng hơn ("ho nặng; bút rơi") | ACTIVE | CANON_FACT | Ch20 §VI; Ch21 §VI |
| D-60 | Vân Chương → Hoắc Thành Lĩnh / Vân Trung | Tội lỗi: bảy ngày im lặng (tầng trách nhiệm riêng của Vân Chương, tách khỏi phần của Tạ Diên) | Ch05 §VII | Ch5: UNPAID | UNPAID (không cập nhật sau Ch05) | CANON_FACT | Ch05 §VII |
| D-61 | Vân Chương → Uyển | Lừa bằng cớ vọng bái | Ch05 §VII | Ch5: UNPAID | UNPAID (không cập nhật sau Ch05) | CANON_FACT | Ch05 §VII |
| D-62 | Vân Chương → Uyển | Thư + gói vỏ quýt, không đáp | Ch20 §VI | (Before chưa trích được; Canon Update không nối với D-61) → Ch20: ACTIVE → Ch21: ACTIVE, không đổi | ACTIVE | CANON_FACT | Ch20 §VI; Ch21 §VI |
| D-63 | Vân Chương → phu xe, người hầu của đoàn | Không đưa được ra khỏi thành | Ch05 §VII | Ch5: UNPAID | UNPAID (không cập nhật sau Ch05) | CANON_FACT | Ch05 §VII |
| D-64 | Vân Chương → Tam Lang | Đã mở miệng rồi không nói | Ch05 §VII | Ch5: UNPAID (ghi nhận) | UNPAID (ghi nhận) | CANON_FACT | Ch05 §VII |
| D-65 | Vân Chương → quan huyện (vô danh) | Chiếu → cái chết (hai dòng, không nối nhân quả) | Ch20 §VI | Ch20: Mới, ACTIVE, không gọi tên → Ch21: ACTIVE, không đổi | ACTIVE | CANON_FACT | Ch20 §VI; Ch21 §VI |
| D-66 | Vân Chương → người mở cửa Dĩnh Xuyên | Chiếu xác nhận lời hứa | Ch20 §VI | Ch20: Mới, ACTIVE | ACTIVE (không cập nhật sau Ch20) | CANON_FACT | Ch20 §VI |
| D-67 | Vân Chương → liên quân | Dùng họ mà không nói (điều (2), lịch lương không giải thích) | Ch21 §VI | Ch21: Mới, ACTIVE → Ch22: không đổi (Ch22 không POV) | ACTIVE | CANON_FACT | Ch21 §VI; Ch22 §VI |
| D-68 | Vân Chương → tướng giữ Hổ Lao (vô danh) | Nhận bằng chữ một điều có thể không giữ được | Ch21 §VI | Ch21: Mới, ACTIVE → Ch22: không đổi | ACTIVE | CANON_FACT | Ch21 §VI; Ch22 §VI |
| D-69 | Vân Chương → thủy quân / phó tướng | Đặt thuyền neo ngang sông, không biết bên kia đọc ra sao | Ch21 §VI | Ch21: Mới, ACTIVE → Ch22: không đổi | ACTIVE | CANON_FACT | Ch21 §VI; Ch22 §VI |
| D-70 | Vân Chương → Kim Lăng | Lương thật xuất kho (nửa tháng); thất bại thì liên minh tan | Ch21 §VI | Ch21: Mới, ACTIVE → Ch22: không đổi | ACTIVE | CANON_FACT | Ch21 §VI; Ch22 §VI |
| D-71 | Uyển → Vân Chương | Chén vỏ quýt; gói vỏ quýt đi sau; câu chàng không hỏi | Ch13 §VI (callback Ch4); Ch18 §V | Ch13: ACTIVE, không gọi tên → Ch18: ACTIVE, không gọi tên | ACTIVE, không gọi tên (Ch18 §VI) | CANON_FACT | Ch13 §VI; Ch18 §V, §VI |
| D-72 | Uyển → bộ nhỏ | Oán thật do luật của nàng (nửa giá) | Ch18 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch18: mới, ACTIVE | ACTIVE | CANON_FACT | Ch18 §VI |
| D-73 | Uyển → Hách Liên Chước | Cớ trao tay | Ch18 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch18: mới, ACTIVE | ACTIVE | CANON_FACT | Ch18 §VI |
| D-74 | Uyển → người chết (thương nhân Hán; Tu Bặc Cốt) | Hai mạng vì luật | Ch18 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch18: mới | Mới | CANON_FACT | Ch18 §VI |
| D-75 | Uyển → ông già sứ | Ông ngồi xa lửa | Ch18 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch18: mới (không giải) | Mới | CANON_FACT | Ch18 §VI |
| D-76 | Tiêu Uyển → lính gác | Không ghi thành nợ (hành động hoàn trả áo không tạo ra món nợ) | Ch03 §VII | — | Không phát sinh nợ | CANON_FACT | Ch03 §VII |
| D-77 | Hoắc Thành Lĩnh → Bùi gia / Bùi Chỉ | Tội lỗi (Hoắc tự mang, không nói; "Sự thật": bị ép vây phủ, đã xin tha, đã để cửa sau mở); giữ mạng, bó chân Chỉ là một phần món nợ | Ch02 §VII | Ch2: chưa trả → Ch3: chưa trả; đặt tên cho Chỉ cũng là một phần, không được giải thích | Chưa trả theo Ch03 §VII; Canon Update Ch06 ghi Hoắc đã chết (Ch06 §I.20) nhưng không cập nhật dòng nợ này | CANON_FACT | Ch02 §VII; Ch03 §VII; Ch06 §I.20 |
| D-78 | Phùng thúc → Dịch [BÍ DANH CHƯA XÁC NHẬN — xem RG-L-05 (= CB-L-01)] | Trách nhiệm bảo hộ | Ch01 §VII ("Chưa hiển thị nguồn gốc") | Ch1: ẩn; không cập nhật dòng này trong Ch2–Ch7 (Ch07 §VI có dòng riêng D-10) | Ẩn | CANON_FACT | Ch01 §VII |
| D-79 | Dịch → Hàn / bộ Ích Châu | Cho họ đứng một đêm trên đê không che | Ch22 §VI | (không có dòng trước; Canon ghi 'Mới') → Ch22: Mới, ACTIVE (Canon Update không nối với D-15) | ACTIVE | CANON_FACT | Ch22 §VI |

---

## D. PLANNING / NON-CANON

> **Toàn bộ mục D là PLANNING_NON_CANON.** Không bảng nào ở D là canon; không dùng D để trả lời "truyện đã nói gì". Mục D không giải quyết mâu thuẫn nào (chỉ trỏ sang mục E).
> D1 = các `PLAN: ChX` do **Canon Update** ghi ở cột Payoff dự kiến (tách khỏi bảng A). D2 = kế hoạch **chép từ Chapter Bible / Production Bible** (chỉ những điểm văn bản nêu rõ). D3 = author-truth / ràng buộc Ch23+ mà Canon Update ghi là **không lên trang**. D4 = nợ cảm xúc chỉ có ở mức planning, hoặc phần PLAN gắn vào nợ đã có ở C.
> Source: `ChNN §…` = Canon Update (đang ghi lại kế hoạch); `CB ChNN` = `bible/CHAPTER_BIBLE_32_CHUONG.txt`; `PB Seed N` / `PB Ch31–32` = `bible/PRODUCTION_BIBLE.txt`.
> Chapter Bible / Production Bible xếp **dưới** Canon Update (LOCKED) về ưu tiên. Chỗ CB/PB không khớp canon đã khóa chỉ được trỏ sang E; Registry không chọn bên.

### D1. PLAN do Canon Update ghi (khóa theo ID seed ở mục A)

Chép nguyên nhãn "Payoff dự kiến" của Canon Update (`PLAN: …`). Không phải payoff đã xảy ra. Registry này dựng đến Ch22; chưa có Canon Update cho chương đích Ch23+ nên không dòng nào ở D1 là "đã trả".

| ID seed | Seed | PLAN (Canon Update ghi) | Source Type | Source |
|---|---|---|---|---|
| S-001 | Bắc Môn / "cửa mở từ bên trong" | PLAN: Ch6, Ch28, Ch32 (Ch01 §IV); PLAN: Ch28 (Ch06 §V); PLAN: Ch21, Ch28 (Ch19 §V); PLAN: Ch28 (Ch21 §V, Ch22 §V) | PLANNING_NON_CANON | Ch01 §IV; Ch06 §V; Ch19 §V; Ch21 §V; Ch22 §V |
| S-002 | Then mới | PLAN: "Chưa khóa (liên quan Ch6, Ch11)" (Ch01 §IV); PLAN: Ch14, Ch26 (Ch11 §V) | PLANNING_NON_CANON | Ch01 §IV; Ch11 §V |
| S-003 | Chu Hạc | PLAN: Ch26–31 (Ch01 §IV, Ch02 §IV, Ch03 §IV) | PLANNING_NON_CANON | Ch01 §IV; Ch02 §IV; Ch03 §IV |
| S-004 | Hụt lương có quy luật | PLAN: "Chưa khóa (tuyến Vân Trung bị làm yếu)" (Ch01 §IV); Ch04 §VIII.1 ghi author-truth tuyến lương cần khóa (xem D3) | PLANNING_NON_CANON | Ch01 §IV; Ch04 §VIII.1 |
| S-005 | Thiếu giấy báo hao | PLAN: "Chưa khóa" (Ch01 §IV) | PLANNING_NON_CANON | Ch01 §IV |
| S-008 | Bàn cờ bị bỏ lại / quân cờ (tiền seed) | PLAN: Ch3, Ch32 (Ch01 §IV; áp cho phần quân cờ, xem S-029) | PLANNING_NON_CANON | Ch01 §IV |
| S-009 | Hoắc Tam Lang (clue thân phận) | PLAN: Ch6, Ch31 (Ch01 §IV) | PLANNING_NON_CANON | Ch01 §IV |
| S-010 | Uyển: nhường đường, giữ đội hình | PLAN: Ch18, Ch25 (Ch01 §IV) | PLANNING_NON_CANON | Ch01 §IV |
| S-011 | Tiếng ho → Sức khỏe Vân Chương (Seed 9) | PLAN: "Seed 9 (giới hạn thời gian của Vân Chương)" (Ch01 §IV); "Giới hạn thời gian" (Ch03 §IV, Ch04 §IV); PLAN: Ch27 (Ch20 §V, Ch21 §V) | PLANNING_NON_CANON | Ch01 §IV; Ch03 §IV; Ch04 §IV; Ch20 §V; Ch21 §V |
| S-012 | Phùng thúc cúi quá thấp | PLAN: Ch4, Ch8 (Ch01 §IV; Ch03 §IV); PLAN: Ch8 (Ch04 §IV, Ch07 §V) | PLANNING_NON_CANON | Ch01 §IV; Ch03 §IV; Ch04 §IV; Ch07 §V |
| S-013 | Đoàn hòa thân mắc lại vì Hắc Sơn tắc tuyết | PLAN: "Ch5–6 phải giải thích kỵ binh Bắc Nhung đi đường nào" (Ch01 §IV) | PLANNING_NON_CANON | Ch01 §IV |
| S-014 | Tuyết | PLAN: "Ký ức chung, Ch32" (Ch01 §IV) | PLANNING_NON_CANON | Ch01 §IV |
| S-016 | Chu Hạc biết mặt Chỉ | PLAN: Ch6 (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-017 | Hoắc giữ Chỉ ngoài sổ | PLAN: Ch6 "lời chứng của Chu Hạc có nền" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-018 | Vết bớt sau tai Chỉ | PLAN: Ch26 (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-019 | Cửa sau phủ Bùi / "Ta ở đó" | PLAN: Ch6, Ch26 (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-020 | "Có người kéo hắn ra" | PLAN: Ch26 (chưa khóa danh tính) (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-021 | Tam Lang–Chỉ chạm mặt lần đầu | PLAN: Ch6 "Chiêu nhận mặt Chỉ" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-022 | Hoắc thức ở thư phòng | PLAN: "Chưa khóa" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-023 | Chỉ biết nhìn thời tiết, chờ tuyết | PLAN: "Năng lực của Chỉ về sau" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-024 | Vết thương tay Tam Lang | "Có thể dùng làm fair-play ở Ch3, không bắt buộc, không thành subplot" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-025 | Bát cháo / bó chân | PLAN: "Bất thường của Hoắc" (Ch02 §IV) | PLANNING_NON_CANON | Ch02 §IV |
| S-027 | Lòng thù Hoắc của Chỉ | PLAN: Ch26 (Ch03 §IV) | PLANNING_NON_CANON | Ch03 §IV |
| S-029 | Quân trắng (Seed 1) | PLAN: Ch10 / Ch12 / Ch13 / Ch32 (Ch03 §IV; Ch07 §V) | PLANNING_NON_CANON | Ch03 §IV; Ch07 §V |
| S-030 | Quân của A Quy, hắn tự nhặt | PLAN: Ch32 (Ch03 §IV) | PLANNING_NON_CANON | Ch03 §IV |
| S-031 | Quân của Tam Lang để lại trên bàn | PLAN: "Ch4 hoặc muộn hơn" (Ch03 §IV) — đã đóng ở Ch4 theo Ch04 §IV (xem A) | PLANNING_NON_CANON | Ch03 §IV |
| S-032 | Tên A Quy | PLAN: Ch26–32 (Ch03 §IV) | PLANNING_NON_CANON | Ch03 §IV |
| S-033 | Tay áo Dịch | PLAN: Ch4 (Ch03 §IV) — đã đóng ở Ch4 theo Ch04 §IV (xem A) | PLANNING_NON_CANON | Ch03 §IV |
| S-034 | Hắc Hà đóng băng | PLAN: Ch5–6 (Ch03 §IV) | PLANNING_NON_CANON | Ch03 §IV |
| S-038 | Uyển–Vân Chương | PLAN: Ch18, Ch24–25 (Ch03 §IV; Ch04 §IV) | PLANNING_NON_CANON | Ch03 §IV; Ch04 §IV |
| S-041 | Luật giữ lượt (Canon Ch3) | PLAN: Ch18, Ch25, Ch32 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-042 | A Quy ngồi quay lưng vào tường | PLAN: Ch32 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-043 | Vết sẹo trên tay Chiêu | PLAN: Ch26 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-044 | Vải bông trong tờ kê | PLAN: Ch31 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-046 | Vân Chương tin về thân phận Dịch | PLAN: Ch28 (Ch04 §IV) | PLANNING_NON_CANON | Ch04 §IV |
| S-047 | Chữ "Huệ" / khuyết bút | PLAN: "Có thể payoff chính danh ở Ch8" (Ch04 §IV) | PLANNING_NON_CANON | Ch04 §IV |
| S-048 | Vân Chương giấu cha (đốt thư) | PLAN: Ch5–6, Ch28 (Ch04 §IV) | PLANNING_NON_CANON | Ch04 §IV |
| S-049 | Vân Chương biết Dịch dựng lại lượng tồn kho | PLAN: Ch5 (Ch04 §IV) | PLANNING_NON_CANON | Ch04 §IV |
| S-050 | Thư Tạ Diên, "một chỗ chỉ hai cha con biết đọc" | PLAN: Ch5 (Ch04 §IV); PLAN: Ch28 (Ch05 §IV) | PLANNING_NON_CANON | Ch04 §IV; Ch05 §IV |
| S-056a | Thuốc vỏ quýt / thư ngắn + gói vỏ quýt | PLAN: Ch24, Ch28 (Ch13 §V); PLAN: Ch20, Ch24, Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch13 §V; Ch18 §V |
| S-057 | Lá thư viết dở gửi Hoắc | PLAN: Ch6 / Ch28 (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-058 | Bảy ngày giữ kín | PLAN: Ch6, Ch28 (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-059 | Bộ sử 12 quyển / mật mã cha con | PLAN: Ch28 ("có thể") (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-060 | Lời mời hai lần | PLAN: Ch6/7, Ch11 (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-061 | Phu xe đoàn ở lại dịch quán | PLAN: Ch6 "nếu cần" (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-063 | Lệnh "không được vào" | PLAN: Ch6 (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-064 | Tùy tùng ở ngoài Nam Môn | PLAN: "Có thể dùng ở Ch6. Chưa khóa" (Ch05 §IV) | PLANNING_NON_CANON | Ch05 §IV |
| S-065 | Câu hỏi về pháo | PLAN: Ch6 (Ch05 §IV) — đã trả theo Ch06 §V (xem A) | PLANNING_NON_CANON | Ch05 §IV |
| S-066 | Âm thanh phía bắc | PLAN: Ch6 (Ch05 §IV) — payoff ghi ở Ch07 §V (xem RG-L-07) | PLANNING_NON_CANON | Ch05 §IV |
| S-067 | Chu Hạc công khai trao chính danh | PLAN: Ch29 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-069 | "A Chiêu" | PLAN: Ch31 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-070 | Xác lính gác trẻ; "trực ở đây"; áo bông kép | PLAN: Ch11, Ch26 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-071 | Phòng củi trống, khóa mở | PLAN: Ch26 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-072 | Xác thích khách Bắc Nhung | PLAN: Ch26 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-073 | A Quy bị quy là nội ứng | PLAN: Ch11, Ch26 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-074 | "Bắt sống" | PLAN: Ch11, Ch26 (Ch06 §V) | PLANNING_NON_CANON | Ch06 §V |
| S-079 | "Cửa mở từ bên trong. Hai người khiêng then." | PLAN: Ch11, Ch26, Ch28 (Ch07 §V); PLAN: Ch26, Ch29 (Ch11 §V) | PLANNING_NON_CANON | Ch07 §V; Ch11 §V |
| S-080 | "Không ai bắt. Nàng tự đi." | PLAN: Ch12–13 (gặp lại Uyển) (Ch07 §V); PLAN: Ch13, Ch18 (Ch12 §V) | PLANNING_NON_CANON | Ch07 §V; Ch12 §V |
| S-081 | Thứ tự: ngừng đốt → thả dân → nàng đi | PLAN: "Khi Dịch hiểu Uyển" (Ch07 §V) | PLANNING_NON_CANON | Ch07 §V |
| S-082 | Lời đồn A Quy không khớp nhau | PLAN: Ch11, Ch26 (Ch07 §V) | PLANNING_NON_CANON | Ch07 §V |
| S-083 | Bọc vải của Phùng thúc | PLAN: Ch8 (thân phận) (Ch07 §V) — đã đóng ở Ch08 §V (xem A) | PLANNING_NON_CANON | Ch07 §V |
| S-084 | Ba câu của Phùng thúc | PLAN: Ch8 (Ch07 §V) | PLANNING_NON_CANON | Ch07 §V |
| S-085 | "Thẩm thư lại" mất tích/chết | PLAN: Ch8 (tin của Vân Chương) (Ch07 §V) | PLANNING_NON_CANON | Ch07 §V |
| S-087 | "Vân Chương về Kim Lăng" | PLAN: Ch8 (P-13) (Ch07 §V "Chuyển sang Ch8") — đã payoff ở Ch08 §V (xem A) | PLANNING_NON_CANON | Ch07 §V |
| S-088 | Khóa trường mệnh | PLAN: Ch9 trở đi; Ch32 (Ch08 §V) | PLANNING_NON_CANON | Ch08 §V |
| S-094a | Luồng tin phía tây về "tung tích Thất hoàng tử" | PLAN: Ch9 / Ch15–16 (Ch08 §V) | PLANNING_NON_CANON | Ch08 §V |
| S-095a | Sứ của Hạ Hầu ở ải Tây | PLAN: Ch9 (Ch08 §V) | PLANNING_NON_CANON | Ch08 §V |
| S-097 | Dịch nghe tên Tạ Vân Chương | PLAN: Ch12 (Ch08 §V) | PLANNING_NON_CANON | Ch08 §V |
| S-099 | Quyền kho hành chính có giới hạn | PLAN: Ch9 (Ch08 §V) | PLANNING_NON_CANON | Ch08 §V |
| S-100 | Ôn nghiêng người | PLAN: Ch9 (Ôn đứng về đâu) (Ch08 §V); "Về sau" (Ch09 §V) | PLANNING_NON_CANON | Ch08 §V; Ch09 §V |
| S-103 | U — Dịch biết gì về Uyển | PLAN: Ch18, Ch25 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-104 | "Hoắc Tam Lang vẫn giữ Hắc Hà." (hook Ch9) | PLAN: Ch10 (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-105 | Hàn: đồng minh quân sự rạn; "Chưa." | PLAN: Ch15–16 (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-106 | "Không ai ăn được huyết thống." | PLAN: Ch19, Ch28, Ch32 (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-107 | Người thật ở ải Tây được cấp đủ lương | PLAN: "Quân tâm về sau" (không ghi chương) (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-108 | Hai câu mồi trong thư | PLAN: Ch15–16 (Ch09 §V); author-truth B3 "mồi" xem D3 | PLANNING_NON_CANON | Ch09 §II, §V |
| S-109 | Thư Bàng / hồi âm chỉ lương gửi Bàng | PLAN: Ch15 (Ch09 §V); PLAN: Ch16, Ch19 (Ch15 §V); PLAN: Ch19 (Bàng đáp) (Ch16 §V) | PLANNING_NON_CANON | Ch09 §V; Ch15 §V; Ch16 §V |
| S-110a | Tiết tướng quân | PLAN: "Sau" (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-111 | Quyền kiểm kê ba huyện | PLAN: Ch10+ (POV Dịch kế tiếp) (Ch09 §V) | PLANNING_NON_CANON | Ch09 §V |
| S-112 | Hạ Hầu đọc thói quen hậu cần | PLAN: Ch19, Ch22 (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-113a | Tờ nhất thư Bàng / "Việc kia" | PLAN: Ch20+ (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-114 | Quân cờ trắng của Khả đôn trên mép bàn | PLAN: Ch18, Ch25, Ch32 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-115 | Quan hệ Chiêu–Uyển | PLAN: Ch12, Ch18, Ch25 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-116 | Thư Chu Hạc | PLAN: Ch29 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-117 | Bắc Nhung chia phe | PLAN: Ch18, Ch25 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-118 | Khương lão tướng muốn lui; tướng trẻ muốn đánh | PLAN: Ch29 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-119 | Mũ trụ lông đen được trả lại | PLAN: Ch31 (Ch10 §V) | PLANNING_NON_CANON | Ch10 §V |
| S-121 | Hách Liên Chước có cớ, tập hợp quân | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-122 | Luật mùa cỏ, giếng, chợ biên | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-123 | "Khả đôn nói thay người Hán" | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-124 | Ông già sứ ngồi ngoài vòng lửa | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-125 | Chiêu làm mồi bằng mũ trụ | PLAN: Ch18, Ch22 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-126 | Câu khóa "hai người… chỉ có một" | PLAN: Ch26, Ch29 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-127 | Kết luận "một người" của Dạ Kiêu sụp | PLAN: Ch14, Ch26 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-128 | "Ta không thấy mặt." | PLAN: Ch26 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-129b | Không có tiếng gọi lính | PLAN: quan hệ Chỉ–Dịch Ch12–Ch14; động cơ chỉ mở khi có Gate (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-130 | Bạc khuôn vảy cá; tiền bị trả | PLAN: Ch14–Ch16 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-131 | "Sẽ có người khác tới" | PLAN: Ch12+ (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-132b | Chỉ phá nguyên tắc 2, 3 với đơn này | "Uy tín với trung gian; quan hệ trong Dạ Kiêu" (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-134 | Sổ trực gác | PLAN: Ch14, Ch29 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-135 | Hook "Ai đã có mặt ở Bắc Môn đêm ấy?" | PLAN: Ch14, Ch26 (Ch11 §V) | PLANNING_NON_CANON | Ch11 §V |
| S-136 | Thỏa thuận thăm dò Lạc Thủy | PLAN: Ch15+ (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-137 | "Người hứa là Hoắc Chiêu." | PLAN: Ch31 (tên trên mộ), Ch32 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-138 | Thư gửi Ôn giữ chữ "Hoắc quân" | PLAN: Ch31 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-139 | "Hết cuộc gặp này." | PLAN: Ch13, Ch14 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-140 | A Quy nói lời của Dạ Kiêu; lý do thật không nói | PLAN: Ch13, Ch14 (Ch12 §V); lý do thật = author-truth, xem D3 | PLANNING_NON_CANON | Ch12 §II, §V |
| S-141 | Người lạ đếm thuyền | PLAN: Ch13 hook, Ch14 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-142 | "Kim Lăng chưa công nhận ai." / "đợi thấy việc" | PLAN: Ch20, Ch21 (Ch12 §V; Ch15 §V) | PLANNING_NON_CANON | Ch12 §V; Ch15 §V |
| S-143 | Uyển vắng Bắc cảnh | PLAN: Ch18 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-144 | Mức ảnh hưởng của Uyển | PLAN: Ch18, Ch25 (Ch12 §V) | PLANNING_NON_CANON | Ch12 §V |
| S-145 | Uyển bị cô lập | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-146 | Lời hứa mùa đông của Khả đôn hết khi băng tan | PLAN: Ch18 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-147 | Dịch hiểu Ch12 ("mỗi bên đứng một mình") | PLAN: Ch16 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-148 | Hoắc quân rút nửa, hạn ba tuần / Hạn Chiêu | PLAN: Ch17, Ch18 (Ch16 §V); PLAN: Ch18 (Ch17 §V) | PLANNING_NON_CANON | Ch16 §V; Ch17 §V |
| S-149 | Ôn đóng ấn có mức tối đa / nợ muối vượt trần / "ấn tới sau" | PLAN: Ch17+, Ch24 (Ch16 §V); Ch24 (Ch17 §V; Ch19 §V; Ch22 §II-A, §IX) | PLANNING_NON_CANON | Ch16 §V; Ch17 §V; Ch19 §V; Ch22 §II-A, §IX |
| S-150 | Kim Lăng ghi "chở lương đường sông cho liên quân" | PLAN: Ch19, Ch24 (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-151 | Bảy chuyến thuyền đỏ chở lương → chở bộ | PLAN: Ch19, Ch22 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-152 | "Không văn thư" → rò tin bên trong | PLAN: Ch14 (Ch13 §V); "Mở rộng Ch15+" (Ch14 §V) | PLANNING_NON_CANON | Ch13 §V; Ch14 §V |
| S-153 | Đường dây quán nước → người bán củi → Lạc Kinh | PLAN: Ch14 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-154 | Hai con ngựa về Kim Lăng | PLAN: Ch20, Ch21 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-155 | "Người tự nhận" trong thư Vân Chương | PLAN: Ch20, Ch21, Ch28 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-156a | Viên quan Kim Lăng gửi không hỏi (K2) | PLAN: K2 "khi có Gate" (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-157a | Lệnh bắt A Quy | PLAN: Ch14–Ch16 (Ch13 §V); PLAN: Ch17 (Ch15 §V); "sau Ch17" (Ch17 §V) | PLANNING_NON_CANON | Ch13 §V; Ch15 §V; Ch17 §V |
| S-158 | "Đêm ấy…" | PLAN: Ch24, Ch31 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-159 | Câu Vân Chương không hỏi Uyển | PLAN: Ch18, Ch24 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-160 | Dạ Kiêu báo cho không bốn bên | PLAN: Ch14, Ch32 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-162a | Vân Chương có thể phải phản bội Dịch | PLAN: Ch20, Ch28 (Ch13 §V) | PLANNING_NON_CANON | Ch13 §V |
| S-163 | Nợ lương của Dịch với Hoắc quân | PLAN: Ch17, Ch24 (Ch15 §V); Ch24 (Ch16 §V) | PLANNING_NON_CANON | Ch15 §V; Ch16 §V |
| S-164 | Mua lương dân bằng muối/vải/phiếu | PLAN: Ch19 (cam kết không trả thù), Ch22 (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-166 | Kha Trọng (G-2) | PLAN: Ch15–Ch17 (tìm), Ch26, Ch29 (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-167 | Lời đồn lão Kha / phủ lớn họ Tạ | PLAN: Ch20+, Ch26, Ch29 (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-168 | Đường văn thư – trạm ngựa có lỗ (G-1) / đường trạm hở dùng có chủ ý | PLAN: Ch15+, Ch20, Ch21 (Ch14 §V); PLAN: Ch21 (thông tin giả) (Ch20 §V); PLAN: Ch22 (Ch21 §V) | PLANNING_NON_CANON | Ch14 §V; Ch20 §V; Ch21 §V |
| S-169 | Hoắc quân chờ lời đáp của Chỉ | PLAN: Ch15–Ch16 (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-170 | Vân Chương nhận hai chỗ hẹn | PLAN: Ch20, Ch28 (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-171 | Hai người lạ ở miếu / trạm Thạch Kiều | PLAN: Ch15+ (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-172 | Cơ chế "năm điểm hẹn" | "Có thể tái dụng Ch21" (Ch14 §V) | PLANNING_NON_CANON | Ch14 §V |
| S-175 | Hạ Hầu đánh đường, không đánh thành | PLAN: Ch16, Ch17, Ch19, Ch22 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-177 | "Người trước, lương sau" | PLAN: Ch19, Ch30 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-178 | Nghi "ai biết cột đi hướng nào" | PLAN: Ch16, Ch20, Ch21 (Ch15 §V); PLAN: Ch20, Ch21 (Ch16 §V, Ch17 §V) | PLANNING_NON_CANON | Ch15 §V; Ch16 §V; Ch17 §V |
| S-179 | Hàn bị thương | PLAN: Ch16+ (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-180 | Nghi binh không ai đuổi | PLAN: Ch16 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-181 | Hai bến | PLAN: Ch16 (Ch15 §V) | PLANNING_NON_CANON | Ch15 §V |
| S-183 | Sĩ quan Ích Châu xin về | PLAN: Ch20 (uy tín) (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-184 | "Có hay không, đường lương cũng phải đổi" | PLAN: Ch20, Ch21 (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-186 | Dĩnh Xuyên | PLAN: Ch17 (Ch16 §V); PLAN: Ch19 (Ch17 §V) | PLANNING_NON_CANON | Ch16 §V; Ch17 §V |
| S-187 | Hạ Hầu mua lương dân → mua ngựa | PLAN: Ch18 (Uyển cắt tiếp tế) (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-188 | Từ chối thắng nhỏ bằng số (200 người) | PLAN: Ch30 (Ch16 §V) | PLANNING_NON_CANON | Ch16 §V |
| S-189 | Dịch nói "Không" / "Ta không biết" | PLAN: Ch19 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-190 | Hạ Hầu chuyển từ chủ động sang phản ứng | PLAN: Ch19+, Ch22 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-191 | Hàn nhận trách nhiệm gửi bộ | PLAN: Ch20 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-192 | Tháp hiệu | PLAN: Ch22 (phối hợp Dịch–Chiêu) (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-193 | Nén hương / ống hương | PLAN: Ch18 (Ch17 §V) | PLANNING_NON_CANON | Ch17 §V |
| S-194 | Nén bạc có dấu | PLAN: Ch25+ (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-195 | Bộ nhỏ nhận nửa giá | PLAN: Ch25 (Ch18 §V) | PLANNING_NON_CANON | Ch18 §V |
| S-196 | "Ai mở cửa, không bị hỏi tội" | PLAN: Ch28, Ch32 (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-197 | Thư Bàng "đo bằng xe" | PLAN: Ch21–22 (Bàng đổi cách đo: OPEN) (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-198 | Lời hứa vượt quyền | PLAN: Ch20 (Ch19 §V); PLAN: Ch22–24 (Dịch/Ôn phản ứng) (Ch20 §V) | PLANNING_NON_CANON | Ch19 §V; Ch20 §V |
| S-199 | Hàng binh sống | PLAN: Ch22 (Ch19 §V); PLAN: Ch23+ (Ch22 §V) | PLANNING_NON_CANON | Ch19 §V; Ch22 §V |
| S-200 | Chiêu không ký; kỵ nhẹ ngoài thành | PLAN: Ch20+ (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-201 | "Để hắn có một con số" | PLAN: Ch21 (thông tin giả) (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-202 | Tờ giấy dán trên cổng (Dĩnh Xuyên) | PLAN: Ch28 (Ch19 §V) | PLANNING_NON_CANON | Ch19 §V |
| S-203 | Ấu đế đặt tay lên ấn | PLAN: Ch23, Ch28, Ch32 (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-204 | Chiếu nêu "sứ Ích Châu Trình Dịch" | PLAN: Ch22–24 (Ch20 §V); PLAN: Ch23, Ch28, Ch32 (Ch22 §V) | PLANNING_NON_CANON | Ch20 §V; Ch22 §V |
| S-205 | Ấn tước phải có người chứng; Vân Chương không rời | PLAN: Ch23, Ch28 (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-206a | Thư xin hàng Hổ Lao | PLAN: Ch21 (Trá Hàng) (Ch20 §V); PLAN: Ch22–23 (Ch21 §V) | PLANNING_NON_CANON | Ch20 §V; Ch21 §V |
| S-207 | Hạn "kể từ ngày chiếu tới" | PLAN: Ch21–22 (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-208a | Quan huyện đọc chiếu rồi bị xử | PLAN: Ch21+ (động cơ OPEN) (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-209 | Ông áo tía không hài lòng | PLAN: Ch23, Ch28 (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-210 | Hôn thư tướng râu quai nón – ngoại thích | PLAN: Ch23 (nếu cần) (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-211 | Thư riêng theo chức | PLAN: Ch21 (Ch20 §V) | PLANNING_NON_CANON | Ch20 §V |
| S-212 | Tờ xin ra tuyến trước | PLAN: Ch23, Ch27 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-213 | Điều (2) | PLAN: Ch23 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-214 | Thư đáp ngoài sổ | PLAN: Ch23, Ch28 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-215 | Lịch lương | PLAN: Ch22 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-216 | Lương thật xuất kho | PLAN: Ch22 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-217 | "Một lời" vs "năm lời" | PLAN: Ch22+ (G-1 OPEN) (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-218 | "Nghỉ một đêm ở nhà trạm của quân" | PLAN: Ch22–23 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-219 | Thuyền neo ngang sông | PLAN: Ch22 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-220 | "Cổng thành mở." | PLAN: Ch22; motif cửa → Ch28 (Ch21 §V) | PLANNING_NON_CANON | Ch21 §V |
| S-222 | Lời hứa C1 / chiếu "xác nhận" | PLAN: Ch23, Ch28, Ch32 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-223 | Danh: "sứ Ích Châu" / "họ Tiêu" | PLAN: Ch23, Ch28, Ch32 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-224 | Phó tướng nhận công; sổ kho | PLAN: Ch23 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-225 | "Thuyền sao không vào bến?" | PLAN: Ch23 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-226 | Cột bại quân + nhóm đi bờ phía tây | PLAN: Ch28 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-227 | Ai "hợp lệ" cai trị Hổ Lao | PLAN: Ch23 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-228 | Tướng giữ thành Hổ Lao "không thấy" | PLAN: Ch23+ (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-229 | "Quá mềm" | PLAN: Ch23–24 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-231 | Thuyền Kim Lăng chở bộ / "Ngoài lương?" | PLAN: Ch23 (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |
| S-232 | Chiếu có ấn / Dịch chỉ có chữ ký | PLAN: Ch23, Ch24 ("ấn tới sau") (Ch22 §V) | PLANNING_NON_CANON | Ch22 §V |

### D2. Kế hoạch chép từ Production Bible (Seed 1–10, Ch31–32) và Chapter Bible (Ch22–32)

Chỉ chép điều văn bản CB/PB **nêu rõ**. Cột "Chủ đề gần trong A/B/C" là chỉ mục tra cứu của Registry (CB/PB không tự gắn ID); không phải claim của CB/PB. Mọi dòng: PLANNING_NON_CANON.

| ID | Kế hoạch (CB/PB ghi) | Chủ đề gần trong A/B/C | Source Type | Source |
|---|---|---|---|---|
| D2-01 | Seed 1 Quân cờ trắng: xuất hiện Ch3, "Năm người giữ". Payoff Ch32: "Chỉ đặt quân cờ. Dịch nhìn bàn cờ." | S-029; S-114; S-041 | PLANNING_NON_CANON | PB Seed 1 |
| D2-02 | Seed 2 Bắc Môn: xuất hiện Ch1, "Dấu hiệu bất thường". Payoff Ch28: "Lạc Kinh mở từ bên trong." | S-001; S-002; S-079 | PLANNING_NON_CANON | PB Seed 2 |
| D2-03 | Seed 3 Hoắc Tam Lang: xuất hiện Ch1. Payoff Ch31: "Hoắc Chiêu." | S-009; S-104 | PLANNING_NON_CANON | PB Seed 3 |
| D2-04 | Seed 4 Chính danh của Dịch: xuất hiện Ch8. Payoff Ch32: "Đăng cơ." | S-088 | PLANNING_NON_CANON | PB Seed 4 |
| D2-05 | Seed 5 Dấu vết sau tai của Chỉ: xuất hiện Ch2. Payoff: "Khi sự thật Bùi gia được xác nhận." (không ghi chương) | S-018 | PLANNING_NON_CANON | PB Seed 5 |
| D2-06 | Seed 6 Tấu chương của Hoắc Thành Lĩnh: "Xuất hiện dưới dạng dấu vết." Payoff Ch26: "Chứng minh ông từng xin giảm tội cho Bùi gia." | D-77; D-45 | PLANNING_NON_CANON | PB Seed 6 |
| D2-07 | Seed 7 Chu Hạc có quyền kiểm soát Bắc Môn. Payoff Ch26–29: "Reveal mạng lưới." | S-003; OP-050; OP-024 | PLANNING_NON_CANON | PB Seed 7 |
| D2-08 | Seed 8 Tạ gia có liên hệ Bắc Nhung. Payoff: "Sự thật Vân Trung." (không ghi chương) | S-050; OP-015b | PLANNING_NON_CANON | PB Seed 8 |
| D2-09 | Seed 9 Sức khỏe Vân Chương: "Không dùng chỉ để tạo thương cảm." Payoff: "Giới hạn thời gian của Vân Chương. Ảnh hưởng trực tiếp tới các quyết định cuối." | S-011 | PLANNING_NON_CANON | PB Seed 9 |
| D2-10 | Seed 10 Uyển có ảnh hưởng thực sự ở Bắc Nhung. Payoff: "Nhạn Môn. Sau khi cô chết, cục diện Bắc Nhung thay đổi." | S-103; S-144; S-145; S-117 | PLANNING_NON_CANON | PB Seed 10 |
| D2-11 | PB Ch31 "Hoắc Chiêu": Dịch đề nghị phong hậu; Chiêu từ chối; "Chiêu lựa chọn chết"; yêu cầu "Chu Hạc phải chết"; tên trên mộ "Hoắc Chiêu"; cái chết "yên tĩnh"; sau đó Dịch "không lập tức đăng cơ". | D-37; S-009; S-105 | PLANNING_NON_CANON | PB Ch31 (mục X) |
| D2-12 | PB Ch32 "Đăng cơ": Dịch lên ngôi; Bùi gia "được minh oan"; Hoắc Thành Lĩnh "được phục danh"; Uyển "được truy phong"; Hoắc Chiêu "được ghi đúng tên". | S-088; D-77; D-45 | PLANNING_NON_CANON | PB Ch32 (mục X) |
| D2-13 | CB Ch22 "Lạc Kinh" (POV Dịch): "Liên minh đánh chiếm Lạc Kinh"; New Information "Lạc Kinh đã nằm trong tay liên minh"; Power Shift "Lạc Kinh đổi chủ"; Ending Hook "Một đạo chiếu từ Kim Lăng xuất hiện." Payoff → Ch23, Ch28, Ch32. **Trỏ sang RG-L-26 (không khớp ràng buộc L1).** | S-001; OP-124 | PLANNING_NON_CANON | CB Ch22 |
| D2-14 | CB Ch23 "Người thắng cuối cùng" (POV Vân Chương): "Dịch bị bắt"; Vân Chương dùng tiểu hoàng đế "tước quyền các đồng minh"; "Chỉ trở thành người cứu Dịch"; Seed: "Vân Chương sẽ phải trả giá"; Hook "Chỉ mở cửa nhà giam. Dịch bước ra." | D-56; D-57; D-23 | PLANNING_NON_CANON | CB Ch23 |
| D2-15 | CB Ch24 "Lời mời" (POV Uyển): Vân Chương muốn Uyển "dẫn quân Bắc Nhung về phía có lợi cho trật tự mới"; "Uyển vẫn nhận nhiệm vụ"; Hidden: "Vân Chương không nói hết kế hoạch"; Hook "Quân Bắc Nhung tiến về Nhạn Môn." Payoff → Ch25, Ch28. | D-71; S-038; S-056a | PLANNING_NON_CANON | CB Ch24 |
| D2-16 | CB Ch25 "Nhạn Môn" (POV Chiêu): "Cho Uyển chết"; "Hách Liên bị đánh tan nhưng Uyển chết"; "Cái chết của Uyển làm Bắc Nhung mất cân bằng"; Hook "Chiêu nhận tin Vân Chương đã rời Lạc Kinh." **Hook trỏ sang RG-L-27.** | S-117; S-145; OP-108 | PLANNING_NON_CANON | CB Ch25 |
| D2-17 | CB Ch26 "Kho Tạ gia" (POV Chỉ): New Information gồm "Lệnh diệt Bùi gia nằm trong tay Tạ Diên"; "Hoắc Thành Lĩnh từng xin tha"; "Tạ Diên liên quan Bắc Nhung"; "Chu Hạc nhận vàng"; "Vân Chương biết một phần sự thật"; Hook "Chỉ nhìn tên Vân Chương trong một tài liệu liên quan." | D-77; D-45; OP-050; OP-006 | PLANNING_NON_CANON | CB Ch26 |
| D2-18 | CB Ch27 "Người sắp chết" (POV Chỉ): Vân Chương thú nhận; "Chỉ không giết Vân Chương"; New Information "Vân Chương biết Bắc Môn sẽ mở", "đã lựa chọn cứu Uyển thay vì cảnh báo Hoắc"; Hook "Đưa thứ này cho Dịch." | D-56; D-48 | PLANNING_NON_CANON | CB Ch27 |
| D2-19 | CB Ch28 "Cửa mở từ bên trong" (POV Dịch): "Tiểu hoàng đế thoái vị"; "Vân Chương chết lúc mặt trời mọc"; "Lạc Kinh mở cửa từ bên trong"; Dịch "không cảnh báo Chiêu"; Seed Payoff "Bắc Môn → Lạc Kinh". | S-001; S-079; S-002 | PLANNING_NON_CANON | CB Ch28 |
| D2-20 | CB Ch29 "Chu Hạc" (POV Chiêu): "Chiêu bắt Chu Hạc nhưng không giết ngay"; New Information "Chu Hạc không phải đại phản diện"; Power Shift "Chu Hạc trốn thoát và bán mình cho triều đình mới"; Hook "Chu Hạc mang theo thông tin về bố trí quân Hoắc." | S-003; OP-050; D-37 | PLANNING_NON_CANON | CB Ch29 |
| D2-21 | CB Ch30 "Tịnh Châu" (POV Dịch): Dịch dùng thông tin Chu Hạc cung cấp "để đánh vào điểm yếu"; Hook "Chiêu bị áp giải về trước mặt Dịch." | S-003; D-04 | PLANNING_NON_CANON | CB Ch30 |
| D2-22 | CB Ch31 "Một đêm, hai cái tên" (POV Chiêu): "Chiêu chọn chết để đổi lấy đại xá cho quân Hoắc"; điều kiện "Chu Hạc phải chết", "Bia mộ ghi tên Hoắc Chiêu"; Key line "Làm hoàng hậu của ngươi thì Hoắc Chiêu chết. Chết thế này, ta vẫn là ta." | S-009; D-37 | PLANNING_NON_CANON | CB Ch31 |
| D2-23 | CB Ch32 "Bàn cờ trắng" (POV Dịch): Dịch đăng cơ; minh oan Bùi gia; truy phong Hoắc Thành Lĩnh; ghi nhận Hoắc Chiêu; tưởng niệm Tiêu Uyển; "Quân cờ trắng → Chỉ đặt quân cuối cùng"; "Không cần thêm mystery mới." | S-029; S-114; S-018 | PLANNING_NON_CANON | CB Ch32 |

### D3. Author-truth / ràng buộc Ch23+ (Canon Update ghi là KHÔNG lên trang)

Mỗi dòng là điều Canon Update ghi là author-truth, ràng buộc kế hoạch, hoặc quyết định chưa lên trang. Trên trang các OPEN tương ứng vẫn là CANON_UNKNOWN (mục B). Cột "Gắn với" là OPEN/seed ở B/A trỏ tới dòng này. ID D3 là ID của Registry này; thứ tự theo chương nguồn, không theo mức quan trọng.

| ID | Author-truth / ràng buộc (Canon Update ghi) | Gắn với | Source Type | Source |
|---|---|---|---|---|
| D3-01 | Motif "thanh mai trúc mã" (Production Bible): Ch01 ghi CHƯA KHÓA; Ch03 ghi "đã quyết không dùng". | — | PLANNING_NON_CANON | Ch01 §II; Ch03 §VIII |
| D3-02 | Đề xuất sửa Chapter Bible Ch6: "Hoắc Tam Lang tiếp nhận quyền lãnh đạo Hoắc gia quân" (thay "Chiêu trở thành Hoắc Tam Lang"); Ch01 ghi chờ duyệt; Ch02/Ch03/Ch05 ghi "treo từ Ch1"; Canon Update Ch06 không ghi trạng thái duyệt. | S-009 | PLANNING_NON_CANON | Ch01 §II; Ch03 §VIII; Ch05 §VIII.7; Ch06 §I.24, §I.28 |
| D3-03 | Lý do Hoắc thức ở thư phòng đêm Ch2: quân báo Hắc Hà do Tam Lang mang về (truyện chưa nói; nếu nói thì dùng đúng nguyên nhân này). | OP-010 | PLANNING_NON_CANON | Ch02 §II |
| D3-04 | Tuyến lương: ai rút lương, tám xe đi đâu, ai báo tin, liên hệ Bắc Môn — Canon Update ghi "phải khóa ít nhất một dòng trước Scene Bible Ch5"; Ch05–Ch07 Canon Update không ghi đã khóa. Seed "Hụt lương có quy luật" cũng ghi "Chưa khóa (tuyến Vân Trung bị làm yếu)". | OP-001; OP-002; S-004 | PLANNING_NON_CANON | Ch04 §VIII.1; Ch01 §IV |
| D3-05 | Vân Chương ở lại Vân Trung ít nhất vài ngày sau mùng một (đã khóa author-truth; trên trang vẫn OPEN "ở đâu đêm ấy"). | OP-034 | PLANNING_NON_CANON | Ch07 §IV, §IX |
| D3-06 | "LOCKED: Phương án C" theo Gate trước Ch8: Vân Chương "không chắc; chủ động không tìm; không can thiệp hồ sơ" (nhận tin gì về Dịch). | D-56; S-087 | PLANNING_NON_CANON | Ch07 §III, §IX |
| D3-07 | Lý do Ôn nghiêng người / không tự tay cầm thư: author-truth, "không diễn giải" trên trang. | OP-042b | PLANNING_NON_CANON | Ch09 §II |
| D3-08 | Hai câu mồi trong thư: trong văn bản chỉ là điều Dịch và Phùng Bảo đoán; author-truth ghi là mồi (B3). | S-108 | PLANNING_NON_CANON | Ch09 §II, §V |
| D3-09 | Suy luận riêng của Dịch về Bắc Môn mười năm (D1 trong Canon Update Ch11): không lên trang, không xác nhận Chu Hạc. | OP-046 | PLANNING_NON_CANON | Ch11 §II |
| D3-10 | K1 (phía Hạ Hầu) là author-truth về người giao Dạ Kiêu nhiệm vụ; Chỉ không biết. | OP-053 | PLANNING_NON_CANON | Ch11 §II–III |
| D3-11 | Lý do thật A Quy chỉ nói lời của Dạ Kiêu: author-truth, không lên trang. | S-140 | PLANNING_NON_CANON | Ch12 §II |
| D3-12 | Hướng rò tin (Ch13 §II, §IX; Chapter Bible Ch14): tuyến thông tin dẫn về "người từng phục vụ Tạ gia", không chỉ Chu Hạc; "OPEN tới Gate Ch14". | OP-070; OP-086; OP-108 | PLANNING_NON_CANON | Ch13 §II, §IX; CB Ch14 |
| D3-13 | Chapter Bible Ch14 "Năm tin giả" (POV Chỉ): Chỉ tung năm tin giả qua năm đường khác nhau; hook "Một cái tên từ mười năm trước xuất hiện." Canon Update Ch13 chuyển các câu hỏi (năm đường là gì, ở đâu/khi nào, ai bị nghi, cái tên) sang Gate Ch14. | OP-075; S-174 | PLANNING_NON_CANON | Ch13 §IX; CB Ch14 |
| D3-14 | "Ai nuôi, dạy Chỉ; nguồn gốc Dạ Kiêu; ai trả tiền nuôi Chỉ những năm đầu; thư phòng Hoắc–Chỉ": Ch01 ghi "phải giải quyết trước Ch11"; Ch11 ghi "trước Ch26". Trên trang vẫn OPEN. | OP-006; OP-108 | PLANNING_NON_CANON | Ch01 §IX; Ch10 §IX; Ch11 §II, §IX |
| D3-15 | Thư Hổ Lao là "thật"; tướng giữ thành "không phải nội gián"; Bàng "không điều khiển/ép/sai" tướng; người đưa thư "không biết thư bị chép". Canon Update ghi "Cấm twist 'thư giả'". | OP-113b; S-206b | PLANNING_NON_CANON | Ch21 §II-B |
| D3-16 | Cách người bên kia biết: thư "bị chép trên chặng qua đất Hạ Hầu"; thư tới Vân Chương "nguyên vẹn". | OP-119 | PLANNING_NON_CANON | Ch21 §II-B |
| D3-17 | Bàng "học quá kỹ": đọc lệnh lương gấp ba và thuyền neo ngang sông như thuyền quân; "sai đúng một điểm: thuyền lần này thật sự chỉ chở lương". | OP-088b; OP-130 | PLANNING_NON_CANON | Ch21 §II-B; Ch22 §II-B |
| D3-18 | Counterfactual: bỏ rò Ch14 / Kha Trọng / K2 / A Quy / Dạ Kiêu thì quyết định của Bàng "không đổi". | OP-070; OP-086 | PLANNING_NON_CANON | Ch21 §II-B |
| D3-19 | Vị trí không thể rút: Ch22 "không là chiến công của Vân Chương". | OP-128 | PLANNING_NON_CANON | Ch21 §II-B |
| D3-20 | Ba điều kiện của thư xin hàng (Gate Ch20): ân xá đúng chữ chiếu; giữ binh giữ chức, không giao binh người ngoài; tờ phong tước như chiếu. Nay đã lên trang ở Ch21 §I.2 (xem OP-113a). | OP-113a | PLANNING_NON_CANON | Ch20 §II, §IX; Ch21 §0 |
| D3-21 | L1 (Lạc Kinh): thành Lạc Kinh chưa chiếm; Dịch chỉ thực sự tiến vào Lạc Kinh ở Ch28; "Cấm viết Lạc Kinh đã đổi chủ/mở cổng ở Ch23–27". Trỏ sang RG-L-26, RG-L-27. | OP-124 | PLANNING_NON_CANON | Ch22 §II-B |
| D3-22 | L2 / GR22-H1 (HARD): Dịch chỉ biết lịch lương; mọi chiến thuật là Dịch tự đọc, có thể sai, trả giá. | OP-130 | PLANNING_NON_CANON | Ch22 §II-B |
| D3-23 | D22-8: Bàng không lên trang Ch22; số phận người giữ thành OPEN; nếu trả thì phải qua vật/hành động. | OP-125 | PLANNING_NON_CANON | Ch22 §II-B |
| D3-24 | D21-4 = b: Bàng "tự ra lệnh mở cổng" ("mở ≠ đầu hàng"). | OP-118b | PLANNING_NON_CANON | Ch21 §II-B |
| D3-25 | Địa lý Hổ Lao (Gate §3): thành chính (cổng đê ở đông; cổng tây chưa lên trang) + khu đầu bến (cổng bến; cổng nối). "Chỉ các phần nêu ở mục I là canon trang." | OP-118b | PLANNING_NON_CANON | Ch22 §II-B |
| D3-26 | Mục tiêu kế hoạch theo Production Bible: Tạ Diên "mục tiêu là Dịch"? Thư có nhắc tìm Dịch không (Canon Update Ch04 ghi là kế hoạch, câu hỏi OPEN). | OP-015b | PLANNING_NON_CANON | Ch04 §VIII.3 |
| D3-27 | Cách Bàng đọc đường lương: author-truth (Gate Ch15 mục 4), không lên trang; trên trang Dịch thấy hai đường trùng nhau, không kết luận. | OP-085 | PLANNING_NON_CANON | Ch15 §II; Ch17 §II |

### D4. Nợ cảm xúc ở mức planning (hoặc phần PLAN gắn vào nợ đã có ở C)

| ID | Cặp (A → B) | Nội dung planning | Gắn với (C) | Source Type | Source |
|---|---|---|---|---|---|
| D4-01 | Tạ Diên → Vân Chương | "Cứu con bằng cách để cả thành chết" — nợ của người cha, ghi "author-level", UNPAID. Không có dòng tương ứng ở C. | — | PLANNING_NON_CANON | Ch05 §VII |
| D4-02 | Chiêu → Chu Hạc | Nợ chính danh bị hiểu sai: Canon Update gắn nhãn "tới Ch29" (PLAN: Ch29). Phần fact (trạng thái Ẩn) ở C. | D-37 | PLANNING_NON_CANON | Ch06 §VI; Ch10 §VI |
| D4-03 | Chiêu (cost) | Cost theo Chapter Bible Ch6 (đã đổi): "mất người cuối cùng gọi nàng bằng tên thật"; "Hoắc Tam Lang" là danh phận duy nhất nàng có thể công khai sống bằng. Canon Update không ghi trạng thái. | — | PLANNING_NON_CANON | Ch06 §VI; CB Ch06 (qua Ch06 §VI) |
| D4-04 | Dịch → những người đã tin mình | Production Bible: "Dịch nợ những người đã tin mình"; Ch7 là điểm bắt đầu. | — | PLANNING_NON_CANON | Ch07 §VI |
| D4-05 | Vân Chương → Dịch | Nợ sau [CANON CHANGE] ("Ta đã có thể đi tìm … Ta đã chọn không đi."): Canon Update Ch07 ghi "mở rõ ở Ch13" (PLAN: Ch13). Phần fact ở C. | D-56 | PLANNING_NON_CANON | Ch07 §VI |

### D5. Chỗ Chapter Bible / Production Bible không khớp canon đã khóa — chỉ trỏ, không giải quyết

| ID | Chỗ lệch | Trỏ sang E | Source Type | Source |
|---|---|---|---|---|
| D5-01 | CB Ch22 ("Lạc Kinh đã nằm trong tay liên minh"; "Lạc Kinh đổi chủ") ↔ ràng buộc L1 ("thành Lạc Kinh chưa chiếm"; vào Lạc Kinh ở Ch28; Production Bible Seed 2 cũng đặt "Lạc Kinh mở từ bên trong" ở Ch28). | RG-L-26 | PLANNING_NON_CANON | CB Ch22; PB Seed 2; Ch22 §II-B |
| D5-02 | CB Ch25 hook ("Vân Chương đã rời Lạc Kinh") ↔ L1 và Ch22 §IX (ghi "hook Ch25 — Chapter Bible; lưu ý L1"). | RG-L-27 | PLANNING_NON_CANON | CB Ch25; Ch22 §II-B, §IX |
| D5-03 | Mối nối Lạc Kinh Chapter Bible Ch22 ("Lạc Kinh đã nằm trong tay liên minh") ↔ Ch28 ("Dịch tiến vào Lạc Kinh" / "Lạc Kinh mở cửa từ bên trong") — Ch21 §II-A, §IX ghi "Gate Ch22/Ch23 phải xử lý" (chuyển từ OP-124). CB Ch22 / Ch25 viết Lạc Kinh ở Ch22–25; Canon Update Ch22 §0 ghi Lạc Kinh không lên trang Ch22. | OP-124; RG-L-26 | PLANNING_NON_CANON | CB Ch22; Ch21 §II-A, §IX; Ch22 §0 |

---

## E. MÂU THUẪN / LỆCH

> Mọi dòng: **CHƯA QUYẾT — chờ chị**. Registry chỉ chỉ ra chỗ lệch, **không chọn bên, không đề xuất đáp án**. "Cách đọc A / B" chỉ nêu hai cách đọc mà Canon Update cho phép, không xếp hạng. Trích mỗi bên ≤ 20 từ. "Type A / Type B" = Source Type của từng bên (đúng một trong 6 giá trị; không dùng `—`). Bên là câu kế hoạch được gắn nhãn `[PLANNING_NON_CANON]` ngay trong ô. ID có tiền tố `RG-L-`; "(= CB-L-xx / TL-L-xx)" = cùng chỗ lệch được ghi ở CHARACTER_BIBLE_DERIVED.md / MASTER_TIMELINE_DERIVED_Ch1-Ch22.md (đối chiếu theo nội dung).
> Lệch có cả hai bên là canon-với-canon, lệch kế hoạch-với-trang, và lệch giữa các văn bản planning. Nhãn trạng thái (UNPAID / ACTIVE / Mới / Ẩn …) đổi giữa các chương không tính là mâu thuẫn; xem GHI CHÚ ĐỘ TIN CẬY.

| ID | Nội dung lệch | Bên A (nguồn + trích) | Bên B (nguồn + trích) | Type A | Type B | Trạng thái |
|---|---|---|---|---|---|---|
| RG-L-01 | Chương gieo của seed motif "cửa" (S-001) | Ch01 §IV: Bắc Môn "cửa mở từ bên trong" gieo ở Ch01 | Ch22 §V ghi chuỗi "Ch6 → Ch19 → Ch21 → Ch22"; Ch19 §V ghi gieo Ch19 | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-02 | Số người khiêng then Bắc Môn (S-002) (= CB-L-06) | Ch01 §I.9: "gỗ sồi đen bọc sắt, hai người khiêng" | Ch06 §I.48: "Bốn lính khiêng then đặt lại vào khung." (Ch07 §I.2 ghi hai bóng người nhấc then) | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-03 | Nhà / bàn cờ của Dịch có cháy không (S-008, OP-037) (= CB-L-04; = TL-L-21) | Ch07 §I (P-09): "Dãy nhà sát tường bắc cháy sạch." | Ch07 §II: "Bàn cờ và căn nhà có thật sự cháy hay không (Dịch không tận mắt thấy)." (Ch07 §IV: "theo lời đồn và P-09") | CANON_FACT | CANON_UNKNOWN | CHƯA QUYẾT — chờ chị |
| RG-L-04 | Ngày nhận áo bông (S-015) (= CB-L-07; = TL-L-05) | Ch03 §I.52: "Đêm ngày 5… Nhận 26 bộ áo" | Ch03 §V: "Ngày 9: 26 bộ áo lên tường thành" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-05 | Phùng thúc = Phùng Bảo (S-047) (= CB-L-01) | Ch04 §I.9: "Sau khi rời cung, Phùng Bảo sửa thói quen này." | Ch04 §II: "Phùng thúc là Phùng Bảo trong nhận thức của Vân Chương" — không phải Canon | CANON_FACT | CANON_BELIEF | CHƯA QUYẾT — chờ chị |
| RG-L-06 | Cùng nhãn P-11 cho hai mục khác nhau (S-054) (= TL-L-22) | Ch03 §II: "P-11 (Lang Nha đóng): không phải Canon" | Ch04 §IV: "Tay áo ở S4 (P-11)" | CANON_UNKNOWN | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-07 | Chương payoff của "Âm thanh phía bắc" (S-066) | [PLANNING_NON_CANON] Ch05 §IV: "Payoff dự kiến Ch6" | Ch07 §V: "Đã payoff (hai POV nghe cùng một âm thanh)"; Canon Update Ch06 không có mục này | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-08 | "Tướng kỳ họ Hoắc" trả payoff nhưng không có dòng gieo (S-068) | Ch06 §V: "Payoff đã trả: tướng kỳ họ Hoắc (Ch1)" | (vắng mặt — không phải một claim) Canon Update Ch01 không có mục nào về tướng kỳ; Ch01 không ghi gieo | CANON_FACT | CANON_UNKNOWN | CHƯA QUYẾT — chờ chị |
| RG-L-09 | Đường tin lọt khỏi phòng kín (S-090) (= TL-L-07) | [PLANNING_NON_CANON] Ch08 §VII: "thương hộ có đường buôn phía tây" (author-truth, không dựng trong Ch8) | Ch09 §I.20, §VII: Hàn nhắn miệng qua viên quản lương, ngày 3. Cùng điểm: Ch09 §0 ghi "viên quản lương về ải ngày 4… Khớp" với Timeline Ch8; Ch08 §VII không có dòng này | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-10 | Cách gọi hạn ngày 31 (S-148) (= CB-L-15; = TL-L-14) | Ch16 §IV: "hạn: hết ba tuần kể từ hội ngày 10 (còn hai ngày)" | Ch17 §I.1: "hạn Ích Châu hết ngày ba mươi mốt, còn hai ngày" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-11 | "Ấn Thứ sử" của Ôn (S-149) (= CB-L-26) | Ch16 §I.16: "Ấn Thứ sử tới sau. Ba tuần." | Ch16 §I.31: "Thư Ôn… ấn đóng ở đầu" (Canon Update không ghi rõ đồng nhất hay không) | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-12 | Seed "mua lương dân → mua ngựa" (S-187) (= CB-L-18) | Ch18 §V: "Đóng một phần" | Ch18 §0: trên trang không nêu "Hạ Hầu"/"Tây Lương" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-13 | "Thông tin giả" kế hoạch Ch19–Ch20 vs nội dung Ch21 (S-201) | [PLANNING_NON_CANON] Ch19 §V và Ch20 §V: PLAN "Ch21 (thông tin giả)" | Ch21 §0: "Vân Chương gửi một lời — và lời ấy là thật." (Ch21 §IX: "Thông tin giả nhiều tầng (Ch21; không dùng ở Ch20)") | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-14 | Hook Ch21 "Cổng thành mở." vs cổng ở Ch22 (S-220) (= TL-L-18) | Ch21 §V: seed "Cổng thành mở." ([PLANNING_NON_CANON] payoff dự kiến Ch22) | Ch22 §0: không câu "cổng thành", "thành mở", "tự mở"; chỉ cổng bến (Ch22 §V ghi PAYOFF Ch22) | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-15 | Nội dung thư Tạ Diên: kế hoạch rộng hơn trang (OP-015a) | [PLANNING_NON_CANON] Ch04 §VIII.2 (kế hoạch Chapter Bible Ch5): "có người bên trong phối hợp; Tạ gia có liên quan" | Ch05 §I.5: mười chữ "Trừ tịch. Tý. Bắc. Môn. Bất quan…" (Ch05 §III: Vân Chương SUY LUẬN hai ý kia, không từ thư) | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-16 | Ai cứu Chỉ đêm phủ Bùi (D-45) | Ch02 §VII: "Sự thật: Hoắc đã cứu Chỉ" | Ch02 §II: danh tính người đã kéo Chỉ ra khỏi chỗ nhìn trộm "(không khóa)". Cách đọc A: "cứu" và "kéo ra" là hai việc; cách đọc B: cùng một việc. | CANON_FACT | CANON_UNKNOWN | CHƯA QUYẾT — chờ chị |
| RG-L-17 | Tầng xác nhận thân phận Dịch (= CB-L-02; = TL-L-20) | Ch01 §IX: "Tiêu Dịch: 17 tuổi ở Ch1" | Ch04 §II: "Dịch là Thất hoàng tử… Canon Ch4 không xác nhận." | CANON_FACT | CANON_UNKNOWN | CHƯA QUYẾT — chờ chị |
| RG-L-18 | Giờ tin "công chúa đã về thành" (S-080 "Không ai bắt. Nàng tự đi.") (= TL-L-04) | Ch06 §I.37: "Gần cuối giờ Dần: tin 'công chúa đã về thành'…" | Ch07 §I.19–25: "Gần cuối giờ Sửu… 'Công chúa về thành rồi!'" (Ch07 §0 ghi "Khớp") | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-19 | Chuyến hụt lương thứ mấy (S-004) (= TL-L-03) | Ch01 §V: "Tháng Chín: chuyến thứ tư của tháng thiếu hai xe" | Ch01 §I.5: "Bốn chuyến (thứ 3, 5, 7, 9)" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-20 | Khoảng cách Lạc Kinh thất thủ → Ch8 ngày 1 (= CB-L-09; = TL-L-01) | Ch08 §VII: "trước ngày 1 khoảng 10–14 ngày" | Ch10 §VII / Ch11 §VII: "Đầu tháng Ba" (thất thủ); "Cuối tháng Ba" (Ch8 ngày 1) | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-21 | Ch9 ngày 24 so với "giữa tháng Tư" (= CB-L-11; = TL-L-02) | Ch11 §VII: "Cuối tháng Ba → giữa tháng Tư" cho Ch8 (ngày 1–14) → Ch9 (ngày 14–24) | Ch10 §VII: "Cuối tháng Ba" cho Ch8 ngày 1; Ch9 ghi "Ch8 ngày 24" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-22 | Ôn "giữ" thư (= CB-L-08; = TL-L-08) | Ch08 §IV: "Phong thư… Ôn giữ, chưa mở" | Ch09 §I.1: "Ôn không nhận thư bằng tay" | CANON_FACT | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-23 | Kha Trọng: PLAN "tìm" vs trang (S-168; OP-077) | [PLANNING_NON_CANON] Ch14 §V: Payoff "Ch15–Ch17 (tìm), Ch26, Ch29" | Ch15 §0: "không chữ nào nối rò Ch14…"; Ch16 §II, Ch17 §II: Kha Trọng giữ OPEN | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-24 | "Hoắc quân chờ lời đáp": PLAN vs Chỉ vắng | [PLANNING_NON_CANON] Ch14 §V: Payoff "Ch15–Ch16" | Ch15 §III, Ch16 §III: Chỉ không xuất hiện | PLANNING_NON_CANON | CANON_FACT | CHƯA QUYẾT — chờ chị |
| RG-L-25 | Chương payoff của thư xin hàng Hổ Lao (S-206a/b) | [PLANNING_NON_CANON] Ch20 §V: payoff "Ch21" (Trá Hàng) | Ch21 §V: thư "Đã đáp"; [PLANNING_NON_CANON] payoff "Ch22–23" | PLANNING_NON_CANON | PLANNING_NON_CANON | CHƯA QUYẾT — chờ chị |
| RG-L-26 | Lạc Kinh đã bị chiếm ở Ch22 hay chưa (mối nối CB Ch22 ↔ Ch28) | [PLANNING_NON_CANON] Ch21 §IX: Chapter Bible Ch22 "Lạc Kinh đã nằm trong tay liên minh" ↔ Ch28 "Lạc Kinh mở cửa từ bên trong" (chi tiết: D5-01, D5-03) | [PLANNING_NON_CANON] Ch22 §II-B L1: "thành Lạc Kinh chưa bị chiếm; Dịch chỉ thực sự tiến vào Lạc Kinh ở Ch28" | PLANNING_NON_CANON | PLANNING_NON_CANON | CHƯA QUYẾT — chờ chị |
| RG-L-27 | Hook Chapter Bible Ch25 (Lạc Kinh) vs L1 | [PLANNING_NON_CANON] Hook Chapter Bible Ch25 về Lạc Kinh (nguyên văn và nguồn CB: xem D2-16, D5-02) | [PLANNING_NON_CANON] Ch22 §IX nhắc dòng này kèm "lưu ý L1"; Ch22 §II-B L1: Lạc Kinh chưa chiếm, Ch23–27 cấm viết đã đổi chủ. Cách đọc A: "Lạc Kinh" ở hook chỉ nơi Vân Chương đang ở; cách đọc B: hook và L1 chưa được đối chiếu với nhau. | PLANNING_NON_CANON | PLANNING_NON_CANON | CHƯA QUYẾT — chờ chị |
| RG-L-28 | Ch21: "thư riêng đã tới tay người giữ chức" là FACT hay suy luận của Vân Chương (OP-115a, S-211b) (= CB-L-20) | Ch21 §I.4: "thư riêng đã tới tay người giữ chức" (narration nêu như dữ kiện); Ch21 §0: "xác nhận OPEN Ch20 'tới tay ai', chỉ ở mức Hổ Lao"; Ch21 §III cột FACT cũng liệt kê | Ch21 §III (Vân Chương): "INFERENCE (một mức): 'Thư riêng đã tới tay người giữ chức'" | CANON_FACT | CANON_SUSPICION | CHƯA QUYẾT — chờ chị |

---

## GHI CHÚ ĐỘ TIN CẬY

**Cách dựng.** Gộp từ 4 file staging (Ch01–07, Ch08–13, Ch14–18, Ch19–22), mỗi file do một agent trích từ `canon/CCLT_Canon_Update_ChNN.md`. Phần planning (mục D2, D5) đọc trực tiếp từ `bible/CHAPTER_BIBLE_32_CHUONG.txt` (Ch22–32) và `bible/PRODUCTION_BIBLE.txt` (Seed 1–10, Ch31–32). Đã qua Consistency Check ba file Derived và QA 30 claim (vòng 1; 10 dòng của file này được bốc, 3 dòng lỗi: S-092b, D-54b, OP-121b — đã sửa vòng 1). Chưa đối chiếu lại từng dòng với Canon Update gốc ngoài các chỗ trích và các chỗ sửa ghi ở NHẬT KÝ SỬA VÒNG 1.

**Quy tắc gộp đã áp dụng**
- Không nâng/hạ Source Type. Ô staging mang hai Source Type được tách thành hai dòng `a` / `b` (A, B) hoặc thành bảng riêng (D).
- `PLAN: ChX` ở bảng A chuyển hết sang D1; author-truth ở bảng B chuyển sang D3 và chỉ để lại con trỏ.
- Seed trùng tên giữa các dải được gộp một dòng (Gieo = chương gieo sớm nhất; Reinforce nối các chương). Chỉ gộp khi cùng tên seed theo Canon Update.
- Chuỗi before → after nối qua các dải; chỗ không khớp không tự sửa, ghi ở E.
- "Không cập nhật sau ChNN" = Canon Update các chương sau không có dòng; không suy ra trạng thái mới.

**Chỗ kém chắc nhất**
1. **Source Type của "lời đồn" và niềm tin**: từ vòng sửa 1, lời đồn / "NGHE / THUẬT LẠI" chưa xác nhận → CANON_SUSPICION (S-082, S-094a, S-167); suy đoán của nhân vật → CANON_SUSPICION (S-178, S-211b, OP-115a, D-54b). S-096 ("Lời đồn sai 'Tam Lang tử trận'") giữ CANON_FACT vì Canon Update đã đính chính và đóng (Ch09 §I.32; Ch10 §V) — claim của dòng là "lời đồn đã được chứng là sai". Nhãn ở RG-L-05, RG-L-06, RG-L-17 do Registry gán theo mục Canon Update ("không phải canon" → UNKNOWN; "nhận thức của X" → BELIEF); chưa có người kiểm.
2. **Ghép hook → payoff không có dòng riêng**: "Hoắc Tam Lang vẫn giữ Hắc Hà" (hook Ch9) → payoff ở Ch10 chỉ qua dòng "lời đồn" (S-104); OP-075 (năm tin giả / cái tên hook Ch14) không có dòng đóng ở staging Ch14–18; Ch14–22 staging không đối chiếu ngược Canon Update Ch01–13.
3. **Gom chuỗi nợ và nhân vật**: các nợ Dịch → Tam Lang / A Quy / Chiêu (D-01…D-04), Dịch → Hoắc quân gộp ba chương; "Phùng thúc = Phùng Bảo" (RG-L-05) không gộp: D-10/D-78 (Phùng thúc) và D-11 (Phùng Bảo) là các dòng riêng, không nối chuỗi; chủ nợ giữ đúng cột "Người | Đối tượng" của Canon Update, không đảo chiều.
4. **Nhãn trạng thái nợ không đồng nhất** giữa các Canon Update (UNPAID ↔ ACTIVE ↔ Mới ↔ Ẩn; vd D-06 Ch07 UNPAID → Ch12 ACTIVE, không nêu lý do). Registry không quy đổi.
5. **Mức (Core/Major/…) và Gieo** chép theo bảng Registry của chương gieo; một số seed gieo ở chương nằm ngoài dải đã đọc (Ch6, Ch9, Ch13 trong staging Ch19–22) nên cột Gieo theo nhãn Canon Update, không đối chiếu ngược.
6. **Mục D2 / D5 chỉ chép điều CB/PB nêu rõ**; cột "Chủ đề gần trong A/B/C" là chỉ mục của Registry, không phải claim của CB/PB. CB và canon đã khóa không khớp ở RG-L-26, RG-L-27; Registry không chọn bên.

**Không có trong file này:** payoff/deadline tự đặt; đáp án cho bất kỳ OPEN nào; quy đổi nhãn; planning nào ngoài CB/PB và các `PLAN`/author-truth do Canon Update tự ghi.

**Chưa làm ở vòng 1:** tách phần chú thích trong ngoặc ở cột "Gieo" của mục A (Consistency S-3: ~249 ô) thành cột riêng — không phải lỗi nguồn, giữ nguyên để không đổi cấu trúc bảng.

---

## NHẬT KÝ SỬA VÒNG 1

Theo FIX_RULES vòng 1 (sau CONSISTENCY_report + QA_30_report). "Dòng" ghi theo ID dòng (S-/OP-/D-/RG-L-), không theo số dòng file.

- **R1** — Đổi mọi ID `L-xx` thành `RG-L-xx` (mục E và mọi chỗ trỏ trong A–D, GHI CHÚ). Thêm chú thích chéo "(= CB-L-xx; = TL-L-xx)" cho 17 dòng E đối chiếu được theo nội dung (RG-L-02, 03, 04, 05, 06, 09, 10, 11, 12, 14, 17, 18, 19, 20, 21, 22, 28).
- **R2** — S-082, S-094a, S-167 → CANON_SUSPICION, đầu nội dung "(lời đồn)" / "(nghe thuật lại)"; S-178 → CANON_SUSPICION (phó tướng Hoắc quân nghi, Ch15 §III). OP-121b tách: OP-121b (phó tướng biết gì; thuyền chở gì — CANON_UNKNOWN) + OP-121c (ai ra lệnh neo: "OPEN với Dịch / trên trang POV Dịch Ch22; Canon đã có ở Ch21 §I.12", trỏ D-69). OP-130 ghi phạm vi "OPEN với Dịch", nêu chỗ Canon đã có ở Ch21. Thêm quy tắc ánh xạ vào CHÚ GIẢI và lời "Cách đọc" mục B.
- **R3** — 5 ô Source Type có chú thích (S-046, S-073, S-108, D-44, D-54b) chỉ còn giá trị chuẩn; tên người tin/nghi chuyển sang cột nội dung. RG-L-08 Type B `—` → CANON_UNKNOWN (ghi "vắng mặt" trong ô nội dung); bỏ quy ước `—` khỏi lời dẫn mục E.
- **R4** — D-54a/D-54b: mỗi dòng chỉ giữ phần đúng loại (a: nợ "Hai dòng 'Kha Trọng'" — FACT; b: nhãn "(nghi rò tin)" — SUSPICION).
- **R5** — D-54b: bỏ cụm "đối tượng bị nghi" (nối Kha Trọng với rò tin); chép sát Ch14 §VI ("Chính hắn (nghi rò tin) | Hai dòng 'Kha Trọng'"), ghi G-1/G-2 chưa nối (Ch14 §II; Ch15 §0). D-54a đặt "(nghi rò tin)" đúng cột Đối tượng như Canon.
- **R6** — D-10, D-11, D-78, S-083, OP-036 gắn "[BÍ DANH CHƯA XÁC NHẬN … RG-L-05 (= CB-L-01)]"; bỏ con trỏ "dòng kế tiếp: D-11" ở D-10. S-149 ghi Ôn ↔ Thứ sử chưa xác nhận (RG-L-11 = CB-L-26).
- **R7** — OP-115 (đã ghi CANON_FACT "ĐÓNG MỘT PHẦN") tách: OP-115a CANON_SUSPICION, "CHƯA QUYẾT ⚠ xem RG-L-28"; OP-115b CANON_UNKNOWN (ngoài mức Hổ Lao). S-211 tách S-211a (gieo, FACT) / S-211b (CANON_SUSPICION, ⚠ RG-L-28). Thêm RG-L-28 (= CB-L-20) vào mục E.
- **R8** — OP-124 chỉ còn phần canon (Lạc Kinh không lên trang Ch21–Ch22); mối nối Chapter Bible Ch22 ↔ Ch28 chuyển sang D5-03. Mục E: 13 ô bên kế hoạch gắn `[PLANNING_NON_CANON]` trong ô (RG-L-07, 09, 13, 14, 15, 23, 24, 25 ×2, 26 ×2, 27 ×2); RG-L-27 bỏ trích nguyên văn hook CB Ch25 khỏi bảng E, trỏ D2-16 / D5-02.
- **R9** — S-102, S-103, S-143: cột Gieo không còn trỏ "Gate Ch8" / "Gate R3"; trỏ mục Canon Update ghi lại (Ch12 §V; Ch12 §IV). Cột Source của file không có tham chiếu Gate/Scene Bible; không có T-153/T-180 (thuộc Timeline).
- **R10** — Mục C: thay mọi "(đầu dải)" bằng "(không có dòng trước; Canon ghi 'Mới')" (D-34, D-43, D-52, D-53, D-72–D-75) hoặc "(Before chưa trích được)" (D-41, D-54a, D-54b); thêm "(Before chưa trích được)" cho D-05, D-15, D-62. D-12 trạng thái cuối sửa thành "ACTIVE (Ch09 §VI)" theo dòng mới nhất. D-15 bỏ phần nối dòng Ch22 (Canon ghi "Mới", khác đối tượng) → tách thành D-79 (Dịch → Hàn / bộ Ích Châu). D-14 ghi dòng Ch19 không được Canon nối. D-05, D-15 thêm Ch20 §VI "Không đổi".
- **R11** — Dòng Trạng thái đầu file; số liệu tóm tắt mục A (250 dòng: 175 / 17 / 1 / 57, đếm theo dòng); CHÚ GIẢI; GHI CHÚ ĐỘ TIN CẬY.
- **Lỗi QA khác** — S-092b (QA #19): CANON_INFERENCE → CANON_FACT, thêm Ch09 §I.12, bỏ "do Canon Update tự ghi". S-079 (QA #12): "Dịch nghe/thấy" → "Dịch thấy" (Ch07 §I.3). OP-050 (QA #13): "động cơ" chỉ gắn Ch10 §II, Ch11–Ch13 §IX; Ch19 §IX, Ch22 §II-A chỉ "Chu Hạc".

<!-- END -->
