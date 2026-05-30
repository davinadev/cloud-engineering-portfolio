# Enable Stop Protection Lab

## Date

May 30, 2026

## Goal

Enable stop protection on the EC2 instance **nautilus-ec2** to prevent the instance from being accidentally stopped.

## AWS Services Used

* Amazon EC2

## What I Did

* Opened the EC2 Dashboard.
* Located the **nautilus-ec2** instance in the **us-east-1** region.
* Selected the instance.
* Navigated to the instance settings.
* Enabled **Stop Protection**.
* Waited for AWS to apply the configuration.
* Verified that Stop Protection was successfully enabled.

## What I Learned

* Stop Protection helps prevent accidental instance shutdowns.
* EC2 instance settings can be modified through the AWS Management Console.
* Some configuration changes take a short amount of time to apply.
* AWS may not immediately show the updated protection status after enabling it.
* Protection settings are useful for critical production resources.

## Problems I Ran Into

I initially thought the configuration had not worked because the Stop Protection status did not update immediately after enabling it.

### Issue Breakdown

* **Problem Encountered:** Stop Protection did not appear enabled right away.
* **Why It Happened:** AWS needed time to apply and update the instance configuration.
* **How I Investigated It:** Refreshed the instance details and checked the protection settings again.
* **How I Solved It:** Waited for AWS to complete the configuration update and then verified the setting was enabled.
* **What I Learned:** Not all AWS configuration changes are applied instantly, and it is important to verify the final state before troubleshooting further.

## Key Configuration

### Instance Name

nautilus-ec2

### Region

us-east-1

### Feature Enabled

Stop Protection

### Purpose

Prevent accidental stopping of the EC2 instance.

## Commands Used

No terminal commands were required for this lab.

## Screenshots

### Instance Settings

(Add Screenshot)

### Stop Protection Enabled

(Add Screenshot)

## Key Takeaways

* Stop Protection helps safeguard important EC2 instances.
* AWS may require a short period of time to apply configuration changes.
* Verifying the final resource state is an important troubleshooting step.
* Protection features help reduce the risk of accidental service disruptions.
* Patience and verification are important when managing cloud resources.

## Skills Practiced

* Amazon EC2
* Instance Management
* Cloud Security
* AWS Fundamentals
* Troubleshooting

## Reflection

Today I learned how to enable Stop Protection on an EC2 instance. The biggest challenge was realizing that AWS needed time to apply the change before it appeared in the console. This lab reinforced the importance of verifying resource states and understanding that cloud configurations may not always update immediately.
