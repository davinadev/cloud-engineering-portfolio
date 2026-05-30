# Enable Termination Protection Lab

## Date

May 30, 2026

## Goal

Enable termination protection on the EC2 instance **nautilus-ec2** to prevent the instance from being accidentally terminated.

## AWS Services Used

* Amazon EC2

## What I Did

* Opened the EC2 Dashboard.
* Located the **nautilus-ec2** instance in the **us-east-1** region.
* Selected the instance.
* Navigated to the instance settings.
* Modified the instance's termination protection setting.
* Enabled **Termination Protection**.
* Verified that termination protection was successfully enabled.

## What I Learned

* Termination Protection prevents an EC2 instance from being accidentally deleted.
* Stop Protection and Termination Protection are different features.
* Protection settings can be configured directly from the EC2 console.
* AWS provides safeguards to help protect critical infrastructure resources.
* It is important to verify protection settings on production resources.

## Problems I Ran Into

I initially confused Termination Protection with Stop Protection because both features are designed to protect EC2 instances.

### Issue Breakdown

* **Problem Encountered:** Understanding the difference between Stop Protection and Termination Protection.
* **Why It Happened:** Both settings are found within EC2 instance management and serve similar protective purposes.
* **How I Investigated It:** Reviewed the available instance protection settings and their descriptions.
* **How I Solved It:** Identified the correct setting and enabled Termination Protection on the instance.
* **What I Learned:** Stop Protection prevents an instance from being stopped, while Termination Protection prevents it from being deleted.

## Key Configuration

### Instance Name

nautilus-ec2

### Region

us-east-1

### Feature Enabled

Termination Protection

### Purpose

Prevent accidental termination of the EC2 instance.

## Commands Used

No terminal commands were required for this lab.

## Screenshots

### Termination Settings

termination-Settings.png

### Termination Protection Enabled

Termination-Protection-Enabled.png

## Key Takeaways

* Termination Protection prevents accidental deletion of EC2 instances.
* AWS provides multiple layers of resource protection.
* Stop Protection and Termination Protection serve different purposes.
* Protection settings are important for production and critical workloads.
* Always verify configuration changes after applying them.

## Skills Practiced

* Amazon EC2
* Instance Management
* Cloud Security
* AWS Resource Protection
* Troubleshooting

## Reflection

Today I learned how to enable Termination Protection on an EC2 instance. This lab helped me understand the difference between Stop Protection and Termination Protection and reinforced the importance of safeguarding cloud resources from accidental changes. Understanding these protection mechanisms is an important part of managing infrastructure in AWS.
