# NHẬN DIỆN VÀ SỬA KẾ HOẠCH SPRINT REVIEW — RikkeiAssist, Sprint 11

## Phần 1 — Rà kế hoạch Sprint Review

| Mã | Phù hợp / Chưa phù hợp | Quy tắc làm căn cứ | Cách sửa ngắn gọn |
|---|---|---|---|
| K-01 | **Phù hợp** | — (nhắc Sprint Goal để mọi người cùng nắm mục tiêu, không vi phạm QT1–QT4) | Giữ nguyên: Product Owner nhắc Sprint Goal (0–5'). |
| K-02 | **Chưa phù hợp** | **QT1** — Sprint Review là buổi cùng kiểm tra kết quả và thích ứng, không phải buổi báo cáo tiến độ | Bỏ phần báo cáo % hoàn thành và giải thích "vì sao nhóm bận". Thay bằng: Developers tóm tắt ngắn kết quả Sprint theo điều kiện Done (PBI nào Done, PBI nào chưa Done và số liệu kèm theo), rồi chuyển sang demo. |
| K-03 | **Chưa phù hợp** | **QT2** — Chỉ PBI đạt điều kiện Done mới được giới thiệu là Increment; phần chưa Done phải nói rõ | Chỉ demo PBI-41 là Increment, qua **User Journey: nhân viên cửa hàng nhập mã đơn trên website → xem trạng thái đơn → nhận kết quả đúng**; để Stakeholders tự thao tác thử. PBI-42 và PBI-44 được nêu riêng là **chưa Done**, kèm số liệu (8 ca kiểm thử lỗi chưa đạt; 6/80 ca phân loại sai, 01 lỗi nghiêm trọng cao). |
| K-04 | **Chưa phù hợp** | **QT4** — Feedback được ghi nhận để xem xét Product Backlog, không tự động thành cam kết; (đồng thời trái QT1 vì Review không phải nghiệm thu) | Bỏ "nghiệm thu toàn bộ" và câu hỏi đóng "Mọi người có đồng ý không?". Thay bằng câu hỏi mở: **"Anh/chị thấy phần demo hỗ trợ công việc theo dõi đơn hàng như thế nào, và khi nào AI nên chuyển hội thoại cho nhân viên?"** Feedback được ghi vào danh sách Feedback (ai góp ý, nội dung, mức ảnh hưởng), sau đó Product Owner xem xét, sắp xếp thứ tự trong Product Backlog; không cam kết cho Sprint sau. |

**Người được mời (bổ sung vào kế hoạch):** Mời thêm **Trưởng nhóm CSKH** (xem Phần 3). Developers trực tiếp làm rõ kết quả thay vì để Product Owner nói thay (QT3).

---

## Phần 2 — Trạng thái PBI

| PBI | Done / Chưa Done | Câu thông báo trong Sprint Review |
|---|---|---|
| PBI-41 — Tra cứu trạng thái đơn trên website | **Done** | "PBI-41 đã chạy trên môi trường thử nghiệm, đạt 60/60 kiểm thử chính và không còn lỗi mức nghiêm trọng cao, nên được giới thiệu là Increment của Sprint 11; mời mọi người thao tác thử." |
| PBI-42 — Tra cứu trạng thái đơn từ mạng xã hội | **Chưa Done** | "PBI-42 chưa được xem là Done vì dù đã tích hợp, còn 8 ca kiểm thử lỗi dịch vụ đơn hàng chưa đạt, nên chưa hoàn thành kiểm thử quan trọng và không được giới thiệu là Increment." |
| PBI-44 — Nhận diện khiếu nại nghiêm trọng | **Chưa Done** | "PBI-44 chưa được xem là Done vì còn 6/80 ca bị phân loại sai và còn 01 lỗi mức nghiêm trọng cao, nên nhóm không giới thiệu đây là Increment." |

---

## Phần 3 — Xử lý tình huống (trả lời Product Owner)

Thưa Product Owner, chúng ta không nên giấu 6 ca phân loại sai: PBI-44 chưa được xem là Done vì còn 6/80 ca sai và 01 lỗi mức nghiêm trọng cao, và Sprint Review cần số liệu thật để Stakeholders góp ý đúng. Nếu giữ nguyên K-03, Sprint Review sẽ giới thiệu sai phần chưa Done là Increment và làm mất lòng tin của Stakeholders khi lỗi lộ ra sau này. Với Feedback của Chủ cửa hàng, chúng ta không hứa làm ngay mọi thứ; Feedback này sẽ được ghi nhận và xem xét khi sắp xếp Product Backlog, không tự động thành cam kết của Sprint sau. Chúng ta nên mời Trưởng nhóm CSKH, vì họ muốn chuyển hội thoại cho nhân viên sớm khi AI không chắc chắn, đây là góc nhìn trái chiều với Chủ cửa hàng (muốn AI tự trả lời nhiều hơn) và liên quan trực tiếp đến PBI-44.

---

## Kế hoạch Sprint Review sau khi sửa (45 phút)

| Mã | Thời gian | Hoạt động |
|---|---|---|
| K-01 | 0–5' | Product Owner nhắc Sprint Goal; giới thiệu người tham dự (có Trưởng nhóm CSKH). |
| K-02 | 5–15' | Developers tóm tắt kết quả theo điều kiện Done: PBI-41 Done; PBI-42 và PBI-44 chưa Done, nêu rõ bằng số liệu. |
| K-03 | 15–35' | Demo PBI-41 theo User Journey tra cứu đơn trên website; Stakeholders tự thao tác và đặt câu hỏi. |
| K-04 | 35–45' | Hỏi câu hỏi mở, ghi nhận Feedback vào danh sách, Product Owner xem xét trong Product Backlog; không cam kết cho Sprint sau. |
