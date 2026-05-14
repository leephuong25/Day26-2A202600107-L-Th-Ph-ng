---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu: tìm 1 case bị big tech AI ảnh hưởng + số liệu thật

Mục tiêu: bạn tự chọn 1 sản phẩm hoặc 1 công ty bị ảnh hưởng nặng sau khi big tech AI (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...) ra mắt tính năng tương tự. Tự tìm số liệu cụ thể về case đó từ nguồn công khai. Mỗi số liệu phải có nguồn (URL + tên báo/tổ chức + ngày tháng). Lab 1 là phần cá nhân — mỗi học viên tự chọn case riêng và tự làm phần research trong repo cá nhân.

Lý do làm bước này: phân tích chỉ có sức nặng khi đứng trên số liệu thật. Bạn cần tự tìm ít nhất 8-10 số liệu cụ thể để có nền tảng phản biện cho 4 câu hỏi ở phase 2.

Quy tắc: **không có số liệu = không có nhận định**. Học viên tự tìm số liệu cho case mình chọn. Mỗi nhận định phải có nguồn (URL + ngày).

## Bước 0 — Chọn case (5 phút đầu)

Trước khi tìm số liệu, bạn quyết định case nào:

1. Sản phẩm/công ty bạn chọn là gì?
2. Big tech AI nào ra tính năng tương tự gây ảnh hưởng? (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...)
3. Vì sao bạn chọn case này? (Có số liệu công khai? Có mốc thời gian rõ? Có liên hệ với ngành bạn quan tâm?)

Ghi câu trả lời ngắn vào ô dưới đây trước khi bắt đầu tìm số liệu.

- **Tên case**: Chegg (nền tảng hỗ trợ học tập, giải bài tập trực tuyến)
- **Big tech AI tạo áp lực**: ChatGPT (OpenAI)
- **Lý do chọn**: Có số liệu cổ phiếu niêm yết (CHGG) rõ ràng từ Yahoo Finance, doanh thu/subscribers giảm mạnh sau ChatGPT ra mắt tháng 11/2022, liên quan ngành EdTech đang hot; dễ verify từ SEC filings và tier-1 media.

## Quy trình 15 phút

```text
5 phút  — Chọn case + xác định 4 nhóm số liệu cần tìm cho case của mình
8 phút  — Tự tìm số liệu trên các nguồn chính (báo chí công nghệ, báo cáo tài chính, blog chính thức...)
2 phút  — Rà lại bảng số liệu, đánh dấu số chưa kiểm chứng
```

---

## Phần A — Các nhóm số liệu cần tìm


### Nhóm 1 — Quy mô trước & sau (cổ phiếu, doanh thu, người dùng)

- Cổ phiếu CHGG đạt đỉnh $113.51 vào 02/2021 (theo MacroTrends). Tính đến 11/05/2026, giá đóng cửa còn $1.00.
- Vốn hóa thị trường đỉnh: $14.7 tỷ USD (tháng 2/2021). Hiện tại (tháng 4/2026): ~$115 triệu USD — mức sụt giảm ~99% giá trị cổ đông.
- Doanh thu năm 2021 đạt đỉnh $776.3 triệu USD, tăng 20% so với năm trước. Số subscriber đạt 7.8 triệu người, tăng 18% YoY.
- Doanh thu toàn năm 2023: $716 triệu USD. Subscription Services giảm 5% xuống còn $641 triệu. Tổng subscriber: 7.7 triệu.
- Doanh thu 2024: $616 triệu USD (giảm 13.9% so với 2023). Net loss 2024: $837 triệu USD. Số subscriber 2024: 6.6 triệu người, giảm 14.2% YoY.
- Subscriber giảm từ đỉnh 7.8 triệu xuống còn ~3.2 triệu vào đầu năm 2025. Doanh thu ước tính annualized 2025 khoảng $290 triệu — giảm 63% so với đỉnh trong 4 năm.

Nguồn đã dùng:
- MacroTrends: https://www.macrotrends.net/stocks/charts/CHGG/chegg/stock-price-history

- Gizmodo: https://gizmodo.com/chegg-is-on-its-last-legs-after-chatgpt-sent-its-stock-down-99-2000522585

- SEC Form 8-K FY2021: https://www.sec.gov/Archives/edgar/data/0001364954/000136495422000007/a9901-financialresultsq421.htm

