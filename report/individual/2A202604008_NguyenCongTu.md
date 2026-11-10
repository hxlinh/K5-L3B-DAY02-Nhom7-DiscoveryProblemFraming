## 1. Thông tin học viên

- Họ tên: Nguyễn Công Tú
- MSSV: 2A202604008
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom7
- Link repo nhóm: https://github.com/hxlinh/K5-L3B-DAY02-Nhom7-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp | Khi cần chọn baseline cho bài toán biểu diễn phân tử hoặc tái định vị thuốc, tôi muốn thấy cạnh nhau phương pháp, dataset, metric, kết quả của nhiều bài báo, để quyết định mà không phải đọc lại từng bài từ đầu. | Sinh viên/nhà nghiên cứu mới vào drug discovery | ~30–60 phút/paper, 8–15 paper/đề tài (ước lượng). |
| 2 | Cần đọc, tổng hợp | Khi thuê phòng trọ/căn hộ ở Hà Nội, tôi muốn biết các điều khoản bất lợi trong hợp đồng (đặt cọc, tăng giá, phạt phá hợp đồng, điện nước), để không bị mất tiền oan khi trả phòng. | Sinh viên, người đi làm thuê nhà | Mỗi lần thuê phải đọc hợp đồng 3–10 trang; đa số ký mà không đọc kỹ; tranh chấp tiền cọc phổ biến trên các hội nhóm thuê nhà. |
| 3 | Tốn thời gian | Khi tìm phòng trọ, tôi muốn lọc tin theo giá, khoảng cách tới trường/chỗ làm và loại tin ảo/trùng, để không mất hàng giờ lướt group Facebook và gọi hỏi từng chỗ. | Sinh viên, người mới chuyển đến | Đầu năm học/đầu tháng: vài giờ/ngày trong 1–2 tuần; nhiều tin đã hết phòng hoặc đăng lặp. |
| 4 | Lặp lại | Khi đi ăn, đi chơi hay chia tiền nhà theo nhóm, tôi muốn tự động chia và đòi từng người, để không phải nhắn nhắc nợ và tính lại bằng tay. | Nhóm bạn, người ở ghép | Hầu như mỗi tuần; nhắc nợ nhiều lần/người; hay tính sai hoặc quên. |
| 5 | Lặp lại |    Khi chạy thí nghiệm distributed (DDP) với nhiều cấu hình (số GPU, batch size), tôi muốn log và so sánh throughput, memory, scaling tự động, để không phải chép tay số liệu rồi vẽ lại bảng sau mỗi lần chạy. | Nhóm làm đề tài phân tích hiệu năng DDP | Mỗi cấu hình phải chạy và ghi số thủ công; lặp theo từng thay đổi tham số (ước lượng 10–20 phút/lần tổng hợp, cần bấm giờ thật). của tôi, viết câu ai gợi ý

**Nếu có dùng AI để gợi ý thêm:** AI gợi ý #3 và bỏ ý "Chatbot hỏi đáp mọi thứ về tài liệu học" do là giải pháp


