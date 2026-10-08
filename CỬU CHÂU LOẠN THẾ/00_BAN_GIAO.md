# CỬU CHÂU LOẠN THẾ — HỒ SƠ BÀN GIAO

*(Bàn giao ngày 02/10/2026, cập nhật 03/10/2026 sau **Ch22 LOCKED**. Đọc file này TRƯỚC khi làm bất cứ việc gì. Chi tiết canon từng chương nằm trong `canon/`; văn bản chuẩn nằm trong `locked/`.)*

---

## 1. TRẠNG THÁI HIỆN TẠI

| Hạng mục | Trạng thái |
|---|---|
| Ch1–Ch22 | **LOCKED** (file trong `locked/`; Ch20 LOCKED sau Audit PASS CÓ ĐIỀU KIỆN — sửa chủ thể "người đưa thư" và cơ chế xấp thư riêng theo chức; Ch21 LOCKED sau Audit Draft PASS CÓ ĐIỀU KIỆN — cắt dầu đèn S5, "Đêm hẹn" ghi tương đối, khóa chức năng câu thư riêng; **Ch22 LOCKED sau Audit Draft PASS CÓ ĐIỀU KIỆN — xóa "Bàng?" (D22-8), cổng nối "mới mở sáng nay", chữ ký gắn bản chép sổ kho (không đọc thành nhận thành)**) |
| Tổng độ dài | **232.295 ký tự** (đếm lại 22 file LOCKED bằng `len()`; Ch19 = 9.085, Ch20 = 7.799, Ch21 = 7.127, **Ch22 = 7.896**). Còn khoảng **67.705 cho 10 chương (Ch23–Ch32)**, trung bình ~**6.770**/chương — cần co ở Ch23–27 để dành đất cho Ch28–32 |
| **Việc đang dở** | **Ch22 CHAPTER LOCKED; Canon Update Ch22 xong** (`canon/CCLT_Canon_Update_Ch22.md`; Canon Sync: không xung đột, không Canon Change; chỉnh Production Check: bộ đi đê/thuyền/cổng bến/trận cùng đêm ~59). Gate Ch22 v2 + Scene Bible Ch22 v2 + Draft/Self-Audit Ch22 giữ trong `gates/`, `scene_bible/`, `draft/`, `audit/` làm hồ sơ. **Foundation Gate Ch23 v1 đã dựng** (`gates/CCLT_Gate_Truoc_Ch23.md`, POV Vân Chương theo Chapter Bible; chờ chị Pre-Audit; chưa LOCK). |
| Bước tiếp theo | **Pre-Audit Gate Ch23 v1 → Gate v2 → LOCK → Scene Bible Ch23** (đã dựng v1; Chapter Bible Ch23: Vân Chương dùng ấu đế tước quyền đồng minh; Dịch bị giam; Chỉ cứu Dịch — **POV do chị chọn**) → Pre-Audit → Gate v2 → LOCK → Scene Bible → … Ch23–27 dùng **Sonnet high**; **Ch28–32 dùng Opus**. Việc Gate Ch23 phải giữ/quyết: **L1 (thành Lạc Kinh chưa bị chiếm; Dịch vào ở Ch28)**; bốn nguyên liệu từ Ch22: **chiếu nêu tên Dịch (có ấn)**, **bản chép sổ kho có chữ ký Dịch gửi Kim Lăng**, **thuyền chưa dỡ / lương còn nguyên**, **ai hợp lệ** (+ ba tay chìa ra: kho · công · cai trị); **điều (2)** lộ khi nào, bằng gì; số phận G / tướng giữ Hổ Lao (D22-8: không bắt buộc trả); **Chiêu/Hoắc ở Ch23 tự thiết lập** (Hoắc ở biên theo Ch17) |
| **Quy tắc SONG SONG (chị khóa)** | (1) **Ch18 là upstream:** Gate Ch19 chỉ dựa vào **khóa xuất E18-1/2/3** của Gate Ch18, điểm nối ở bảng **DEPENDENCY/OPEN** (Gate Ch19 mục 0B). (2) **Không** coi kết quả Ch18 là canon cho Ch19 cho tới khi **Ch18 CHAPTER LOCKED**. (3) Nếu Audit Ch18 đổi dependency: **chỉ sửa dòng nối tương ứng** của Gate Ch19, **không** mở lại toàn bộ Gate. (4) Ch19 **không** tự suy author-truth từ chi tiết Ch18 chưa khóa. (5) Hiện tại Gate Ch19 **độc lập dữ kiện** với Ch18 (J19-1…6 mặc định không nối) |
| Kế hoạch của chị | Đã viết tới **Ch22** → làm Gate Ch23. **Phân model (chị chốt 02/10/2026): Ch28, 29, 30, 31, 32 viết bằng Opus; Ch20–27 dùng Sonnet high.** |

---

## 2. CÁCH LÀM VIỆC (bắt buộc)

**Người dùng:** biên tập viên / auditor, xưng **"chị"**; Claude xưng **"em"**. Trả lời bằng tiếng Việt.

**Quy trình mỗi chương (không bỏ bước):**
Foundation Gate (author-truth) → Pre-Audit → Gate v2 → **LOCK** → Scene Bible v1 → Pre-Audit → v2 → Pre-Audit Final → **LOCK** → Draft v1 + Self-Audit → Audit → Draft v2 → Final Audit → **CHAPTER LOCKED** (tạo file `_LOCKED.md`, giữ file `_DRAFT.md`) → **Canon Update** (Revision / Canon Change / Canon Sync → Canon mới → Không phải canon/OPEN → Knowledge Matrix → State Ledger → Seed→Payoff → Emotional Debt → Master Timeline → Length → OPEN chuyển tiếp).