- FY2023 Chegg IR: https://investor.chegg.com/Press-Releases/press-release-details/2024/Chegg-Reports-2023-Fourth-Quarter-and-Full-Year-Financial-Results/default.aspx

- FY2024 Business of Apps: https://www.businessofapps.com/data/chegg-statistics/

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

- ChatGPT ra mắt chính thức ngày 30/11/2022 miễn phí. Đạt 1 triệu người dùng trong 5 ngày, và 100 triệu người dùng chỉ trong 2 tháng — trở thành ứng dụng người dùng tăng trưởng nhanh nhất lịch sử. 
- ChatGPT trùng lặp trực tiếp với use case cốt lõi của Chegg: hỏi-đáp bài tập, giải thích step-by-step, hỗ trợ toán và văn. Miễn phí so với Chegg $15.95–$19.95/tháng.

Nguồn đã dùng:
- Wikipedia: https://en.wikipedia.org/wiki/ChatGPT

- European Business Magazine: https://europeanbusinessmagazine.com/chegg-stock-collapse-chatgpt-ai-disruption-2026/


### Nhóm 3 — Phản ứng của sản phẩm / công ty sau khi big tech AI ra mắt

- Ngày 02/05/2023 — CEO Dan Rosensweig lần đầu thừa nhận trên earnings call: "Kể từ tháng 3, chúng tôi thấy sự tăng đột biến đáng kể về sự quan tâm của sinh viên với ChatGPT. Chúng tôi tin rằng điều này đang ảnh hưởng đến tốc độ tăng trưởng khách hàng mới của chúng tôi." Cổ phiếu giảm 48.41% trong một ngày (xuống $9.08). 
- Tháng 4/2023, Chegg ra mắt CheggMate — sản phẩm AI hợp tác với chính OpenAI, tích hợp GPT-4 và 120 triệu câu trả lời lưu trữ. Khoảng cách từ khi ChatGPT ra mắt đến khi Chegg phản ứng: ~5 tháng.
- Tháng 5/2025: Chegg sa thải 22% nhân sự (~248 nhân viên), đóng cửa văn phòng tại Mỹ và Canada. 
- Tháng 10/2025: Chegg sa thải thêm 45% nhân sự (~388 nhân viên), trích dẫn "thực tại mới của AI" và lưu lượng truy cập từ Google sụt giảm. Tổng 2 đợt sa thải trong 6 tháng: 636 người, tương đương ~67% lực lượng lao động. 
- Tháng 2/2025: Chegg kiện Google với cáo buộc tính năng AI Overviews chuyển hướng lưu lượng truy cập khỏi website Chegg. 

Nguồn đã dùng:
- CNBC: https://www.cnbc.com/2023/05/02/chegg-drops-more-than-40percent-after-saying-chatgpt-is-killing-its-business.html

- Final Round AI: https://www.finalroundai.com/blog/chegg-layoffs-2025

- Sherwood News: https://sherwood.news/business/chegg-biggest-chatgpt-gen-ai-loser/

### Nhóm 4 — Đối thủ AI thay thế

- ChatGPT thay thế Chegg ở use case cốt lõi: hỏi-đáp bài tập tức thời, giải thích step-by-step, câu hỏi follow-up không giới hạn — miễn phí và nhanh hơn (Chegg yêu cầu chờ contractor trả lời, đôi khi vài giờ). 
- Khanmigo (Khan Academy AI) — ra mắt 2023, dùng phương pháp Socratic, miễn phí cho học sinh (tài trợ phi lợi nhuận). 
- Socratic by Google — miễn phí hoàn toàn, chụp ảnh bài tập và giải thích step-by-step. 


So sánh giá:

| Sản phẩm | Giá/tháng | Mô hình | Ra mắt |
|---|---|---|---|
| Chegg Study Pack | $19.95 | Trả phí, chờ contractor | 2010s |
| ChatGPT (free tier) | **$0** | AI tức thì, không giới hạn | 30/11/2022 |
| ChatGPT Plus | $20 | GPT-4/5, ngang giá Chegg | Feb 2023 |
| Khanmigo (Khan Academy) | **$0** (học sinh) | AI Socratic, phi lợi nhuận | 2023 |
| Socratic by Google | **$0** | Chụp ảnh → giải thích ngay | 2017, AI update 2019 |
| Google Gemini | **$0** (free tier) | Tổng quát + tích hợp Google Search | 2023 |

Nguồn đã dùng:

- CNBC Nasdaq: https://www.nasdaq.com/articles/will-chatgpt-be-the-final-nail-in-the-coffin-for-chegg

