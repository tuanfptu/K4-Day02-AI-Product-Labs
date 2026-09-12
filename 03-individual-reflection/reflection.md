# 03 — Individual Reflection

> Ghi chú trung thực: nội dung cá nhân đã hoàn thành với hỗ trợ của AI. Vì chưa có bằng chứng về buổi làm nhóm, bài không tự nhận đã pitch, phỏng vấn hay challenge thành viên khác.

## Thông tin cá nhân

- Họ và tên: _Bổ sung trước khi nộp_
- Mã học viên: _Bổ sung trước khi nộp_
- Nhóm: _Bổ sung sau khi ghép nhóm_
- Candidate problem nhóm chọn: _Chưa chốt; candidate cá nhân đề xuất là Assignment Control Tower_

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Xây danh sách 10 pain points theo 4 lăng kính và gắn kế hoạch đo | Hoàn thành đầu vào cá nhân để pitch |
| Pitch Problem Card | Chuẩn bị pitch cho Assignment Control Tower | Sẵn sàng trình bày; chưa ghi nhận hoạt động pitch thật |
| Challenge bài của bạn khác | Chưa thực hiện | Chờ buổi convergence, không tạo dữ liệu giả |
| Gom trùng / cluster | Chuẩn bị ba candidate để đối chiếu với nhóm | Chưa có artifact nhóm |
| Chọn candidate problem | Chấm điểm và chọn candidate cá nhân | Assignment Control Tower đạt 32/35 trong bảng cá nhân |
| Validation / research | Trực tiếp làm literature review về nhận diện va chạm ô tô, tìm từ Google Scholar đến các paper/hội nghị như CVPR; đồng thời kiểm nguồn cho candidate deadline | Xác nhận workflow literature review tốn thời gian và tạo thêm một candidate có trải nghiệm thật |
| Workflow nhóm | Vẽ current/future workflow ở mức cá nhân, chỉ rõ AI, rule và human boundary | Có bản nháp để nhóm phản biện |
| Problem Statement | Làm rõ actor, bottleneck, impact, metric và boundary | Có nội dung cá nhân; chờ nhóm viết v0/v1 |
| Rule / Workflow / Agent | So sánh non-AI, rule và workflow; không chọn Agent | Đề xuất mức Workflow |
| Decision | Chọn Not Yet thay vì Go | Đặt điều kiện pilot 20 sinh viên trong 4 tuần |

**Dấu tay rõ nhất của tôi trong artifact cuối:** Tôi xác định khoảng trống không nằm ở một app nhắc deadline chung chung mà ở lớp hợp nhất thông tin đa nguồn có dẫn nguồn, phát hiện conflict và yêu cầu người dùng xác nhận.

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mở rộng góc nhìn và phản biện mô tả pain | Giúp chuẩn hóa actor, workflow và cách đo | Dễ tạo pain nghe hợp lý nhưng không gắn trải nghiệm thật | Chỉ giữ vấn đề có workflow và kế hoạch đo |
| Problem Card | Kiểm tra actor, metric và boundary | Làm rõ logic giữa pain và outcome | Có xu hướng đề xuất Agent quá sớm | Buộc so sánh với form, rule và workflow |
| Workflow | Chuyển mô tả thành flow và liệt kê edge case | Làm rõ điểm AI can thiệp và bước con người duyệt | Có thể che mất conflict và lỗi ngày giờ | Thêm source snippet, abstain, confirmation và fallback |
| Research | Mở rộng từ khóa, nhóm paper và tổng hợp limitation | Giúp bao quát nhanh hơn các hướng liên quan đến nhận diện va chạm ô tô | Có thể coi limitation của một paper là research gap hoặc đề xuất gap đã có người giải | Mở paper gốc, tìm cited-by/paper mới và yêu cầu ít nhất 2 nguồn cùng search phản chứng cho mỗi gap |
| Problem Statement | Phản biện độ cụ thể của bottleneck và metric | Giúp tách market signal khỏi bằng chứng pain | Dễ biến market size thành bằng chứng nhu cầu | Ghi rõ desk research chưa thay thế validation khách hàng |
| Rule / Workflow / Agent | So sánh quyền hạn và rủi ro của ba mức | Chỉ ra rule phù hợp với validation và lịch | Có xu hướng xem tự chủ cao là tốt hơn | Chọn Workflow, giữ human confirmation trước khi ghi lịch |
| Decision | Kiểm tra Go / Not Yet / No-Go | Làm lộ các bằng chứng còn thiếu | Dễ lạc quan về product-market fit | Chọn Not Yet và đặt metric cùng kill criteria định lượng |

---

## 3. Reflection câu hỏi mở

**Reflection:**

Trong tuần 05–11/09/2026, tôi đã dành hơn ba ngày để làm literature review và tìm khoảng trống nghiên cứu cho bài toán nhận diện va chạm ô tô. Tôi phải đi qua ít nhất ba tầng nguồn từ Google Scholar đến trang lưu trữ hoặc publisher và các paper ở venue như CVPR. Workflow thực tế có 12 bước, từ đặt câu hỏi, mở rộng từ khóa và snowball citation đến kiểm tra gap cùng nguồn lực thực hiện. Tôi nhận ra tìm được nhiều paper chưa có nghĩa là tìm được hướng nghiên cứu tốt. Phần tốn công nhất là phân biệt paper thực sự cùng bài toán, nối kết quả với nhau và xác định hạn chế nào tạo thành một research gap có thật. Một limitation riêng lẻ không đủ để kết luận có gap vì công trình mới hơn có thể đã giải quyết nó. Gap cũng không hữu ích với tôi nếu cần dataset không thể tiếp cận, GPU vượt khả năng, thời gian quá dài hoặc kiến thức nền chưa đáp ứng. Vì vậy tôi đề xuất hệ thống tạo evidence map, search phản chứng cho từng candidate gap và chấm feasibility theo data, compute, thời gian cùng skill hiện có. AI hữu ích khi mở rộng từ khóa và phân nhóm phương pháp, nhưng có thể bịa citation hoặc biến nhận xét chung thành một gap nghe hấp dẫn. Tôi sẽ chỉ chấp nhận gap khi có paper gốc hỗ trợ, metadata kiểm được và chưa bị phủ định bởi search công trình mới hơn. Mốc hơn ba ngày là self-report hồi tưởng; ở lần review tiếp theo tôi sẽ lưu số giờ từng bước, số query, số paper mở, số paper giữ lại và lý do loại. Candidate này vì thế có bằng chứng trải nghiệm cá nhân rõ và xứng đáng được đưa vào buổi convergence cùng Assignment Control Tower.

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Cá nhân đã so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Cá nhân có quyết định Not Yet + lý do rõ
- [x] [10đ] Reflection có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
