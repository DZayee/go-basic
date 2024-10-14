# Concurrency Pattern

## worker pool
- worker pool là 1 khái niệm khá phổ biến trong khi lập trình, còn trong `golang` mục đích để hạn chế số lượng goroutines được tạo ra để phục vụ một mục đích nhất định.
- pattern này cực kì hữu ích trong quá trình sử dụng, nhắm giới hạn số lượng process cần thực hiện, và quản lý tài nguyên.
  - để handle request từ client
  - để process các job backgrount
