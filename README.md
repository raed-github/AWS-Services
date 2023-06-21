# AWS-Services


## AWS Elastic Load Balancer
AWS Elastic Load Balancer (ELB) is a managed load balancing service provided by Amazon Web Services (AWS). It distributes incoming traffic across multiple instances of applications or services running in Amazon's cloud infrastructure.

ELB automatically scales and manages the availability of the application or service by distributing incoming traffic to healthy instances and monitoring the health of each instance. It can also automatically route traffic to different availability zones (AZs) to ensure high availability and fault tolerance.

There are three types of ELBs: 

1. Application Load Balancer (ALB)
2. Network Load Balancer (NLB)
3. Classic Load Balancer (CLB). 

ALB is best suited for HTTP/HTTPS traffic, NLB is designed for TCP/UDP traffic, and CLB is the original load balancer that is now being phased out in favor of ALB and NLB.

In summary, AWS Elastic Load Balancer is a scalable and highly available load balancing service that helps ensure the availability and performance of applications or services running in AWS.

---

## AWS Lambda

AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). It allows developers to run code without provisioning or managing servers, making it an ideal platform for building event-driven, serverless applications.

1. Supports multiple programming languages, including Node.js, Python, Java, C#, and Go. 
2. It is a small piece of code that perform a specific task or respond to an event. 
3. It Can be triggered by a variety of events, such as changes to data in an Amazon S3 bucket, a new message in an Amazon SNS topic, or an HTTP request to an Amazon API Gateway.

AWS Lambda automatically scales the execution of functions to handle incoming requests and charges only for the compute time used to run the code. This makes it a cost-effective solution for building highly scalable and responsive applications.

In summary, AWS Lambda is a serverless computing service that allows developers to run code without managing servers. It supports multiple programming languages and can be triggered by a variety of events. AWS Lambda is a cost-effective and scalable solution for building event-driven, serverless applications.

---

## AWS Cognito
AWS Cognito is a managed service provided by Amazon Web Services (AWS) that provides user authentication, authorization, and user management capabilities to web and mobile applications. 

With AWS Cognito, developers can easily add user sign-up, sign-in, and access control to their web and mobile applications. 
It also provides features such as multi-factor authentication, social identity providers, and integration with other AWS services such as Amazon S3, Amazon DynamoDB, and AWS Lambda.

AWS Cognito enables developers to create and manage user profiles and user data, and provides APIs to enable developers to integrate these features into their applications. It also supports both user pools and identity pools. User pools are used to manage user authentication and authorization, while identity pools are used to grant access to AWS services and resources.

In summary, AWS Cognito is a managed service that provides user authentication, authorization, and user management capabilities to web and mobile applications. It enables developers to easily add user sign-up, sign-in, and access control to their applications, and integrates with other AWS services.

---

## AWS Amplify

AWS Amplify is a development platform provided by Amazon Web Services (AWS) that allows developers to build scalable and secure cloud-powered mobile and web applications. Amplify provides a set of tools and services that enable developers to quickly configure and deploy cloud-based infrastructure and backend services for their applications.

Amplify supports a wide range of popular front-end frameworks and libraries such as React, React Native, Angular, Vue, and Ionic. It also provides a set of pre-built UI components that developers can use to quickly build and customize the user interface of their applications.

Amplify provides a variety of backend services such as authentication, storage, APIs, and analytics. These services are fully managed by AWS, which means that developers don't need to worry about infrastructure management or configuration.

In addition, Amplify provides a CLI tool that simplifies the development process by automating tasks such as code generation, deployment, and testing. This makes it easier for developers to focus on building features and functionality for their applications.

In summary, AWS Amplify is a development platform that enables developers to build scalable and secure cloud-powered mobile and web applications. It provides a set of tools and services that simplify the development process and enables developers to quickly configure and deploy cloud-based infrastructure and backend services for their applications.

---

### AWS Amplify features

1. Backend Services: Amplify provides a variety of fully managed backend services such as authentication, storage, APIs, and analytics. Developers can easily configure and deploy these services for their applications without worrying about infrastructure management or configuration.

2. Frontend Framework Support: Amplify supports a wide range of popular front-end frameworks and libraries such as React, React Native, Angular, Vue, and Ionic. This makes it easy for developers to build and customize the user interface of their applications.

3. Pre-built UI Components: Amplify provides a set of pre-built UI components that developers can use to quickly build and customize the user interface of their applications. These components are fully customizable and can be easily integrated into any application.

4. Continuous Deployment: Amplify provides continuous deployment capabilities that enable developers to automatically build, test, and deploy their applications to production. This helps ensure that applications are always up-to-date and running smoothly.

5. CLI Tool: Amplify provides a CLI tool that simplifies the development process by automating tasks such as code generation, deployment, and testing. This makes it easier for developers to focus on building features and functionality for their applications.

6. Integration with AWS Services: Amplify integrates with other AWS services such as Amazon S3, Amazon DynamoDB, and AWS Lambda. This enables developers to easily leverage these services for their applications without needing to manually configure them.

---

## AWS ECS/EKS

AWS ECS (Elastic Container Service) and EKS (Elastic Kubernetes Service) are two container orchestration services provided by Amazon Web Services (AWS) that enable developers to deploy and manage containerized applications in the cloud.

AWS ECS is a fully managed container orchestration service that enables developers to run Docker containers in the AWS cloud. ECS enables developers to easily deploy, manage, and scale containerized applications using AWS services such as Amazon EC2, Elastic Load Balancing, and Amazon VPC.

AWS EKS is a fully managed Kubernetes service that enables developers to run Kubernetes clusters in the AWS cloud. EKS enables developers to easily deploy, manage, and scale containerized applications using Kubernetes, the popular open-source container orchestration system.