---

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 Chọn baseline từ nhiều paper (kèm so sánh công bằng split/metric) | Tôi là người dùng thật, pain lặp lại ở mọi đề tài của Group 3, đo được thời gian trước/sau | AI trích số liệu từ PDF có đủ chính xác không; ngoài nhóm có ai gặp pain này không |
| 2 | #2 Đọc hợp đồng thuê nhà, tìm điều khoản bất lợi | Pain gắn với tiền thật (tiền cọc), nhiều sinh viên/người đi làm gặp, bài toán đọc-tổng hợp rõ ràng | AI có nhận diện đúng điều khoản rủi ro không; người dùng có tin kết quả AI để quyết định ký không |
| 3 | #5 Tự động log và so sánh kết quả thí nghiệm DDP | Lặp lại, có quy trình rõ, tôi tự làm được và đo được | Có thể chỉ cần script/rule, không cần AI; phạm vi người dùng hẹp |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần chọn baseline cho bài toán biểu diễn phân tử hoặc tái định vị thuốc, tôi muốn thấy cạnh nhau phương pháp, dataset, metric và kết quả của nhiều bài báo, để quyết định mà không phải đọc lại từng bài từ đầu. |
| Actor | Sinh viên làm đề tài drug discovery/design |
| Thời điểm / bối cảnh | Đầu đề tài khi chốt baseline; lặp lại mỗi lần đổi bài toán |
| Quy trình hiện tại (3–7 bước) | 1) Tìm paper 2) Lọc bằng abstract 3) Đọc method/experiment 4) Chép vào bảng 5) Đối chiếu split/metric có tương đương không 6) Chọn baseline |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: ~30–60 phút/paper, 8–15 paper → 4–12 giờ |
| Impact (nếu không giải thì sao) | Chọn baseline thiếu cơ sở, so sánh không công bằng, đọc lại từ đầu khi đổi hướng |
| Success metric (baseline → target) | Thời gian tổng hợp 10 paper: ~6 giờ → ≤ 1,5 giờ; độ chính xác các trường trích ≥ 90% (kiểm tay 20 ô ngẫu nhiên) |
| Phương án không dùng AI | Template bảng chuẩn + checklist trích thông tin, chia paper cho thành viên |
| Giả thuyết về AI (nếu có) | AI trích thông tin có cấu trúc từ PDF thành bảng; người kiểm các ô quan trọng (số liệu, split) |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Tìm paper -> Lọc bằng abstract -> Đọc method/experiment -> Chép vào bảng
-> Đối chiếu split/metric -> Chọn baseline
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi thuê phòng trọ/căn hộ ở Hà Nội, tôi muốn biết các điều khoản bất lợi trong hợp đồng (đặt cọc, tăng giá, phạt phá hợp đồng, điện nước), để không bị mất tiền oan khi trả phòng. |
| Actor | Sinh viên, người đi làm thuê nhà |
| Thời điểm / bối cảnh | Trước khi ký hợp đồng và đặt cọc, thường bị chủ nhà hối ký nhanh |
| Quy trình hiện tại (3–7 bước) | 1) Nhận hợp đồng (giấy/ảnh/file) 2) Đọc lướt 3) Hỏi bạn bè/người nhà 4) Thương lượng 1–2 điều khoản 5) Ký và đặt cọc |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: ~20–40 phút/hợp đồng 3–10 trang, và vẫn không chắc điều khoản nào là rủi ro |
| Impact (nếu không giải thì sao) | Mất tiền cọc, bị phạt, bị tăng giá đột ngột; tranh chấp khó giải quyết |
| Success metric (baseline → target) | Thời gian rà hợp đồng: ~30 phút → ≤ 5 phút; phát hiện ≥ 90% điều khoản rủi ro so với danh sách do người có kinh nghiệm đánh dấu |
| Phương án không dùng AI | Checklist điều khoản cần kiểm (cọc, tăng giá, phạt, điện nước, thời hạn, trả phòng) |
| Giả thuyết về AI (nếu có) | AI đọc hợp đồng, đánh dấu điều khoản bất lợi theo checklist và giải thích ngắn bằng tiếng Việt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Nhận hợp đồng -> Đọc lướt -> Hỏi bạn bè -> Thương lượng -> Ký và đặt cọc
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chạy thí nghiệm distributed (DDP) với nhiều cấu hình (số GPU, batch size), tôi muốn log và so sánh throughput, memory, scaling tự động, để không phải chép tay số liệu rồi vẽ lại bảng sau mỗi lần chạy. |
| Actor | Nhóm làm đề tài phân tích hiệu năng DDP |
| Thời điểm / bối cảnh | Sau mỗi lần chạy thí nghiệm hoặc đổi tham số cấu hình |
| Quy trình hiện tại (3–7 bước) | 1) Chạy một cấu hình 2) Đọc log 3) Chép throughput/memory vào bảng 4) Lặp cho cấu hình khác 5) Vẽ biểu đồ scaling |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 5: ~10–20 phút/lần tổng hợp (cần bấm giờ thật) |
| Impact (nếu không giải thì sao) | Chép sai số, khó so sánh giữa các lần chạy, mất thời gian vẽ lại |
| Success metric (baseline → target) | Thời gian tổng hợp kết quả: ~15 phút/lần → ≤ 2 phút/lần; 0 lỗi chép số |
| Phương án không dùng AI | Script parse log và vẽ biểu đồ tự động |
| Giả thuyết về AI (nếu có) | Không cần AI; có thể chỉ dùng AI để sinh script ban đầu |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
Chạy cấu hình -> Đọc log -> Chép số vào bảng -> Lặp cấu hình khác -> Vẽ biểu đồ
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Tôi là người dùng thật, pain lặp lại ở mọi đề tài của Group , đo được thời gian trước/sau và gắn trực tiếp với bài toán của nhóm.
- Câu hỏi muốn nhóm phản biện: Nếu AI trích sai một con số kết quả, làm sao tôi phát hiện mà không phải đọc lại cả paper?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Thời gian 30–60 phút/paper chưa đo thực tế | Đồng ý | Ghi rõ là ước lượng, sẽ bấm giờ 3 paper thật ở CP4 |
| Metric "độ chính xác ≥ 90%" chưa nói cách kiểm | Đồng ý | Chốt cách kiểm: 20 ô ngẫu nhiên/bảng, so với paper gốc |
| Chỉ mình tôi gặp pain này, thiếu bằng chứng từ người khác | Đồng ý một phần | Thêm phỏng vấn ít nhất 3 bạn cùng nhóm/lớp (Mom Test) |
| Có thể giải bằng template bảng, không cần AI | Đồng ý | Giữ template tay làm phương án đối chứng để so sánh |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (chọn baseline từ nhiều paper) cho nhóm | Nhóm thấy pain có thật nhưng hẹp, nên card không được chọn làm candidate chính.] |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: "Con số thời gian này bạn đo hay ước lượng?" | Bạn bổ sung cách đo vào card |
| Nhận phản biện | Câu hỏi tôi nhận được: "Nếu AI trích sai thì sao?" | Tôi đã sửa: thêm cách kiểm tay và giữ phương án không dùng AI để đối chứng |
| Gom cluster / cây OST | Cùng nhóm gom các card theo pain | Card của tôi vào cluster "đọc và tổng hợp nhiều nguồn" |
| Chọn candidate problem | Cùng nhóm chấm điểm shortlist | Nhóm chọn bài ôn thi |
| Kiểm chứng / research | Hỗ trợ nhóm phỏng vấn, poll và rà các công cụ có sẵn | Nhóm thu hẹp phạm vi về gom và tổng hợp tài liệu |
| Quy trình nhóm | Góp ý quy trình trước/sau | Quy trình có phân vai Human/Rule/AI |
| Problem Statement | Phụ trách CP6: viết v1 từ v0, thêm Boundary, điểm can thiệp AI, metric và 5 tiêu chí đánh giá đầu ra | Nhóm có bản v1 đo được để dùng cho pilot |
| Mức can thiệp AI | Phụ trách CP6: so sánh No AI / Rule / Workflow / Agent, làm AI Canvas và PAIR | Nhóm chọn Workflow, giữ No AI làm baseline |
| Quyết định | Phụ trách CP6: đánh giá 4 rủi ro, đề xuất pilot nhỏ và ngưỡng dừng | Nhóm chọn Go có điều kiện |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm vấn đề ngoài 3 ý tôi tự nghĩ | Mở rộng góc nhìn, gợi ý được ý đọc hợp đồng thuê nhà | Nhiều gợi ý chung chung, như "trợ lý AI quản lý toàn bộ dự án" | Giữ ý có quy trình thật, bỏ ý quá rộng |
| CP2 Problem Card | Nháp Job Story, metric và phản biện card | Chỉ ra metric chưa có cách đo, chưa có phương án không dùng AI | Số liệu thời gian chỉ là ước lượng, chưa có căn cứ | Ghi rõ là ước lượng, thêm cách kiểm tay và phương án đối chứng |
| CP4 Research | Hỗ trợ nhóm tìm và so sánh các công cụ có sẵn | Gợi ý được NotebookLM, Notion, Quizlet để so sánh | Chỉ là gợi ý ban đầu, chưa kiểm chứng thực tế các công cụ | Nhóm tự rà lại từng công cụ và gắn với quy trình thật |
| CP5 Quy trình | Nháp sơ đồ quy trình trước/sau và phân vai Human/Rule/AI | Giúp tách rõ bước nào do AI, bước nào do người | Số thời gian ở cột "sau" là giả định, chưa có thử nghiệm | Nhóm ghi rõ đó là mục tiêu cần kiểm chứng |
| CP5–6 Problem Statement | Nháp v1 và các tiêu chí đánh giá | Câu gọn, có metric và boundary | Có lúc thêm cả giải pháp vào phần phát biểu vấn đề | Tôi bỏ phần giải pháp, chỉnh ngưỡng cho vừa pilot nhỏ |
| CP6 Mức can thiệp / quyết định | So sánh 4 mức can thiệp và nháp phân tích rủi ro | Giúp thấy rõ vì sao Rule và Agent chưa phù hợp | Dễ nghiêng về dùng AI, đánh giá rủi ro hơi lạc quan | Tôi chọn Go có điều kiện, thêm ngưỡng dừng và đường lùi về No AI |

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Khi nghe các bạn trình bày, tôi nhận ra mỗi người có cách nhìn nhận vấn đề khác nhau, ngay cả khi cùng hướng đến một mục tiêu. Một vấn đề có thể xuất phát từ cá nhân nhưng chưa chắc xảy ra với nhiều người.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
- Có. Ban đầu, khi nghĩ về bài toán hỗ trợ sinh viên ôn thi, nhóm đã nhanh chóng hình dung ra một hệ thống AI có thể lưu trữ tài liệu, tổng hợp kiến thức, tạo đề thi và đánh giá kết quả học tập. Tuy nhiên, đây mới là những ý tưởng giải pháp, chưa chứng minh được sinh viên thực sự gặp khó khăn ở tất cả các bước.

