 **Yêu cầu thực hiện chi tiết**
Sử dụng kỹ thuật chia nhỏ prompt (Prompt Chaining) để viết cẩm nang theo từng phần:

Phần 1: Cách AI đoán từ (LLM hoạt động thế nào).

- Ai dự đoán từ qua cơ chế thuật toán và tính xác xuất cực kì phức tạp.
- LLM là mô hình ngôn ngữ lớn hoạt động bằng cách chia nhỏ token , chuyển token thành các con số để máy hiểu được , dùng self-attention để quét toàn bộ và nắm được ngữ cảnh , dự đoán hàng loạt từ tiếp theo , viết ra từng từ một rồi dùng từ đó làm gốc để lặp lại hết câu.

Phần 2: 3 cách nhận diện ảo giác của AI.

- cách nhận biết ảo giác AI là qua các câu trả lời mơ hồ , chung chung , kiểm tra bằng cách truy nhập trang web chính chủ check xem thông tin có chính xác không , yêu cầu AI dẫn chứng.
- 
Phần 3: Cấu trúc prompt mẫu tối ưu bằng khung CREATE.

-   khung CRATE :
1.  context : bối cảnh (gắn cho AI là góc nhìn chuyên gia cụ thể góc nhìn và chuyên môn  ) 
2.   requet : yêu cầu cốt lõi ( nêu rõ hành động AI thực hiện  )    
3.    explanation : giải thích và ràng buộc (đặt ra các ranh giới trong bài làm)  
4.   action : các bước hành động ( bắt AI tạo ra nhiều văn bản cùng lúc hãy chia nhỏ quy trình xử lí )
5. tone : giọng điệu và văn phong biểu đạt (quy định văn phong mong muốn )
6. extras : định dạng đầu ra (chỉ định dạng bạn muốn nhận về )

 **yêu cầu đầu ra**
 
b1 :  cách AI đoán từ , token hóa , embeddings , self-attention.

b2 : nhận diện ảo giác AI bằng cách kiểm chứng thông tin , trang web chính thống.

b3 : sử dụng cấu trúc CREATE : Context, Request, Explanation, Action, Tone, Extras.

b4 : lắp ráp thành cuốn cẩm nang hoàn chỉnh.

