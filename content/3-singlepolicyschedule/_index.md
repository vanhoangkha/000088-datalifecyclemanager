---
title: "Using a Single Policy Schedule"
date: "`r Sys.Date()`"
weight: 3
chapter: false
pre: "<b> 3. </b>"
---

### Use a Policy Schedule

1. **Access the EC2 Console**
   - Navigate to the **Lifecycle Manager**.
   - Click on **Next step**.

   ![Use Single Policy Schedule](/images/2/0001.png?featherlight=false&width=90pc)

2. **In the Settings Step, Target Resources**
   - For **Target resource type**, choose **Volume**.
   - Filter by tags, specifically **FCJ-Volume**.

   ![Use Single Policy Schedule](/images/2/0002.png?featherlight=false&width=90pc)

3. **Utilize the Default IAM Role**

   ![Use Single Policy Schedule](/images/2/0003.png?featherlight=false&width=90pc)

4. **Proceed by Selecting Next**

   ![Use Single Policy Schedule](/images/2/0004.png?featherlight=false&width=90pc)

5. **Configure the Schedule**
   - This step involves setting up one schedule and one policy.
   - In the **Schedule name** field, enter a name of your choice.
   - For **Frequency**, select **Daily**.
   - Under **Every**, choose **1 hour**.
   - Set **Starting at** to **14:00** or adjust as needed.
   - For **Retention type**, select **30 days**.

   ![Use Single Policy Schedule](/images/2/0005.png?featherlight=false&width=90pc)

6. **Review the Policy**

   ![Use Single Policy Schedule](/images/2/0006.png?featherlight=false&width=90pc)

7. **Create the Policy**

   ![Use Single Policy Schedule](/images/2/0007.png?featherlight=false&width=90pc)

8. **Lifecycle Policy Created Successfully**

   ![Use Single Policy Schedule](/images/2/0008.png?featherlight=false&width=90pc)
