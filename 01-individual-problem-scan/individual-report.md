# Individual Problem Scan — Day 02

> Bối cảnh giả định: tôi là sinh viên đại học, học song song trên LMS, email, nhóm chat và tài liệu chia sẻ. Đây là desk research hoàn thành ngày 11/09/2026. Các số liệu bên ngoài có nguồn; baseline cá nhân là giả thuyết cần đo lại trong pilot, không được trình bày như kết quả khảo sát.

## 1. Scan rộng 10 vấn đề

| # | Lăng kính | Problem quan sát được | Actor | Dấu hiệu / cách kiểm chứng |
|---:|---|---|---|---|
| 1 | Lặp lại + tốn thời gian | Gom deadline và yêu cầu bài tập từ LMS, email, chat, PDF vào lịch cá nhân | Sinh viên học nhiều môn | 15–25 phút/ngày là baseline cá nhân cần time-log 2 tuần |
| 2 | Pain từ người khác | Thành viên nhóm hiểu khác nhau về deliverable, format và người phụ trách | Nhóm đồ án 3–6 người | Nhiều vòng hỏi lại; đo số clarification/thread và rework |
| 3 | AI có thể tốt hơn | Đọc nguồn dài nhưng không biết claim nào đủ uy tín để dùng | Sinh viên làm research | Đo thời gian từ câu hỏi đến 3 nguồn đạt tiêu chí CRAAP/SIFT |
| 4 | Tốn thời gian | Chuyển ghi chú bài giảng rời rạc thành kế hoạch ôn tập | Sinh viên trước kỳ thi | Đo phút/tuần và tỷ lệ kế hoạch được thực hiện |
| 5 | Lặp lại | Viết progress update cho nhóm theo nhiều format khác nhau | Nhóm trưởng/thành viên | 10–15 phút/lần, 2–3 lần/tuần — cần time-log |
| 6 | Pain từ người khác | Action item sau họp bị bỏ sót vì nằm trong chat/meeting notes | Nhóm dự án | Đo task quá hạn và task không có owner |
| 7 | Tốn thời gian | Kiểm tra bài nộp có đủ tên file, link, rubric, cấu trúc | Sinh viên trước khi submit | Đo lỗi bị trả lại và phút checklist thủ công |
| 8 | Lặp lại | Phân loại chi tiêu nhỏ từ nhiều ví/ngân hàng | Sinh viên tự quản tài chính | Đo số giao dịch chưa gắn nhãn và thời gian cuối tuần |
| 9 | AI có thể tốt hơn | Tìm lại quyết định cũ trong nhóm chat bằng từ khóa không chính xác | Nhóm học tập/CLB | Đo search time và tỷ lệ tìm đúng message nguồn |
| 10 | Pain từ người khác | Người mới vào CLB phải hỏi lại quy trình và biểu mẫu | Thành viên mới/ban vận hành | Đo câu hỏi lặp lại trong 30 ngày đầu |

## 2. Sàng lọc bằng bằng chứng và cơ hội kinh doanh

### 2.1 Tín hiệu thị trường

- Bộ GD&ĐT ghi nhận **2.036.689 sinh viên đại học** trong năm học 2022–2023 (không gồm khối An ninh, Quốc phòng). Đây là quy mô người dùng tiềm năng, không phải TAM doanh thu.^1
- Chính phủ đặt mục tiêu dạy và học số trở thành hoạt động hằng ngày, lớp trực tuyến tại cơ sở giáo dục đại học đạt trung bình 20%, và trên 50% học sinh/sinh viên dùng nền tảng học trực tuyến trong nước.^2
- U.S. Commercial Service ước tính EdTech Việt Nam đạt **364,7 triệu USD năm 2024**, CAGR 13,5% đến 2032, có hơn 750 doanh nghiệp; số người học trực tuyến có thể đạt 11,8 triệu vào 2029.^3 Đây là nguồn market-intelligence thứ cấp, hữu ích để định hướng nhưng không dùng thay validation khách hàng.
- Nghiên cứu IEEE về reminder deadline trên LMS cho thấy submission tăng **3,7 điểm phần trăm** trong thử nghiệm ngẫu nhiên (133 người ở 5 lớp) và tăng **5,7 điểm phần trăm** trong pilot lớn hơn (564 app users) so với các course không bật app.^4 Kết quả không chứng minh hiệu quả tại Việt Nam, nhưng xác nhận cơ chế “nhắc đúng lúc” đáng thử.
- Google Classroom đã có calendar, due-date notification và khả năng hỏi Gemini về bài tập.^5 Điều đó bác bỏ ý tưởng “một app nhắc deadline chung chung”; sản phẩm mới chỉ có lý do tồn tại nếu xử lý được dữ liệu **ngoài một LMS**, truy vết nguồn và luồng xác nhận.

