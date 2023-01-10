---
title : "Using a single policy schedule"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Use a policy schedule

1. Access to **EC2** console

   - Select **Lifecycle Manager**
   - Select **Next step**

![Use single policy schedule](/images/2/0001.png?featherlight=false&width=90pc)

2. In the **setting** step, select **Target resources**

   - **Target resource type** select **Volume**
   - Select by tags as **FCJ-Volume**

![Use single policy schedule](/images/2/0002.png?featherlight=false&width=90pc)

3. Use the default IAM role.

![Use single policy schedule](/images/2/0003.png?featherlight=false&width=90pc)

4. Then select **Next**

![Use single policy schedule](/images/2/0004.png?featherlight=false&width=90pc)

5. For **Schedule** configuration.

   - In this section, we will configure 1 schedule and 1 policy.
   - Section **Schedule name**, name it arbitrarily.
   - In the **Frequency** section, select **Daily**.
   - **Every**, choose **1 hour**.
   - **Starting at** at **14:00**, you can customize.
   - For ***Retention type**, choose **30 days**.

![Use single policy schedule](/images/2/0005.png?featherlight=false&width=90pc)

6. Select **Review policy**

![Use single policy schedule](/images/2/0006.png?featherlight=false&width=90pc)

7. Select **Create policy**

![Use single policy schedule](/images/2/0007.png?featherlight=false&width=90pc)

8. Create **lifecycle policy** successfully.

![Use single policy schedule](/images/2/0008.png?featherlight=false&width=90pc)