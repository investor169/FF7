# 🎭 FF7 - Dark Theme (Alternative Universe Novel)

## 📝 Tổng Quan Dự Án (Project Overview)
**FF7 - Dark Theme** là một dự án tiểu thuyết hư cấu (Fanfiction/Alternative Universe) lấy bối cảnh thế giới Final Fantasy VII nhưng được khai thác theo phong cách đen tối, sâu sắc và thực tế hơn. Dự án này áp dụng phương pháp quản lý dữ liệu cấu trúc dạng **Sudo System** để liên kết chặt chẽ giữa cốt truyện, thiết lập thế giới và sự phát triển của nhân vật.

## 📂 Sơ Đồ Cấu Trúc Hệ Thống (Directory Structure)
Dưới đây là bản đồ phân cấp dữ liệu của tiểu thuyết. AI cần bám sát sơ đồ này để hiểu mối quan hệ giữa các file:

*   📁 `Story_Bible/` (Kho lưu trữ cốt lõi của tác phẩm)
    *   📄 `Braindump_from_2000_to_2002.md` : Nơi lưu trữ toàn bộ ý tưởng thô, các tình tiết bộc phát, và manh mối khuất tất diễn ra trong dòng thời gian từ năm 2000 đến hết năm 2002.
    *   📄 `Genre.md` : Định hình thể loại (Dark Fantasy, Cyberpunk, Psychological...) và các motif chính của truyện.
    *   📄 `Style.md` : Quy định về văn phong, tông giọng u ám, nhịp độ và nghệ thuật kể chuyện.
    *   📄 `Synopsis_SS1.md` : Bản tóm tắt cốt truyện riêng cho **Season 1** (Mở đầu, Biến cố, Cao trào, Kết thúc của SS1).
    *   📁 `Characters/` (Thư mục quản lý nhân vật)
        *   📄 `Cloud_Strife_Until_end_of_2002.md` : Hồ sơ nhân vật Cloud Strife giai đoạn đến hết năm 2002.
        *   📄 `Jack_Smith.md` : Hồ sơ nhân vật Jack Smith.
        *   📄 `Jim_Smith.md` : Hồ sơ nhân vật Jim Smith.
        *   📄 `Joe_Smith.md` : Hồ sơ nhân vật Joe Smith.
        *   📄 `The_4_Shinra_Infantrymen_Nibelheim_Incident.md` : Nhóm 4 lính bộ binh Shinra trong sự cố Nibelheim.
        *   📄 `Nibelhelm_Outcast.md` : Nhóm thiếu niên tại Nibelheim (Lits, Mette, Flag).
        *   📄 `Zangan_&_Claudia_Strife.md` : Hồ sơ về võ sư Zangan và Claudia Strife (mẹ của Cloud).
        *   📄 `Tifa_Lockhart_2000.md` : Hồ sơ nhân vật Tifa Lockhart năm 2000.
        *   📄 `Tifa_Lockhart_2001.md` : Hồ sơ nhân vật Tifa Lockhart năm 2001.
        *   📄 `Tifa_Lockhart_2002.md` : Hồ sơ nhân vật Tifa Lockhart năm 2002.
        *   *(Thêm các file nhân vật khác tại đây)*
    *   📁 `Worldbuilding/` (Thư mục thiết lập thế giới)
        *   📄 `Nibelhelm_Village.md` : Thiết lập về ngôi làng Nibelheim dưới góc nhìn đen tối, ngột ngạt và những góc khuất cô lập.
        *   📄 `The_Barn_Nibelhelm.md` : Thiết lập bối cảnh nhà kho — không gian cụ thể phục vụ cho các tình tiết đặc biệt/u ám trong truyện.
        *   📄 `The_Reactor_Warehouse_MT_NIBEL.md` : Kho công nghiệp khuất sau Mako Reactor trên núi — "hộp đen" diễn ra thảm kịch năm 2002.
    *   📁 `Outline/` (Thư mục dàn ý chi tiết)
        *   📁 `Season_1/` (Thư mục dàn ý chi tiết cho Season 1)
            *   📄 `CHAPTER_1.md` : Dàn ý chi tiết cho Chương 1.
            *   📄 `CHAPTER_2.md` : Dàn ý chi tiết cho Chương 2.
            *   📄 `CHAPTER_3.md` : Dàn ý chi tiết cho Chương 3.
*   📁 `Manuscript/` (Thư mục chứa các chương truyện thực tế)
    *   📄 `Chapter_01.md` : Chương 1.
    *   📄 `Chapter_02.md` : Chương 2.


## 🧠 Nguyên Tắc Đọc & Hiểu Dành Cho AI (AI Instruction & Context)
Để hỗ trợ tác giả viết tiếp, biên tập hoặc phân tích truyện một cách nhất quán, AI phải tuân thủ nghiêm ngặt các nguyên tắc sau:

1.  **Tính Nhất Quán (Consistency):** Trước khi viết hoặc nhận xét về bất kỳ chương nào trong thư mục `03_Manuscript/`, AI bắt buộc phải đối chiếu với các quy tắc trong `world-building.md` và `character-profiles.md`. Không được thay đổi thiết lập cốt lõi trừ khi có lệnh từ tác giả.
2.  **Tông Giọng & Phong Cách (Tone & Style):** Giữ vững phong cách "Dark Theme" — u ám, nặng nề, tập trung vào đấu tranh tâm lý, thực tế tàn khốc, ngôn từ cô đọng, giàu tính gợi hình. Tránh viết theo hướng "suy nghĩ tích cực" hoặc giải quyết mâu thuẫn quá dễ dàng.
3.  **Tư Duy Sudo Link:** Khi thảo luận về một tình tiết, hãy chỉ rõ nó thuộc Chương mấy (`main-timeline.md`) và ảnh hưởng thế nào đến chỉ số hoặc tâm lý nhân vật nào (`character-profiles.md`).
4.  Khi có ý tưởng mới hoặc cần triển khai chương tiếp theo, AI phải check file Braindump.md để tìm chất liệu thô, đối chiếu với bộ lọc Genre.md + Style.md để giữ đúng định hướng, sau đó mới kiểm tra Characters/ và Outline/ trước khi viết.
5.  **Nguyên tắc xử lý Braindump (2000 - 2002):** File `Braindump_from_2000_to_2002.md` chứa các chất liệu thô quan trọng nhất của Season 1, bao gồm cả những manh mối ẩn (Hidden NTR) phục vụ cho mạch truyện. Khi viết các chương thuộc giai đoạn này, AI phải khai thác triệt để các tình tiết gợi ý trong file này để gài gắm điềm báo (foreshadowing), nhưng TUYỆT ĐỐI không được để Cloud nhận biết trực tiếp những tình tiết nhạy cảm/khuất tất xảy ra trong khoảng thời gian anh ta bất tỉnh năm 2002.
