# Case Study 3: UMG vs Anthropic (Vi phạm Bản quyền Lời bài hát)

## 1. Khái quát Sự kiện (Brief Case)

| Thông tin | Chi tiết |
| :--- | :--- |
| **Sản phẩm / Công ty bị lỗi** | Universal Music Group (UMG) cùng các nhà xuất bản kiện Anthropic (công ty phát triển Claude AI) |
| **AI Use Case** | Sử dụng dữ liệu văn bản khổng lồ (Web Scraping) bao gồm vạn lời bài hát có bản quyền để huấn luyện Mô hình Ngôn ngữ Lớn (LLM). |
| **Thời điểm xảy ra** | Bắt đầu khởi kiện Tháng 10/2023 - Đang tiếp diễn |
| **Bối cảnh chi tiết** | Các hãng xuất bản âm nhạc lớn dẫn đầu là UMG kiện Anthropic vì cáo buộc đã "cào" (scrape) và sử dụng trái phép hàng vạn lời bài hát có bản quyền từ internet để huấn luyện mô hình Claude. Khi bị prompt, Claude có thể nhả ra nguyên văn lời các bài hát nổi tiếng của Beyoncé, Rolling Stones... hoạt động hệt như một website cung cấp lyrics trả phí nhưng lại hoàn toàn miễn phí và không trả tiền tác quyền. |
| **Stakeholder bị ảnh hưởng** | Hàng triệu nhạc sĩ, nghệ sĩ toàn cầu, các nhà xuất bản âm nhạc truyền thống, và hệ sinh thái AI. |
| **Số liệu chính** | Hơn **20.000** bài hát bị cáo buộc vi phạm bản quyền rõ ràng; mức bồi thường đòi hỏi hơn **3 tỷ USD** (lên tới 150.000 USD cho mỗi vi phạm). |
| **Nguồn gốc** | 1. [The Guardian (2023)](https://www.theguardian.com/music/2023/oct/19/universal-music-sues-ai-company-anthropic-over-copied-lyrics) <br>2. [Music Business Worldwide (2023)](https://www.musicbusinessworldwide.com/universal-music-group-anthropic-lawsuit-ai-lyrics/) |

## 2. Bảng phân tích Tác hại (Harm Map Worksheet)

| Khía cạnh | Đánh giá / Phân tích chi tiết |
| :--- | :--- |
| **High-risk moment** | Thu thập hàng loạt dữ liệu bản quyền đưa vào huấn luyện mô hình; AI sinh ra văn bản bản quyền nguyên văn (verbatim) khi nhận prompt từ người dùng. |
| **Failure mode** | **Misuse** (Sử dụng dữ liệu huấn luyện không xin phép) / **Bias-fairness** (Bóc lột công sức lao động của người sáng tạo). |
| **Layer xảy ra lỗi** | **Model** (Quá trình huấn luyện - Training Data Pipeline). |
| **Tác hại (Harm) đã xảy ra** | Thiệt hại kinh tế khổng lồ cho người sáng tạo nội dung gốc do không được trả tiền bản quyền tác giả. Phá vỡ hoàn toàn cấu trúc trả tiền bản quyền hợp pháp của ngành công nghiệp âm nhạc. |
| **Harm lens** | **Opportunity loss** (Mất cơ hội kinh tế và thiệt hại tài chính). |
| **Severity (Độ nghiêm trọng)** | **High (3)** - Vi phạm diện rộng đạo luật sở hữu trí tuệ toàn cầu. |
| **Scale (Quy mô)** | **Critical (4)** - Tác động đến cơ sở dữ liệu của toàn bộ nền âm nhạc thế giới. Hàng triệu người sáng tạo bị ảnh hưởng bát cơm. |
| **Probability (Xác suất)** | **High (3)** - AI chắc chắn sẽ sinh ra lời bài hát nếu người dùng cố ý nhập prompt vì dữ liệu đã nằm sâu trong weights của mô hình. |
| **Frequency (Tần suất)** | **High (3)** - Mọi mô hình LLM hiện nay (OpenAI, Google, Meta) đều đối mặt với phương thức cào dữ liệu tương tự để tiết kiệm chi phí. |
| **Lý giải chung** | Rủi ro kinh tế khổng lồ (3 tỷ USD) liên quan đến hàng vạn tác giả. Nếu các công ty AI thắng kiện bằng chiêu bài "fair use", ngành sáng tạo truyền thống có nguy cơ sụp đổ do không còn nguồn thu. |