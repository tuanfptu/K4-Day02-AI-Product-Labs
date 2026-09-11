# Individual Reflection — Day 02

> Ghi chú trung thực: bài này được hoàn thiện với sự hỗ trợ của AI theo yêu cầu. Vì chưa có buổi làm nhóm, tôi không nhận mình đã pitch, phỏng vấn hay challenge người khác. Các phát biểu về trải nghiệm cá nhân cần được tôi rà soát lần cuối trước khi nộp.

## Tôi đã tham gia vào phần nào?

| Hoạt động | Đóng góp ở mức cá nhân | Kết quả / trạng thái |
|---|---|---|
| Scan cá nhân | Xây danh sách 10 pain points theo 4 lăng kính | Hoàn thành |
| Top 3 | Chấm 7 tiêu chí và viết 3 Problem Cards | Hoàn thành |
| Research | Đối chiếu số liệu Bộ GD&ĐT, Chính phủ, nghiên cứu IEEE, UNESCO và feature hiện có của Google Classroom | Hoàn thành desk research; chưa có primary interview |
| Business gap | Tách “reminder app” khỏi “cross-channel trust layer” | Có hypothesis và rủi ro cần kiểm chứng |
| Workflow | Vẽ before/after, chỉ rõ AI, rule và human boundary | Hoàn thành draft cá nhân |
| Decision | Chọn Not Yet thay vì Go vội | Cần pilot 20 người / 4 tuần |
| Pitch/challenge nhóm | Chưa diễn ra | Không bịa dữ liệu; chuẩn bị pitch + self-challenge để dùng khi làm nhóm |

## AI đã được dùng như thế nào?

| Phase | AI hỗ trợ | Hữu ích | Điểm yếu/rủi ro | Cách tôi kiểm soát |
|---|---|---|---|---|
| Scan | Mở rộng góc nhìn và chuẩn hóa cách mô tả | Tránh solution-first | Dễ bịa pain “nghe hợp lý” | Chỉ giữ pain có workflow và kế hoạch đo |
| Problem Card | Phản biện actor, metric, boundary | Làm rõ logic | Có xu hướng đề xuất agent quá sớm | Buộc so với rule và workflow |
| Research | Tìm lead và tổng hợp nguồn | Tốc độ cao | Có thể trộn năm, population, correlation/causation | Mở nguồn gốc, ghi rõ loại nghiên cứu và giới hạn suy rộng |
| Market | Tách market signal khỏi revenue forecast | Tránh coi mọi sinh viên là khách trả tiền | Market-size thứ cấp có thể không minh bạch phương pháp | Dùng như directional signal; không dựng forecast |
| Workflow | Chuyển mô tả thành flow có fallback | Thấy rõ điểm can thiệp | Có thể che mất edge case | Thêm conflict, abstain, confirmation và source provenance |
| Decision | So sánh Go/Not Yet/No-Go | Ép nhìn vào bằng chứng thiếu | AI có thể “lạc quan sản phẩm” | Chọn Not Yet và đặt kill criteria định lượng |

## Reflection

Điểm học được lớn nhất là một thị trường lớn không tự động tạo ra một bài toán tốt. Hơn hai triệu sinh viên và hàng trăm doanh nghiệp EdTech cho thấy nhu cầu số hóa, nhưng đồng thời cảnh báo rằng “làm thêm một app học tập” là hướng quá rộng và cạnh tranh. Cơ hội chỉ trở nên sắc nét khi tôi đặt workflow hiện tại cạnh feature đã có: LMS và calendar xử lý tốt dữ liệu có cấu trúc trong hệ sinh thái của chúng, còn pain giả định nằm ở khâu biến thông tin đa nguồn thành task đáng tin.

Tôi cũng thay đổi quan điểm về vai trò của AI. Ban đầu, một agent tự đọc mọi kênh, tự lên lịch và tự nhắc có vẻ hấp dẫn. Sau khi phân tích hậu quả của một deadline sai, giải pháp phù hợp hơn là workflow có quyền hạn hẹp: AI trích xuất, rule kiểm tra, con người xác nhận. Với bài toán high-impact nhưng dễ review, khả năng “không hành động khi không chắc” quan trọng hơn mức độ tự chủ.

Research làm rõ cả mặt thuận lẫn mặt nghịch. Nghiên cứu IEEE là bằng chứng tốt rằng reminder gần deadline có thể cải thiện submission, nhưng không chứng minh sinh viên Việt Nam gặp đúng pain đa nguồn hoặc sẽ trả tiền. Nghiên cứu về nudge fatigue cũng nhắc rằng nhiều notification hơn không đồng nghĩa tốt hơn. Vì vậy success metric phải gồm cả outcome, độ chính xác và cảm nhận về notification, không chỉ số message được gửi.

Phần yếu nhất hiện tại là primary evidence. Desk research cho biết “đáng hỏi tiếp”, chưa cho phép tuyên bố product-market fit. Nếu làm tiếp, tôi sẽ bắt đầu bằng diary study thay vì survey câu hỏi chung: 10–15 sinh viên chụp lại nơi mỗi assignment xuất hiện, ghi thời gian chuyển sang lịch, các thay đổi và lỗi. Dữ liệu hành vi này sẽ giúp phân biệt ba tình huống: pain thực sự do phân mảnh; pain do thói quen cá nhân; hoặc trường đã có LMS đủ tốt.

Nếu làm lại, tôi sẽ đưa kill criteria vào ngay từ đầu. Ý tưởng phải dừng hoặc chuyển về rule-only nếu phần lớn input đã có due date structured, người dùng không tin tưởng cơ chế forward dữ liệu, hoặc extraction vẫn cần sửa quá nhiều. Một quyết định No-Go có bằng chứng tốt đáng giá hơn một demo AI đẹp nhưng giải sai vấn đề.

## Tôi tự giải thích mạch bài toán

```text
Problem
Thông tin bài tập rải ở nhiều nguồn và phải tự diễn giải
  ↓
Workflow
Mở nguồn → lọc → đọc → nhập lịch → nhắc → kiểm lại
  ↓
Bottleneck
Lọc và chuyển văn bản tự do thành task đúng
  ↓
Metric
Thời gian, missed-task rate, field precision, edit rate, reminder usefulness
  ↓
Boundary
Không tự đổi deadline/nộp bài; luôn dẫn nguồn; human confirm; abstain khi conflict
  ↓
AI fit
AI tốt ở extraction ngôn ngữ; rule tốt ở validation/schedule; người chịu trách nhiệm chốt
  ↓
Decision
Not Yet: validate pain và trust trước, pilot workflow nhỏ, chưa cần Agent
```

## Cam kết bước tiếp theo

1. Thực hiện 10–15 interview và diary study 2 tuần.
2. Thu 100 thông báo thật đã ẩn dữ liệu nhạy cảm để tạo test set.
3. Benchmark AI workflow với baseline form/rule-only.
4. Không lưu toàn bộ inbox/chat; pilot bằng cơ chế forward-only và consent rõ.
5. Chỉ chuyển sang Go khi đạt ngưỡng metric đã nêu trong individual report.
