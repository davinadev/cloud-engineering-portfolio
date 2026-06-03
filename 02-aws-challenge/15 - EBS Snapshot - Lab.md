# Create EBS Snapshot Lab

## Date

June 3, 2026

## Goal

Create a snapshot of the EBS volume **datacenter-vol**, name it **datacenter-vol-ss**, add the required description, and verify the snapshot reaches the **Completed** state.

## AWS Services Used

* Amazon EC2
* Amazon EBS (Elastic Block Store)
* EBS Snapshots

## What I Did

* Opened the EC2 Dashboard.
* Navigated to the **Volumes** section under Elastic Block Store (EBS).
* Located the volume **datacenter-vol**.
* Selected **Create Snapshot**.
* Entered the snapshot name **datacenter-vol-ss**.
* Added the description **datacenter Snapshot**.
* Created the snapshot.
* Monitored the snapshot creation process.
* Verified the snapshot status changed to **Completed**.

## What I Learned

* EBS snapshots create backups of EBS volumes.
* Snapshots are stored in Amazon S3 behind the scenes.
* Snapshots can be used to restore data or create new EBS volumes.
* AWS requires time to process snapshots before they become available.
* Snapshots are an important part of backup and disaster recovery strategies.

## Problems I Ran Into

I initially thought the snapshot was ready immediately after creation, but the task required the snapshot status to be **Completed** before submission.

### Issue Breakdown

* **Problem Encountered:** Snapshot was still processing after creation.
* **Why It Happened:** AWS needs time to create and store snapshot data.
* **How I Investigated It:** Monitored the snapshot status in the Snapshots section.
* **How I Solved It:** Waited until the snapshot status changed to **Completed**.
* **What I Learned:** AWS resources often require time to finish processing, and status verification is an important final step.

## Key Configuration

### Source Volume

datacenter-vol

### Snapshot Name

datacenter-vol-ss

### Description

datacenter Snapshot

### Final Status

Completed

## Commands Used

No terminal commands were required for this lab.

## Screenshots

### Source Volume

(Add Screenshot)

### Snapshot Configuration

(Add Screenshot)

### Snapshot Completed

(Add Screenshot)

## Key Takeaways

* EBS snapshots provide point-in-time backups of volumes.
* Snapshots help support backup and disaster recovery plans.
* AWS stores EBS snapshots separately from the original volume.
* Snapshot creation is not instant and requires processing time.
* Always verify the final resource state before completing a task.

## Skills Practiced

* Amazon EBS
* EBS Snapshots
* Backup and Recovery
* AWS Storage Services
* Cloud Infrastructure

## Reflection

Today I learned how to create an EBS snapshot from an existing volume. This lab introduced me to AWS backup capabilities and showed how snapshots can be used to protect important data. I also learned the importance of verifying that a snapshot has fully completed before considering the task finished.
