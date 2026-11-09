# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên mất từ vài giờ trở lên cho mỗi môn để tổng hợp tài liệu | Value | 5 | 1 | ✅ |
| 2 | Tài liệu bị phân tán (slide, PDF, ghi chú, nhóm chat) khiến việc tìm lại mất nhiều thời gian | Value | 4 | 1 | ✅ |
| 3 | Sinh viên khó tìm đủ đề thi cũ hoặc câu luyện sát nội dung môn | Value | 5 | 1 | ✅ |
| 4 | Thiếu bao quát nội dung khi ôn dẫn đến bỏ sót kiến thức trong bài thi | Value | 4 | 0 | Sau lab |
| 5 | Sinh viên sẵn sàng đưa tài liệu môn học lên một công cụ bên thứ ba | Viability | 5 | 0 | Hỏi trước |
| 6 | Sinh viên tin câu hỏi do công cụ tạo ra đủ sát với đề thi thật | Usability | 4 | 0 | ✅ |

### 3.2. Kiểm chứng

Nhóm phỏng vấn 3 sinh viên đã thi ít nhất một kỳ trong 6 tháng gần đây và làm poll 4 người trong lớp.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi | A, sinh viên năm ba, thi môn giải tích 2 |
| Câu nói đáng nhớ nhất | Giải tích là dễ, phần lâu nhất là tìm tài liệu để học |
| Lần gần nhất gặp vấn đề này | 3 tuần trước khi thi, mất khoảng 4 giờ cho việc tìm tài liệu tổng ôn từ các nguồn khác nhau |
| Hiện đang xử lý bằng cách nào (workaround)? | Note hết tài liệu vào 1 chỗ |
| Mất bao lâu, bao lần? | Mất khoảng 4 giờ cho việc tổng hợp tài liệu, khoảng 1 tuần 1 lần |
| Insight / opportunity rút ra | Pain nằm ở phần tìm tài liệu |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 3 | 2/3 người mất trên 3 giờ để tìm và tổng hợp tài liệu | 1 người nói chỉ cần học nhóm là đủ |
| Poll trong lớp | 4 | 2/4 người từng phải tìm lại đề cũ từ nhiều nguồn | 2/4 người còn lại nói rằng lấy đề từ Khoa là đủ | 

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- **Thu hẹp phạm vi:** từ tổng hợp kiến thức và tìm đề luyện tập thành gom và tổng hợp tài liệu ôn thi từ nhiều nguồn.
- **Lý do:** 2/3 người phỏng vấn mất trên 3 giờ ở việc tìm và tổng hợp tài liệu. Trong poll, 2/4 người từng phải tìm lại đề cũ từ nhiều nguồn, nhưng 2/4 người còn lại nói đề từ Khoa là đủ. Điều này cho thấy pain về đề luyện tập không đồng đều giữa các sinh viên và các môn.
- **Bottleneck:** giữ bước 3 (đọc, phân loại, tổng hợp), giảm trọng tâm ở bước 4 (tìm đề). Bước 4 chỉ là vấn đề với những môn không có đề cũ từ Khoa.
- **Phương án không dùng AI:** giữ nguyên (Notion/Google Docs theo chương, thư mục, checklist), vì một người phỏng vấn đã dùng cách này và vẫn mất nhiều thời gian ở bước tìm tài liệu.
- **Giả định 3** (khó tìm đủ đề cũ) vẫn chưa đủ bằng chứng, vì tín hiệu phản bác từ poll còn mạnh.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Notion / Google Docs (ghi chú theo chương) | https://www.notion.so | Bước 3: tổng hợp và lưu ghi chú | Miễn phí, quen thuộc, người phỏng vấn đang dùng | Không tự tìm hay gom tài liệu từ nguồn khác; phụ thuộc người nhập tay | Workaround này đã có sẵn, nên giải pháp mới phải làm được thứ nó chưa làm: gom tự động từ nhiều nguồn |
| NotebookLM (hỏi đáp dựa trên tài liệu tải lên) | https://notebooklm.google.com | Bước 2 và 3: phân loại và tổng hợp từ tài liệu đã tải lên | Trả lời dựa trên tài liệu của chính người dùng | Phải tải tài liệu môn học lên; rủi ro bản quyền và quy định của khoa (A5); không tự tìm nguồn ngoài | Gần nhất với ý tưởng của nhóm, nên là điểm kiểm chứng chính cho A5 trước khi chọn hướng |
| Quizlet | https://quizlet.com | Bước 6: luyện tập và đối chiếu | Luyện tập lặp lại có hệ thống | Không tổng hợp từ tài liệu gốc; cần người tự tạo thẻ | Phần luyện tập đã có công cụ phổ biến, nên pain của nhóm nằm ở bước trước đó |
| Đề thi cũ của Khoa / thư viện | https://tailieuvnu.com/ | Bước 4: tìm đề thi và bài tập | Đúng cấu trúc đề thật | Không có cho mọi môn; 2/4 người trong poll nói đây là đủ | Cho thấy pain về đề chỉ có ở một số môn; không nên xem là vấn đề chung của mọi sinh viên |