### 2.2 Shortlist

Thang 1–5; `Evidence` đánh giá độ mạnh của bằng chứng hiện có, không phải mức độ chắc chắn tuyệt đối.

| Candidate | Pain | Tần suất | Đo được | AI advantage | Business gap | Feasible | Evidence | Tổng /35 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| A. Gom deadline + yêu cầu đa nguồn | 5 | 5 | 5 | 4 | 5 | 4 | 4 | **32** |
| B. Research copilot có kiểm chứng nguồn | 4 | 4 | 4 | 5 | 3 | 4 | 5 | **29** |
| C. Action-item tracker cho nhóm sinh viên | 4 | 4 | 5 | 4 | 3 | 5 | 3 | **28** |
| D. Tự động viết progress update | 3 | 4 | 4 | 4 | 2 | 5 | 2 | 24 |
| E. Phân loại chi tiêu | 4 | 4 | 4 | 3 | 2 | 3 | 3 | 23 |

Chọn **A — gom deadline và yêu cầu bài tập đa nguồn** vì pain lặp lại, outcome đo trực tiếp được, có bằng chứng reminder tạo tác động, và khoảng trống nằm ở interoperability + provenance thay vì cạnh tranh trực diện với LMS.

## 3. Top 3 Problem Cards

### Card #1 — Assignment Control Tower

**Problem một câu:** Sinh viên học nhiều môn phải tự đọc và hợp nhất deadline, yêu cầu, rubric và thay đổi từ LMS, email, chat và file; dữ liệu dễ bị bỏ sót hoặc hiểu sai trước khi được đưa vào lịch.

**Actor:** Sinh viên đại học học 5–7 môn/kỳ, có ít nhất hai kênh nhận thông tin học tập.

**Job-to-be-done:** Khi giảng viên đăng hoặc sửa yêu cầu, tôi muốn biết chính xác “phải nộp gì, khi nào, ở đâu và theo điều kiện nào”, kèm link về nguồn gốc, để lên kế hoạch mà không đọc lại toàn bộ luồng tin.

**Current workflow:**

```text
[Mở từng LMS/email/chat]
  → [lọc thông báo liên quan]
  → [đọc bài đăng/file đính kèm]
  → [tự diễn giải deadline + deliverable + rubric]
  → [copy sang Calendar/To-do]
  → [tự chọn thời điểm nhắc]
  → [trước khi nộp, mở lại nguồn để kiểm tra]
```

**Bottleneck:** Hai bước “lọc” và “diễn giải”. Calendar chỉ hữu ích sau khi dữ liệu đã được nhập đúng; due date có thể nằm trong văn bản tự do hoặc bị cập nhật ở một kênh khác.

**Impact:** Tốn thời gian kiểm tra hằng ngày, tạo lỗi nhập lịch và missed assignment. Tác động kinh doanh cuối cùng là retention/engagement của nhà trường và kết quả học tập của sinh viên, nhưng cần pilot nội địa để định lượng.

**Evidence:**

