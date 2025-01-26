# Build-a-Web-App-using-AWS-Cloud9

Set Up a Web App in the Cloud


7 series project, to achieve this: 


![image](https://github.com/user-attachments/assets/ecbaea21-1f35-4739-9cdb-380b91a41667)



# A CI/CD (Continuous Integration and Continuous Deployment/Delivery) pipeline 
is a key tool to automate the steps from development (i.e. created by developers) to deployment (i.e. published to users), which help software get built and released even faster.

In the first project of this series, you'll learn the basics of building a web app using AWS and another tool called VSCode. This will lay the foundation for your DevOps work for the rest of this series!

# Basic outline of steps : 
1) 💻 Launch an EC2 instance.
   
![image](https://github.com/user-attachments/assets/ec918036-f94f-495d-b53b-f8138917b25e)



2) 🔌 Use VSCode to set up a remote SSH connection to your EC2 instance.
   



3) ☕️ Install Maven and Java and generate a basic web app.




# Get started

# Step 1 : Set up an IAM user
Before we dive in, log in to your AWS account with your IAM user, Login with your IAM admin user

tip :  make sure you log in to your IAM Admin User instead of the root user - it's truly best practise for account security


#  What is an IAM user? Why are we setting one up? 
In AWS, a user is a person or a computer that can do things on the AWS cloud.
When you create an AWS account for the first time, the login you get is called the root user of the AWS account. AWS actually recommends to not use your root user for everyday tasks to protect it from security breaches.
You should create IAM users instead. If a root user is a master key to your AWS account, think of IAM users as key copies. IAM users have separate usernames and passwords to your root user, and you can set them to have limited access to your account's resources.

# Step 2 : Launch an EC2 Instance
we want our web app to be entirely created and run on the cloud, we'll use a virtual server (EC2 instance) to house our development work.
1) Launch a new EC2 instance.



2) Set up a key pair for secure access.



3) Set up network settings for your instance.

 #  what your're building in this step :
 
   ![image](https://github.com/user-attachments/assets/4dfc9c12-3252-454d-a4f3-3a87e8741cca)

# What is EC2? A legendary AWS service!
Amazon EC2 is a service that lets you rent and use virtual computers in the cloud. They're like your personal computers, but they exist on the internet instead of being physically in front of you. You can create, customize, and use these computers for all different reasons, from running applications to hosting websites.

Psssst... EC2 = Elastic Compute Cloud.

Here's what the three words mean: Elastic = flexible. This service can easily adapt and change in size and power to fit your needs. Compute = computing power. EC2 provides virtual computers that can do various tasks, just like your personal computer. Cloud = available over the internet.

# Step 3 : 