- Nhóm nhận ra điều này khi phân tích quy trình hiện tại . Sau đó, nhóm tập trung xác định bottleneck thay vì cố gắng giữ lại tất cả chức năng đã nghĩ ra.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
- Có. Ban đầu, tôi đề xuất vấn đề liên quan đến việc lựa chọn baseline drug trong bài toán nghiên cứu drug repositioning. Tuy nhiên, sau khi lắng nghe các thành viên trình bày và cùng nhóm phản biện, tôi nhận ra vấn đề mình đưa ra có phạm vi khá chuyên môn và chưa thể hiện rõ mức độ phổ biến cũng như nhu cầu của nhóm người dùng mục tiêu.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
- Có. Tôi khá bất ngờ khi nhận ra vấn đề tìm đề thi không phổ biến như suy nghĩ ban đầu. Một số sinh viên có thể dễ dàng lấy đề từ Khoa, trong khi những người khác phải tìm kiếm từ nhiều nguồn khác nhau.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
- Điều khó nhất là xác định đúng vấn đề  và giới hạn phạm vi sao cho vừa phản ánh nhu cầu thực tế, vừa có thể kiểm chứng và triển khai được.
-Tôi cũng nhận ra việc viết Success Metric không đơn giản là đặt mục tiêu giảm thời gian, mà cần có baseline, cách đo và tiêu chí đảm bảo chất lượng đầu ra.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
- Nếu được làm lại, tôi sẽ dành nhiều thời gian hơn để phỏng vấn và khảo sát người dùng trước khi lựa chọn candidate problem.
- Tôi sẽ phản biện nhóm mạnh hơn ở :Tính phổ biến của vấn đề: Liệu khó khăn này có xuất hiện ở nhiều sinh viên hay chỉ một số môn học cụ thể?

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
- Nhóm tôi lựa chọn vấn đề sinh viên mất nhiều thời gian tìm kiếm và tổng hợp tài liệu khi chuẩn bị cho các kỳ thi giữa kỳ và cuối kỳ. Quy trình ôn tập hiện tại gồm 7 bước: thu thập tài liệu, đọc và phân loại, tổng hợp kiến thức, tìm đề luyện tập, chọn câu hỏi, làm bài và xác định phần kiến thức còn yếu. Nhóm đặt mục tiêu giảm ít nhất 40% thời gian tổng hợp và tìm kiếm tài liệu, độ bao phủ CLO đạt từ 90%, độ chính xác nội dung đạt từ 95% và khả năng phát hiện kiến thức yếu đạt từ 80%. Phạm vi hệ thống giới hạn ở tài liệu do sinh viên tải lên và CLO được cung cấp, không tự tìm kiếm nguồn bên ngoài, không dự đoán đề thi thật và không thay thế giảng viên. Nhóm lựa chọn mức can thiệp Workflow with AI, trong đó AI hỗ trợ phân loại, tổng hợp kiến thức, tạo câu hỏi, chấm và phân tích kết quả ôn tập theo một quy trình cố định. Sinh viên vẫn chủ động kiểm tra nội dung, lựa chọn câu hỏi và quyết định phần kiến thức cần ôn lại. Cuối cùng, nhóm quyết định Go with conditions: thử nghiệm trước với một môn học và 5–10 sinh viên, đo lường hiệu quả theo các tiêu chí đã đặt ra rồi mới cân nhắc mở rộng.

---

## 7. Tài liệu tham khảo

-