- Quy mô sinh viên Việt Nam và chiến lược học số tạo tập người dùng đủ lớn.^1,2
- RCT/pilot cho thấy proactive deadline reminders cải thiện submission.^4
- Google Classroom chỉ đưa item lên calendar khi assignment có due date; hệ thống xử lý tốt dữ liệu nội bộ nhưng không giải quyết đầy đủ thông tin rải ở email/chat/file.^5
- Một nghiên cứu 2026 cảnh báo nudge fatigue: thêm quá nhiều reminder có thể bị xem như “nag”; timing và targeting quan trọng.^6

**Success metrics cho pilot 20 sinh viên / 4 tuần:**

| Metric | Baseline | Target | Cách đo |
|---|---|---|---|
| Thời gian tổng hợp task học tập | Đo tuần 0 | Giảm ≥50% | Screen/time diary, median phút/tuần |
| Tỷ lệ task bị bỏ sót | Đo tuần 0 | Giảm ≥30% | Đối chiếu submission/LMS |
| Precision của extracted field | Chưa có | ≥95% với deadline; ≥90% với deliverable | Human-labelled test set |
| Tỷ lệ người dùng sửa extraction | Chưa có | <15% item | Audit log |
| Notification hữu ích | Chưa có | ≥70% reminder được đánh dấu hữu ích | One-tap feedback |

**Non-AI alternative:** Một form chuẩn cho giảng viên + đồng bộ LMS → calendar + rule nhắc D-3/D-1. Đây phải là baseline; nếu trường dùng một LMS nhất quán thì có thể đã đủ.

**AI hypothesis:** AI chỉ dùng để trích cấu trúc từ tiếng Việt tự do và so sánh bản cập nhật. Rule đảm nhiệm dedupe, lịch và reminder; sinh viên xác nhận mọi item có độ tin cậy thấp.

**Business gap:**

1. LMS hiện hữu tối ưu trong “walled garden”; sinh viên thực tế nhận thông tin qua nhiều nguồn.
2. Tool lịch/task đòi người dùng nhập dữ liệu sạch; chatbot trả lời thì khó audit.
3. Khoảng trống khả thi là một **trust layer**: mỗi field có đoạn trích + deep link về nguồn, phát hiện conflict, không tự ghi lịch nếu chưa chắc.
4. Go-to-market nên B2B2C theo khoa/trường hoặc cohort, vì CAC consumer EdTech cao và tích hợp cần quyền quản trị. Direct-to-student chỉ nên là pilot/PLG.

**Willingness-to-pay cần kiểm chứng:** giả thuyết 29.000–49.000đ/tháng cho cá nhân hoặc license theo active student cho trường. Không đưa con số này vào forecast trước 10–15 interview và landing-page smoke test.

**Quick gut:** **Workflow**, không phải Agent.

### Draft future workflow

```text
[Sinh viên forward/share nguồn được phép]
  → [Parser + AI trích field, giữ nguyên source snippet]
  → [Rule validate ngày, múi giờ, duplicate, conflict]
  → {confidence cao?}
       ├─ Không → [Sinh viên sửa/xác nhận]
       └─ Có    → [Sinh viên one-tap confirm]
  → [Ghi Calendar/To-do]
  → [Rule gửi tối đa 2 reminder theo trạng thái]
  → [Sinh viên mở nguồn gốc và nộp bài]

Fallback: không đọc được hoặc nguồn mâu thuẫn → không tạo deadline; hiển thị “cần kiểm tra”.
Human boundary: AI không tự đổi deadline, không tự nộp bài, không đọc nguồn chưa được cấp quyền.
```

### Card #2 — Evidence-first Research Copilot

**Problem một câu:** Sinh viên mất thời gian tìm và sàng lọc nguồn, trong khi câu trả lời GenAI có thể thiếu provenance hoặc bịa citation.

**Actor:** Sinh viên làm report/essay có yêu cầu nguồn học thuật hoặc nguồn chính thức.

**Workflow:** đặt câu hỏi → search web/library → mở nhiều tab → đánh giá tác giả/ngày/phương pháp → lưu citation → viết claim → kiểm tra claim-source.

**Bottleneck:** đánh giá độ phù hợp của nguồn và map từng claim sang bằng chứng, không phải việc sinh văn bản.

