# AWS-DynamoDB-PHP-Backend
Automation Project to Create DynamoDb table using Php Backend Script 


Before proceeding, ensure you have:

-> An AWS account with necessary permissions (EC2, IAM, and DynamoDB).
  -An EC2 instance running Amazon Linux.
  -Connect to Your EC2 Instance
  -Once connected, execute the commands in the EC2 server:

sudo -i

yum install git httpd php -y

service httpd start

cd /var/www/html

echo "Hello everyone" > index.html

git clone the repo

curl -sS https://getcomposer.org/installer | php 

php composer.phar require aws/aws-sdk-php



-> Attach an IAM Role to Your EC2 Instance
  AmazonDynamoDBFullAccess

-> Execute the PHP Script
  Run your PHP script to automate DynamoDB table creation and EC2 provisioning

   Open http://(your-ec2-public-ip)/dyanamodb/ in a browser to see the web page.
   (ex.  http://98.81.128.125/dynamodb/createtables.php
         http://98.81.128.125/dynamodb/uploaddata.php)

-> Verify the Setup
  Check AWS DynamoDB to confirm table creation.

  See below Screenshots for refrence and Let me know if you need any modifications! 🚀

  ![image](https://github.com/user-attachments/assets/af9dac88-f949-4749-a695-3eab525c623a)


  ![image](https://github.com/user-attachments/assets/79f067ab-c3d4-4fdd-8a6f-4b0e545db3ef)

  ![image](https://github.com/user-attachments/assets/d95486f9-2819-4d30-ae82-ee3e8ba261e6)

![image](https://github.com/user-attachments/assets/bf1d314c-39fd-44da-8422-b0344446ace4)

![image](https://github.com/user-attachments/assets/671dcb7b-13ec-49be-933b-99899f89fbda)

![image](https://github.com/user-attachments/assets/9d4f559d-7ab0-4e4f-8422-82f1818e7ce0)

![image](https://github.com/user-attachments/assets/ccb85565-4456-41b6-a4e8-0631d4d4471e)






  

  
