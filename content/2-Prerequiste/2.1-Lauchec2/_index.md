---
title: "Launch EC2 Instance"
date: 2024-01-01
weight: 1
chapter: false
pre: "<b> 2.1 </b>"
---

#### Launch EC2 Instance

1. In the AWS Management Console, navigate to and select **EC2**.

   ![Launch EC2](/images/1/0001.png?featherlight=false&width=90pc)

2. Within the **EC2** console, click on **Instances**.
   
   - Then, click on **Launch instances**.

   ![Launch EC2](/images/1/0002.png?featherlight=false&width=90pc)

3. On the **Launch Instances** page:
   
   - Specify **Name and tags** as **`FCJ Snapshot`**.

   ![Launch EC2](/images/1/0003.png?featherlight=false&width=90pc)

4. Under **Key Pair**, you may select **Proceed without a key pair (Not recommended)**.
   
   - For **Networking**, retain the default configuration.

   ![Launch EC2](/images/1/0004.png?featherlight=false&width=90pc)

5. For **Storage**, maintain the default settings and then click on **Launch instance**.

   ![Launch EC2](/images/1/0005.png?featherlight=false&width=90pc)

6. Once the EC2 instance is launched, click on **View all instances**.

   ![Launch EC2](/images/1/0006.png?featherlight=false&width=90pc)

7. Allow approximately 2 minutes for the instance to initialize. Wait until the **Status check** shows **2/2 checks passed**.

   ![Launch EC2](/images/1/0007.png?featherlight=false&width=90pc)

8. Select the newly created instance, navigate to **Storage**, and then click on **Volume**.

   ![Launch EC2](/images/1/0008.png?featherlight=false&width=90pc)

9. Assign the volume tag as **FCJ-Volume**.

   ![Launch EC2](/images/1/0009.png?featherlight=false&width=90pc)