#### Kết luận research
Một phần quy trình đã có công cụ làm được (ghi chú, luyện tập lặp lại). Phần gom tài liệu và sinh câu luyện bám nội dung môn còn trống, nhưng chưa đủ bằng chứng để xây mới.
Hướng hợp lý: Rule gom tài liệu theo chương/CLO → AI soạn câu luyện và tóm tắt từ tài liệu đã gom → SV duyệt, đối chiếu với tài liệu gốc → ôn phần yếu.

---
## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Hiện tại, sinh viên chủ yếu tự thu thập tài liệu, tổng hợp kiến thức và tìm kiếm câu hỏi để ôn tập. Các công việc được thực hiện thủ công, phân tán trên nhiều nguồn khác nhau.

**Sơ đồ quy trình hiện tại:**

```text
[1. Thu thập tài liệu]
        |
        v
[2. Đọc và phân loại tài liệu]
        |
        v
[3. Tổng hợp kiến thức]  <-- BOTTLENECK 1
        |
        v
[4. Tìm kiếm đề thi và bài tập]  <-- BOTTLENECK 2
        |
        v
[5. Lựa chọn câu hỏi phù hợp]
        |
        v
[6. Làm bài và đối chiếu đáp án]
        |
        v
[7. Xác định kiến thức còn yếu và ôn tập lại]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|:----:|-------|-------|--------|----------------------|---------|
| 1 | Sinh viên | Slide, PDF, giáo trình, ghi chú từ nhiều nguồn | Tập hợp tài liệu môn học | 20 phút / mỗi kỳ ôn tập | Tài liệu phân tán, có thể trùng lặp hoặc thiếu |
| 2 | Sinh viên | Tập hợp tài liệu đã thu thập | Tài liệu đã đọc và phân loại theo chương/chủ đề | 30 phút / mỗi kỳ ôn tập | Phải tự xác định nội dung quan trọng |
| 3 | Sinh viên | Tài liệu đã phân loại | Bản tổng hợp kiến thức, ghi chú ôn tập | 60 phút / mỗi kỳ ôn tập | **Bottleneck:** Tốn thời gian tổng hợp, khó đảm bảo không bỏ sót kiến thức |
| 4 | Sinh viên | Nội dung môn học, các nguồn tài liệu bên ngoài | Tập hợp đề thi cũ, bài tập và câu hỏi | 45 phút / mỗi kỳ ôn tập | **Bottleneck:** Khó tìm được câu hỏi phù hợp với nội dung và phạm vi thi |
| 5 | Sinh viên | Đề thi, bài tập đã tìm được | Bộ câu hỏi phù hợp để luyện tập | 20 phút / mỗi kỳ ôn tập | Phải tự đánh giá mức độ liên quan và độ khó |
| 6 | Sinh viên | Bộ câu hỏi luyện tập | Bài làm và kết quả đối chiếu đáp án | 45 phút / mỗi kỳ ôn tập | Phụ thuộc vào việc có đáp án hoặc lời giải |
| 7 | Sinh viên | Kết quả làm bài, các câu trả lời sai | Danh sách kiến thức cần ôn tập lại | 20 phút / mỗi kỳ ôn tập | Việc xác định lỗ hổng kiến thức chủ yếu dựa vào tự đánh giá |

**Tổng thời gian ước tính: 240 phút (khoảng 4 giờ).**

**Bottleneck chính:**

1. **Bước 3 – Tổng hợp kiến thức:** Sinh viên phải đọc và tổng hợp thông tin từ nhiều tài liệu khác nhau. Quá trình này tốn thời gian, đòi hỏi khả năng chọn lọc và có nguy cơ bỏ sót nội dung quan trọng.
2. **Bước 4 – Tìm kiếm đề thi và bài tập:** Sinh viên phải tìm kiếm từ nhiều nguồn, sau đó tự đánh giá mức độ phù hợp với nội dung môn học. Việc tìm được đủ câu hỏi chất lượng và đúng trọng tâm không phải lúc nào cũng dễ dàng.

### 4.2. Quy trình tương lai

Đề xuất xây dựng một hệ thống hỗ trợ ôn tập có AI, cho phép sinh viên lưu trữ tài liệu môn học xuyên suốt học kỳ. Khi đến kỳ thi, hệ thống sử dụng tài liệu đã lưu và chuẩn đầu ra môn học (CLOs) để hỗ trợ tổng hợp kiến thức, tạo câu hỏi luyện tập và đánh giá kết quả học tập.

**Sơ đồ quy trình tương lai:**

```text
[1. Tải tài liệu trong suốt học kỳ] (HUMAN)
        |
        v