**Sau mỗi Canon Update (từ Ch23):** Canon Update ChNN → ghi **delta** vào 3 file `derived/` → **rebuild các mục bị ảnh hưởng** (không chỉ append) → **Consistency Check** → **QA lấy mẫu** → Registry cập nhật. Derived **không bao giờ giải quyết mâu thuẫn Canon**, chỉ chỉ ra (mục `CB-L / RG-L / TL-L`).

**GOLDEN RULE: DRAFT KHÔNG TỰ ĐỘNG TRỞ THÀNH CANON.**
- Chi tiết mới đánh dấu **[P]** cho tới khi chương LOCK.
- **Không retcon ngầm.** Mọi thay đổi canon cũ phải ghi **Canon Change** rõ ràng trong Canon Update; **không sửa ngược file Gate/Canon cũ** (giữ làm hồ sơ lịch sử).
- **Belief ≠ Fact.** Knowledge Matrix tách FACT / INFERENCE / NIỀM TIN / UNKNOWN.
- Giữ OPEN những gì chị chưa quyết. Không mở lại Gate/chương đã LOCK trừ khi có xung đột canon thật.
- **Không tự quyết thay chị** những lựa chọn có nhiều phương án: đưa phương án + khuyến nghị, chờ duyệt.
- Không xóa `Cuu_Chau_Loan_The_Chuong_02_DRAFT.md` (giữ đối chiếu lịch sử).

**Quyền canon theo loại file:** LOCKED / Canon Update → Bible quy định → **Derived** (`derived/`, *zero canon authority — chỉ là chỉ mục tiện tra*) → Draft. Derived sai thì sửa/xóa Derived; **không bao giờ sửa Canon để Derived khớp**.

**Thứ tự ưu tiên khi xung đột:** logic / sự thật > Knowledge Matrix > Timeline > State Ledger > Seed/Payoff > Emotional Debt > Chapter Bible > Scene Bible > câu chữ. (Master Bible: LOGIC → NHÂN VẬT → CẢM XÚC → RETENTION.)

**Độ dài (ĐÃ CHỐT, 29/09/2026):** giữ **Production Bible**: tổng ~**300.000** ký tự, **32 chương**, mỗi chương **7k–10k**. **Không** áp quy định "20–25k/chương" của project instructions cho truyện này. Muốn đổi phải có Production Bible Revision riêng. Không thêm cảnh để đủ số. Đếm ký tự theo **file LOCKED** (`len()` Python, tính ký tự, không tính byte).

---

## 3. LUẬT VĂN PHONG ĐÃ HỌC TỪ CÁC LẦN AUDIT

- **Không narrator reveal:** cấm "Thì ra…", "Sự thật là…", "Nàng không biết rằng…". Reveal qua hành động, vật chứng, đối chất.
- **Subtext > giải thích.** Không giải thích động cơ; hiện tượng để người nghe tự hiểu (ví dụ Ch11: "Không có tiếng gọi nào." — không viết "hắn có thể gọi lính mà không gọi").
- **POV nghiêm:** chỉ viết điều nhân vật POV thấy/nghe/biết. Narration gọi tên **theo knowledge của POV**, không theo nhu cầu giấu tên với độc giả.
- **Không câu đúc kết, không moralize, không câu suy luận nói đáp án trước khi xác nhận** (Ch12: bỏ "Trừ khi người dạy không phải là con trai.").
- **Không tín hiệu cơ thể để nhận diện giới tính**; dùng tín hiệu xã hội (Ch12: "không giữ khoảng cách khách sáo" thay "vai gần như chạm vai").
- **Không lặp ý hai lần** (Ch11: bỏ câu lặp cuối S5).
- **Không để Production Bible "lọt" vào văn** (Ch11: bỏ câu narrator nêu nguyên tắc Dạ Kiêu).
- **Mỗi POV tối đa một ký ức ngắn**; không flashback dựng lại chuỗi suy luận.
- Audio-first: mỗi đoạn/POV mở bằng **ai, ở đâu**; câu ngắn; hội thoại gạch đầu dòng "— ".
- Mỗi cảnh phải đổi thế cờ; cảnh chỉ thêm dữ kiện thì gộp.
- Khi phân vân giữa giữ mơ hồ và xác nhận vấn đề phụ → **xác nhận** (trừ khi lộ bí mật trung tâm).
- Cuộc họp/thắng lợi không được trông như thắng hoàn chỉnh khi chưa đủ nền.

---

## 4. BỐI CẢNH & QUY ƯỚC

**Đại Ung** (Trung Hoa cổ trang hư cấu). Họ hoàng tộc: **Tiêu**.

**Sáu trục quyền lực:** Thế, Mưu, Gián, Quân tâm, Ngoại giao, Danh. Võ công chỉ đổi một khoảnh khắc.

**Năm 0 — ba khối quyền lực lớn:** Hạ Hầu (Lạc Kinh, gốc Tây Lương), Nam triều Kim Lăng (ấu đế ~6 tuổi + Vân Chương), Hoắc quân (Bắc cảnh). **Ích Châu** đứng giữa. Bắc Nhung chia phe: **Khả đôn (Uyển, chủ hòa)** / **Hách Liên Chước (chủ chiến)**.

**Xưng hô / gọi tên:**
- **Dịch:** narration "Dịch"/"hắn". Ở Ích Châu: "Trình tiên sinh", "Trình Dịch". Dịch tự xưng "ta" với Ôn/Tô/Hàn. Với Phùng Bảo: "thúc"/"cháu" (Phùng gọi Dịch "cậu", tự xưng "lão"). Không ai gọi "điện hạ" (Ch12–13).
- **Chiêu:** POV narration "nàng"; quân gọi "Tam tướng quân"; công khai là **Hoắc Tam Lang**. Tên "Hoắc Chiêu" chỉ nói **trong phòng năm người**, **không lên văn thư**. **"A Chiêu"** (lời trăng trối của cha) là **Core seed → Ch31**, không ai được dùng.
- **Bùi Chỉ:** POV narration "Bùi Chỉ"/"hắn"; Dịch gọi "A Quy"; người Dạ Kiêu gọi "đương gia". Chỉ **không** tự nói tên "Bùi Chỉ" trước người khác (nối Bùi gia, Ch26).
- **Vân Chương:** narration "Vân Chương"/"chàng"; "Tạ đại nhân"; tự xưng "Tạ mỗ" khi khách sáo.
- **Uyển:** "Uyển"/"nàng"; công khai "Khả đôn"; xưa là Vĩnh Ninh công chúa, con Hoài Nam vương.

