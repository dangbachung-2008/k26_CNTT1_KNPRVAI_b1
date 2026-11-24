# [Vận dụng cơ bản 1] Sửa đổi prompt thiếu cấu trúc ràng buộc định dạng

**Bước 1: Phân tích lỗi (3 phần thừa thãi ở prompt cũ)**

-   **Lời chào mở đầu:** Các câu xã giao không cần thiết (_"Chào bạn! Dưới đây là..."_).
    
-   **Diễn giải lan man:** Viết thành đoạn văn dài, thêm câu dẫn dắt thay vì tách ý trực tiếp.
    
-   **Lời kết gợi ý:** Các câu hỏi thăm ở cuối (_"Hy vọng thông tin trên hữu ích..."_).

**Bước 2: Prompt tối ưu**

Giải thích ngắn gọn 3 khái niệm: Custom Instructions, Prompt Library, Prompt Injection.
Ràng buộc:
- Trình bày bằng gạch đầu dòng, mỗi ý tối đa 1-2 câu.
- Cấm viết lời chào, câu dẫn đầu bài và lời kết cuối bài.

**Bước 3: Kết quả phản hồi mẫu (đã lọc chữ thừa)**

-   **Custom Instructions:** Là thiết lập vai trò, ngữ cảnh và quy tắc mặc định áp dụng xuyên suốt mọi cuộc trò chuyện để không phải nhập lại nhiều lần.
    
-   **Prompt Library:** Là kho lưu trữ các prompt mẫu có gắn biến số (như `[chủ đề]`,  `[định dạng]`) giúp tái sử dụng nhanh cho các tác vụ lặp lại.
    
-   **Prompt Injection:** Là kỹ thuật chèn chỉ dẫn độc hại vào dữ liệu đầu vào nhằm đánh lừa AI bỏ qua quy tắc gốc và làm theo ý kẻ tấn công.
