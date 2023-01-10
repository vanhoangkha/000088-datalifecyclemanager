---
title : "Use multiple policy schedules"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 4. </b> "
---

#### Use multiple policy schedules

1. Same, but we will create multiple policy schedules with 1 policy lifecycle.

   - In the **Data Lifecycle Manager** console
   - Select **Create lifecycle policy**

![Use mutilple policy schedule](/images/3/0001.png?featherlight=false&width=90pc)

2. Select **EBS snapshot policy**

   - Select **Next**

![Use mutilple policy schedule](/images/3/0002.png?featherlight=false&width=90pc)

3. For **Target resource**, select **Volume**

   - Select by tag: **FCJ-Volume**
   - Set description as **FCJ-DLM-Week policy**

![Use mutilple policy schedule](/images/3/0003.png?featherlight=false&width=90pc)

4. Use default **IAM Role**.

   - Select **Next**.

![Use mutilple policy schedule](/images/3/0004.png?featherlight=false&width=90pc)

5. Go to **Schedule** configuration step

   - For **Schedule name**, enter optionally.
   - Select **Frequency** as **Weekly**
   - Choose the dates of your choice.
   - Choose **starting at** time as **09:00**
   - For **Retention type**, select **Age** and select **180 days**

![Use mutilple policy schedule](/images/3/0005.png?featherlight=false&width=90pc)

6. Select **Add another schedule**

![Use mutilple policy schedule](/images/3/0006.png?featherlight=false&width=90pc)

7. Perform the 2nd **Schedule** Configuration

   - For **Schedule name**, enter optionally.
   - Select **Frequency** as **Monthly**
   - Select **Day** and **Last**
   - Choose **starting at** time as **09:00**
   - For **Retention type**, select **Age** and select **1 days**

![Use mutilple policy schedule](/images/3/0007.png?featherlight=false&width=90pc)

8. Select **Advanced settings**

![Use mutilple policy schedule](/images/3/0008.png?featherlight=false&width=90pc)

9. For **Snapshot archiving**

   - Select **Archive snapshots created by this schedule**
   - Archive snapshots for **90 days**
   - Select **Review policy**

![Use mutilple policy schedule](/images/3/0009.png?featherlight=false&width=90pc)

10. Check again and select **Create policy**

![Use mutilple policy schedule](/images/3/00010.png?featherlight=false&width=90pc)

11. Finish creating **lifecycle policy**

![Use mutilple policy schedule](/images/3/00011.png?featherlight=false&width=90pc)