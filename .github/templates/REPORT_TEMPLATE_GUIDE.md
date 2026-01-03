# 📖 Hướng dẫn sử dụng Report Template

## 🎯 Mục đích

Template này được thiết kế để đảm bảo mọi báo cáo phân tích từ hệ thống NoLine đều có:

- ✅ Cấu trúc thống nhất, chuyên nghiệp
- ✅ Dễ đọc, dễ tìm thông tin
- ✅ Đầy đủ thông tin cần thiết
- ✅ Tính nhất quán giữa các báo cáo

## 📋 Cấu trúc Template

### 1. Header Section (Bắt buộc)

```markdown
# 📊 BÁO CÁO PHÂN TÍCH

## [TIÊU ĐỀ]

**Session ID:** BF-YYYY-MM-DD-XXX
**Ngày tạo:** DD/MM/YYYY, HH:MM
**Hệ thống:** NoLine - Phân tích Dư luận
**Độ tin cậy:** ⭐⭐⭐⭐ (XX%)
```

**Lưu ý:**

- Session ID format: `BF-YYYY-MM-DD-XXX` (BF = Brief/Báo cáo)
- Độ tin cậy: Đánh giá từ 1-5 sao dựa trên chất lượng dữ liệu

### 2. Tóm tắt Điều hành (Bắt buộc)

- 2-3 đoạn văn ngắn gọn
- 5 điểm nổi bật với icon phù hợp
- Sử dụng số liệu cụ thể

### 3. Phần nội dung chính (10 phần)

#### Phần 1: Tổng quan Thị trường

- Sentiment Analysis (nếu phù hợp)
- Quy mô & Tăng trưởng
- So sánh theo thời gian
- Top Items/Trends

#### Phần 2-5: Phân tích Chi tiết

Mỗi phần tập trung vào 1 khía cạnh cụ thể:

- Phần 2: Thường về pricing, cost, financial metrics
- Phần 3: Về technology, tools, innovations
- Phần 4: Về behavior, preferences, lifestyle
- Phần 5: Về skills, capabilities, competencies

#### Phần 6: Xu hướng Chính

Bảng tổng hợp với:

- Impact level: 🔴 Critical / 🟠 High / 🟡 Medium / 🟢 Low
- Confidence score (%)

#### Phần 7: Khuyến nghị

- Box format cho target audience 1
- Table format cho target audience 2
- Segmentation recommendations

#### Phần 8: Dự báo

- Chia theo timeframe cụ thể
- Sử dụng icons: ✅ (Positive), ⚠️ (Caution), 🔄 (Neutral)

#### Phần 9: So sánh (Nếu phù hợp)

- Regional comparison
- Competitive positioning
- SWOT elements

#### Phần 10: Số liệu Chi tiết

- Raw data
- Detailed breakdowns
- Supporting statistics

### 4. Kết luận (Bắt buộc)

- Quote mạnh mẽ tóm tắt báo cáo
- 5 Key Takeaways

### 5. Phụ lục (Bắt buộc)

- Nguồn dữ liệu
- Methodology
- Limitations

## 🎨 Quy tắc Format

### Icons & Emojis

Sử dụng consistent icon set:

- 📊 📈 💰 🤖 🏠 📚 🎯 💡 🔮 🌏 📎 ✅
- 🟢 🟡 🟠 🔴 (cho status/severity)
- ⭐ (cho ratings)
- 🥇 🥈 🥉 (cho rankings)
- ✅ ⚠️ 🔄 (cho trends/predictions)

### Tables

```markdown
| Column 1 | Column 2 | Column 3    |
| -------- | -------- | ----------- |
| **Bold** | Value    | Description |
```

### Visual Bars

```markdown
Category: ████████░░ XX%
```

Sử dụng █ cho filled, ░ cho empty (tổng 10-12 blocks)

### Code Blocks

Dùng cho:

- Numerical comparisons
- Hierarchical data
- Visual representations

