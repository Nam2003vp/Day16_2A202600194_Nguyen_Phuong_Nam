# Day 16 Submission

## Members
- Nguyễn Phương Nam — Product / AI

---

## 1. Idea reframed

### Original idea:
Xây dựng AI để đánh giá độ rủi ro của chủ đầu tư / dự án bất động sản.

### Reframed as a product opportunity:
Người mua bất động sản cá nhân tại Việt Nam đang phải đưa ra quyết định tài chính lớn trong khi thông tin về chủ đầu tư và dự án bị phân mảnh, thiếu minh bạch và dễ bị bias từ môi giới.

Hiện tại, họ vẫn có thể tìm thông tin, nhưng không có một cách đánh giá rủi ro có cấu trúc và đáng tin. Điều này dẫn đến quyết định dựa trên cảm tính hoặc nguồn tin không kiểm chứng.

Cơ hội sản phẩm là xây dựng một hệ thống AI không chỉ tổng hợp dữ liệu mà còn chuẩn hóa thành risk scoring + explanation có thể kiểm chứng, giúp người dùng ra quyết định với độ tin cậy cao hơn.

**Founding belief:** Decision quality, not information access, is the real bottleneck.

---

## 2. Customer / Segment Card

### Segment name:
First-time retail real estate investors (urban Vietnam)

### Operational context:
Cá nhân mua BĐS lần đầu để đầu tư hoặc tích sản (ticket size lớn so với thu nhập)

### Recurring workflow:
- Xem listing → shortlist dự án → research chủ đầu tư → hỏi môi giới / cộng đồng → so sánh → quyết định

### Pain moment:
Khi phải quyết định “có xuống tiền không” nhưng không chắc độ tin cậy của dự án

### Why now:
- Thị trường nhiều biến động, nhiều case rủi ro được public
- Người dùng đã quen với việc dùng AI để hỗ trợ decision
- Dữ liệu online (forum, pháp lý, báo chí) ngày càng nhiều nhưng khó tổng hợp

### Access path:
- Facebook groups (BĐS, đầu tư)
- Platform listing (Batdongsan, Chotot)
- YouTube / KOL tài chính cá nhân

### One-sentence description:
Người mua BĐS lần đầu đang tự research dự án nhưng không có cách đáng tin để đánh giá rủi ro trước khi xuống tiền.

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)

**Statement (JTBD):**
When I am about to commit to buying a real estate project, I want a reliable and explainable risk assessment of the developer and project, so I can avoid large financial loss.

**Current workaround:**
Google, hỏi môi giới, đọc forum, hỏi người quen

**Pain signal:**
- Rủi ro mất hàng trăm triệu – hàng tỷ
- Stress cao trước quyết định
- Tốn nhiều giờ research nhưng vẫn không chắc

**Evidence / proxy evidence:**
- Nhiều bài đăng “có nên mua dự án X không?”
- Case dự án chậm tiến độ / pháp lý không rõ ràng

**Why underserved:**
- Không có hệ thống chuẩn hóa đánh giá
- Nguồn thông tin bị bias (môi giới, quảng cáo)

### Need #2

**Statement (JTBD):**
When comparing multiple real estate projects, I want a standardized risk scoring system, so I can prioritize safer options quickly.

**Current workaround:**
So sánh cảm tính hoặc dựa vào lời khuyên

**Pain signal:**
- Decision fatigue
- Bias theo người tư vấn

**Evidence / proxy evidence:**
- Người dùng thường hỏi “dự án nào ổn hơn” thay vì có tiêu chí rõ

**Why underserved:**
- Không có benchmark chung giữa các dự án

---

## 4. Strategy Statement

For first-time retail real estate investors in Vietnam
who struggle with unreliable and fragmented risk information,
our product helps them make safer investment decisions
through an explainable AI-driven risk scoring system built on multi-source data,
unlike manual research or agent-driven advice,
because we can leverage structured data aggregation + domain-specific risk modeling.

---

## 5. Moat Hypothesis

**Moat mechanism:** Domain-learning flywheel + data compounding

If we deploy 50 times in the same vertical:
- Risk model accuracy improves (learn from real outcomes)
- Developer behavior patterns become clearer
- Trust → usage → more data → better model (feedback loop)

**Why competitors cannot easily replicate this:**
- Cần thời gian tích lũy dữ liệu thực tế + mapping giữa dữ liệu và outcome (dự án thành công / fail).
- Đây là dạng learning theo workflow dài hạn, không thể copy chỉ bằng model hoặc scraping dữ liệu.

---

## 6. Initial TAM / SAM / SOM view

**Approach:** bottom-up + assumption-based (không fake precision)

| Layer | Estimate          | Key assumptions                              | Confidence |
|-------|-------------------|---------------------------------------------|------------|
| TAM   | $300M–$800M/year | ~1–2M người mua BĐS/năm × $100–$500 willingness to pay | low        |
| SAM   | $30M–$100M/year  | ~10–20% là investor tự research online      | low        |
| SOM   | $0.5M–$2M (12–24mo) | capture ~1–2% early adopters               | low        |

**Top 3 unknowns requiring further research:**
- Willingness to pay thực sự (user có trả tiền cho “risk insight” không?)
- Data coverage có đủ để tạo trust không?
- UX nào khiến user tin AI hơn môi giới?

**Judgment:**
Worth pursuing but need to validate willingness to pay early

👉 (điểm cộng so với A: bạn không “ảo tưởng market”, có critical thinking)

---

## 7. Positioning Note (2 sentences)

**What we are:**
An AI-powered decision support tool that quantifies and explains real estate investment risk.

**What we are not / not yet:**
Not a listing platform or a brokerage service, and not a guarantee of investment outcome.

---

## 8. Self-assessment before Day 17

**Weakest link:**
Need validation (đặc biệt là willingness to pay và trust)

**Open questions:**
- Người dùng có trust AI đủ để ra quyết định tài chính lớn không?
- Risk score nên “explain thế nào” để không bị black-box?
- MVP nên bắt đầu từ use case nào (check 1 dự án vs so sánh nhiều dự án)?