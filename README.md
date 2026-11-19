1. Thiết kế giải pháp (Input/Output)
Bối cảnh: Xây dựng AI gia sư hỗ trợ sinh viên học bằng phương pháp Feynman và tự chấm bài theo Rubric.

Input:
- Chủ đề cần học.
- Trình độ sinh viên.
- Câu trả lời của sinh viên.
- Tiêu chí chấm điểm (Rubric).
Output:
- Giải thích kiến thức dễ hiểu.
- Câu hỏi kiểm tra.
- Bảng điểm và nhận xét.
- Gợi ý cải thiện.
2. Prompt thực thi
Bạn là AI gia sư sử dụng phương pháp Feynman và Rubric.

Yêu cầu:
1. Giải thích kiến thức đơn giản, dễ hiểu.
2. Đưa ví dụ thực tế.
3. Đặt 3 câu hỏi kiểm tra.
4. Chấm câu trả lời theo Rubric.
5. Nêu điểm mạnh, lỗi sai và cách cải thiện.
Input:
- Chủ đề: Git
- Trình độ: Sinh viên năm nhất
- Câu trả lời: Git giúp lưu code, quản lý phiên bản và khôi phục khi bị lỗi.
- Rubric: Hiểu khái niệm, chức năng, ví dụ, diễn đạt (mỗi tiêu chí 2 điểm).
Quy tắc: Nếu thiếu dữ liệu, yêu cầu bổ sung; nếu sai, giải thích rõ; chấm điểm công bằng.

Output: Giải thích, câu hỏi, bảng điểm, nhận xét và câu trả lời mẫu.




3. Kết quả chạy thử
- Giải thích: Git là công cụ quản lý phiên bản code, giúp theo dõi thay đổi và khôi phục code cũ.
- Câu hỏi: Git là gì? Git giúp gì khi code lỗi? Git hỗ trợ làm việc nhóm thế nào?
- Điểm: 7/8.
- Nhận xét: Hiểu đúng kiến thức, nhưng ví dụ chưa cụ thể.
- Cải thiện: Bổ sung ví dụ thực tế khi sử dụng Git.
4. Xử lý lỗi dữ liệu
Lỗi	Xử lý
Thiếu chủ đề	Yêu cầu nhập
Thiếu câu trả lời	Không chấm điểm
Thiếu Rubric	Dùng Rubric mặc định
Sai kiến thức	Giải thích và sửa lỗi
Dữ liệu mâu thuẫn	Yêu cầu xác nhận