---

## 5. TIMELINE CỐT LÕI

| Mốc | Sự kiện |
|---|---|
| Năm -21 | Thẩm chiêu nghi bị vu (Dịch 6 tuổi) |
| Năm -20 | Bùi gia bị diệt; Hoắc bí mật thả Chỉ (8 tuổi) |
| Năm -20 → -11 | Chỉ được **lão Mặc** nuôi dạy; lão Mặc chết ~-11 |
| **Năm -10, tháng Chạp → trừ tịch** | **Vân Trung (Ch1–Ch7)**: bàn cờ năm người; đêm trừ tịch Bắc Môn mở từ bên trong; Hoắc Thành Lĩnh chết; Uyển tự sang Bắc Nhung; Dịch bỏ đi; A Quy bị quy nội ứng |
| Năm -9 → -5 | Chỉ dựng **Dạ Kiêu**; ~-9→-8 Uyển được lập Khả đôn |
| Năm -6 | Phụ hoàng băng, hoàng huynh kế vị |
| Năm -4 → -2 | Tạ Diên chết |
| **Năm 0, tháng Giêng – đầu tháng Hai** | **Ch10** Hắc Hà (Chiêu) |
| Đầu tháng Ba năm 0 | Lạc Kinh thất thủ; hoàng đế chết; Vân Chương đưa ấu đế về Kim Lăng |
| Cuối tháng Ba → tháng Tư | **Ch8** (ngày 1–14), **Ch9** (ngày 14–24) — Ích Châu |
| Cuối tháng Năm → tháng Sáu | **Ch11** Dạ Kiêu |
| Cuối tháng Sáu → đầu tháng Bảy | Ôn đặt cược có điều kiện vào Dịch (CC-2 Ch12) |
| **Cuối tháng Chín năm 0** | **Ch12** Lạc Thủy (chiều ngày 1 + ngày 2 + đêm); **Ch13** (ngày 3) |
| **Đầu tháng Mười → ngày 18** | **Ch14** (Chỉ): năm điểm hẹn ở các đêm 11–15; báo Vân Chương ngày 12; Kha Trọng ngày 18 *(ngày-tháng tuyệt đối là suy ra, không nêu trên trang)* |
| **Đầu xuân năm 1, ~ngày 56 chiều → ~61 sáng sau Hổ Lao** *(chồng lên Ch21)* | **Ch22** (Dịch): lịch lương (đêm thứ ba; bốn chuyến; đường qua bến dưới); hai sáng trinh sát (*dồn quân ra phía bến*); Hàn *"Ta đem. Ta chọn."*; **~59 đêm:** bộ Hàn đi đê, thuyền neo ngang sông, dự bị mặt ra sông, **cổng bến mở không ai hô**, Dịch *"Họ nhìn ra sông."* → giữ cổng suốt đêm; hàng binh đặt giáo theo tờ văn; **~60:** vào thành chính qua cổng nối (mới mở sáng nay), giữ kho không truy, cho hàng binh xô; ba tay chìa ra; ký bản chép sổ kho; *"Lương còn nguyên."*; **~61 sáng:** cổng đê mở, chiếu có ấn dán lên cổng *(số ngày là suy ra; trên trang không số ngày)* |
| **Đầu xuân năm 1, ~ngày 51 đêm → ~65 sau Hổ Lao** | **Ch21** (Vân Chương, Kim Lăng): thư Hổ Lao (ba điều); ba câu đo; hạn ba đêm; người đi bến *"Ba ngày"* / *"Một lời"*; lệnh lương gấp ba (lương thật xuất kho) qua trạm; lịch lương + lời miệng neo ngang sông qua thủy quân; thư đáp (điều (2) bằng chữ, dấu riêng, ngoài sổ); chờ; báo hai dòng; hook *"Cổng thành mở."* *(sự kiện tuyến trước ~ngày 52–60; số ngày là suy ra)* |
| **Đầu xuân năm 1, ~ngày 44 → 51 sau Hổ Lao** | **Ch20** (Vân Chương, Kim Lăng): báo cáo Dĩnh Xuyên + thư Uyển; soạn chiếu (R2); triều nghị, ấu đế đặt tay lên ấn; chiếu đi hai đường; quan huyện đọc chiếu rồi bị Hạ Hầu xử; đêm: thư xin hàng Hổ Lao *(số ngày là suy ra; trên trang không số ngày)* |
| **Đầu xuân năm 1, ngày 37 → 41 sau Hổ Lao** | **Ch19** (Dịch): hàng binh buông giáp; thư Bàng; văn an dân; cảnh cáo; Dĩnh Xuyên mở cổng từ bên trong (ngày 41) |
| **Ch18** (Uyển, không nối số ngày với Ch19/20) | Hội các bộ sáu ngày; phiên xử Tu Bặc Cốt ngày thứ sáu; thư "Một bộ trái lời. Đã xử. Trướng giữ." qua bốn chặng; gói vỏ quýt "Đi sau."; hook Hách Liên Chước tập hợp quân |
| **Đầu xuân năm 1 (băng tan), ngày 30 → 36 sau Hổ Lao** | **Ch17** (Chiêu): ngày 30 Dịch mang giấy tới, Chiêu đặt ba điều kiện; ngày 30–33 vòng ngoài Hổ Lao; ngày 35 rạng vây Dĩnh Xuyên, đốt kho bến; ngày 36 kỵ viện tới rạng, bộ viện hoàng hôn; Chiêu thắp hương; thuyền tới, bộ Ích Châu nhảy lên đê; kỵ viện vỡ; Tiểu Thất chết |
| **Đầu xuân năm 1 (băng tan), ngày 9 → 29 sau Hổ Lao** | **Ch16** (Dịch): sổ ải Tây (ngày 9); hội, Chiêu rút nửa, hạn ba tuần (ngày 10); làng mua lương, "chợ Dĩnh Xuyên" (ngày 12); hồi âm Bàng đọc công khai (ngày 14); thư Ôn tới (ngày 28); đêm ngày 29: hook Dĩnh Xuyên; hạn Chiêu hết ngày 31 |
| **Đầu xuân năm 1 (băng tan), ngày 1 → 8** | **Ch15** (Dịch): Hổ Lao; cột lương bị chặn ở bến trên ngày 5; Chiêu tới Hổ Lao ngày 7, tới doanh Dịch sáng ngày 8 (cưỡi gấp); sứ Hạ Hầu chạng vạng ngày 8 |