**Metric:** time-to-3-qualified-sources giảm 40%; citation precision ≥98%; 100% claim quan trọng có link và đoạn bằng chứng; zero invented DOI.

**Non-AI alternative:** checklist SIFT + Zotero + database filters. Đây là baseline mạnh.

**AI hypothesis:** AI đề xuất query, tóm tắt và highlight evidence; rule kiểm DOI/URL/metadata; người dùng quyết định nguồn có đủ mạnh không.

**Vì sao xếp #2:** AI advantage cao và UNESCO xác nhận nhu cầu human-centred validation, privacy và ethical design,^7 nhưng thị trường research assistant đã đông và việc tiếp cận full-text/licensing khó.

**Draft future workflow:** query decomposition → search APIs → rule lọc metadata → AI map claim/evidence → sinh viên mở nguồn và approve → export citation.

### Card #3 — Group Action-item Reconciler

**Problem một câu:** Sau họp nhóm, nhiệm vụ nằm rải trong transcript/chat nên thiếu owner, deadline hoặc bị thay đổi mà bảng task không cập nhật.

**Actor:** Nhóm đồ án sinh viên 3–6 người.

**Workflow:** họp → ghi notes → nhắn lại → nhóm trưởng diễn giải → gán owner → nhập board → nhắc → hỏi tiến độ.

**Bottleneck:** chuyển hội thoại không cấu trúc thành commitment rõ và reconcile thay đổi.

**Metric:** 100% task có owner + due date; task quá hạn không báo trước giảm 30%; thời gian recap giảm 50%; precision extraction ≥90%.

**Non-AI alternative:** meeting template bắt buộc cú pháp `Owner — Task — Due` và bot rule-based.

**AI hypothesis:** AI draft action items và phát hiện conflict; mỗi owner phải accept trước khi task có hiệu lực.

**Vì sao xếp #3:** workflow và MVP dễ, nhưng Slack/Teams/Notion đã có nhiều tính năng summary/action item; willingness-to-pay của nhóm sinh viên thấp hơn mô hình license tổ chức.

**Draft future workflow:** notes/chat → AI draft → rule kiểm field → từng owner accept → task board → targeted reminder → weekly reconcile.

## 4. Pitch 60 giây cho Card #1

“Vấn đề không phải sinh viên thiếu thêm một to-do app. Vấn đề là dữ liệu đầu vào cho lịch học đang rải ở LMS, email, chat và file, trong đó deadline và yêu cầu thường là văn bản tự do. Việt Nam có hơn 2 triệu sinh viên đại học, còn nghiên cứu thực nghiệm cho thấy nhắc đúng lúc có thể tăng tỷ lệ nộp bài 3,7–5,7 điểm phần trăm. Sản phẩm đề xuất là workflow trích xuất có dẫn nguồn: AI đọc nội dung được người dùng cho phép, rule kiểm ngày và conflict, sinh viên xác nhận rồi hệ thống mới ghi lịch và gửi reminder giới hạn. Pilot 4 tuần sẽ đo thời gian tổng hợp, task bỏ sót, độ chính xác extraction và notification fatigue. Nếu trường đã chuẩn hóa một LMS và calendar sync giải quyết đủ, chúng ta không build AI.”

## 5. Self-challenge trước khi đưa vào nhóm

| Câu hỏi challenge | Trả lời hiện tại | Việc phải kiểm chứng |
|---|---|---|
| Đây có thật sự là pain hay chỉ là bất tiện? | Evidence quốc tế cho thấy reminder tác động submission, nhưng pain đa nguồn tại Việt Nam chưa được định lượng | 10–15 interview + diary study 2 tuần |
| Vì sao Google Classroom/Gemini chưa đủ? | Chúng mạnh trong Classroom; gap giả định là cross-channel + provenance + conflict | Test với 5 workflow thực, lập competitor matrix mới nhất |
| AI sai deadline thì sao? | Sai một deadline là high-impact | Default human confirmation; deterministic date validator; source snippet; abstain khi conflict |
| Người dùng có chịu cấp quyền email/chat? | Chưa biết; đây có thể là blocker | Prototype “forward-only” không cần inbox-wide permission để test trust |
| Reminder có tạo thêm noise? | Có bằng chứng nudge fatigue | Cap 2 reminder/task, theo trạng thái, cho snooze/tắt theo môn |
| Ai trả tiền? | Giả thuyết khoa/trường trả vì retention; student PLG để chứng minh usage | 5 interview B2B + pricing smoke test; chưa tính revenue |

