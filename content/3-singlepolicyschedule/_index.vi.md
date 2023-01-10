---
title : "Sử dụng một policy schedule"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Sử dụng một policy schedule

1. Truy cập vào giao diện **EC2**

   - Chọn **Lifecycle Manager**
   - Chọn **Next step**

![Use single policy schedule](/images/2/0001.png?featherlight=false&width=90pc)

2. Trong bước **setting** thực hiện chọn **Target resources**

   - **Target resource type** chọn **Volume**
   - Chọn theo tags là **FCJ-Volume**

![Use single policy schedule](/images/2/0002.png?featherlight=false&width=90pc)

3. Sử dụng IAM role mặc định.

![Use single policy schedule](/images/2/0003.png?featherlight=false&width=90pc)

4. Sau đó, chọn **Next**

![Use single policy schedule](/images/2/0004.png?featherlight=false&width=90pc)

5. Đối với cấu hình **Schedule**.

   - Ở mục này, chúng ta sẽ cấu hình 1 schedule và 1 policy
   - Phần **Schedule name**, đặt tên tùy ý.
   - Phần **Frequency**, chọn **Daily**
   - **Every**, chọn **1 hour**
   - **Starting at** lúc **14:00**, bạn có thể tùy biến.
   - Đối với ***Retention type**, chọn **30 days**

![Use single policy schedule](/images/2/0005.png?featherlight=false&width=90pc)

6. Chọn **Review policy**

![Use single policy schedule](/images/2/0006.png?featherlight=false&width=90pc)

7. Chọn **Create policy**

![Use single policy schedule](/images/2/0007.png?featherlight=false&width=90pc)

8. Tạo **lifecycle policy** thành công.

![Use single policy schedule](/images/2/0008.png?featherlight=false&width=90pc)



