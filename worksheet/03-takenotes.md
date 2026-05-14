---
artifact: 03-takenotes — Quan sát cá nhân sau phần chia sẻ nhóm khác
bai-tap: 3 — Quan sát + rút ra bài học (cá nhân)
phase: Sau phần shareout của các nhóm
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác)
input: Phần thuyết trình của ít nhất 2 nhóm khác trên lớp
nop-cuoi: Có — file cuối Lab 3 (cá nhân)
---

# 03 — Take notes: quan sát + bài học cá nhân

Đây là phần cá nhân. Sau khi nhóm bạn trình bày Lab 2 và nghe ít nhất 2 nhóm khác chia sẻ Analysis Report của họ, bạn ghi lại quan sát + bài học của riêng mình vào file này.

Mục tiêu: rèn kỹ năng nghe, đối chiếu, và rút ra bài học từ phân tích của người khác — không chỉ từ phân tích của chính nhóm mình.

Quy tắc khi viết:

- Trích dẫn cụ thể tên sản phẩm + nhóm đã quan sát (không nói chung chung).
- Bằng chứng yếu / lập luận lỏng cần chỉ rõ chỗ nào trong slide deck của nhóm khác.
- Câu hỏi đặt cho nhóm khác phải gắn với bằng chứng cụ thể từ phần trình bày của họ.

---

## Thông tin

- **Mã học viên**: 2A202600107
- **Họ tên**: Lê Thị Phương
- **Ngày**: 2026-05-14
- **Nhóm Lab 2 của tôi**: Elicit và NotebookLM (Ngành D) 

---

## Phần 1 — Nhóm đã quan sát (≥ 2 nhóm khác)

| # | Tên nhóm / mã 2 học viên | Ngành | 2 sản phẩm họ test |
|---|---|---|---|
| 1 | Quách Ngọc Quang (2A202600285) & Nguyễn Đông Hưng (2A202600392) | [B] Lập trình | Cursor vs GitHub Copilot |
| 2 | Hoàng Văn Bắc — 2A202600076; Trịnh Xuân Đạt — 2A202600326 | [B] Lập trình | Cursor vs GitHub Copilot |

---

## Phần 2 — Điều thấy hay từ nhóm khác

Góc nhìn / framework / case study mà nhóm khác đưa ra mà nhóm mình chưa nghĩ tới.

**Quan sát 1** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể họ đưa ra: Nhận định ở mục S3.3 "Với code generation, trust không đến từ citation mà đến từ khả năng execute và verify bằng unit test".
- Vì sao tôi thấy hay: Góc nhìn này cực kỳ thực tế và đúng với bản chất ngành lập trình. Nhóm không bị rập khuôn vào template (phải có citation mới là trust) mà linh hoạt định nghĩa lại Trust Signal dựa trên đặc thù của loại output (Code).


**Quan sát 2** (từ nhóm Hoàng Văn Bắc — Cursor vs GitHub Copilot):

- Cụ thể họ đưa ra: Nhóm không chỉ so sánh code đúng/sai mà so sánh workflow tạo landing page HTML/Tailwind. Họ chỉ ra Cursor dùng Composer/Inline Edit để tạo và sửa file ngay trong IDE, còn Copilot thường trả code block lớn trong VS Code Chat nên người dùng cần insert/copy-paste nhiều hơn.
- Vì sao tôi thấy hay: Cách nhìn này đúng tinh thần Product Moment và Workflow Evidence. Với sản phẩm AI coding, điểm khác biệt không chỉ là model sinh code tốt, mà là AI có giảm được bao nhiêu bước trung gian trong workflow thật của developer.




---

## Phần 3 — Điểm yếu / chỗ chưa thuyết phục

Bằng chứng yếu, lập luận lỏng, framework dùng sai. Chỉ rõ chỗ nào trong slide deck của nhóm khác.

**Điểm yếu 1** (từ nhóm: Quang & Hưng - Cursor vs Copilot):

- Cụ thể: Ở S2.2, nhóm đánh giá Cognitive burden của GitHub Copilot là "Thấp" (tương đương Cursor) vì "giao tiếp tự nhiên".
- Bằng chứng gì còn thiếu: Nhóm bỏ qua việc Copilot Chat yêu cầu user tự copy/paste code vào đúng vị trí và tự duy trì context trong đầu (so với nút Apply của Cursor). Bằng chứng ở S2.1 của nhóm ghi rõ user phải "copy thủ công".
- Tôi sẽ đề xuất họ làm thêm gì: Đánh giá Cognitive burden của Copilot là "Trung bình/Cao" vì mental load cho việc map code từ chat vào editor thủ công là khá lớn.