## 6. Quyết định cá nhân

**Not Yet — tiến hành discovery/pilot, chưa build product đầy đủ.**

Lý do: problem có quy mô và cơ chế tác động hợp lý, nhưng bằng chứng Việt Nam về fragmentation, baseline missed assignments, willingness-to-pay và willingness-to-connect-data còn thiếu. MVP nhỏ nhất không cần agent:

1. Người dùng forward 20 thông báo/bài tập thật vào prototype.
2. Hệ thống extract 5 field: môn, deliverable, deadline, nơi nộp, source link.
3. Người dùng confirm/edit; chỉ sau đó mới ghi Calendar.
4. Pilot 20 sinh viên trong 4 tuần, so sánh với tuần baseline.
5. **Go** nếu deadline precision ≥95%, thời gian giảm ≥50%, ít nhất 60% weekly active và không có sự cố privacy nghiêm trọng.
6. **No-Go / pivot về rule** nếu dữ liệu phần lớn đã structured trong một LMS, người dùng không cấp quyền/forward nguồn, hoặc edit rate >25% sau hai vòng cải tiến.

## 7. Tài liệu tham khảo

1. Bộ Giáo dục và Đào tạo. “[Số liệu chung Giáo dục Đại học năm học 2023–2024](https://moet.gov.vn/content/tintuc/Lists/News/Attachments/10555/so-lieu-chung-dh-23-24.pdf).” Truy cập 11/09/2026.
2. Chính phủ Việt Nam. “[Tăng cường ứng dụng công nghệ thông tin và chuyển đổi số trong giáo dục và đào tạo](https://media.chinhphu.vn/tang-cuong-ung-dung-cong-nghe-thong-tin-va-chuyen-doi-so-trong-giao-duc-va-dao-tao-102220126174621634.htm).” 26/01/2022.
3. U.S. International Trade Administration. “[Vietnam — Education and Training](https://www.trade.gov/country-commercial-guides/vietnam-education-and-training).” Truy cập 11/09/2026.
4. Motz, B. A. và cộng sự. “[Automated Educative Nudges to Reduce Missed Assignments in College](https://doi.org/10.1109/TLT.2021.3064613).” *IEEE Transactions on Learning Technologies*, 14(2), 2021.
5. Google for Education. “[View due dates and events in a calendar](https://support.google.com/edu/classroom/answer/6272985?hl=en-GB)” và “[About Classroom](https://support.google.com/edu/classroom/answer/6020279?hl=en).” Truy cập 11/09/2026.
6. Taylor, H. A. và cộng sự. “[Are you still engaged? Leveraging the LMS to support engagement in asynchronous courses](https://doi.org/10.1017/cts.2026.10752).” *Journal of Clinical and Translational Science*, 2026.
7. UNESCO. “[Guidance for generative AI in education and research](https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research?hub=195885).” 2023, cập nhật 16/01/2026.

## 8. Checklist cá nhân

- [x] Scan ≥5 problems (đã scan 10).
- [x] Có actor, workflow, bottleneck và dấu hiệu cho mỗi top card.
- [x] Có top 3 Problem Cards và draft before/after workflow.
- [x] Có research nguồn chính thức/nghiên cứu gốc, competitor và khoảng trống kinh doanh.
- [x] Có metric baseline/target/cách đo và boundary.
- [x] So sánh non-AI với AI; không mặc định Agent.
- [x] Có pitch và self-challenge.
- [x] Quyết định dựa trên mức độ bằng chứng: Not Yet, discovery trước build.