Some of the key features of AWS ECS and EKS are:

1. Scalability: Both ECS and EKS enable developers to easily scale containerized applications up or down based on demand. This helps ensure that applications are always running at peak performance.

2. High Availability: ECS and EKS provide high availability and fault tolerance by automatically distributing containers across multiple availability zones.

3. Security: Both ECS and EKS provide a range of security features such as encryption, IAM roles, and network isolation, which help ensure that containerized applications are secure and compliant.

4. Integration with Other AWS Services: ECS and EKS integrate with other AWS services such as Amazon EC2, Elastic Load Balancing, Amazon VPC, and Amazon S3. This makes it easy for developers to build and deploy containerized applications using a wide range of AWS services.

5. Cost-Effective: Both ECS and EKS are cost-effective solutions for container orchestration, as they charge only for the resources used to run containers.

In summary, AWS ECS and EKS are two container orchestration services provided by Amazon Web Services that enable developers to easily deploy, manage, and scale containerized applications in the cloud. They provide scalability, high availability, security, integration with other AWS services, and are cost-effective solutions for container orchestration.

---

## AWS IAM security policies

AWS IAM (Identity and Access Management) is a service provided by Amazon Web Services (AWS) that enables developers to manage access to AWS resources. IAM allows developers to create and manage users, groups, and roles, and assign permissions to them to access AWS resources.

IAM security policies are used to define the permissions that are granted to users, groups, and roles in AWS. These policies are written in JSON format and define the resources that users are allowed to access and the actions they are allowed to perform on those resources.

IAM security policies can be attached to users, groups, and roles, and can be used to grant or deny access to AWS resources. Policies can be created at the account level, or at the resource level, and can be customized to meet the specific needs of an organization.

IAM security policies are used to enforce the principle of least privilege, which means that users are granted only the permissions they need to perform their tasks, and no more. This helps to reduce the risk of unauthorized access to AWS resources and helps to ensure that sensitive data is protected.

In summary, AWS IAM is a service provided by Amazon Web Services that enables developers to manage access to AWS resources. IAM security policies are used to define the permissions that are granted to users, groups, and roles in AWS, and are used to enforce the principle of least privilege. IAM security policies can be customized to meet the specific needs of an organization, and help to reduce the risk of unauthorized access to AWS resources.

---

## AWS VPC

AWS VPC (Virtual Private Cloud) is a service provided by Amazon Web Services (AWS) that enables developers to create a private, isolated network in the cloud. A VPC is a virtual network that is logically isolated from other networks in the AWS cloud, and can be used to launch Amazon EC2 instances, RDS databases, and other AWS resources.

With AWS VPC, developers have complete control over the virtual network, including IP address range, subnets, and routing tables. This enables developers to customize the network to meet the specific needs of their applications.

Some of the key features of AWS VPC are:

1. Security: AWS VPC provides a high level of security by enabling developers to control access to resources within the virtual network. VPC provides features such as security groups, network ACLs, and VPN connectivity to help protect against unauthorized access.

2. Scalability: AWS VPC is highly scalable, and can be easily expanded to accommodate the needs of growing applications. Developers can add additional subnets, gateways, and other resources as needed to scale the network.

3. Connectivity: AWS VPC can be connected to other networks, including on-premises data centers, using VPN or Direct Connect. This enables developers to create hybrid cloud architectures that span both on-premises and cloud environments.

4. Customization: AWS VPC provides a high degree of customization, enabling developers to create a virtual network that meets the specific needs of their applications. Developers have complete control over the IP address range, subnets, routing tables, and other network settings.

In summary, AWS VPC is a service provided by Amazon Web Services that enables developers to create a private, isolated network in the cloud. It provides a high level of security, scalability, connectivity, and customization, enabling developers to create virtual networks that meet the specific needs of their applications.

---

## Building AWS architectures for Web Applications using VPCs, IAM security policies, Kubernetes, Docker and MongoDB Atlas

Building AWS architectures for Web Applications using VPCs, IAM security policies, Kubernetes, Docker, and MongoDB Atlas involves several steps. Here is an overview of the process:

1. Create a VPC: Start by creating a VPC in AWS and configure the network settings, such as IP address range, subnets, and routing tables. This will provide a secure and isolated network for your application.

2. Set up IAM security policies: Create IAM roles and policies to control access to AWS resources. This helps ensure that only authorized users have access to your application and data.

3. Set up Kubernetes: Deploy a Kubernetes cluster in your VPC to manage containerized applications. Kubernetes provides features such as load balancing, auto-scaling, and rolling updates.

4. Deploy Docker containers: Use Docker to package your application code and dependencies into containers. These containers can be easily deployed and managed in Kubernetes.

5. Deploy MongoDB Atlas: MongoDB Atlas is a fully-managed database service that provides high availability, scalability, and security. Deploy your MongoDB database in Atlas and configure it to work with your Kubernetes cluster.

6. Connect the pieces: Connect your Docker containers to your MongoDB Atlas database using Kubernetes. This will allow your application to store and retrieve data from the database.

7. Test and Deploy: Test your application thoroughly to ensure it is working as expected. Once you are satisfied, deploy it to production.

8. Monitor and Manage: Monitor your application and AWS resources using AWS CloudWatch, and manage them using AWS Management Console or the AWS CLI.

In summary, building AWS architectures for Web Applications using VPCs, IAM security policies, Kubernetes, Docker, and MongoDB Atlas involves creating a secure and isolated network, setting up IAM roles and policies to control access, deploying a Kubernetes cluster, deploying Docker containers, deploying MongoDB Atlas, connecting the pieces, testing and deploying, and monitoring and managing the application. With these steps, you can create a scalable, secure, and high-performing web application in AWS.

---

