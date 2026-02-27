# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: N.Shalini
* **Register Number**:212224040305 
* **Date of Submission**: 

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

Explored Amazon EBS volume types in the EC2 dashboard and noted their differences in performance and use cases.

Created a new EBS volume in the same Availability Zone as my EC2 instance with an appropriate size and type.

Attached the newly created EBS volume to the running EC2 instance as an additional block device.

Connected to the EC2 instance via SSH and formatted the attached volume with the ext4 file system.

Mounted the formatted volume to a directory (e.g., /data) and stored sample files to verify data persistence.

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="1920" height="1200" alt="Screenshot (122)" src="https://github.com/user-attachments/assets/97740906-4b6e-4d00-a652-a256568fc27e" />


### Screenshot 2: EBS Volume Attached to EC2

<img width="1920" height="1200" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/e45fb2b1-8da6-468f-a3cb-369233d686ac" />


### Screenshot 3: Mounted Volume with Data


<img width="1920" height="1200" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/e7e2b838-af0d-42ad-8941-4f90b81417bc" />



## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
