# Track 1 - Day 17: Finding and Validating Pain Points

## 1. Thông tin cá nhân và nhóm
* **MHV:** 2A202601501
* **Họ tên:** Nguyễn Đặng Kỳ Anh
* **Tên nhóm:** chim sẻ đi nắng
* **Thành viên:**
  * Đặng Đức Hòa - `2A202601351`
  * Nguyễn Đức Anh - `2A202601063`
  * Nguyễn Đặng Kỳ Anh - `2A202601501`
* **Case đã chọn:** Case A — AI Tutor: Diagnostic Refresher

---

## 2. Problem Hypothesis Brief

### Solution Parking Lot
| Hướng giải quyết có thể có | AI / không sử dụng AI |
|---|---|
| **AI Tutor Diagnostic Refresher** (solution gốc) — nút bấm → AI chẩn đoán → ôn khái niệm nền → quay lại bài. | AI-based |
| Self-check trước khi tiếp tục bài — chèn 1 câu hỏi tự đánh giá ngắn ("Bạn thấy phần này thế nào: Rõ / Hơi rối / Chưa hiểu") ngay sau mỗi đoạn, giúp học viên tự định vị mức độ hiểu trước khi họ kịp lướt qua. | Không cần AI — chỉ là UI check-in đơn giản |
| Bản đồ khái niệm tiên quyết hiển thị sẵn — mỗi bài học hiển thị rõ "bài này cần bạn đã nắm: A, B, C" ngay từ đầu, để học viên tự nhận ra lỗ hổng trước khi bị vướng, thay vì xử lý sau khi đã tắc. | Không cần AI |
| Nút "Hỏi bạn học / hỏi trợ giảng" thay vì hỏi AI — khi vướng, kết nối học viên với người thật (peer hoặc TA) đang online, dựa trên giả thuyết rằng vấn đề không phải thiếu nội dung ôn tập mà thiếu ai đó giúp định vị đúng câu hỏi cần hỏi. | Không cần AI |
| AI theo dõi hành vi ngầm (không cần bấm nút) — AI phát hiện dấu hiệu "có thể đang vướng" qua hành vi thực tế (dừng lâu bất thường, tua lại video, đổi đáp án nhiều lần) và chủ động gợi ý hỗ trợ, thay vì chờ học viên tự nhận ra và bấm nút — giải quyết đúng pain là "học viên không tự định vị được vấn đề". | AI-based, nhưng khác cơ chế trigger |
| Diễn đàn/thread hỏi-đáp theo từng bài học — mỗi bài có sẵn khu vực câu hỏi thường gặp, học viên đọc câu hỏi người khác từng hỏi ở đúng bài đó để tự nhận ra "à, đây đúng là chỗ mình đang vướng". | Không cần AI — dựa vào dữ liệu cộng đồng có sẵn |

* **Problem Hypothesis:** Khi đang học một bài trên VLearn và gặp một bước/khái niệm mới mà không theo kịp, học viên gặp khó khăn nhưng vẫn cố gắng tiếp tục tiến trình học vì không xác định được chính xác mình đang không hiểu chỗ nào (chỉ cảm nhận chung chung là "khó/rối"), dẫn đến việc họ đọc lại lan man, đoán đáp án, hoặc bỏ qua/thoát ra tìm nguồn khác, làm mất mạch học và có thể dừng học giữa chừng.
* **Điều kiện đứng vững:** Học viên thực sự không tự định vị được vấn đề; việc này xảy ra thường xuyên; có workaround quan sát được; gây ra hậu quả thật (mất mạch, dừng học).
* **Điều kiện bác bỏ:** Học viên biết rất rõ mình hổng ở đâu (vấn đề chỉ là thiếu thời gian/tài liệu).

---

## 3. Conversation Guide
* **Tiêu chí tuyển:** Người đã học bài giảng online và gặp khái niệm/bước không theo kịp trong 7 ngày gần đây, người nghỉ học do lý do cá nhân làm mất kiến thức những ngày nghỉ...
* **Recruitment check:** *"Trong tuần rồi, có lúc nào bạn đang học online hoặc học trên trường mà cảm thấy rối, mất phương hướng không hiểu gì không?"*  
* **Lời mở đầu:** *"Chào bạn, bọn mình đang làm nghiên cứu nhỏ về trải nghiệm học online hoặc học trên lớp. Bọn mình rất muốn nghe câu chuyện thực tế của bạn,về những gì bạn đã trải qua."*  
* **Story opener:** *"Kể mình nghe về lần gần nhất bạn đang học mà tự nhiên thấy 'rối' hoặc bị bế tắc trong việc học tập lại đi, lúc đó bạn đang học bài gì và chuyện gì đã xảy ra?"*  

**Big 3 Questions:**
1. **Khả năng tự chẩn đoán:** *"Lúc bị tắc lại đó, bạn làm thế nào để xác định xem mình đang bị hổng kiến thức ở phần nào?"*
2. **Hành vi phản ứng:** *"Ngay khoảnh khắc thấy rối như vậy, bạn đã thao tác gì tiếp theo trên màn hình hoặc làm gì để xử lý?"*
3. **Hậu quả thực tế:** *"Sự cố đó đã ảnh hưởng thế nào đến kết quả hoặc tiến độ của buổi học ngày hôm đó?"*

**Probe bank (Câu hỏi đào sâu):**
* “Lúc đó chuyện gì xảy ra tiếp theo?” / “Bạn đã làm gì?”
* “Bạn đã dùng từ khóa gì để tra cứu Google/AI?” 
* “Phần nào khó nhất?” / “Việc đó kéo theo hậu quả gì?”

---

## 4. Practice Reflection
* **Câu hỏi nào đã giúp user kể một tình huống cụ thể?**  
  Câu Story Opener đã giúp user nhớ lại đúng một sự kiện thực tế trong quá khứ thay vì trả lời các thói quen chung chung.
* **Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**  
  Cần tránh hỏi các câu hỏi đóng hoặc giả định tương lai (VD: *"Bạn có muốn hệ thống giúp bạn không?"*). Cần tập trung follow up sát hơn vào các Workaround của user (VD: Khi user bảo đi tìm tài liệu khác, phải hỏi ngay *"Lúc đó bạn gõ từ khóa gì để tìm?"*).
* **Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?**  
  Nhóm đã sửa Câu hỏi 1 từ việc hỏi trực tiếp *"Lý do là gì?"* sang *"Bạn làm thế nào để xác định vị trí hổng?"*. Việc này giúp user dễ trả lời hơn, không bị cảm giác như đang "trả bài", đồng thời khai thác đúng việc họ có khả năng tự định vị vấn đề hay không. Bổ sung thêm câu probe hỏi về *"từ khóa tra cứu"*.

---

## 5. AI Support Log
* **AI đã giúp gì:** Hỗ trợ sắp xếp logic chuỗi Solution -> Change -> Problem; brainstorm các hướng tiếp cận giả thuyết (ví dụ chuyển từ "tốn thời gian tra cứu" sang "không tự chẩn đoán được lỗ hổng"); rà soát Conversation Guide để đảm bảo không chứa câu hỏi dẫn dắt hoặc làm lộ tính năng AI.
* **Điểm sai/hời hợt của AI:** Ở bước 1 (Solution), AI ban đầu có xu hướng viết nhầm sang Situation & Workaround thay vì bóc tách tính năng trung tính.
* **Cách tự sửa:** Đã chủ động điều chỉnh lại prompt và tự phân tách phần nào là Hoàn cảnh (Situation), phần nào là Tính năng hệ thống (Capability) để đưa vào đúng các bước trong framework bài Lab.