[2. Tự động lưu trữ và phân loại tài liệu] (RULE)
        |
        v
[3. AI phân tích tài liệu và đối chiếu CLOs] (AI)
        |
        v
[4. AI tổng hợp kiến thức và tạo đề luyện tập] (AI)
        |
        v
[5. Sinh viên kiểm tra nội dung và lựa chọn đề] (HUMAN - HITL)
        |
        v
[6. Sinh viên làm bài, AI hỗ trợ đánh giá kết quả] (HUMAN + AI)
        |
        v
[7. AI phân tích lỗi sai, đề xuất nội dung cần ôn tập] (AI)
        |
        v
[8. Sinh viên kiểm tra và ôn tập lại] (HUMAN)
```

**Phân định vai trò và phạm vi xử lý:**

| Bước | Thành phần | Nhiệm vụ | Boundary / Kiểm soát |
|:----:|:----------:|----------|----------------------|
| 1 | Human | Tải lên slide, PDF, giáo trình, ghi chú và CLOs trong quá trình học | Sinh viên chịu trách nhiệm cung cấp đúng tài liệu và thông tin môn học |
| 2 | Rule | Lưu trữ, sắp xếp tài liệu theo môn học, chương và loại tài liệu | Chỉ xử lý các thao tác lưu trữ, phân loại theo quy tắc; không tự suy diễn nội dung |
| 3 | AI | Đọc, trích xuất và phân tích nội dung tài liệu; đối chiếu với CLOs | Kết quả phân tích phải dựa trên tài liệu được cung cấp; cần thông báo nếu không đọc được hoặc thiếu dữ liệu |
| 4 | AI | Tổng hợp kiến thức theo chủ đề, tạo câu hỏi và đề luyện tập theo phạm vi tài liệu và CLOs | Không tự khẳng định nội dung do AI tạo ra là chính xác tuyệt đối; cần chỉ ra nguồn tham chiếu khi có thể |
| 5 | Human | Kiểm tra bản tổng hợp, lựa chọn hoặc chỉnh sửa bộ câu hỏi trước khi sử dụng | Sinh viên có quyền chấp nhận, chỉnh sửa hoặc từ chối kết quả AI |
| 6 | Human + AI | Sinh viên làm bài; AI hỗ trợ chấm và giải thích đáp án | AI chỉ đưa ra kết quả đánh giá tham khảo; sinh viên có thể yêu cầu kiểm tra lại |
| 7 | AI | Phân tích câu trả lời sai, xác định chủ đề còn yếu và đề xuất nội dung cần ôn tập | Không tự kết luận năng lực tổng thể của sinh viên chỉ từ một bài kiểm tra |
| 8 | Human | Kiểm tra đề xuất và chủ động ôn tập lại kiến thức | Quyết định nội dung và cách thức học tập cuối cùng thuộc về sinh viên |

**Boundary và phương án quay về khi AI sai:**

- AI chỉ xử lý tài liệu do sinh viên cung cấp, không tự ý bổ sung kiến thức ngoài phạm vi môn học mà không thông báo nguồn.
- Các nội dung tổng hợp, câu hỏi và đáp án do AI tạo ra cần có nguồn tham chiếu để sinh viên kiểm tra.
- Nếu AI không đọc được tài liệu, thiếu dữ liệu hoặc đưa ra kết quả không đáng tin cậy, hệ thống phải thông báo thay vì tự tạo nội dung như thể đã xác minh.
- Sinh viên có thể chỉnh sửa nội dung, tự đối chiếu với tài liệu gốc hoặc quay về phương pháp ôn tập thủ công.
- AI đóng vai trò hỗ trợ học tập, không thay thế giảng viên trong việc xác định kiến thức chính thức hoặc đánh giá kết quả học tập có tính quyết định.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|--------|:-----:|:-------------:|---------|
| Số bước | 7 | 8 | Bổ sung bước lưu trữ tài liệu xuyên suốt học kỳ và bước kiểm tra kết quả AI |
| Tổng thời gian | ~240 phút | ~120 phút | Mục tiêu giảm khoảng 50% thời gian chuẩn bị; chưa tính thời gian học và làm bài thực tế |
| Số bước thủ công | 7/7 | 4/8 | Các bước lưu trữ, phân tích, tổng hợp và đánh giá được AI/Rule hỗ trợ |
| Bottleneck chính | Tổng hợp kiến thức và tìm kiếm câu hỏi | Kiểm tra độ chính xác, mức độ bao phủ và tính phù hợp của kết quả AI | Bottleneck chuyển từ xử lý thủ công sang kiểm soát chất lượng đầu ra |
| Rủi ro mới phát sinh | Tốn thời gian, bỏ sót kiến thức, tài liệu phân tán | AI tổng hợp sai, tạo câu hỏi không phù hợp, đánh giá sai câu trả lời hoặc bỏ sót nội dung | Cần nguồn tham chiếu, Human-in-the-loop và phương án xử lý thủ công |

> *Lưu ý: Các số liệu ở cột Sau là mục tiêu giả định ban đầu để định hướng thiết kế giải pháp. Cần kiểm chứng bằng thử nghiệm thực tế với sinh viên và cùng một bộ tài liệu trước khi kết luận hiệu quả.*

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|--------|----------|
| **Actor** | Sinh viên đại học đang chuẩn bị cho các kỳ kiểm tra giữa kỳ hoặc cuối kỳ. |
| **Quy trình** | Sinh viên thu thập tài liệu từ nhiều nguồn, đọc và phân loại nội dung, tự tổng hợp kiến thức, tìm kiếm đề thi và bài tập, lựa chọn câu hỏi phù hợp, luyện tập và xác định phần kiến thức còn yếu để ôn tập lại. |
| **Bottleneck** | Việc tổng hợp kiến thức từ nhiều tài liệu và tìm kiếm câu hỏi luyện tập phù hợp chủ yếu được thực hiện thủ công, tốn thời gian và khó đảm bảo mức độ bao phủ đầy đủ nội dung môn học. |
| **Impact** | Sinh viên mất nhiều thời gian chuẩn bị trước kỳ thi, tài liệu ôn tập bị phân tán, có nguy cơ bỏ sót kiến thức quan trọng và thiếu câu hỏi luyện tập phù hợp. Điều này làm giảm hiệu quả ôn tập và gây khó khăn trong việc xác định chính xác những phần kiến thức còn yếu. |
| **Success Metric** | **Thời gian chuẩn bị:** giảm từ khoảng 240 phút xuống tối đa 120 phút cho một chu kỳ chuẩn bị ôn tập với cùng phạm vi tài liệu.<br>**Mức độ bao phủ kiến thức:** tăng tỷ lệ nội dung trong CLOs được đề cập trong bản tổng hợp và bộ câu hỏi.<br>**Mức độ phù hợp:** tỷ lệ câu hỏi được sinh viên đánh giá là phù hợp với tài liệu và phạm vi môn học.<br>**Cách đo:** thử nghiệm trên cùng một bộ tài liệu, ghi nhận thời gian thực hiện và khảo sát/đánh giá đầu ra bởi sinh viên. |
| **Boundary** | AI không được tự ý khẳng định kiến thức chưa có căn cứ trong tài liệu, tự mở rộng phạm vi môn học mà không thông báo, hoặc đưa ra kết quả đánh giá có tính quyết định thay cho giảng viên. Sinh viên cần kiểm tra bản tổng hợp, câu hỏi và đáp án do AI tạo ra trước khi sử dụng. Khi tài liệu không đọc được, thiếu thông tin hoặc kết quả AI không đáng tin cậy, hệ thống phải thông báo và cho phép sinh viên quay về kiểm tra tài liệu gốc hoặc thực hiện thủ công. |

### Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không

1. **Phản biện 1:** Hai bottleneck hiện tại (tổng hợp kiến thức và tìm kiếm câu hỏi) mới là giả thuyết ban đầu, chưa có dữ liệu khảo sát chứng minh đây là những khó khăn lớn nhất của sinh viên.
    - **Đồng ý.** Cần phỏng vấn hoặc khảo sát sinh viên để xác định mức độ phổ biến, thời gian thực tế và mức độ ảnh hưởng của từng bottleneck.

2. **Phản biện 2:** Các chỉ số thành công cần có baseline và cách đo cụ thể. Việc giảm thời gian chưa đủ để chứng minh giải pháp hiệu quả nếu chất lượng kiến thức tổng hợp hoặc câu hỏi luyện tập bị giảm.
    - **Đồng ý.** Cần đánh giá đồng thời thời gian tiết kiệm được, mức độ bao phủ kiến thức và độ phù hợp của câu hỏi.

3. **Phản biện 3:** Phạm vi giải pháp ban đầu khá rộng, bao gồm lưu trữ tài liệu, phân tích CLOs, tổng hợp kiến thức, tạo đề, chấm bài và phân tích lỗ hổng kiến thức. Việc triển khai tất cả chức năng cùng lúc có thể làm tăng độ phức tạp.
    - **Đồng ý.** Nên ưu tiên kiểm chứng hai chức năng cốt lõi là tổng hợp kiến thức từ tài liệu và tạo câu hỏi luyện tập phù hợp. Các chức năng còn lại có thể được phát triển ở những giai đoạn tiếp theo.

4. **Phản biện 4:** AI có thể tổng hợp sai, tạo câu hỏi không sát nội dung hoặc đánh giá sai câu trả lời. Vì vậy, không nên để AI tự quyết định toàn bộ quá trình ôn tập.
    - **Đồng ý.** Sinh viên cần giữ vai trò kiểm tra và quyết định cuối cùng; hệ thống cần cung cấp nguồn tham chiếu và phương án quay về xử lý thủ công khi AI không đáng tin cậy.



## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Workflow có AI

Vì sao: Độ mơ hồ: trung bình (Đầu vào rõ (tài liệu, CLOs), nhưng “đủ bao quát” và “câu hỏi phù hợp” cần diễn giải nội dung.) Độ phức tạp: trung bình-cao . Nhiều nguồn, nhiều định dạng (slide, PDF, ghi chép), nhưng chuỗi bước ổn định và biết trước.

### 6.2 So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI**| Notion/Google Docs chia ghi chú theo chương; thư mục theo môn; checklist tiến độ; tự gom đề cũ và bài tập.  | Môn ít tài liệu, ít chương; sinh viên có sẵn đề cũ và đủ thời gian tự tổng hợp. | Bước 3 và 4 vẫn thủ công, tốn thời gian. Khó kiểm tra độ phủ CLO. Thiếu nguồn câu hỏi nếu không có đề cũ. | Không (dùng làm baseline) |
| **Rule** | Quy tắc cố định: gắn tag theo tên chương/từ khóa; tìm câu hỏi theo từ khóa; checklist CLO tự động đánh dấu "đã có tài liệu". | Tài liệu chuẩn hóa, đặt tên và cấu trúc thống nhất; chỉ cần phân loại và tìm kiếm, không cần hiểu nội dung. | Tài liệu đa dạng (slide, PDF, ghi chép) làm rule sai hoặc bỏ sót. Không tổng hợp được ngữ nghĩa, không sinh câu hỏi mới, không map câu hỏi ↔ CLO. | Không |
| **Workflow** | Pipeline cố định: upload → parse và phân loại → map CLO → tổng hợp có trích nguồn → sinh câu hỏi/đề luyện tập → chấm và đối chiếu → báo chủ đề yếu. AI làm từng bước đã định, sinh viên duyệt. | Các bước ổn định, biết trước; cần AI xử lý nội dung (tóm tắt, sinh câu hỏi, map CLO) nhưng không cần tự quyết hướng đi. | Ảo giác (đáp án/tóm tắt sai); bỏ sót chủ đề; parse lỗi với hình, công thức; chi phí LLM. Giảm được bằng trích nguồn, sinh viên kiểm tra, eval E1–E5. | **Chọn** |
| **Agent** | AI tự tìm nguồn ngoài, tự lập kế hoạch ôn, tự quyết bước tiếp theo theo tiến độ sinh viên. | Bài toán mở, không có quy trình cố định, cần AI tự chọn công cụ và thích nghi liên tục. | Khó kiểm soát và eval; có thể lấy nguồn sai hoặc lệch phạm vi môn; chi phí cao; sinh viên khó kiểm chứng. | Không (để phiên bản sau) |

**Mức chọn:** **Workflow**. AI hỗ trợ (augment) ở bước 3 (tổng hợp), bước 4–5 (sinh/chọn câu hỏi) và bước 7 (phát hiện lỗ hổng). Sinh viên giữ quyền quyết định và kiểm tra.

**Vì sao không chọn mức đơn giản hơn:**

- **Không chọn No AI:** Đây là cách sinh viên đang làm, và chính nó tạo ra bottleneck ở bước 3 và 4 (tốn thời gian, thiếu sót, thiếu nguồn câu hỏi). Chỉ sửa quy trình (thư mục, checklist) giúp gọn gàng hơn nhưng không giảm công việc tổng hợp và tìm câu hỏi.
- **Không chọn Rule:** Rule chỉ phân loại và tìm kiếm theo từ khóa, không hiểu nội dung. Rule không tổng hợp ngữ nghĩa từ nhiều nguồn, không sinh câu hỏi bám tài liệu và CLO, không phát hiện lỗ hổng kiến thức. Đó chính là các việc tạo ra giá trị chính.
- **Không chọn Agent (mức phức tạp hơn):** Quy trình đã rõ và ổn định nên không cần AI tự quyết bước tiếp theo. Workflow dễ kiểm soát, dễ đo bằng eval và rẻ hơn, phù hợp với nguyên tắc chọn mức đơn giản nhất đủ dùng.

### 6.3 AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| AI dự đoán | Chủ đề/khái niệm chính của từng tài liệu; chủ đề ↔ CLO; câu hỏi + đáp án + giải thích bám tài liệu; chủ đề sinh viên còn yếu |
| Con người cân nhắc | Tóm tắt có đúng và đủ không; câu hỏi có đúng phạm vi môn học không; chọn câu nào để luyện |
| Hành động | Sinh viên ôn theo tóm tắt, làm đề luyện tập, ôn lại phần được đánh dấu yếu |
| Outcome | Thời gian tổng hợp + tìm bài tập, % CLO được bao phủ, số lỗ hổng phát hiện trước thi |
| Dữ liệu đầu vào | Slide, PDF, giáo trình, ghi chú, đề cũ, danh sách CLOs, kết quả làm bài |
| Phản hồi để cải thiện | Sinh viên đánh dấu câu sai/lạc đề, sửa mapping CLO, kết quả làm bài đúng/sai, đánh giá "hữu ích" cho từng tóm tắt |

### 6.4 Google PAIR

- **Augment hay automate?** **Augment.** Sinh viên vẫn là người quyết định ôn gì và làm gì. AI đề xuất, có trích nguồn, sinh viên kiểm tra và chỉnh. Giao hẳn việc ôn tập cho AI thì không kiểm chứng được độ đúng của nội dung.
- **Sai kiểu nào tệ hơn?** **Bỏ sót tệ hơn báo nhầm.** Bỏ sót chủ đề/CLO quan trọng khiến sinh viên tin mình đã ôn đủ, và lỗ hổng chỉ lộ ra trong phòng thi. Báo nhầm (đánh dấu yếu ở phần đã vững, thêm câu thừa) chỉ tốn thêm thời gian. Ngoài ra, đáp án sai do ảo giác cũng nguy hiểm vì sinh viên học sai mà không biết, nên mọi đáp án phải trích dẫn đoạn nguồn.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học chuẩn bị kiểm tra giữa kỳ/cuối kỳ. |
| **Quy trình** | Khoảng 1–2 tuần trước thi: (1) thu thập tài liệu → (2) đọc, phân loại → (3) tổng hợp kiến thức → (4) tìm đề cũ, bài tập → (5) chọn câu hỏi phù hợp → (6) làm bài, đối chiếu đáp án → (7) ôn lại phần yếu. |
| **Bottleneck** | Bước 3 và 4: tổng hợp kiến thức từ nhiều nguồn (slide, PDF, giáo trình, ghi chú) và tìm đề, bài tập phù hợp đều làm thủ công, tài liệu phân tán. |
| **Impact** | Tốn nhiều thời gian cho mỗi môn thi; nội dung tổng hợp dễ thiếu sót; thiếu nguồn câu hỏi luyện tập phù hợp; khó phát hiện lỗ hổng kiến thức trước thi. Mức độ thực tế cần định lượng qua khảo sát. |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian bước 3 + 4 mỗi môn: baseline đo bằng khảo sát/tự báo cáo → giảm ≥ 40%. (2) Độ phủ CLO trong tài liệu ôn và câu hỏi luyện tập: baseline đối chiếu thủ công → ≥ 90%. (3) Lỗ hổng phát hiện: chủ đề được đánh dấu yếu khớp chủ đề làm sai → recall ≥ 80%. Cách đo: khảo sát trước/sau, thử nghiệm trên 1 môn với nhóm sinh viên. |
| **Boundary** | **Trong phạm vi:** tài liệu sinh viên tự upload + CLOs sinh viên cung cấp; tổng hợp, sinh câu hỏi/đề luyện tập, chấm, báo chủ đề yếu; prototype 1 môn. **Ngoài phạm vi:** tự tìm nguồn ngoài (Agent); dự đoán đề thi thật; thay giảng viên xác nhận CLO; phân phối lại giáo trình/đề có bản quyền. |
| **AI intervention point** | Bước 3 (tổng hợp có trích nguồn, map CLO), bước 4–5 (sinh và chọn câu hỏi, đề luyện tập), bước 7 (phát hiện chủ đề yếu từ kết quả làm bài). Bước 1, 2, 6 giữ nguyên hoặc chỉ hỗ trợ nhẹ (kho upload, parse). |
| **Mức chọn** | **Workflow** (pipeline cố định, AI làm từng bước đã định, sinh viên duyệt; mức augment). |
| **Rủi ro & người kiểm tra** | **Rủi ro:** bỏ sót chủ đề/CLO (nghiêm trọng nhất); tóm tắt hoặc đáp án sai do ảo giác; câu hỏi lệch phạm vi môn; parse lỗi hình/công thức; bản quyền tài liệu. **Người kiểm tra:** sinh viên (đối chiếu trích dẫn nguồn, đánh dấu câu sai/lạc đề, sửa mapping CLO); tùy chọn giảng viên/bạn học đối chiếu CLO và đề mẫu. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| AI intervention point | Chưa xác định rõ; giả thuyết chung "AI hệ thống hóa kiến thức, tạo câu hỏi" | Cụ thể ở bước 3, 4–5, 7, không đụng bước 1, 2, 6 | CP6 yêu cầu chỉ rõ điểm can thiệp; giới hạn phạm vi để dễ đo và kiểm soát |
| Hướng giải | "Tổng hợp tài liệu và tìm đề, bài tập phù hợp" | "Tổng hợp, **sinh** câu hỏi bám CLO và **phát hiện lỗ hổng**" | Đề cũ thường thiếu hoặc không phủ hết CLOs; bỏ sót là lỗi tệ nhất theo PAIR nên cần map CLO và báo lỗ hổng |
| Mức chọn | Cảm nhận nhanh: Workflow / Agent | Chốt **Workflow**, để Agent cho phiên bản sau | Quy trình ổn định, Workflow dễ kiểm soát và eval hơn, rẻ hơn Agent |
| Success Metric | Nêu hướng chung (giảm thời gian, tăng độ phủ) | Có baseline → target và cách đo cụ thể | Cần ngưỡng đo được để ra quyết định Go/Not Yet/No-Go |
| Rủi ro & người kiểm tra | Chưa có | Thêm rủi ro chính và người kiểm tra | CP6 yêu cầu bắt buộc; AI sai có hệ quả trực tiếp tới kết quả thi |
| Boundary | Chưa có | Thêm phạm vi trong/ngoài | Tránh mở rộng sang Agent và vấn đề bản quyền |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ phủ CLO (mỗi CLO có ≥ 1 mục tổng hợp và ≥ 1 câu hỏi) | ≥ 90% CLO được bao phủ | < 90%, hoặc thiếu CLO trọng yếu |
| 2 | Độ trung thực (tóm tắt, đáp án đúng với tài liệu gốc, có trích nguồn) | ≥ 95% mục kiểm tra mẫu đúng và đều có trích dẫn | Có đáp án sai hoặc không truy được nguồn |
| 3 | Câu hỏi đúng phạm vi và mức độ môn học | ≥ 80% câu được sinh viên đánh giá "dùng được" | < 80%, hoặc có câu ngoài phạm vi môn |
| 4 | Phát hiện lỗ hổng kiến thức | Recall ≥ 80% so với chủ đề sinh viên thực sự làm sai (trên dữ liệu thử) | Recall < 80% (bỏ sót nhiều) |
| 5 | Tiết kiệm thời gian bước 3 + 4 | Giảm ≥ 40% so với baseline thủ công | Giảm < 20%, hoặc tốn thêm thời gian sửa lỗi |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Trung bình** | Nỗi đau có thật: bước 3 và 4 làm thủ công, tài liệu phân tán, thiếu nguồn câu hỏi. Nhưng chưa có số liệu định lượng (thời gian mất, tỷ lệ sinh viên sẵn sàng dùng), và nhu cầu có tính mùa vụ (chỉ cao trước kỳ thi). Cần khảo sát để xác nhận. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp** | Luồng quen thuộc: upload → xem tóm tắt → làm đề → xem chủ đề yếu. Đầu ra có trích nguồn nên sinh viên đối chiếu được; sinh viên có thể đánh dấu câu sai và sửa mapping CLO. Chế độ augment, không tự quyết thay sinh viên. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Trung bình** | Công cụ có sẵn (LLM + RAG, parse PDF/slide) và dữ liệu do sinh viên cung cấp. Khó ở: parse hình/công thức/slide, đảm bảo đáp án đúng (ảo giác), map CLO chính xác, sinh câu hỏi đúng mức độ. Giảm rủi ro bằng cách làm prototype 1 môn và bắt buộc trích nguồn. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Trung bình** | Chi phí LLM/parse tăng theo số tài liệu; vấn đề bản quyền khi upload giáo trình, slide, đề thi; chưa rõ trường có cho phép dùng tài liệu và đề cũ không; sinh viên có thể chỉ dùng trong mùa thi nên khó duy trì. Giai đoạn đầu nhóm tự vận hành ở quy mô nhỏ, rủi ro chấp nhận được. |

### 8.2. Kết luận

**Quyết định:** **Go có điều kiện** (pilot nhỏ, chưa mở rộng)

**Lý do:**

- Không rủi ro nào ở mức Cao; Usability thấp, còn lại trung bình và đều có cách kiểm chứng bằng pilot.
- Bottleneck ở bước 3 và 4 rõ, Rule không giải quyết được (không tổng hợp ngữ nghĩa, không sinh câu hỏi bám CLO), nên Workflow là mức đơn giản nhất đủ dùng.
- Chế độ augment với trích nguồn giữ sinh viên làm người kiểm tra, giảm hậu quả của đáp án sai.
- Điều kiện của Go: phải khảo sát xác nhận Value và đạt các ngưỡng eval ở pilot trước khi mở rộng.

**Nếu Go — pilot nhỏ nhất:**

- Chọn **1 môn học**, **5–10 sinh viên** tham gia thử.
- Dựng Workflow tối thiểu: upload tài liệu + CLOs → tổng hợp có trích nguồn → sinh 20–30 câu hỏi luyện tập → làm bài và báo chủ đề yếu.
- Đo E1–E5: độ phủ CLO, độ trung thực, câu hỏi dùng được, recall lỗ hổng, thời gian tiết kiệm.
- Song song khảo sát ≥ 15 sinh viên để định lượng thời gian bước 3 + 4 hiện tại và mức sẵn sàng dùng.
- Chưa làm Agent, chưa hỗ trợ nhiều môn.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Khảo sát có ≥ 50% sinh viên xác nhận bước 3 và 4 tốn thời gian đáng kể và muốn dùng công cụ.
- Chạy thử parse và sinh đáp án trên một bộ tài liệu thật của 1 môn để kiểm tra tỷ lệ lỗi ban đầu (đặc biệt hình, công thức).
- Làm rõ vấn đề bản quyền/quy định khi upload tài liệu và đề cũ.

**Nếu No-Go — nên làm gì thay AI:**

- Quay về **No AI**: Notion/Google Docs chia ghi chú theo chương, thư mục theo môn, checklist CLO, ngân hàng đề thủ công và quy ước upload tài liệu ngay khi nhận.
- Nếu cần thêm tự động hóa nhẹ: dùng **Rule** (tag theo chương/từ khóa, tìm kiếm theo từ khóa).

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Sau **1 tuần** khảo sát (≥ 15 sinh viên): nếu **< 50%** xác nhận bước 3–4 tốn đáng kể thời gian và muốn dùng công cụ → **quay về Not Yet**, xem lại Value.
- Sau **3 tuần** pilot trên 1 môn: nếu **độ trung thực < 95%** (E2) **hoặc độ phủ CLO < 90%** (E1) → **quay về Rule + No AI** (chỉ tổ chức tài liệu, gắn tag chương, ngân hàng đề thủ công).
- Sau **3 tuần** pilot: nếu thời gian bước 3 + 4 **giảm < 20%** (E5) → **dừng, quay về No AI** (Notion + checklist).

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- Baseline mới chỉ dựa trên mô tả quy trình của nhóm, chưa có số liệu thật về thời gian bước 3 và 4. Cần khảo sát ≥ 15 sinh viên để định lượng..
- Chưa kiểm tra thực tế khả năng parse slide/PDF lẫn hình, công thức và tỷ lệ đáp án sai do ảo giác.
- Chưa làm rõ vấn đề bản quyền và quy định của trường khi upload giáo trình, slide, đề cũ.
- Nhu cầu có tính mùa vụ (chỉ cao trước kỳ thi), chưa rõ sinh viên có dùng đều đặn trong học kỳ để upload dần tài liệu hay không.

**Hướng tiếp theo:**

- Khảo sát ≥ 15 sinh viên: thời gian bước 3 + 4 hiện tại, mức sẵn sàng dùng, môn nào khó ôn nhất.
- Làm prototype Workflow tối thiểu trên 1 môn (5–10 sinh viên), sau đó chỉnh lại ngưỡng.
- Chạy thử parse và sinh câu hỏi trên bộ tài liệu thật để đo tỷ lệ lỗi sớm.
- Làm rõ bản quyền: chỉ xử lý tài liệu sinh viên tự upload, không phân phối lại.
- "Lập kế hoạch ôn tập tự động theo tiến độ và kết quả làm bài" là candidate tiềm năng cho vòng sau (mức Agent), chỉ xem xét khi Workflow đã đạt ngưỡng eval.

## 10. Tài liệu tham khảo

-
