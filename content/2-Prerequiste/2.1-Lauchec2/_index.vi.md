---
title: "Khởi Tạo EC2"
date: 2024-01-01
weight: 1
chapter: false
pre: "<b> 2.1 </b>"
---

#### Khởi Tạo EC2

1. Trong giao diện **AWS Management**, tìm và chọn **EC2**.

    ![Khởi động EC2](/images/1/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **EC2**, chọn **Instances**.
   
   - Chọn **Launch instances**.

    ![Khởi động EC2](/images/1/0002.png?featherlight=false&width=90pc)

3. Trong giao diện **Launch instances**.

   - Nhập **Name and tags** với giá trị **`FCJ Snapshot`**.

    ![Khởi động EC2](/images/1/0003.png?featherlight=false&width=90pc)

4. Đối với **Key pair**, bạn có thể chọn **Proceed without a key pair (Not recommended)**.
   
   - Đối với **Networking**, có thể giữ nguyên cấu hình mặc định.

    ![Khởi động EC2](/images/1/0004.png?featherlight=false&width=90pc)

5. Đối với **Storage**, giữ nguyên và sau đó chọn **Launch instance**.

    ![Khởi động EC2](/images/1/0005.png?featherlight=false&width=90pc)

6. Sau khi khởi tạo, chọn **View all instances**.

    ![Khởi động EC2](/images/1/0006.png?featherlight=false&width=90pc)

7. Đợi khoảng 2 phút cho đến khi **Status check** hiển thị **2/2 checks passed**.

    ![Khởi động EC2](/images/1/0007.png?featherlight=false&width=90pc)

8. Chọn **instance** đã tạo và chọn **Storage**, sau đó chọn **Volume**.

    ![Khởi động EC2](/images/1/0008.png?featherlight=false&width=90pc)

9. Thực hiện đặt tag cho volume với tên là **FCJ-Volume**.

    ![Khởi động EC2](/images/1/0009.png?featherlight=false&width=90pc)
