---
title : "Khởi tạo EC2"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

#### Khởi tạo EC2

1. Trong giao diện AWS Management, tìm và chọn **EC2**

![Launch EC2](/images/1/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **EC2**, chọn **Instances**

   - Chọn **Launch instances**

![Launch EC2](/images/1/0002.png?featherlight=false&width=90pc)

3. Trong giao diện **Lauch instances**

   - Nhập **Name and tags** là **```FCJ Snapshot```**

![Launch EC2](/images/1/0003.png?featherlight=false&width=90pc)

4. Đối với **Key pair**, bạn có thể chọn **Proceed without a key pair (Not recommended)**

   - Đối với **Networking**, bạn có thể giữ nguyên cấu hình.

![Launch EC2](/images/1/0004.png?featherlight=false&width=90pc)

5. Đối với **storage** giữ nguyên và sau đó chọn **Launch instance**

![Launch EC2](/images/1/0005.png?featherlight=false&width=90pc)

6. Sau khi khởi tạo, bạn chọn **View all instances**

![Launch EC2](/images/1/0006.png?featherlight=false&width=90pc)

7. Đợi khoảng 2 phút, **Status check** là **2/2 checks passed**

![Launch EC2](/images/1/0007.png?featherlight=false&width=90pc)

8. Chọn **instance** đã tạo và chọn **Storage**, sau đó chọn **Volume**

![Launch EC2](/images/1/0008.png?featherlight=false&width=90pc)

9. Thực hiện đặt tag cho volume là **FCJ-Volume**

![Launch EC2](/images/1/0009.png?featherlight=false&width=90pc)

