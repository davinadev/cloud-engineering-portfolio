# Terminate EC2 Instance Lab

## Date

June 3, 2026

## Goal

Terminate the EC2 instance **xfusion-ec2** and verify that the instance reaches the **Terminated** state.

## AWS Services Used

* Amazon EC2

## What I Did

* Opened the EC2 Dashboard.
* Located the EC2 instance **xfusion-ec2** in the **us-east-1** region.
* Selected the instance.
* Opened the **Instance State** menu.
* Chose **Terminate Instance**.
* Confirmed the termination request.
* Monitored the instance state transition.
* Verified the instance reached the **Terminated** state.

## What I Learned

* Terminating an EC2 instance permanently deletes the virtual server.
* AWS changes the instance state from Running → Shutting Down → Terminated.
* A terminated instance cannot be restarted.
* It is important to verify resources are no longer needed before termination.
* Resource cleanup helps reduce unnecessary cloud costs.

## Problems I Ran Into

I was initially unsure whether simply selecting **Terminate Instance** was enough or if additional steps were required to complete the task.

### Issue Breakdown

* **Problem Encountered:** Understanding how to properly remove an EC2 instance.
* **Why It Happened:** I was unfamiliar with the EC2 termination process and lifecycle states.
* **How I Investigated It:** Reviewed the available instance state options and monitored the status changes.
* **How I Solved It:** Confirmed the termination action and waited until the instance status changed to **Terminated**.
* **What I Learned:** AWS resources often require time to complete state changes, and verification is an important final step.

## Key Configuration

### Instance Name

xfusion-ec2

### Region

us-east-1

### Action Performed

Terminate Instance

### Final State

Terminated

## Commands Used

No terminal commands were required for this lab.

### Screenshots

### EC2 Instance Before Termination

(Add Screenshot)

### Termination Confirmation

(Add Screenshot)

### Instance in Terminated State

(Add Screenshot)


## Key Takeaways

* EC2 instances can be permanently removed through termination.
* Terminated instances cannot be recovered or restarted.
* AWS uses lifecycle states to track resource changes.
* Resource cleanup is an important part of cloud management.
* Always verify the final state of a resource after making changes.

## Skills Practiced

* Amazon EC2
* Resource Management
* Cloud Infrastructure
* AWS Fundamentals
* Troubleshooting

## Reflection

Today I learned how to terminate an EC2 instance and verify that the resource was successfully removed. This lab helped me better understand the EC2 lifecycle and reinforced the importance of verifying state changes before considering a task complete. Understanding how to properly decommission resources is an important cloud engineering skill.