- Khanmigo My Engineering Buddy: https://www.myengineeringbuddy.com/blog/khanmigo-reviews-alternatives-pricing-offerings/

---

## Phần B — Bảng tổng hợp số liệu

Sau khi tìm đủ 4 nhóm số liệu, bạn gộp vào bảng dưới đây. Mục tiêu: tối thiểu 8-10 số liệu có nguồn cụ thể.

### Bảng số liệu case Chegg

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Cổ phiếu CHGG đỉnh | $113.51 | 12/02/2021 | [MacroTrends](https://www.macrotrends.net/stocks/charts/CHGG/chegg/stock-price-history) | Có — cross-check MacroTrends + TradingView |
| S-02 | Cổ phiếu CHGG hiện tại | ~$1.00 | 11/05/2026 | [MacroTrends](https://www.macrotrends.net/stocks/charts/CHGG/chegg/stock-price-history) | Có |
| S-03 | Vốn hóa đỉnh → hiện tại | $14.7B → ~$115M (~-99%) | Feb 2021 → Apr 2026 | [Gizmodo 25/02/2025](https://gizmodo.com/chegg-is-on-its-last-legs-after-chatgpt-sent-its-stock-down-99-2000522585) | Có |
| S-04 | Doanh thu đỉnh (FY2021) | $776.3M (+20% YoY) | FY2021 | [SEC 8-K Chegg](https://www.sec.gov/Archives/edgar/data/0001364954/000136495422000007/a9901-financialresultsq421.htm) | Có — nguồn gốc SEC |
| S-05 | Doanh thu FY2024 + net loss | $617.6M doanh thu; -$837.1M net loss | FY2024 | [Business of Apps](https://www.businessofapps.com/data/chegg-statistics/) | Chưa — cần verify tại investor.chegg.com |
| S-06 | ChatGPT ra mắt | 30/11/2022, miễn phí | 30/11/2022 | [Wikipedia ChatGPT](https://en.wikipedia.org/wiki/ChatGPT) | Có |
| S-07 | ChatGPT đạt 100M users | 2 tháng sau ra mắt (Jan 2023) | Jan 2023 | [Wikipedia ChatGPT](https://en.wikipedia.org/wiki/ChatGPT) | Có |
| S-08 | Cổ phiếu -48% trong 1 ngày + CEO thừa nhận ChatGPT | -48.41%, xuống $9.08 | 02/05/2023 | [CNBC 02/05/2023](https://www.cnbc.com/2023/05/02/chegg-drops-more-than-40percent-after-saying-chatgpt-is-killing-its-business.html) | Có — CNBC tier-1 |
| S-09 | CheggMate ra mắt (phản ứng AI) | Tháng 4/2023, GPT-4 + OpenAI | Apr 2023 | [Final Round AI](https://www.finalroundai.com/blog/chegg-layoffs-2025) | Chưa — cross-check Chegg IR |
| S-10 | Thời gian phản ứng sau ChatGPT | ~5 tháng | Nov 2022 → Apr 2023 | [Sherwood News Nov 2024](https://sherwood.news/business/chegg-biggest-chatgpt-gen-ai-loser/) | Có |
| S-11 | Sa thải tổng 2 đợt (2025) | 636 người, ~67% workforce | May–Oct 2025 | [CNBC 27/10/2025](https://www.cnbc.com/2025/10/27/chegg-slashes-45percent-of-workforce-blames-new-realities-of-ai.html) | Có — CNBC tier-1 |
| S-12 | Subscriber đỉnh → Q1 2025 | 7.8M → ~3.2M (-59%) | 2021 → Q1 2025 | [European Business Magazine](https://europeanbusinessmagazine.com/chegg-stock-collapse-chatgpt-ai-disruption-2026/) | Chưa — cross-check Q1 2025 earnings release |
| S-13 | Giá Chegg vs ChatGPT | $19.95/tháng vs $0 | 2023–2026 | [CNBC Nasdaq 08/05/2023](https://www.nasdaq.com/articles/will-chatgpt-be-the-final-nail-in-the-coffin-for-chegg) | Có |
| S-14 | Traffic non-subscriber giảm | -49% YoY | Jan 2025 | [European Business Magazine](https://europeanbusinessmagazine.com/chegg-stock-collapse-chatgpt-ai-disruption-2026/) | Chưa — cần verify |

---

## Phần C — Kiểm chứng nguồn

Trước khi chuyển sang phân tích, rà lại từng số liệu:

### Checklist kiểm chứng

- [ ] Mỗi số liệu có URL nguồn cụ thể.
- [ ] URL mở được, không 404.
- [ ] Nội dung URL có khớp với số liệu mình ghi (ít nhất là cùng đơn vị, cùng năm).
- [ ] Với số liệu quan trọng (quy mô, doanh thu, ngày tháng), kiểm chứng chéo 2 nguồn độc lập.
- [ ] Nếu chưa chắc, đánh dấu `[CHƯA KIỂM CHỨNG]` thay vì xoá.

### Quy tắc loại nguồn

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 — Nguồn gốc | Báo cáo tài chính, thông báo chính thức, hồ sơ pháp lý | 10-K filings, SEC filings, blog công ty |
| 2 — Báo lớn | Báo chí công nghệ/kinh doanh uy tín | CNBC, Bloomberg, TechCrunch, Reuters, FT |
| 3 — Báo cáo phân tích | Báo cáo tài chính độc lập | MacroTrends, Yahoo Finance, Google Finance |
| 4 — Tránh dùng | Bài đăng cá nhân, blog không nguồn, mạng xã hội | Reddit posts, Medium articles không có citation |

### Cảnh báo

AI có thể bịa cả nguồn — đặc biệt khi bạn hỏi AI số liệu thay vì tự tìm. Nếu dùng AI để gợi ý nơi tìm, vẫn phải tự mở URL và xác minh.


**Số liệu cần fact-check thủ công trước khi dùng trong phân tích:**

- S-05 (doanh thu và net loss FY2024): nguồn Business of Apps là tổng hợp — cần xác minh tại https://investor.chegg.com hoặc SEC filing FY2024.
- S-12 (subscriber Q1 2025: ~3.2M): nguồn European Business Magazine. Nasdaq báo cáo Q4 2024 là 3.6M — cần earnings release Q1 2025 chính thức để xác nhận con số chính xác.

---

## Phần D — Phát hiện ban đầu

- Chegg mất ~99% giá trị cổ phiếu (từ $113.51 xuống ~$1.00) chỉ trong ~39 tháng kể từ khi ChatGPT ra mắt — nhanh hơn Kodak, Blockbuster hay Nokia nhiều lần (các case đó mất 5–10 năm mới sụp đổ).
- Chegg mất 5 tháng mới ra sản phẩm AI phản ứng (CheggMate, tháng 4/2023), trong khi ChatGPT đã đạt 100 triệu người dùng chỉ sau 2 tháng — thời điểm CheggMate ra mắt, sinh viên đã quen dùng ChatGPT miễn phí và không có lý do để trả $19.95/tháng.
- Giá sản phẩm gốc là $19.95/tháng, trong khi ChatGPT free là $0 — đây không phải disruption kiểu "rẻ hơn một chút" mà là "tốt hơn + miễn phí hoàn toàn", xóa sổ toàn bộ lý do trả tiền cho Chegg.
- Chegg là công ty niêm yết đầu tiên trên thế giới chính thức thừa nhận AI gây thiệt hại doanh thu (02/05/2023) — điều này khiến case có giá trị lịch sử đặc biệt trong phân tích AI disruption.
- Hai đợt sa thải trong 6 tháng (22% + 45%) xóa sổ ~67% lực lượng lao động — Chegg không pivot chiến lược có kiểm soát mà đang thu nhỏ khẩn cấp để tồn tại.


---

## Phần E — Câu hỏi mở (cho phân tích Phần 2)

- Câu hỏi 1: Chegg có nhận ra mối đe dọa từ AI trước 11/2022 không? Nếu có — tại sao leadership không phản ứng sớm hơn? (Internal resistance, hay không tin ChatGPT đủ tốt?)
- Câu hỏi 2: CheggMate thất bại vì lý do gì cụ thể — thiếu differentiation hay thiếu execution? Đây có phải bẫy "partner with the disruptor" kinh điển không?
- Câu hỏi 3: Chegg còn use case nào ChatGPT/AI chưa thay thế được không, và công ty có thể xây moat mới từ đó không (vd: academic integrity, institutional B2B)?
- Câu hỏi 4: Google AI Overviews phá hủy traffic của Chegg như thế nào — và điều này báo hiệu gì cho tất cả các công ty đang dựa vào SEO/organic search làm kênh phân phối chính?