Năm 0: Dịch 27 tuổi, Chỉ 28.

---

## 6. TÓM TẮT CANON TỪNG CHƯƠNG (một dòng; chi tiết trong `canon/`)

- **Ch1 Tuyết Vân Trung (Dịch):** Thẩm thư lại ở Vân Trung; Bắc Môn thay then mới (hai người khiêng), Chu Hạc cho bôi dầu, cầm sổ ca trực.
- **Ch2 Kẻ ám sát (Chỉ):** Chỉ ám sát Hoắc thất bại, bong gân cổ chân trái; rạch tay Tam Lang; bị bắt, được gọi "A Quy".
- **Ch3 Bàn cờ trong tuyết (Dịch):** áo bông; bàn cờ năm người, luật giữ lượt; quân trắng; Uyển học ngựa với Tam Lang.
- **Ch4–Ch5 (Vân Chương):** Hắc Hà đóng băng; thuốc vỏ quýt; Vân Chương đưa Uyển ra miếu ngoài thành đêm trừ tịch, tự quay vào.
- **Ch6 Cửa thành mở (Chiêu):** Bắc Môn mở từ bên trong; Hoắc chết, gọi "A Chiêu"; Chiêu nhận binh phù; lệnh bắt sống A Quy.
- **Ch7 Đường tan vỡ (Dịch):** Dịch thấy hai người khiêng then (không thấy mặt); Uyển tự đi; Dịch rời thành cùng Phùng thúc. "Mười năm sau."
- **Ch8 Mười năm sau (Dịch):** Ích Châu; công khai "Ta là con của Thẩm chiêu nghi"; khóa trường mệnh; hook "Thất điện hạ."
- **Ch9 Ích Châu (Dịch):** thư Tây Lương; nhà Đỗ, gian kho thứ chín; Hàn tự nhận đã nhắn ải Tây; "Hoắc Tam Lang vẫn giữ Hắc Hà."
- **Ch10 Hắc Hà (Chiêu, lùi thời gian):** cờ đổ, mũ trụ trên giáo → lời đồn tử trận; đình chiến qua sứ Khả đôn; quân cờ trắng trên mép bàn.
- **Ch11 Dạ Kiêu (Chỉ):** Dạ Kiêu nhận đơn giết Dịch; Chỉ tự đi, nhận ra Thẩm thư lại; **"Đêm đó ta thấy người khiêng then cửa Bắc có hai người. Ngươi chỉ có một."**; Chỉ trả tiền (phá 2/3 nguyên tắc — Canon Change); hook "Ai đã có mặt ở Bắc Môn đêm ấy?"
- **Ch12 Lạc Thủy (Dịch):** năm thế lực gặp lại; A Quy vào dưới bảo chứng Ích Châu; thỏa thuận **thăm dò qua mùa đông**, bằng lời, **không văn thư**; **"Người hứa là Hoắc Chiêu."**; thư Ôn chỉ ghi "Hoắc quân".
- **Ch13 Những điều không nói (5 POV):** vải bông chống rét; Chiêu hoãn (không tha) lệnh bắt A Quy qua mùa đông; vỏ quýt; Chỉ truy kẻ đếm thuyền → phía Hạ Hầu, nhận ra rò tin bên trong qua chữ "không văn thư", báo cả bốn bên miễn phí; tin giả "Kim Lăng đã công nhận Thất hoàng tử"; viên quan Kim Lăng gửi ngựa trước; Vân Chương viết "người tự nhận"; hook "đã có một con ngựa đi trước".
- **Ch14 Năm tin giả (Chỉ, cả chương):** năm tin giả = năm điểm hẹn khác nhau (3 tuyến miệng, T4 nói riêng với Vân Chương, T5 tờ giấy qua người giữ ngựa không biết chữ); chỉ **T5 quay lại** (hai người lạ ở miếu thổ địa, đêm 11) → **"đường văn thư – trạm ngựa Kim Lăng có lỗ"**; Vân Chương: "đã nhận hai chỗ hẹn, lần sau báo một chỗ"; Chỉ chưa trả lời Hoắc quân; sổ thuê ngựa Thạch Kiều ghi **"Người bảo lãnh: Kha Trọng"** đặt cạnh bản chép sổ Nam Môn cũ **"Kha Trọng, người Lạc Kinh, buôn giấy"**; lời đồn lão Kha, quản sự một phủ lớn họ Tạ; hook "Hắn không đóng sổ lại."
- **Ch15 Hổ Lao (Dịch):** đầu xuân năm 1; hội minh có điều kiện (không tổng chỉ huy; Hàn chỉ huy đạo Ích Châu, Dịch kế hoạch/lương); kế hoạch ba cột đồng bộ hội ở Hổ Lao; kho Hổ Lao đầy (Dịch đọc là Hạ Hầu giữ thành); kỵ Hạ Hầu đánh chỗ nối của cột lương ở bến trên; Dịch cắt xe cứu người ("Người trước"); mất ~nghìn tám và toàn bộ đoàn xe; Chiêu mất bảy trăm (tổn thất chiến đấu), lui, giao hai xe lương cho cột Ích Châu (ghi sổ hội minh, "Ghi bằng tên Ích Châu"); sứ Hạ Hầu trả thương binh + "thư ông ấy gửi, Ích Châu chưa có hồi âm"; hội nhỏ nghi "ai biết cột đi hướng nào", "nhà buôn tin"; hook Dịch vẽ vòng chỉ chạm hai bến, gạch chữ "Hổ Lao", tờ giấy trắng.
- **Ch16 Thế (Dịch):** ba tuần sau Hổ Lao; Hàn xác nhận fact giao dịch (Bàng mua lương ải Tây nhiều năm, biết một xe Ích Châu chở bao nhiêu); Dịch từ chối trận kiếm cỏ (~200 người) bằng số; Hàn: "Không đánh"; Dịch: "Có hay không, đường lương cũng phải đổi"; Chiêu: "Ngươi cần bao lâu?" → ba tuần → rút **một nửa** Hoắc quân vì chi phí và hạn, **kỵ nhẹ + Chiêu ở lại** ăn lương Ích Châu; Kim Lăng nhận việc chở lương ("đường sông cho liên quân"); làng bán một phần ba, trả muối/vải bông + phiếu nợ mang tên Dịch và Hàn, "ấn Thứ sử tới sau"; **Hạ Hầu cũng mua lương dân một phần ba** (fact); làng trưởng nhắc **"chợ Dĩnh Xuyên"**, Dịch nhìn theo dòng nước hạ lưu; hồi âm Bàng đọc công khai, chỉ lương (sổ cũ một nghìn suất, ba trăm ngựa), Hàn ký kèm, **"Việc kia Thứ sử đã xem"**; một sĩ quan xin về áp tải thương binh; ngày 29: nợ muối 300 bao, thuyền 7 chuyến, mất 6 xe, **chín** đường chạy; Hổ Lao thêm quân; thư Ôn: ấn tới hết vụ thu, tối đa 400 bao muối / 200 tấm vải; hook Dịch vẽ đường than tới **Dĩnh Xuyên** trên tờ giấy trắng.
- **Ch17 Vây điểm diệt viện (Chiêu):** ngày 30 Dịch mang tờ giấy đường than tới, Chiêu hỏi như hỏi đường vận; Dịch nói "Không" khi hỏi chắc, im ở "vì sao họ sẽ cứu"; Chiêu tự quyết làm mồi (đội mũ chùm lông đen), đặt ba điều kiện (tự chọn chỗ đứng; một nén hương sau mặt trời lặn; hết trận kỵ nhẹ về biên, tối đa ngày 42); "Lệnh còn." (một dòng); Hàn "Ta quyết"; Chiêu tự xem đê, thấy tháp hiệu, quyết không phá; vây và đốt kho bến rạng ngày 35, cả ngày không ai tới, đêm đuốc sớm hơn nửa ngày; ngày 36 kỵ viện tới rạng, Chiêu giữ cả ngày (ngựa chết, Tiểu Thất chết chặn khe, cánh tay trái bị rạch, kỵ nhẹ hao); bộ viện đi gấp tới hoàng hôn; Chiêu thắp hương, đèn lên gần tàn; bộ Ích Châu nhảy lên đê, hiệu địch muộn, hàng đứt, kỵ viện vỡ; kho bến cháy, Dĩnh Xuyên chưa hạ, Hổ Lao còn; hook: cờ Hạ Hầu dừng ở cổ chai.

