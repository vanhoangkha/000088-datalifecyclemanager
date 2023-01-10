---
title : "Sử dụng nhiều policy schedule"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 4. </b> "
---

#### Sử dụng nhiều policy schedule

1. Tương tự, nhưng chúng ta sẽ tạo nhiều policy schedule với 1 policy lifecycle.

   - Trong giao diện **Data Lifecycle Manager**
   - Chọn **Create lifecycle policy**

![Use mutilple policy schedule](/images/3/0001.png?featherlight=false&width=90pc)

2. Chọn **EBS snapshot policy**

   - Chọn **Next**

![Use mutilple policy schedule](/images/3/0002.png?featherlight=false&width=90pc)

3. Đối với **Target resource**, chọn **Volume**

   - Chọn theo tag: **FCJ-Volume**
   - Đặt mô tả là **FCJ-DLM-Week policy**

![Use mutilple policy schedule](/images/3/0003.png?featherlight=false&width=90pc)

4. Sử dụng **IAM Role** mặc định.

   - Chọn **Next**.

![Use mutilple policy schedule](/images/3/0004.png?featherlight=false&width=90pc)

5. Đến bước cấu hình **Schedule**

   - Đối với **Schedule name**, nhập tùy ý.
   - Chọn **Frequency** là **Weekly**
   - Chọn các ngày theo ý bạn.
   - Chọn thời gian **starting at** là **09:00**
   - Đối với **Retention type**, chọn **Age** và chọn **180 days**

![Use mutilple policy schedule](/images/3/0005.png?featherlight=false&width=90pc)

6. Chọn **Add another schedule**

![Use mutilple policy schedule](/images/3/0006.png?featherlight=false&width=90pc)

7. Thực hiện cấu hình **Schedule** thứ 2

   - Đối với **Schedule name**, nhập tùy ý.
   - Chọn **Frequency** là **Monthly**
   - Chọn **Day** và **Last**
   - Chọn thời gian **starting at** là **09:00**
   - Đối với **Retention type**, chọn **Age** và chọn **1 days**

![Use mutilple policy schedule](/images/3/0007.png?featherlight=false&width=90pc)

8. Chọn **Advanced settings**

![Use mutilple policy schedule](/images/3/0008.png?featherlight=false&width=90pc)

9. Đối với **Snapshot archiving**

   - Chọn **Archive snapshots created by this schedule**
   - Archive snapshots for **90 days**
   - Chọn **Review policy**

![Use mutilple policy schedule](/images/3/0009.png?featherlight=false&width=90pc)

10. Kiểm tra lại và chọn **Create policy**

![Use mutilple policy schedule](/images/3/00010.png?featherlight=false&width=90pc)

11. Hoàn thành tạo **lifecycle policy**

![Use mutilple policy schedule](/images/3/00011.png?featherlight=false&width=90pc)



