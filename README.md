# Exercise M10W02 - Boosting LLMs’ SAT Reading Proficiency via Instruction Tuning - AIO2024

**Instruction Tuning (IT)** là một trong những kỹ thuật training mô hình ngôn ngữ lớn (LLMs) rất quan trọng. Trong đó, IT giúp cải thiện khả năng của mô hình cũng như kiểm soát kết quả đầu ra. Là kiểu huấn luyện mô hình có giám sát từ bộ dữ liệu theo cặp (instruction-output), từ đó giúp mô hình thu hẹp khoảng cách giữa từ kế tiếp được sinh ra và sự chỉ dẫn của con người.

Bài tập trình bày quá trình huấn luyện một mô hình ngôn ngữ lớn (LLM) với dữ liệu instruction để thực hiện các câu hỏi trắc nghiệm trong bài đọc hiểu thuộc kỳ thi SAT. Mục tiêu là xây dựng một mô hình có khả năng cải thiện độ chính xác trong các bài kiểm tra đọc hiểu SAT, đồng thời hỗ trợ nâng cao kỹ năng đọc hiểu tiếng Anh một cách tổng quát. Bài toán được định nghĩa với đầu vào và đầu ra như sau

- **Input:** Một câu prompt với lời hướng dẫn (instruction) để LLM thực hiện một bài bài đọc hiểu SAT và lựa chọn phương án đúng.
- **Output:** Lời phản hồi từ mô hình, trong trường hợp này là một trong các phương án trắc nghiệm đã được mô tả trong prompt

Dưới đây là pipeline của bài tập:
![Pipeline Instruction Tuning](/readme_img/pipeline.png "AIO2024")