- **Ch18 Luật mùa cỏ (Uyển):** hội các bộ sáu ngày; luật mùa cỏ bốn điều; giếng; phiên xử Tu Bặc Cốt (ngày thứ sáu, đã chết); thư một dòng gửi Kim Lăng qua bốn chặng tin + gói vỏ quýt (*"Đi sau."* — lời Uyển với thị nữ); hook Hách Liên Chước tập hợp quân.
- **Ch19 Cửa tự mở (Dịch):** Dĩnh Xuyên mở cổng từ bên trong qua chuỗi năm mắt xích; thư Bàng (*"Lương của ngài đi nhanh hơn sổ của ta… Thư này chỉ bàn việc lương."*); văn an dân năm câu ký "Trình Dịch, sứ Ích Châu", không ấn; Chiêu *"Ta không ký."* / *"Không ai của ta tự vào."*; hook *"Đô úy. Sổ đêm qua không thêm tên."*
- **Ch20 Đứa trẻ trên ngôi (Vân Chương):** nhận báo cáo Dĩnh Xuyên + thư Uyển (không đáp); soạn chiếu R2 — *"nhận việc, không nhận người"*, không gửi Dịch một dòng; triều nghị ba nhóm nhượng một phần, hôn thư, ấu đế đặt tay lên ấn (*"Đóng ở đâu?"*); *"Hạ Hầu có nhận chiếu này không?"* không ai đáp; chiếu đi hai đường (trạm hở; thư riêng theo chức); quan huyện đọc chiếu rồi bị Hạ Hầu xử (chỉ hai dữ kiện); tờ xin ra tuyến trước bị gấp vì ai chứng ấn; hook *"Hổ Lao xin hàng."*
- **Ch21 Trá Hàng (Vân Chương):** ba điều của thư Hổ Lao; hỏi thứ đo được, không hỏi thật/trá (*"Đại nhân không hỏi thư thật hay không?" — "Không."*); người đi bến *"Ba ngày"*, Chỉ chào *"năm lời"* — *"Một lời."*; lệnh lương số suất gấp ba số thủy thủ, lương **thật** xuất kho (*"Đúng số ghi."*); lịch lương *ngày–lương–đường* (*"Ba thứ ấy. Không thêm."*) + lời miệng *"Tới bến thì neo ngang sông. Một đêm."*; thư đáp tự viết, nhận điều (2) *"không giao người ngoài"*, dấu riêng, không vào sổ; chờ (thuyền đi, sổ kho bị võ tướng xem, báo cũ *"Thuyền đã neo ngang sông"*/*"Hổ Lao dồn quân ra phía bến"* — *"Báo không nói."*); hook *"Cổng thành mở."*
- **Ch22 Đường Lạc Kinh (Dịch):** lịch lương *ngày–lượng–đường* (*"Ai ăn số này?"* không đáp; *"Lịch ghi lương."*); hai sáng trinh sát *"Hổ Lao dồn quân ra phía bến"*; Hàn tự chọn đi (*"Ta đem. Ta chọn."*; fail-safe *"Ông lui trước sáng"*); đêm trên đê: thuyền không vào bến, dự bị mặt ra sông, cổng bến (cổng khu đầu bến) mở không ai hô → *"Họ nhìn ra sông."* → *"Giữ cổng. Chỉ giữ cổng."* (cổ chai); sĩ quan Ích Châu hô tờ văn, hàng binh đặt giáo, một nhóm đi bờ tây; sáng vào thành chính qua cổng nối, giữ kho **không truy** cột bại quân (*"Ngươi để chúng đi."*), cho chính người cầm đuốc cầm xô dập kho; chiều: *"Ai đổ máu, người ấy giữ."* / *"Sông do thủy quân giữ. Ta ghi sổ."* + sổ kho một bản gửi Kim Lăng (Dịch ký *Trình Dịch, sứ Ích Châu*, không ấn) / *"Thuyền chưa dỡ. Lương còn nguyên."* / quan cũ *"Ai hợp lệ?"* không ai đáp, tướng giữ thành *không thấy*, *"họ Tiêu?"* không đáp; hook: thư lại dán chiếu có ấn lên cổng đê — *"Tên hắn không ở cuối tờ. Nó nằm giữa dòng, trong chữ của người khác."*

---

## 7. KNOWLEDGE MATRIX HIỆN TẠI (cuối Ch17; chi tiết Ch17 trong `canon/CCLT_Canon_Update_Ch17.md`)

> **Ch17 (Chiêu):** biết đường than (Dịch tự mang), Dĩnh Xuyên cảng cấp lương, tháp hiệu, đường đồi có đồn; thuyền tới đúng cọc; Tiểu Thất chết; mình bị thương. **Không biết** vì sao Dịch chắc họ sẽ cứu, ai chỉ huy viện, Dịch ở đâu trong trận, ý đồ hồi âm, A Quy ở đâu.

| Người | Biết | Không biết |
|---|---|---|
| **Dịch** | (Ch16) Bàng biết cách xe Ích Châu chở (Hàn xác nhận giao dịch); Hoắc quân rút nửa, hạn ba tuần; Hạ Hầu cũng mua lương dân; Ôn ấn có mức tối đa; đã vẽ đường lương tới Dĩnh Xuyên (chưa biết dùng làm gì). (Ch15) cột lương bị chặn đúng chỗ ép; Hạ Hầu đánh chỗ nối, giữ đường chứ không giữ thành; vòng chỉ chạm hai bến; Bàng nhắc thư chưa hồi âm; **không biết** Bàng đọc bằng cách nào, **không biết** Ch14 (lỗ văn thư, Kha Trọng). Tam Lang = Hoắc Chiêu; Uyển vận hành như Khả đôn (thấy một phần); Kim Lăng chưa công nhận; A Quy nói lời Dạ Kiêu; A Quy từng được thuê giết hắn (giữ kín); hai người khiêng then (giữ kín) | A Quy là đầu lĩnh hay chỉ là người của Dạ Kiêu; tên "Bùi Chỉ"; có rò tin bên trong; thư "người tự nhận" |
| **Chiêu** | Trình Dịch = Thẩm thư lại; A Quy sống, nói lời Dạ Kiêu; đã hoãn lệnh bắt qua mùa đông | Hai người khiêng then; A Quy từng được thuê giết Dịch |
| **Uyển** | Trình Dịch = Thẩm thư lại; biết Tam Lang là nữ từ Vân Trung (căn cứ: OPEN) | Bắc Môn; rò tin |
| **Chỉ** | Thẩm thư lại = Trình Dịch; Tam Lang = Hoắc Chiêu; kết luận cũ "một người mở cửa" đã sụp; kẻ đếm thuyền → phía Hạ Hầu (qua ba mắt xích); **có rò tin bên trong** (chỉ mình hắn biết); **đường văn thư – trạm ngựa Kim Lăng có lỗ** (T5); **Kha Trọng**: hai dòng chữ cạnh nhau (sổ Nam Môn cũ / sổ thuê ngựa Thạch Kiều), lời đồn lão Kha–phủ họ Tạ (**OPEN**) | Người thứ hai khiêng then; **ai rò**; Kha Trọng có là một người / còn sống / liên quan Bắc Môn, Chu Hạc, Tạ gia; người ra lệnh giết Dịch (K1: phía Hạ Hầu — author-truth) |
| **Vân Chương** | Kết quả chuỗi suy luận: Trình Dịch là con Thẩm chiêu nghi (mức tin rất cao); viên quan Kim Lăng gửi tin không hỏi chàng; đã viết "người tự nhận" (**chưa quyết phản bội**); Chỉ báo "đường văn thư – trạm ngựa Kim Lăng có lỗ"; đã nhận hai chỗ hẹn (miệng và giấy) | Ai rò; viên quan gửi cho ai; **vì sao Chỉ chọn Kim Lăng / Chỉ nghi ai** (G-3); Kha Trọng |

---

## 8. AUTHOR-TRUTH QUAN TRỌNG (không lên trang trước hạn)

- **Bắc Môn:** Chu Hạc bị Tạ Diên mua; Dịch có **nghi riêng** (nhớ lệnh bôi dầu) nhưng **không nói tên** (D1). **Không xác nhận Chu Hạc** trước Ch26/Ch29.
- **K1:** phía Hạ Hầu thuê Dạ Kiêu giết Dịch qua trung gian. **K2** (nhóm ngoại thích Kim Lăng) để dành.
- **Ai trả tiền nuôi Chỉ** những năm đầu; **những gì giữa Hoắc và Chỉ trong thư phòng**: OPEN, khóa trước Ch26.
- **Ba nguyên tắc Dạ Kiêu:** không hỏi lý do; mục tiêu không thấy mặt; nhận thì làm. Ch11: Chỉ phá **2/3** (không phá nguyên tắc 1).
- **Lệnh bắt A Quy:** còn; **không truy qua mùa đông**; hết mùa đông hoặc thỏa thuận vỡ thì chạy lại.

---

## 9. OPEN (chưa quyết)

Nguồn rò trên tuyến văn thư – trạm ngựa Kim Lăng (G-1); Kha Trọng (G-2); hai người lạ ở miếu; lời đáp cho Hoắc quân; Người thứ hai khiêng then; người dò tin bị bắt (Ch11); phản ứng của người thuê (Ch11); vì sao Dịch không gọi lính (Ch11); quân trắng của từng người; động cơ Chu Hạc; Lão Tần; Chiêu có từng tới ngõ cháy không; người gia nhân năm -20; căn cứ Uyển biết Tam Lang là nữ; viên quan Kim Lăng gửi cho ai (K2); triều Kim Lăng phản ứng; Hạ Hầu phản ứng sau tin giả; Khả hãn hiện tại; con của Uyển; quan hệ huyết thống Hoài Nam vương.

---

## 10. GUARDRAIL ĐANG HIỆU LỰC (CH14–CH15)

- **G-1:** nguồn rò trên tuyến văn thư – trạm ngựa Kim Lăng **OPEN**; chưa được nói rò nằm trong đoàn Kim Lăng.
- **G-2: Kha Trọng OPEN.** Chưa được kết luận: cùng một người; còn sống; liên quan Bắc Môn; liên quan Chu Hạc; Tạ gia đứng sau; chủ mưu. Chỉ ghi nhận khả năng ("Tìm lão ấy. Không bắt. Không lại gần.").
- **Canon Guardrail:** năm tin giả đo đường truyền, không đo lòng trung thành. Một tuyến bị rò ≠ người đứng đầu phản bội; một tuyến sạch ≠ tuyến an toàn tuyệt đối ("Là không ai", không nói "sạch").
- **G-3:** Vân Chương biết Chỉ đã thử hai tuyến của Kim Lăng; **không** biết vì sao Chỉ chọn Kim Lăng; không để chàng suy ra "Kim Lăng bị nghi nhất".
- Năm nhân vật chính không nghi nhau trực tiếp trên trang; không tin nào được báo là test.
- **K-1/K-2 (Gate Ch15):** Bàng không biết kế hoạch Dịch, chỉ suy từ seed cũ (sổ lương ải Tây, quan sát công khai, địa hình); **rò Ch14 ≠ nguyên nhân Hổ Lao**; kế hoạch liên quân không đi qua văn thư – trạm ngựa Kim Lăng. Tiếp tục hiệu lực ở Ch16–19.
- **GR16-11…19 (Gate/Scene Bible/Audit Ch16):** Hàn chỉ xác nhận giao dịch, không về người báo tin; Chiêu rút nửa vì chi phí + hạn, ở lại; thư Bàng chỉ lương, đọc công khai; Dĩnh Xuyên chỉ giới thiệu như hướng mới, lý do giải ở Ch17; "Việc kia" không giải thích thêm; Hạ Hầu mua lương dân chỉ là fact; sĩ quan xin về là chi phí nhân lực; Dịch gõ vào dòng "Một nghìn suất" thay lời; Dịch nhìn theo dòng nước hạ lưu thay lời.
- **GR17 (Gate Ch17 LOCK v2):** GR17-1 Dĩnh Xuyên chỉ nói chức năng/vị trí/kho/người giữ, không giải vì sao Dịch chắc Bàng cứu (→ Ch19); GR17-2/04 Chiêu chỉ biết theo nguồn trên trang, không biết author-truth; GR17-3/PA-A A Quy chỉ một dòng "Lệnh còn." ở S1, không nối Dĩnh Xuyên; GR17-05 Dĩnh Xuyên chưa phải "nước chắc thắng" (Dịch nói "Không", có khoảng không ai đến, viện tới sớm, mất mát thật, thắng một phần); GR17-06 Bàng chỉ một điểm đọc sai (bộ binh trên thuyền Kim Lăng đọc là thuyền lương), mọi quyết định khác của phía Hạ Hầu đúng; GR17-17 K-1/K-2; GR17-18 "một nén hương" thay "nửa canh"; D17-12 Đô úy vô danh.
- **G-15-1/2/3:** "700" = tổn thất chiến đấu (không mặc định tử trận); Chiêu hành động ở cấp quyết định quân sự, không cứu riêng Dịch; "thư chưa hồi âm" chỉ nối về thư Ch9, tuyệt đối không nối Ch14.

- **GR20 (Gate Ch20 v2 LOCK):** R2 = hợp thức hóa hậu quả, **không ủy quyền** (Dịch vẫn "sứ Ích Châu"; không "điện hạ"); sáu công cụ **không combo hoàn hảo** (hạn mơ hồ; câu "Hạ Hầu có nhận chiếu không?" không ai đáp; ông áo tía không hài lòng); đường trạm hở **dùng, không truy nguồn**, không bẫy tin giả (→ Ch21); quan huyện **chỉ hai dữ kiện** (đã đọc chiếu / bị Hạ Hầu xử), Vân Chương không suy động cơ; ấu đế chỉ thao tác hành chính; **cost "không rời" bằng việc chứng ấn**, không diễn giải; hook = dòng đầu thư *"Hổ Lao xin hàng."*, **ba điều kiện không lên trang**; Vân Chương **không tính trước kết quả**.

- **GR21 (Gate Ch21 v2 LOCK):** thư Hổ Lao **thật ở người viết** (G không phải nội gián, Bàng không điều khiển/ép), bẫy ở **cách Bàng dùng tin thật** — **không twist "thư giả"**, trang **không** chứa thật/trá; **"một lời" = thông tin thật** (con số lương khớp lương thật xuất kho); **Bàng sai đúng một điểm** (thuyền lần này chỉ chở lương), không "nhìn thấu Vân Chương"; **không tên Bàng** trong POV Vân Chương; lịch lương chỉ **ngày/lượng lương/đường**, **cấm** *hãy đánh/phục kích/đón thuyền*; **Dịch tự đọc**, Ch22 không là chiến công Vân Chương; Chỉ chỉ **đo**, G-1 OPEN; **điều (2) = seed Ch23** (nhận bằng chữ, không nói liên quân, không câu đạo đức); **mở cổng ≠ đầu hàng** (Bàng tự ra lệnh mở; Ch22 hiện hậu quả; không lặp *"dân tự chọn mở"* Ch19); hook = **một dòng** *"Cổng thành mở."* không nêu ai mở/vì sao/bẫy hay thắng; **Lạc Kinh chỉ OPEN** (Gate Ch22/Ch23 xử lý nối Ch22↔Ch28).

- **GR22 (Gate Ch22 v2 LOCK):** **L1:** Lạc Kinh **chưa bị chiếm** (Hổ Lao = cửa/điểm khóa trên tuyến; **Dịch chỉ vào Lạc Kinh ở Ch28**; Ch23–27 **không** viết Lạc Kinh đổi chủ/mở cổng); **L2 / GR22-H1 (HARD):** Dịch chỉ biết lịch lương, mọi chiến thuật **tự đọc, tự quyết, có thể sai**; không biết thư Hổ Lao/điều (2)/lời miệng *neo ngang sông*/Bàng đọc gì; Vân Chương **không** điều khiển chiến thắng; **D22-5:** Chiêu/Hoắc **vắng** (hạn ngày 42, Ch17; không gia hạn); **D22-8:** Bàng/người giữ thành **không lên trang** (*"Không thấy."* — cả "Bàng?" cũng đã bỏ); **GR22-22:** *cổng bến* = cổng **khu đầu bến**, *cổng nối* = đường vào thành chính (sáng), *cổng đê* chỉ mở ở S5 do Hàn; không *"cổng thành"/"thành mở"/"tự mở"*; **hook = chiếu có ấn dán trên cổng** (gương Ch19); chữ ký *Trình Dịch, sứ Ích Châu* chỉ là ghi nhận sổ kho, **không** là nhận thành; **thắng nhờ thế, không nhờ số**; Dịch không kết luận về thuyền, không giận Vân Chương.

---

## 11. CHỈ MỤC THƯ MỤC

| Thư mục | Nội dung |
|---|---|
| `bible/` | Production Bible, Chapter Bible 32 chương, Writing Control System, Luật vận hành Bible–Draft, Scene Bible Quyển I (gốc) |
| `locked/` | **Văn bản chuẩn** Ch1–Ch22 |
| `canon/` | Canon Update Ch1–Ch22 (**nguồn canon chi tiết**) |
| `gates/` | Foundation Gate các chương (+ Gate Vân Chương, Gate tiếp tế mùa đông, Proposal) |
| `scene_bible/` | Scene Bible Ch2–Ch22 |
| `audit/` | Self-Audit Ch7–Ch22 |
| `draft/` | Các bản DRAFT (lịch sử) |
| `derived/` | **DERIVED / NON-CANON** (dựng từ Canon Update Ch1–22; Consistency Check + QA 30 claim vòng 1 + sửa vòng 1): `CHARACTER_BIBLE_DERIVED.md`, `SEED_PAYOFF_EMOTIONAL_DEBT_REGISTRY.md`, `MASTER_TIMELINE_DERIVED_Ch1-Ch22.md`. Mỗi claim có Source Type (CANON_FACT / BELIEF / SUSPICION / INFERENCE / UNKNOWN / PLANNING_NON_CANON) + Source. Báo cáo QA: `audit/DERIVED_*_vong1.md` |
| `tham_khao/` | Các ghi chú audit cũ của chị (Ch1–Ch2) |

---

## 12. CÁCH BẮT ĐẦU CHAT MỚI

Gửi cho Claude:

> Đọc `CỬU CHÂU LOẠN THẾ/00_BAN_GIAO.md` trong repo `lyhoa82-byte/suatruyen`. Sau đó đọc `canon/CCLT_Canon_Update_Ch22.md` (đặc biệt mục II-B và mục IX: open threads trước Gate Ch23) và `locked/Cuu_Chau_Loan_The_Chuong_22_LOCKED.md`. Đọc thêm Chapter Bible Ch23 trong `bible/` và `gates/CCLT_Gate_Truoc_Ch22.md` (L1/L2, author-truth). Việc tiếp theo: **Foundation Gate Ch23 v1** (v1 đã có, chờ Pre-Audit). Không mở lại Ch18–22. Ch23–27 dùng Sonnet high; Ch28–32 Opus.

Khi viết Draft: đọc thêm Scene Bible đã LOCK của chương đó và **1–2 chương LOCKED gần nhất** để giữ giọng văn.
