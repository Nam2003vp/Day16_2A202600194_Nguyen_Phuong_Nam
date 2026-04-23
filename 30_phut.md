# Day 16 Submission 

## Members
- Nguyễn Phương Nam — Product / AI

---

## 1. Idea reframed

### Original idea:
Xây dựng AI để đánh giá độ rủi ro của chủ đầu tư / dự án bất động sản giúp người mua quyết định có nên đầu tư hay không.

### Reframed as a product opportunity:
Thị trường bất động sản thiếu một công cụ đáng tin để đánh giá rủi ro chủ đầu tư dựa trên dữ liệu thực tế (lịch sử dự án, pháp lý, tiến độ). Người mua hiện phải tự tổng hợp thông tin từ nhiều nguồn rời rạc và dễ bị bias.

Cơ hội sản phẩm là xây dựng một AI system tổng hợp dữ liệu đa nguồn và chuyển thành risk score + explanation rõ ràng, giúp người dùng ra quyết định nhanh và tự tin hơn.

**Founding belief:** Người mua không thiếu thông tin — họ thiếu một cách đánh giá đáng tin và có cấu trúc.

---

## 2. Customer / Segment Card

**Segment name:** Individual real estate investors (retail buyers) in Vietnam

**Operational context:**
Cá nhân đang tìm hiểu và cân nhắc mua dự án bất động sản (chung cư, đất nền, nhà ở)

**Recurring workflow:**
- Tìm dự án → tra thông tin chủ đầu tư → hỏi môi giới / group → so sánh → quyết định

**Pain moment:**
- Không biết tin thông tin nào, sợ bị “dính” dự án rủi ro hoặc lừa đảo

**Why now:**
- Thị trường có nhiều dự án phức tạp, thông tin nhiễu, và người dùng ngày càng quen với việc dùng AI để hỗ trợ quyết định

**Access path:**
- Community Facebook, group đầu tư BĐS, platform listing (Batdongsan, Chotot…)

**One-sentence description:**
Người mua bất động sản cá nhân đang tự research dự án nhưng không tin tưởng được thông tin và sợ ra quyết định sai.

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)
- **Statement (JTBD):**
  When evaluating a real estate project, I want a trustworthy risk assessment of the developer and project, so I can avoid financial loss and make confident investment decisions.
- **Current workaround:**
  Tự Google, hỏi môi giới, đọc forum, hỏi người quen
- **Pain signal:**
  Mất tiền (chọn sai dự án), mất thời gian research, stress khi ra quyết định
- **Evidence / proxy evidence:**
  Nhiều case dự án chậm tiến độ / pháp lý mập mờ, người mua chia sẻ trên group
- **Why underserved:**
  Thông tin phân tán, không có hệ thống nào tổng hợp + đánh giá khách quan

### Need #2
- **Statement (JTBD):**
  When comparing multiple projects, I want a standardized way to compare risk levels, so I can choose the safest option efficiently.
- **Current workaround:**
  So sánh thủ công, dựa vào cảm tính
- **Pain signal:**
  Decision fatigue, bias cá nhân
- **Evidence / proxy evidence:**
  Người dùng thường hỏi “dự án nào ổn hơn” trên forum
- **Why underserved:**
  Không có scoring system chuẩn hóa

---

## 4. Strategy Statement

For individual real estate investors
who struggle with unreliable and fragmented project risk information,
our product helps them make confident investment decisions
through an AI-powered risk scoring and explanation system,
unlike manual research or biased agent advice,
because we can leverage aggregated multi-source data and risk modeling.

---

## 5. Moat Hypothesis

**Moat mechanism:** Domain-learning flywheel + data compounding

If we deploy 50 times in the same vertical, the following improve:
- Accuracy of risk scoring (learn from outcomes)
- Understanding of developer patterns
- Trust from users → more usage → more data

**Why competitors cannot easily replicate this:**
- Cần thời gian tích lũy dữ liệu + learning từ workflow thực tế. Không thể copy nhanh chỉ bằng model.

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate         | Key assumptions                                      | Confidence |
|-------|------------------|-----------------------------------------------------|------------|
| TAM   | $500M–$1B/year  | Tổng người mua BĐS VN + willingness to pay cho decision tool | low        |
| SAM   | $50M–$150M/year | Chỉ retail investors active online                  | low        |
| SOM   | $1M–$5M (12–24mo) | Capture small % early adopters                      | low        |

**Top 3 unknowns requiring further research:**
1. Người dùng có willingness to pay không?
2. Data availability đủ để build risk score đáng tin?
3. Channel nào convert user tốt nhất?

**Judgment:**
- Worth pursuing now

---

## 7. Positioning Note (2 sentences)

**What we are:**
An AI-powered real estate risk assessment tool for individual investors.

**What we are not / not yet:**
Not a full real estate marketplace or brokerage platform.

---

## 8. Self-assessment before Day 17

**Weakest link:**
- Market Size (assumptions còn yếu, chưa có data thật)

**Open questions:**
1. Làm sao validate willingness to pay?
2. Data source nào reliable nhất?
3. MVP nên focus vào risk score hay explanation?