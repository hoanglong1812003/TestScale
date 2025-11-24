+++
title = "Điểm từng bộ tiêu chuẩn"
weight = 3
chapter = false
pre = "<b>3. </b>"
+++


#### Kiểm tra đánh giá theo từng bộ tiêu chuẩn

Sau một khoản thời gian, Security Hub sẽ đưa ra các đánh giá dựa trên số điểm cũng như chỉ ra các rủi ro về bảo mật đang tồn tại trên tài khoản của bạn. Để liệt kê các rủi ro được tìm thấy, các bạn có thể truy cập vào từng bộ tiêu chuẩn để xem các điểm đánh giá:

1. Đăng nhập vào **Amazon Management Console**. Trên thanh tìm kiếm, nhập và tìm kiếm dịch vụ **Security Hub CSPM**.

![Security Hub](/images/image-ws00018/9.png)

2. Ở thanh điều hướng bên trái, chọn **Security standards** để xem thông tin tổng quan về điểm đánh giá theo từng bộ tiêu chuẩn đánh giá bảo mật.


3. Để xem chi tiết các tiêu chí đánh giá của từng bộ tiêu chuẩn, chọn **View results** (theo từng bộ tiêu chuẩn.)

    - VD: Bộ tiêu chuẩn **Foundational Security Best Practices v1.0.0**

![Security Hub](/images/image-ws00018/14.png)

![Security Hub](/images/image-ws00018/15.png)



4. Với trường hợp bạn có một số tiêu chí không muốn áp dụng, để loại bỏ khỏi đánh giá, bạn có thể chọn vào tiêu chí đó trong danh sách của bộ tiêu chuẩn.
    - **Ví dụ**: Bạn muốn loại bỏ *EC2 instances managed by Systems Manager should have an association compliance status of COMPLIANT* ở bộ tiêu chuẩn **PCI DSS v3.2.1**

![Security Hub](/images/image-ws00018/16.png)

![Security Hub](/images/image-ws00018/17.png)

- Ở trang thông tin chi tiết về tiêu chí, ấn **Enabled**, sau đó chọn **Disable**.

![Security Hub](/images/image-ws00018/18.png)


- Nhập lý do loại bỏ, chọn **Disable**.

![Security Hub](/images/image-ws00018/19.png)

