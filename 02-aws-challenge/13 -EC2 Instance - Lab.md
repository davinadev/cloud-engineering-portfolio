# Create AMI from EC2 Instance Lab

## Date

June 2, 2026

## Goal

Create an Amazon Machine Image (AMI) named **xfusion-ec2-ami** from the existing EC2 instance **xfusion-ec2** and verify that the AMI reaches the **Available** state.

## AWS Services Used

* Amazon EC2
* Amazon Machine Image (AMI)

## What I Did

* Opened the EC2 Dashboard.
* Located the EC2 instance **xfusion-ec2**.
* Selected the instance.
* Opened the **Actions** menu.
* Selected **Image and templates → Create image**.
* Entered the AMI name **xfusion-ec2-ami**.
* Submitted the image creation request.
* Navigated to the **AMIs** section.
* Monitored the image creation process.
* Verified the AMI status changed to **Available**.

## What I Learned

* An AMI (Amazon Machine Image) is a template used to launch EC2 instances.
* AMIs can contain operating systems, applications, and configurations.
* Creating an AMI captures the current state of an EC2 instance.
* AMIs can be used to quickly deploy identical instances.
* AWS requires time to create and process an AMI before it becomes available.

## Problems I Ran Into

I initially had trouble figuring out where AMIs were created and how to create one from an existing EC2 instance.

### Issue Breakdown

* **Problem Encountered:** Could not find the option to create an AMI.
* **Why It Happened:** I was unfamiliar with the EC2 image creation workflow.
* **How I Investigated It:** Explored the EC2 instance actions menu and reviewed the available options.
* **How I Solved It:** Located the **Create Image** option under the instance actions menu and followed the image creation process.
* **What I Learned:** AMIs are created directly from EC2 instances and require time to transition to the **Available** state.

## Key Configuration

### Source Instance

xfusion-ec2

### AMI Name

xfusion-ec2-ami

### Final Status

Available

## Commands Used

No terminal commands were required for this lab.

## Screenshots

## Screenshots

Screenshots were not captured during this lab.

This lab focused on creating an Amazon Machine Image (AMI) from an existing EC2 instance and understanding how AWS creates reusable server templates.

Future labs will include screenshots of key configuration steps and successful task completion.


## Key Takeaways

* AMIs are reusable templates for launching EC2 instances.
* Creating an AMI captures the current configuration of an EC2 instance.
* AMIs simplify backup, recovery, and deployment processes.
* AWS requires time to create and register AMIs.
* Verifying the AMI reaches the **Available** state is an important final step.

## Skills Practiced

* Amazon EC2
* Amazon Machine Images (AMI)
* Cloud Infrastructure
* AWS Resource Management
* Troubleshooting

## Reflection

Today I learned how to create an AMI from an existing EC2 instance. The most challenging part was figuring out where the AMI creation option was located in the AWS console. After finding the correct workflow and waiting for the image to become available, I gained a better understanding of how AWS uses AMIs to create reusable server templates and simplify infrastructure deployment.
