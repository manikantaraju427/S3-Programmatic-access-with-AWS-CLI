# S3-Programmatic-access-with-AWS-CLI

# S3
Amazon Simple Storage Service (Amazon S3):- is an object storage service that

provides a secure and scalable way to store and access data on the cloud.

It is designed for storing any kind of data, such as text files, images, videos, backups, and more.


# TASK 1

Launch an EC2 instance using the AWS Management Console and connect to it using Secure Shell (SSH).

Log in to the AWS Management Console.

Navigate to the EC2 service and launch an EC2 instance using the console.

Connect to the EC2 instance using SSH.

![Screenshot (375)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/4f5101ee-6dac-4486-ab4d-f81e1e373157)

Create an S3 bucket and upload a file to it using the AWS Management Console.

Log in to your AWS Management Console and go to the S3 service.

Click on the “Create bucket” button.

Enter a unique name for your bucket, select the region you want to create it in, and then click “Create.”

![Screenshot (376)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/3d37401d-1eec-46ad-a45e-4d052e846214)

Click on ‘Create Bucket’

Once your bucket is created, click on its name to open it.

Click on the “Upload” button to upload a file.

![Screenshot (377)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/c5410f84-fd43-48aa-a283-c0dcb8e6a79d)

In the “Upload” window, click on the “Add files” button to select the file you want to upload.

Once you’ve selected your file, click “Next.”

![Screenshot (378)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/5b72294f-8efc-4551-ab79-5ed26b028ed9)

next you can set permissions for your file, configure storage class and set metadata.

review the details before clicking on the “Upload” button to upload your file.

Once the upload is complete, you can see the file in your S3 bucket.

![Screenshot (379)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/138e7511-624b-4bce-98f0-9eb958ee71d9)

Access the file from the EC2 instance using the AWS Command Line Interface (AWS CLI).

Install the AWS CLI.

![Screenshot (381)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/fa22b5ea-f918-4b46-a405-927be8b547d1)

Check aws-cli installed or not using checking aws version

Once you have installed the AWS CLI, open a terminal and run the command aws configure to configure your account credentials.

Enter your AWS Access Key ID and Secret Access Key

and

List s3 buckets using below command:

![Screenshot (380)](https://github.com/manikantaraju427/S3-Programmatic-access-with-AWS-CLI/assets/125948783/93a83807-7024-4a10-b63e-7b60ad4da31f)

you can use the aws s3 cp command to copy the file from your S3 bucket to
your EC2 instance and view content of file using cat command.












