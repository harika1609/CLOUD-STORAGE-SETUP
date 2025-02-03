# CLOUD-STORAGE-SETUP

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : MOGALAPALLI HARIKA

*INTERN ID* : CT08NSB

*DOMAIN NAME* : CLOUD COMPUTING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

##DESCRIPTION##
Task 1: Cloud Storage Setup on AWS S3
In this task, I was assigned to create and configure cloud storage using Amazon Web Services (AWS) S3, one of the most popular and reliable object storage services. The goal was to establish an S3 bucket, upload example files to it, and configure access permissions to demonstrate secure and organized data storage in the cloud.

Overview of AWS S3
AWS S3 is a highly scalable and secure cloud storage service that allows users to store and retrieve any amount of data from anywhere. It offers durability, scalability, and high availability, making it ideal for use cases such as data storage, content distribution, backup, and disaster recovery. S3 ensures high durability of data over a given year.

Step 1: Creating an S3 Bucket
The first step in setting up cloud storage was creating an S3 bucket. A bucket is a container used to store files (also called objects) in S3. I navigated to the S3 console, clicked on "Create Bucket," and chose a globally unique name for it. Selecting the appropriate AWS region was an important step, as it determines where the data will be physically stored, affecting latency and performance. For this task, I opted for a region close to the user base to ensure faster access times.

One of the key decisions during bucket creation was configuring the Block Public Access settings. By default, AWS restricts public access to buckets to protect data. However, since the task required uploading files to be publicly accessible, I had to disable the block public access option to allow public read access to the bucket. This setting was crucial for ensuring the files would be accessible via a URL.

Step 2: Uploading Files to the S3 Bucket
Once the bucket was created, the next step was to upload example files. These files could include images, documents, or any other data that needed to be stored in the cloud. I used the AWS S3 console to upload multiple files to the bucket. AWS S3 allows easy file management through the console interface, where users can drag and drop files for upload or use the AWS CLI for bulk uploads. After uploading the files, they were securely stored and available for access.

Step 3: Configuring Bucket Permissions
The next task was configuring the bucket permissions to control access to the files stored in the S3 bucket. Initially, I enabled public read access to allow anyone with the URL to view the files. This was done by configuring the bucket policy to provide unrestricted read access to all users. Additionally, I explored other access control mechanisms such as IAM roles and S3 Access Control Lists (ACLs) to manage more specific permissions. These mechanisms allow for more granular control over who can perform actions such as read, write, and delete on the files.

Step 4: Testing Access and Verifying Configuration
After configuring the permissions, I tested the setup by trying to access the uploaded files through their publicly accessible URLs. This step was essential to verify that the files were accessible as intended. Using AWS CLI, I also validated the configuration and verified that the permissions and file uploads were correctly applied.

Conclusion
This task provided valuable hands-on experience with AWS S3, allowing me to understand how to create, configure, and manage cloud storage. By setting up an S3 bucket, uploading files, and configuring access permissions, I was able to practice secure storage, access control, and data management in a cloud environment. This experience enhanced my understanding of cloud storage solutions and their application in real-world scenarios, where security, scalability, and availability are key factors.