**Điểm yếu 2** (từ nhóm Hoàng Văn Bắc — Cursor vs GitHub Copilot):

- Cụ thể: Nhóm kết luận Cursor thắng nhờ workflow agentic và trải nghiệm ít gián đoạn hơn, nhưng phần Business Signal có một số claim adoption khá mạnh như "NVIDIA trang bị cho toàn bộ 40.000 kỹ sư" mà trong slide/report chưa thấy nguồn cụ thể đi kèm.
- Bằng chứng gì còn thiếu: Cần URL nguồn chính thức hoặc báo uy tín cho số adoption enterprise. Nếu không có nguồn, nên đổi thành nhận định mềm hơn như "Cursor đang được nhiều đội engineering lớn thử nghiệm/sử dụng".
- Tôi sẽ đề xuất họ làm thêm gì: Thêm 1 slide nguồn cho pricing/adoption, hoặc ghi rõ claim nào là số liệu công khai, claim nào là quan sát/ước tính.

---

## Phần 4 — Câu hỏi đặt cho nhóm khác

Câu hỏi gắn với bằng chứng cụ thể, không hỏi chung chung.

- Cho nhóm Hoàng Văn Bắc: Nếu test cùng task landing page nhưng yêu cầu sửa 3 vòng theo feedback của khách hàng, Cursor còn thắng Copilot bao nhiêu phần là nhờ workflow, và bao nhiêu phần là nhờ chất lượng output ban đầu?
- Cho nhóm Hoàng Văn Bắc: Với Copilot có lợi thế distribution trong VS Code/GitHub, nhóm đánh giá switching cost từ Copilot sang Cursor trong một team thật là thấp, trung bình hay cao? Bằng chứng nào trong workflow ủng hộ nhận định đó?
- Cho nhóm Quang & Hưng: Ở S3.1, các bạn đánh giá cả 2 tool đều "Không bịa (hallucination)". Tuy nhiên với code, AI thường hay bịa các hàm thư viện không tồn tại khi gặp edge cases khó. Các bạn đã thử các edge cases cực đoan để ép AI hallucinate chưa, hay chỉ đang test "happy path"?

---

## Phần 5 — Điều tôi rút ra cho bản thân

Bài học cụ thể tôi sẽ áp dụng vào lần phân tích sản phẩm AI tiếp theo. Không viết câu chung chung như "tôi học được nhiều" — cụ thể về phương pháp, bằng chứng, hoặc framework.

**Bài học 1**:

- Tôi sẽ làm khác lần sau: Linh hoạt định nghĩa lại "Trust Signal" (Tín hiệu tin cậy) dựa trên đặc thù ngành và định dạng output, thay vì áp dụng cứng nhắc một tiêu chuẩn. Ví dụ: với tool lập trình, trust là code chạy được và vượt qua unit test; với tool nghiên cứu, trust là trích dẫn chính xác trang PDF gốc (source-grounding).
- Lý do: Nếu đánh giá sai yếu tố cốt lõi tạo nên niềm tin của người dùng cuối, toàn bộ phân tích về Product Moment và lợi thế cạnh tranh của sản phẩm sẽ bị lệch hướng, không phản ánh đúng lý do vì sao người dùng sẵn sàng trả tiền.

**Bài học 2**:

- Tôi sẽ làm khác lần sau: Đi sâu vào đánh giá độ ma sát ("friction") và tải nhận thức ("cognitive burden") trong toàn bộ workflow, thay vì chỉ so sánh chất lượng AI model. Tôi sẽ cụ thể hóa bằng cách đếm số thao tác thủ công (copy/paste) hoặc số lần chuyển đổi ngữ cảnh (context-switch) mà user phải làm để ra được kết quả cuối.
- Lý do: AI model xuất sắc chưa chắc tạo ra một AI product xuất sắc. Trải nghiệm ít gián đoạn (như tính năng Composer/Apply của Cursor) thường mang lại giá trị cao hơn nhiều so với việc model sinh text hay code tốt nhưng bắt người dùng phải tự lắp ráp thủ công.



---

## Checklist trước khi nộp

- [ ] Phần 1 ghi rõ ≥ 2 nhóm đã quan sát (mã 2 học viên + ngành + sản phẩm).
- [ ] Phần 2 có ≥ 2 quan sát hay, gắn với nhóm cụ thể.
- [ ] Phần 3 có ≥ 2 điểm yếu / câu hỏi chưa được trả lời.
- [ ] Phần 4 có ≥ 2 câu hỏi cụ thể cho nhóm khác.
- [ ] Phần 5 có ≥ 2 bài học rút ra, kèm lý do và cách áp dụng lần sau.
