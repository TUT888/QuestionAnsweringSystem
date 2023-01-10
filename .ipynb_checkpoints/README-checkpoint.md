# Information Retrieval-Based Question Answering System
Đề tài: Xây dựng hệ thống trả lời câu hỏi tự động bằng phương pháp truy hồi thông tin <br>
Đây là một phần nội dung của đồ án cuối kỳ môn "Nhập môn xử lý ngôn ngữ tự nhiên" <br>

## Project Description

Đồ án bao gồm các phần:

1. Đọc dữ liệu các hỏi đáp: 
- Dữ liệu các cặp câu hỏi-đáp được thu thập từ các bạn trong lớp. Những dữ liệu này đều được chia theo từng chủ đề.
2. Trích xuất đặc trưng dữ liệu văn bản: Sử dụng kỹ thuật TF-IDF để trích xuất đặc trưng
3. Huấn luyện và dự đoán chủ đề của câu hỏi
4. Tìm câu trả lời từ câu hỏi nhập vào
- Câu hỏi nhập vào sẽ được đưa vào mô hình để dự đoán chủ đề
- Sử dụng độ tương tự cosin (Cosine Similarity) để tìm kiếm câu hỏi tương tự có cùng chủ đề trong tập dữ liệu hỏi-đáp có sẵn.
- Đưa ra câu trả lời của câu hỏi có độ tương đồng cao nhất từ tập dữ liệu.

## Libraries
Phiên bản sử dụng của một số thư viện
| Library | Version |
| --- | --- | 
| numpy | 1.19.5 |
| scipy | 1.5.4 |
| keras_preprocessing | 1.1.2 |
| sklearn | 0.19.0 |

## Files in repository
- File retrieval_based_qa.ipynb: file Jupyter Notebook của dự án
- Folder chatbot: các file text chứa dữ liệu các cặp câu hỏi-đáp theo chủ đề
  
## Tham khảo
Tham khảo mục 'Information Retrieval based chatbots (IR-based)' tại: [Tìm hiểu và xây dựng hệ thống chatbot trong thực tế](https://viblo.asia/p/tim-hieu-va-xay-dung-cac-he-thong-chatbot-trong-thuc-the-XL6lA8D4Zek)