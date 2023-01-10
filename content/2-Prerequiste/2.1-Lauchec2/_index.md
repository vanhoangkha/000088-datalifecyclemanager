---
title : "Launch EC2 instance"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

#### Launch EC2 instance

1. In the AWS Management console, find and select **EC2**

![Launch EC2](/images/1/0001.png?featherlight=false&width=90pc)

2. In the **EC2** console, select **Instances**

   - Select **Launch instances**

![Launch EC2](/images/1/0002.png?featherlight=false&width=90pc)

3. In the **Lauch instances** console

   - Enter **Name and tags** as **```FCJ Snapshot```**

![Launch EC2](/images/1/0003.png?featherlight=false&width=90pc)

4. For **Key pair**, you can choose **Proceed without a key pair (Not recommended)**

   - For **Networking** you can keep the same configuration.

![Launch EC2](/images/1/0004.png?featherlight=false&width=90pc)

5. For **storage** keep the same and then select **Launch instance**

![Launch EC2](/images/1/0005.png?featherlight=false&width=90pc)

1. After launch EC2, select **View all instances**

![Launch EC2](/images/1/0006.png?featherlight=false&width=90pc)

7. Wait about 2 minutes, **Status check** is **2/2 checks passed**

![Launch EC2](/images/1/0007.png?featherlight=false&width=90pc)

8. Select the **instance** created and select **Storage**, then select **Volume**

![Launch EC2](/images/1/0008.png?featherlight=false&width=90pc)

9. Set the volume tag as **FCJ-Volume**

![Launch EC2](/images/1/0009.png?featherlight=false&width=90pc)