### Quotes

```markdown
> _"Quote text"_
> — Source, Title
```

### Bullet Points

- ✅ cho positive points
- ⚠️ cho warnings/cautions
- 🔄 cho neutral/ongoing
- 📌 cho highlights

## 🔧 Customization Guidelines

### Phần nào bắt buộc?

**Bắt buộc:**

1. Header Section
2. Tóm tắt Điều hành
3. Phần 1: Tổng quan
4. Phần 6: Xu hướng Chính
5. Phần 7: Khuyến nghị
6. Kết luận
7. Phụ lục

**Tùy chọn:**

- Phần 2-5: Chọn 2-4 phần phù hợp với topic
- Phần 8: Dự báo (nếu có đủ data)
- Phần 9: So sánh (nếu relevant)
- Phần 10: Chi tiết (nếu cần)

### Khi nào dùng phần nào?

| Topic Type        | Recommended Sections |
| ----------------- | -------------------- |
| Market Analysis   | 1,2,6,7,8,9,10       |
| Technology Trends | 1,3,5,6,7,8          |
| Consumer Behavior | 1,4,6,7,8            |
| Career/Job Market | 1,2,3,4,5,6,7,8,9,10 |
| Product/Service   | 1,2,4,6,7,8,9        |

## 📝 Best Practices

### 1. Tiêu đề

- Rõ ràng, cụ thể
- Bao gồm topic + timeframe
- VD: "Xu hướng Ngành FMCG Việt Nam 2026-2028"

### 2. Số liệu

- Luôn có đơn vị (USD, VNĐ, %, etc.)
- Round to reasonable precision
- Cite source khi cần

### 3. Tone

- Chuyên nghiệp nhưng dễ hiểu
- Tránh jargon không cần thiết
- Balance giữa data và insight

### 4. Length

- Tóm tắt: 150-250 từ
- Mỗi phần chính: 200-400 từ
- Tổng báo cáo: 2,500-5,000 từ (tùy complexity)

### 5. Visual Elements

- Sử dụng tables cho structured data
- Sử dụng code blocks cho comparisons
- Sử dụng visual bars cho percentages
- Sử dụng bullet points cho lists

## 🚀 Quick Start cho LLMs

### Step 1: Xác định thông tin cơ bản

```
- Topic: [Chủ đề báo cáo]
- Timeframe: [Giai đoạn phân tích]
- Session ID: [Generate theo format BF-YYYY-MM-DD-XXX]
- Confidence: [Đánh giá độ tin cậy dữ liệu]
```

### Step 2: Chọn sections phù hợp

- Xem bảng "Khi nào dùng phần nào" ở trên
- Bắt buộc: 1, 6, 7, Kết luận, Phụ lục
- Tùy chọn: 2-5, 8, 9, 10

### Step 3: Điền nội dung

- Bắt đầu từ Tóm tắt Điều hành
- Điền lần lượt các phần đã chọn
- Đảm bảo có đủ tables, visuals
- Kết thúc với Key Takeaways mạnh mẽ

### Step 4: Review checklist

- [ ] Có đầy đủ metadata (Session ID, date, confidence)?
- [ ] Tóm tắt có 5 highlights?
- [ ] Mỗi section có ít nhất 1 table/visual?
- [ ] Có quote trong Kết luận?
- [ ] Có liệt kê nguồn data trong Phụ lục?

## 💾 File Naming Convention

Format: `{slug}-{date}_{time}.md`

Example:

- `xu-huong-fmcg-gia-vi-2026-2028_2026-01-03_21-15.md`
- `thi-truong-viec-lam-it-vietnam-2026_2026-01-03_20-06.md`

Rules:

- Slug: lowercase, dấu gạch ngang, tiếng Việt không dấu
- Date: YYYY-MM-DD
- Time: HH-MM (24h format)

---

_Template Version: 1.0.0 | Last Updated: 03/01/2026_
