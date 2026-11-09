# Báo cáo cá nhân — 2A202604017_HoangXuanLinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Hoàng Xuân Lĩnh
- MSSV: 2A202604017
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom7
- Link repo nhóm: https://github.com/hxlinh/K5-L3B-DAY02-Nhom7-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị cho kỳ kiểm tra một môn học, tôi muốn tổng hợp kiến thức từ nhiều nguồn tài liệu và có hệ thống câu hỏi, đề thi phù hợp để luyện tập, nhằm ôn tập hiệu quả và đạt kết quả tốt trong kỳ thi | Sinh viên đại học chuẩn bị kiểm tra giữa kỳ/cuối kỳ | Ước tính khoảng 240 phút cho mỗi chu kỳ ôn một môn; phỏng vấn: 2/3 sinh viên mất trên 3 giờ để tìm và tổng hợp tài liệu; poll: 2/4 người từng phải tìm lại đề cũ từ nhiều nguồn |
| 2 | Tốn thời gian | Khi cần nhớ lại một câu trả lời mà lớp từng thảo luận, tôi muốn tìm ra ngay trong nhóm chat, để không phải hỏi lại cả lớp | Sinh viên trong lớp, người hay bị hỏi lại | Khoảng 10–15 phút mỗi lần tìm, 3–4 lần/tuần |
| 3 | Tốn thời gian | Khi chuẩn bị nộp bài lab lúc 22h, tôi muốn biết bài còn thiếu mục nào, để không bị trừ điểm vì sai cấu trúc | Sinh viên làm lab, giảng viên chấm bài | Khoảng 20 phút/bài để đối chiếu thủ công với yêu cầu đề; 1–2 lần/tuần vào mùa lab |
| 4 | Lặp lại | Khi bắt đầu tuần mới, tôi muốn thấy toàn bộ deadline của các môn ở một chỗ, để không bỏ sót hạn nộp | Sinh viên đang học nhiều môn | Khoảng 15 phút/tuần chép deadline từ nhiều kênh vào một lịch |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi phải đọc một bài báo hoặc tài liệu dài trước buổi seminar, tôi muốn nắm nhanh ý chính và đóng góp của nó, để kịp tham gia thảo luận | Sinh viên năm cuối, nhóm seminar | Khoảng 60–90 phút/bài, 1–2 bài/tuần |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.
- Bỏ ý "tự động tạo thời khóa biểu tối ưu" vì đó là giải pháp, không phải problem, và tôi không có dấu hiệu thật.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Gom tài liệu và có câu luyện tập khi ôn thi (#1) | Actor rõ, quy trình 7 bước vẽ được, bottleneck nằm ở bước 3 và 4, có thể đo thời gian trước/sau, so sánh được cả 4 mức | Baseline mới là ước tính, chưa đo thật; bước 4 có thể không đau với môn đã có đề cũ từ Khoa |
| 2 | Tìm lại câu trả lời trong nhóm chat (#2) | Lặp lại nhiều lần mỗi tuần, nhiều người cùng gặp | Phải đọc dữ liệu chat riêng tư; khó đo "tìm đúng" |
| 3 | Kiểm tra bài lab thiếu mục trước khi nộp (#3) | Vấn đề cụ thể, vừa sức một buổi lab, đo được | Có thể checklist hoặc rule đã đủ, chưa chắc cần AI |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị cho kỳ kiểm tra một môn, tôi muốn gom kiến thức từ nhiều nguồn tài liệu và có bộ câu hỏi, đề luyện tập sát nội dung, để ôn đủ phạm vi và đạt kết quả tốt |
| Actor | Sinh viên đại học chuẩn bị cho kỳ kiểm tra giữa kỳ hoặc cuối kỳ |
| Thời điểm / bối cảnh | Khoảng 1–2 tuần trước kỳ kiểm tra, khi cần hệ thống hóa kiến thức và luyện các dạng bài có thể xuất hiện trong đề |
| Quy trình hiện tại (3–7 bước) | 1. Thu thập tài liệu từ slide, PDF, giáo trình, ghi chép · 2. Đọc và phân loại nội dung · 3. Tổng hợp kiến thức quan trọng thành ghi chú · 4. Tìm đề thi cũ và bài tập từ nhiều nguồn · 5. Chọn câu hỏi phù hợp với nội dung đã học · 6. Làm bài và đối chiếu đáp án · 7. Ôn lại phần kiến thức còn yếu |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 (tổng hợp kiến thức, khoảng 60 phút) và bước 4 (tìm đề, bài tập, khoảng 45 phút): làm thủ công, tài liệu phân tán, khó chắc là đã phủ hết nội dung môn |
| Impact (nếu không giải thì sao) | Khoảng 240 phút cho mỗi chu kỳ ôn một môn; tài liệu rải rác nên bản tổng hợp dễ thiếu sót; thiếu câu luyện tập phù hợp nên ôn kém hiệu quả. Mức ảnh hưởng thực tế cần khảo sát để định lượng |
| Success metric (baseline → target) | Tổng thời gian chuẩn bị: 240 phút → tối đa 120 phút; độ phủ nội dung môn (CLOs) trong bản tổng hợp và bộ câu hỏi: đối chiếu thủ công → từ 90% trở lên; chủ đề yếu được phát hiện đúng: từ 80% trở lên. Đo trên cùng một bộ tài liệu, ghi giờ và để sinh viên đánh giá đầu ra |
| Phương án không dùng AI | Dùng Notion/Google Docs chia ghi chú theo chương, thư mục theo môn, checklist tiến độ ôn; tự gom và phân loại câu hỏi từ đề cũ, giáo trình, bài tập |
| Giả thuyết về AI (nếu có) | Có một nơi để sinh viên tải tài liệu lên dần ngay khi nhận được, đến lúc thi mọi thứ nằm ở cùng một chỗ. AI đọc tài liệu và chuẩn đầu ra môn học (CLOs) do sinh viên cung cấp để hệ thống hóa kiến thức, sinh câu hỏi và đề luyện tập bám tài liệu, hỗ trợ chấm và chỉ ra phần cần ôn thêm |
| Cảm nhận nhanh | Workflow / Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 240 phút/kỳ ôn tập

[1 Thu thập tài liệu: 20'] → [2 Đọc và phân loại: 30']
→ [3 Tổng hợp kiến thức: 60'] ← BOTTLENECK
→ [4 Tìm đề thi, bài tập: 45'] ← BOTTLENECK
→ [5 Chọn câu hỏi phù hợp: 20'] → [6 Làm bài, đối chiếu đáp án: 45']
→ [7 Ôn lại phần yếu: 20']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần nhớ lại một câu trả lời mà lớp từng thảo luận, tôi muốn tìm ra ngay trong nhóm chat, để không phải hỏi lại cả lớp |
| Actor | Sinh viên trong lớp dùng chung một nhóm chat (Discord/Zalo/Messenger) |
| Thời điểm / bối cảnh | Trong học kỳ, đặc biệt khi làm bài tập hoặc lab và nhớ rằng "hình như đã có người hỏi rồi" |
| Quy trình hiện tại (3–7 bước) | 1. Nhớ ra câu hỏi từng có · 2. Tìm bằng từ khóa trong nhóm chat · 3. Lướt các kết quả · 4. Đọc lại cả luồng tin nhắn · 5. Kiểm tra câu trả lời còn đúng không, nếu không thì hỏi lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4, đọc lại cả luồng tin nhắn để hiểu ngữ cảnh: khoảng 6 phút trong tổng 10–15 phút mỗi lần |
| Impact (nếu không giải thì sao) | Khoảng 30–60 phút/tuần cho mỗi người; cùng một câu hỏi bị lặp lại, làm nhiễu nhóm chat và mất thời gian của người hay trả lời |
| Success metric (baseline → target) | Thời gian tìm lại một câu trả lời: 10–15 phút → dưới 3 phút/lần, đo bằng tự bấm giờ trong 2 tuần |
| Phương án không dùng AI | Ghim tin nhắn quan trọng; một tài liệu FAQ chung của lớp do người trả lời cập nhật |
| Giả thuyết về AI (nếu có) | AI tóm tắt và trả lời câu hỏi từ lịch sử chat, có dẫn tin nhắn gốc |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 15 phút/lần

[1 Nhớ ra câu hỏi từng có: 1'] → [2 Tìm theo từ khóa: 3'] → [3 Lướt kết quả: 3']
→ [4 Đọc lại cả luồng tin nhắn: 6'] ← BOTTLENECK
→ [5 Kiểm tra còn đúng không / hỏi lại: 2']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp bài lab lúc 22h, tôi muốn biết bài còn thiếu mục nào, để không bị trừ điểm vì sai cấu trúc |
| Actor | Sinh viên làm bài lab theo template có sẵn |
| Thời điểm / bối cảnh | Tối hôm hạn nộp, sau khi hoàn thành phần nội dung |
| Quy trình hiện tại (3–7 bước) | 1. Mở lại đề và rubric · 2. Đọc lại bài làm · 3. Đối chiếu từng mục yêu cầu với bài làm · 4. Ghi lại mục thiếu và bổ sung · 5. Nộp bài |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đối chiếu từng mục: khoảng 7 phút trong tổng khoảng 20 phút/bài; dễ bỏ sót khi mệt hoặc gấp |
| Impact (nếu không giải thì sao) | Thiếu mục bị trừ điểm dù nội dung đúng; mỗi lần nộp gấp tăng nguy cơ sai cấu trúc |
| Success metric (baseline → target) | Thời gian kiểm tra: khoảng 20 phút → dưới 5 phút/bài; số mục thiếu khi nộp: về 0 |
| Phương án không dùng AI | Checklist sao chép từ rubric; template có sẵn các mục bắt buộc |
| Giả thuyết về AI (nếu có) | Chưa chắc cần AI; có thể một script kiểm tra các tiêu đề mục còn trống là đủ |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 20 phút/bài

[1 Mở lại đề, rubric: 3'] → [2 Đọc lại bài làm: 5']
→ [3 Đối chiếu từng mục: 7'] ← BOTTLENECK
→ [4 Ghi mục thiếu, bổ sung: 4'] → [5 Nộp: 1']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Nỗi đau rõ và nhiều bạn cùng gặp trước mỗi kỳ thi; quy trình 7 bước vẽ ra được với bottleneck cụ thể ở bước 3 và 4; có thể đo bằng thời gian và độ phủ nội dung; và có nhiều mức giải pháp để so sánh (từ Notion + checklist đến Workflow).
- Câu hỏi muốn nhóm phản biện: Nếu chỉ dùng Notion, checklist hoặc một công cụ có sẵn như NotebookLM thì đã giảm được một nửa thời gian chưa? Bottleneck thật là bước 3 hay bước 4?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 240 phút mới là ước tính của tôi, chưa có số đo thật | Đồng ý | Ghi rõ là ước tính, đưa vào kế hoạch khảo sát và phỏng vấn để định lượng |
| Hai bottleneck (bước 3 và bước 4) là giả thuyết, chưa chắc bước 4 đau với mọi sinh viên | Đồng ý một phần | Giữ bước 3 làm trọng tâm, ghi bước 4 là vấn đề chủ yếu với môn không có đề cũ |


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Problem Card về ôn thi: quy trình, bottleneck và tác động | Được đưa vào shortlist và chọn làm candidate chính |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: về bằng chứng thực tế và cách giải quyết đơn giản hơn không cần AI | Giúp các bạn làm rõ vấn đề và số liệu của mình |
| Nhận phản biện | Câu hỏi tôi nhận được: về việc cách làm thủ công đã đủ chưa và bottleneck thật nằm ở bước nào | Tôi đã sửa gì: làm rõ phạm vi, tách bottleneck và đưa phương án không dùng AI vào kiểm chứng |
| Gom cluster / cây OST | Tham gia gom các candidate theo pattern và loại các ý là giải pháp khỏi cây OST | Cây OST chỉ còn nhu cầu và pain |
| Chọn candidate problem | Tham gia chấm điểm và đề xuất candidate của mình | Nhóm chọn candidate ôn thi |
| Kiểm chứng / research | Tham gia phỏng vấn, poll và tìm hiểu các công cụ có sẵn | Nhóm thu hẹp phạm vi problem và giữ No AI làm baseline |
| Quy trình nhóm | Góp ý và hoàn thiện quy trình hiện tại và tương lai | Nhóm dùng làm bản cuối |
| Problem Statement | Tham gia viết và chỉnh sửa theo phản biện | Có baseline, target và cách đo rõ hơn |
| Mức can thiệp AI | Tham gia so sánh 4 mức can thiệp | Nhóm chọn Workflow |
| Quyết định | Tham gia đánh giá 4 rủi ro và đặt ngưỡng dừng | Nhóm chọn Go có điều kiện |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm problem | Gợi ra thêm các tình huống tôi chưa nghĩ tới | Có ý quá rộng hoặc thiếu dấu hiệu thật | Giữ ý có quy trình thật, bỏ ý quá rộng |
| CP2 Problem Card | Phản biện Problem Card | Chỉ ra điểm yếu về baseline và phạm vi | Có gợi ý đi quá xa, thiên về giải pháp phức tạp | Giữ phạm vi vừa sức, chỉ nhận ý phù hợp |
| CP4 Research | Tìm các công cụ có sẵn | Nhanh chóng có danh sách để so sánh | Thông tin hoặc link có thể chưa chính xác | Tự kiểm tra lại nguồn |
| CP5 Quy trình | Chuyển mô tả thành sơ đồ | Tiết kiệm thời gian trình bày | Có thể gộp bước hoặc mất bottleneck | Chỉnh lại cho đúng quy trình thật |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi học được rằng nhiều problem khác nhau thực ra có chung một pattern, và một Job Story tốt cần có tình huống cụ thể cùng con số. Tôi cũng thấy không phải problem nào cũng cần AI.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, lúc đầu tôi nghĩ đến AI tạo đề thi trước rồi mới nghĩ đến vấn đề sau. Nhưng sau khi phát hiện thì đã update lại

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Sau khi bị hỏi liệu cách làm thủ công đã đủ chưa, tôi thu hẹp phạm vi problem và giữ phương án không dùng AI làm baseline thay vì mặc định cần AI.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có. Mức độ khó khăn không giống nhau giữa các sinh viên và các môn, và đã có công cụ làm được một phần việc. Điều đó cho thấy cần kiểm chứng trước khi quyết định hướng giải.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là không để giải pháp lẫn vào problem, và đặt được metric có baseline, target, cách đo rõ ràng khi số liệu còn là ước tính.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ đo baseline thật và kiểm chứng với nhiều người hơn ngay từ đầu. Tôi cũng sẽ phản biện mạnh hơn về phạm vi giải pháp và việc đã thật sự cần AI hay chưa.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Problem của nhóm là sinh viên mất nhiều thời gian tổng hợp tài liệu và tìm câu luyện tập khi ôn thi. Quy trình hiện tại gồm 7 bước làm thủ công, bottleneck ở bước tổng hợp kiến thức và tìm đề. Metric là giảm thời gian chuẩn bị, tăng độ phủ nội dung môn và phát hiện được phần kiến thức còn yếu. Boundary là AI chỉ làm trên tài liệu sinh viên cung cấp, có trích nguồn và sinh viên luôn là người kiểm tra và quyết định. Nhóm chọn mức Workflow vì quy trình ổn định và cần AI xử lý nội dung nhưng không cần tự quyết hướng đi. Quyết định cuối là Go có điều kiện, chạy pilot nhỏ trước khi mở rộng.

---

## 7. Tài liệu tham khảo
