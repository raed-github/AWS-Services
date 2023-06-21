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

## AWS SNS

AWS SNS (Simple Notification Service) is a messaging service provided by Amazon Web Services (AWS) that enables developers to send and receive messages between distributed systems, applications, and services. SNS uses a publish-subscribe model, where publishers send messages to topics, and subscribers receive messages from those topics.

Some of the key features of AWS SNS are:

1. Scalability: AWS SNS is highly scalable and can handle millions of messages per second. This makes it ideal for applications that need to send and receive large volumes of messages.

2. Flexibility: AWS SNS supports a wide range of messaging protocols, including HTTP, HTTPS, email, SMS, and mobile push notifications. This makes it easy to integrate with a variety of applications and services.

3. Reliability: AWS SNS is designed to be highly reliable, with built-in redundancy and failover mechanisms. This ensures that messages are delivered reliably, even in the event of hardware or network failures.

4. Security: AWS SNS provides several layers of security, including encryption, access controls, and monitoring. This helps ensure that messages are protected against unauthorized access and other security threats.

5. Cost-Effective: AWS SNS is a cost-effective solution for sending and receiving messages. Developers only pay for the messages they send and receive, and can easily scale up or down as needed.

AWS SNS can be used for a wide range of use cases, including:

1. Sending notifications: Use SNS to send notifications to users or other applications when certain events occur, such as a new order being placed or a server going down.

2. Broadcasting messages: Use SNS to broadcast messages to multiple subscribers, such as updates to a website or changes to a database.

3. Building event-driven architectures: Use SNS to build event-driven architectures, where different services and applications communicate with each other using messages.

In summary, AWS SNS is a messaging service provided by Amazon Web Services that enables developers to send and receive messages between distributed systems, applications, and services. SNS is highly scalable, flexible, reliable, secure, and cost-effective, and can be used for a wide range of use cases, including sending notifications, broadcasting messages, and building event-driven architectures.

---

## AWS SQS

AWS SQS (Simple Queue Service) is a message queuing service provided by Amazon Web Services (AWS) that enables developers to decouple and scale microservices, distributed systems, and serverless applications. SQS allows developers to send, receive, and process messages between different components of an application, without requiring them to be connected directly.

Some of the key features of AWS SQS are:

1. Scalability: AWS SQS is highly scalable and can handle any amount of traffic, making it ideal for applications that need to process large volumes of messages.

2. Durability: SQS is designed to be highly durable, with messages stored across multiple availability zones to ensure that they are always available when needed.

3. Flexibility: AWS SQS supports two types of queues: standard queues and FIFO (First-In, First-Out) queues. This makes it easy to choose the right queue type for your application's needs.

4. Security: AWS SQS provides several layers of security, including encryption, access controls, and monitoring. This helps ensure that messages are protected against unauthorized access and other security threats.

5. Cost-Effective: AWS SQS is a cost-effective solution for queuing messages. Developers only pay for the messages they send and receive, and can easily scale up or down as needed.

AWS SQS can be used for a wide range of use cases, including:

1. Decoupling microservices: Use SQS to decouple microservices and enable them to communicate with each other asynchronously.

2. Building serverless applications: Use SQS to enable different components of a serverless application to communicate with each other, without requiring them to be connected directly.

3. Processing messages: Use SQS to process messages, such as orders or requests, and ensure that they are handled in a timely and reliable manner.

In summary, AWS SQS is a message queuing service provided by Amazon Web Services that enables developers to decouple and scale microservices, distributed systems, and serverless applications. SQS is highly scalable, durable, flexible, secure, and cost-effective, and can be used for a wide range of use cases, including decoupling microservices, building serverless applications, and processing messages.

---

## AWS S3

AWS S3 (Simple Storage Service) is a cloud-based object storage service provided by Amazon Web Services (AWS). S3 allows developers to store and retrieve any amount of data from anywhere on the web. S3 is designed to be highly scalable, available, and durable, with multiple layers of security and compliance built-in.

AWS S3 buckets are containers for storing objects in S3. An object in S3 can be anything from a small text file to a large video file. S3 buckets can be used to store a wide range of data types, including images, videos, audio files, documents, and backups.

Some of the key features of AWS S3 buckets are:

1. Scalability: AWS S3 buckets are highly scalable and can store virtually unlimited amounts of data. Developers can start with a small bucket and easily scale up as their storage needs grow.

2. Availability: S3 buckets are designed to be highly available, with multiple copies of data stored across multiple availability zones. This ensures that data is always available when needed.

3. Durability: S3 buckets are designed to be highly durable, with data stored across multiple devices and availability zones. This helps ensure that data is protected against hardware failures and other types of data loss.

4. Security: S3 buckets come with several layers of security built-in, including encryption, access controls, and logging. This helps ensure that data is protected against unauthorized access and other security threats.

5. Cost-Effective: S3 buckets are a cost-effective solution for storing data in the cloud. Developers only pay for the storage they use and can easily scale up or down as needed.

In summary, AWS S3 is a cloud-based object storage service that provides highly scalable, available, and durable storage for a wide range of data types. S3 buckets are containers for storing objects in S3, and come with several layers of security and compliance built-in. S3 buckets are a cost-effective solution for storing data in the cloud and can be easily scaled up or down as needed.

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

## AWS CloudFormation

AWS CloudFormation is a service provided by Amazon Web Services (AWS) that enables you to create and manage AWS resources using templates. CloudFormation allows you to define your infrastructure as code, which means you can version-control your infrastructure changes, test them, and deploy them in a repeatable and automated way.

With CloudFormation, you can create and manage multiple AWS resources as a single unit, called a stack. You can define a stack using a JSON or YAML template, which describes the resources that you want to create and their dependencies. CloudFormation takes care of provisioning and configuring the resources for you, so you don't have to manually create each resource individually.

Some of the key features of AWS CloudFormation are:

1. Infrastructure as code: CloudFormation enables you to define your infrastructure as code, which means you can version-control your infrastructure changes, test them, and deploy them in a repeatable and automated way.

2. Consistency: CloudFormation ensures that your infrastructure is consistent across all environments, which reduces the risk of errors and misconfigurations.

3. Efficiency: CloudFormation enables you to create and manage multiple AWS resources at once, which saves time and reduces manual errors.

4. Flexibility: CloudFormation supports a wide range of AWS resources, which enables you to create complex architectures and applications.

5. Rollback and recovery: CloudFormation provides rollback and recovery options, so you can easily revert to a previous version of your infrastructure if an error occurs during deployment.

CloudFormation can be used for a wide range of use cases, such as:

1. Creating and managing AWS resources: Use CloudFormation to create and manage AWS resources, such as EC2 instances, RDS databases, and S3 buckets.

2. Deploying applications: Use CloudFormation to deploy and manage applications on AWS, such as web applications, mobile applications, and microservices.

3. DevOps automation: Use CloudFormation to automate your DevOps workflows, such as creating and managing development, staging, and production environments.

In summary, AWS CloudFormation is a service provided by Amazon Web Services that enables you to create and manage AWS resources using templates. CloudFormation enables you to define your infrastructure as code, which provides several benefits, such as consistency, efficiency, and flexibility. CloudFormation can be used for a wide range of use cases, such as creating and managing AWS resources, deploying applications, and automating DevOps workflows.

---

## Is their a way to create AWS services using yaml files
Yes, AWS provides a service called AWS CloudFormation that allows you to create and manage AWS resources using YAML or JSON templates. AWS CloudFormation enables you to define your infrastructure as code, which means you can version-control your infrastructure changes, test them, and deploy them in a repeatable and automated way.

Here's how you can use YAML files to create AWS resources using AWS CloudFormation:

1. Create a YAML template: Start by creating a YAML template that describes the AWS resources you want to create. The YAML file should include the resource type, properties, and any dependencies or relationships between resources.

2. Upload the template: Upload the YAML file to AWS CloudFormation, either through the AWS Management Console, AWS CLI, or AWS SDKs.

3. Create the stack: Create a stack from the uploaded template. The stack is a collection of AWS resources that are created and managed as a single unit.

4. Monitor the stack: Monitor the status of the stack creation process through the AWS Management Console or the AWS CLI. You can view the status of each resource and any errors or warnings that occur during the creation process.

5. Update the stack: If you need to make changes to the stack, you can update the YAML template and apply the changes to the stack. AWS CloudFormation will automatically update the resources as needed.

Using YAML files to create AWS resources with AWS CloudFormation provides several benefits, such as:

1. Infrastructure as code: By defining your infrastructure as code, you can version-control your infrastructure changes, test them, and deploy them in a repeatable and automated way.

2. Consistency: AWS CloudFormation ensures that your infrastructure is consistent across all environments, which reduces the risk of errors and misconfigurations.

3. Efficiency: AWS CloudFormation enables you to create and manage multiple AWS resources at once, which saves time and reduces manual errors.

4. Flexibility: AWS CloudFormation supports a wide range of AWS resources, which enables you to create complex architectures and applications.

In summary, AWS CloudFormation allows you to create and manage AWS resources using YAML or JSON templates. Using YAML files to define your infrastructure provides several benefits, such as consistency, efficiency, and flexibility.

---

## Build AWS Services using CloudFormation YAML

1- ElasticLoadBalanced example

```html
Resources:
  MyELB:
    Type: 'AWS::ElasticLoadBalancing::LoadBalancer'
    Properties:
      AvailabilityZones:
        - us-west-2a
        - us-west-2b
      Listeners:
        - LoadBalancerPort: '80'
          Protocol: 'HTTP'
          InstancePort: '80'
          InstanceProtocol: 'HTTP'
      HealthCheck:
        Target: 'HTTP:80/'
        HealthyThreshold: '3'
        UnhealthyThreshold: '5'
        Interval: '30'
        Timeout: '5'
      SecurityGroups:
        - sg-0123456789abcdef0
      Subnets:
        - subnet-0123456789abcdef0
        - subnet-0123456789abcdef1
```
In this example, we're creating an ELB with the following properties:

- Availability Zones: The ELB will be created in two different availability zones in the us-west-2 region.
- Listeners: The ELB will listen on port 80 and forward traffic to instances on port 80 using the HTTP protocol.
- Health Check: The ELB will perform an HTTP health check on port 80 every 30 seconds, with a timeout of 5 seconds. The health check will be considered successful if it returns a 200 status code after 3 attempts, and unsuccessful if it returns a 200 status code after 5 attempts.
- Security Groups: The ELB will be associated with a security group identified by its ID.
- Subnets: The ELB will be associated with two subnets identified by their IDs.

To create the ELB using this YAML file, you can use the AWS CloudFormation console, AWS CLI, or AWS SDKs. Once the stack is created, you can use the ELB to distribute traffic to your instances.

2- AWS Lamda's example

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS Lambda function

Resources:
  LambdaFunction:
    Type: 'AWS::Lambda::Function'
    Properties:
      FunctionName: MyLambdaFunction
      Handler: index.handler
      Role: !GetAtt LambdaExecutionRole.Arn
      Code:
        ZipFile: |
          exports.handler = async (event) => {
            console.log('Hello from Lambda!');
            return 'Lambda executed successfully!';
          }
      Runtime: nodejs14.x

  LambdaExecutionRole:
    Type: 'AWS::IAM::Role'
    Properties:
      RoleName: LambdaExecutionRole
      AssumeRolePolicyDocument:
        Version: '2012-10-17'
        Statement:
          - Effect: Allow
            Principal:
              Service: lambda.amazonaws.com
            Action: 'sts:AssumeRole'
      Path: /
      Policies:
        - PolicyName: LambdaExecutionPolicy
          PolicyDocument:
            Version: '2012-10-17'
            Statement:
              - Effect: Allow
                Action:
                  - 'logs:CreateLogGroup'
                  - 'logs:CreateLogStream'
                  - 'logs:PutLogEvents'
                Resource: arn:aws:logs:*:*:*
```

3. AWS Cognito example:

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS Cognito User Pool

Resources:
  CognitoUserPool:
    Type: 'AWS::Cognito::UserPool'
    Properties:
      UserPoolName: MyUserPool
      AutoVerifiedAttributes:
        - email
      Policies:
        PasswordPolicy:
          MinimumLength: 8
          RequireLowercase: true
          RequireNumbers: true
          RequireSymbols: true
          RequireUppercase: true
      Schema:
        - AttributeDataType: String
          Name: email
          Required: true
          Mutable: true
      UsernameAttributes:
        - email

  CognitoUserPoolClient:
    Type: 'AWS::Cognito::UserPoolClient'
    Properties:
      UserPoolId: !Ref CognitoUserPool
      ClientName: MyUserPoolClient

Outputs:
  UserPoolId:
    Value: !Ref CognitoUserPool
  UserPoolClientId:
    Value: !Ref CognitoUserPoolClient
```

This template creates an AWS Cognito User Pool (`CognitoUserPool`) and a User Pool Client (`CognitoUserPoolClient`). The User Pool is configured to auto-verify email addresses, enforce a password policy, and require users to specify their email address as their username. The User Pool Client is associated with the User Pool.

The `Outputs` section of the template exports the `UserPoolId` and `UserPoolClientId` values, which can be used in other parts of the CloudFormation stack.

4. AWS Amplify example:

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS Amplify app

Resources:
  AmplifyApp:
    Type: 'AWS::Amplify::App'
    Properties:
      Name: MyAmplifyApp
      Repository: https://github.com/aws-samples/aws-amplify-graphql.git
      OAuthToken: !Sub '{{resolve:ssm:/my/ssm/parameter}}'
      EnvironmentVariables:
        - Name: API_URL
          Value: https://my-api.example.com/graphql
        - Name: API_KEY
          Value: !Sub '{{resolve:ssm:/my/ssm/parameter}}'

  AmplifyBranch:
    Type: 'AWS::Amplify::Branch'
    Properties:
      AppId: !Ref AmplifyApp
      BranchName: main
      EnvironmentVariables:
        - Name: API_URL
          Value: https://my-api.example.com/graphql
        - Name: API_KEY
          Value: !Sub '{{resolve:ssm:/my/ssm/parameter}}'

Outputs:
  AppId:
    Value: !Ref AmplifyApp
  AppName:
    Value: !GetAtt AmplifyApp.Name
  BranchName:
    Value: !Ref AmplifyBranch
```
This template creates an AWS Amplify app (`AmplifyApp`) and an Amplify branch (`AmplifyBranch`). The app is configured with a GitHub repository, OAuth token, and environment variables for the API URL and API key. The branch is associated with the app and has its own environment variables.

4. AWS Application Load Balancer

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS Application Load Balancer

Resources:
  LoadBalancer:
    Type: 'AWS::ElasticLoadBalancingV2::LoadBalancer'
    Properties:
      Name: MyLoadBalancer
      Scheme: internet-facing
      Type: application
      IpAddressType: ipv4
      SecurityGroups:
        - !Ref LoadBalancerSecurityGroup
      Subnets:
        - !Ref PublicSubnet1
        - !Ref PublicSubnet2

  LoadBalancerSecurityGroup:
    Type: 'AWS::EC2::SecurityGroup'
    Properties:
      GroupName: LoadBalancerSecurityGroup
      GroupDescription: Security group for the load balancer
      VpcId: !Ref VPC
      SecurityGroupIngress:
        - IpProtocol: tcp
          FromPort: 80
          ToPort: 80
          CidrIp: 0.0.0.0/0

  TargetGroup:
    Type: 'AWS::ElasticLoadBalancingV2::TargetGroup'
    Properties:
      Name: MyTargetGroup
      Protocol: HTTP
      Port: 80
      VpcId: !Ref VPC
      TargetType: ip
      HealthCheckIntervalSeconds: 30
      HealthCheckPath: /health
      HealthCheckProtocol: HTTP
      HealthCheckTimeoutSeconds: 5
      HealthyThresholdCount: 2
      UnhealthyThresholdCount: 2

  Listener:
    Type: 'AWS::ElasticLoadBalancingV2::Listener'
    Properties:
      LoadBalancerArn: !Ref LoadBalancer
      Protocol: HTTP
      Port: 80
      DefaultActions:
        - Type: forward
          TargetGroupArn: !Ref TargetGroup

Outputs:
  LoadBalancerDNSName:
    Value: !GetAtt LoadBalancer.DNSName
```

This template creates an AWS Application Load Balancer (`LoadBalancer`) with a security group (`LoadBalancerSecurityGroup`) and a target group (`TargetGroup`). The load balancer is associated with two public subnets and allows traffic on port 80. The target group is configured with a health check path and protocol.

The `Listener` resource sets up the forwarding rules for the load balancer. In this case, all incoming traffic on port 80 is forwarded to the target group.

The `Outputs` section of the template exports the `LoadBalancerDNSName` value, which can be used to access the load balancer.

5. AWS ECS/EKS example

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS ECS/EKS Cluster

Parameters:
  ClusterType:
    Type: String
    Default: ecs
    AllowedValues:
      - ecs
      - eks

Resources:
  VPC:
    Type: 'AWS::EC2::VPC'
    Properties:
      CidrBlock: 10.0.0.0/16
      EnableDnsSupport: true
      EnableDnsHostnames: true
      Tags:
        - Key: Name
          Value: MyVPC

  PublicSubnet1:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.1.0/24
      AvailabilityZone: !Select [0, !GetAZs '']
      Tags:
        - Key: Name
          Value: PublicSubnet1

  PublicSubnet2:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.2.0/24
      AvailabilityZone: !Select [1, !GetAZs '']
      Tags:
        - Key: Name
          Value: PublicSubnet2

  InternetGateway:
    Type: 'AWS::EC2::InternetGateway'
    Properties:
      Tags:
        - Key: Name
          Value: InternetGateway

  GatewayAttachment:
    Type: 'AWS::EC2::VPCGatewayAttachment'
    Properties:
      VpcId: !Ref VPC
      InternetGatewayId: !Ref InternetGateway

  RouteTable:
    Type: 'AWS::EC2::RouteTable'
    Properties:
      VpcId: !Ref VPC
      Tags:
        - Key: Name
          Value: RouteTable

  PublicRoute:
    Type: 'AWS::EC2::Route'
    DependsOn: GatewayAttachment
    Properties:
      RouteTableId: !Ref RouteTable
      DestinationCidrBlock: 0.0.0.0/0
      GatewayId: !Ref InternetGateway

  RouteTableAssociation1:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PublicSubnet1
      RouteTableId: !Ref RouteTable

  RouteTableAssociation2:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PublicSubnet2
      RouteTableId: !Ref RouteTable

  Cluster:
    Type: 'AWS::ECS::Cluster'
    Properties:
      ClusterName: MyCluster

  TaskDefinition:
    Type: 'AWS::ECS::TaskDefinition'
    Properties:
      Family: MyTaskDefinition
      ContainerDefinitions:
        - Name: MyContainer
          Image: nginx
          PortMappings:
            - ContainerPort: 80

  Service:
    Type: 'AWS::ECS::Service'
    Properties:
      Cluster: !Ref Cluster
      ServiceName: MyService
      TaskDefinition: !Ref TaskDefinition
      DesiredCount: 1
      LaunchType: FARGATE
      NetworkConfiguration:
        AwsvpcConfiguration:
          AssignPublicIp: ENABLED
          Subnets:
            - !Ref PublicSubnet1
            - !Ref PublicSubnet2

Outputs:
  ClusterArn:
    Value: !GetAtt Cluster.Arn
  ServiceArn:
    Value: !GetAtt Service.Arn
```

This template creates an AWS ECS or EKS cluster depending on the value of the `ClusterType` parameter. It also creates a VPC with two public subnets, an internet gateway, and a route table with a default route to the internet. The cluster is created with a task definition that defines a single container running NGINX. A service is created to run the task definition with a desired count of 1 and a Fargate launch type. The service is also configured with an AWS VPC configuration that assigns a public IP address and uses the two public subnets created earlier.

6. AWS VPCs example

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: AWS VPC with public and private subnets

Resources:
  VPC:
    Type: 'AWS::EC2::VPC'
    Properties:
      CidrBlock: 10.0.0.0/16
      EnableDnsSupport: true
      EnableDnsHostnames: true
      Tags:
        - Key: Name
          Value: MyVPC

  PublicSubnet1:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.1.0/24
      AvailabilityZone: !Select [0, !GetAZs '']
      MapPublicIpOnLaunch: true
      Tags:
        - Key: Name
          Value: PublicSubnet1

  PublicSubnet2:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.2.0/24
      AvailabilityZone: !Select [1, !GetAZs '']
      MapPublicIpOnLaunch: true
      Tags:
        - Key: Name
          Value: PublicSubnet2

  PrivateSubnet1:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.3.0/24
      AvailabilityZone: !Select [0, !GetAZs '']
      Tags:
        - Key: Name
          Value: PrivateSubnet1

  PrivateSubnet2:
    Type: 'AWS::EC2::Subnet'
    Properties:
      VpcId: !Ref VPC
      CidrBlock: 10.0.4.0/24
      AvailabilityZone: !Select [1, !GetAZs '']
      Tags:
        - Key: Name
          Value: PrivateSubnet2

  InternetGateway:
    Type: 'AWS::EC2::InternetGateway'
    Properties:
      Tags:
        - Key: Name
          Value: InternetGateway

  GatewayAttachment:
    Type: 'AWS::EC2::VPCGatewayAttachment'
    Properties:
      VpcId: !Ref VPC
      InternetGatewayId: !Ref InternetGateway

  RouteTable:
    Type: 'AWS::EC2::RouteTable'
    Properties:
      VpcId: !Ref VPC
      Tags:
        - Key: Name
          Value: RouteTable

  PublicRoute:
    Type: 'AWS::EC2::Route'
    DependsOn: GatewayAttachment
    Properties:
      RouteTableId: !Ref RouteTable
      DestinationCidrBlock: 0.0.0.0/0
      GatewayId: !Ref InternetGateway

  PrivateRoute:
    Type: 'AWS::EC2::Route'
    Properties:
      RouteTableId: !Ref RouteTable
      DestinationCidrBlock: 0.0.0.0/0
      NatGatewayId: !Ref NatGateway

  NatGateway:
    Type: 'AWS::EC2::NatGateway'
    Properties:
      AllocationId: !GetAtt ElasticIP.AllocationId
      SubnetId: !Ref PublicSubnet1

  ElasticIP:
    Type: 'AWS::EC2::EIP'

  PublicSubnet1RouteTableAssociation:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PublicSubnet1
      RouteTableId: !Ref RouteTable

  PublicSubnet2RouteTableAssociation:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PublicSubnet2
      RouteTableId: !Ref RouteTable

  PrivateSubnet1RouteTableAssociation:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PrivateSubnet1
      RouteTableId: !Ref RouteTable

  PrivateSubnet2RouteTableAssociation:
    Type: 'AWS::EC2::SubnetRouteTableAssociation'
    Properties:
      SubnetId: !Ref PrivateSubnet2
      RouteTableId: !Ref RouteTable

Outputs:
  VPCId:
    Value: !Ref VPC
  PublicSubnet1Id:
    Value: !Ref PublicSubnet1
  PublicSubnet2Id:
    Value: !Ref PublicSubnet2
  PrivateSubnet1Id:
    Value: !Ref PrivateSubnet1
  PrivateSubnet2Id:
    Value: !Ref PrivateSubnet2
  InternetGatewayId:
    Value: !Ref InternetGateway
  NatGatewayId:
    Value: !Ref NatGateway
```
This template creates a VPC with two public subnets (`PublicSubnet1` and `PublicSubnet2`) and two private subnets (`PrivateSubnet1` and `PrivateSubnet2`). The public subnets are associated with a default route to an internet gateway (`InternetGateway`) and have the `MapPublicIpOnLaunch` property set to true, which allows instances launched in these subnets to be assigned public IP addresses. The private subnets do not have direct access to the internet and are associated with a default route to a NAT gateway (`NatGateway`) that is deployed in the public subnet 1.

7. IAM security policies example

```html
AWSTemplateFormatVersion: '2010-09-09'
Description: IAM policy example

Resources:
  Policy:
    Type: 'AWS::IAM::Policy'
    Properties:
      PolicyName: MyPolicy
      PolicyDocument:
        Version: '2012-10-17'
        Statement:
          - Effect: Allow
            Action:
              - s3:GetObject
            Resource: arn:aws:s3:::my-bucket/*

  User:
    Type: 'AWS::IAM::User'
    Properties:
      UserName: MyUser

  UserPolicyAttachment:
    Type: 'AWS::IAM::UserPolicyAttachment'
    Properties:
      UserName: !Ref User
      PolicyArn: !Ref Policy

Outputs:
  PolicyArn:
    Value: !Ref Policy
  PolicyName:
    Value: !GetAtt Policy.PolicyName
```
8. Building AWS architectures for Web Applications using VPCs, IAM security policies, Kubernetes, Docker and MongoDB Atlas

```html
#Create a VPC
Resources:
  VPC:
    Type: AWS::EC2::VPC
    Properties:
      CidrBlock: 10.0.0.0/16
      EnableDnsSupport: true
      EnableDnsHostnames: true
      Tags:
        - Key: Name
          Value: my-vpc

#Create an IAM user and policy
  IAMUser:
    Type: AWS::IAM::User
    Properties:
      UserName: my-user
  IAMPolicy:
    Type: AWS::IAM::Policy
    Properties:
      PolicyName: my-policy
      PolicyDocument:
        Version: "2012-10-17"
        Statement:
          - Effect: Allow
            Action:
              - s3:*
            Resource: "*"
      Users:
        - Ref: IAMUser

#Create a Kubernetes cluster
  EKSRole:
    Type: AWS::IAM::Role
    Properties:
      AssumeRolePolicyDocument:
        Statement:
          - Effect: Allow
            Principal:
              Service: eks.amazonaws.com
            Action: sts:AssumeRole
      Path: "/"
      Policies:
        - PolicyName: eks-policy
          PolicyDocument:
            Version: "2012-10-17"
            Statement:
              - Effect: Allow
                Action:
                  - ec2:*
                  - eks:*
                Resource: "*"
  EKSCluster:
    Type: AWS::EKS::Cluster
    Properties:
      Name: my-eks-cluster
      RoleArn: !GetAtt EKSRole.Arn
      ResourcesVpcConfig:
        SubnetIds:
          - !Ref PrivateSubnet1
          - !Ref PrivateSubnet2
        SecurityGroupIds:
          - !Ref EKSSecurityGroup

#Create a Docker container
  ECSCluster:
    Type: AWS::ECS::Cluster
    Properties:
      ClusterName: my-ecs-cluster
  ECSTaskDefinition:
    Type: AWS::ECS::TaskDefinition
    Properties:
      Family: my-task-family
      ContainerDefinitions:
        - Name: my-container
          Image: my-docker-image
          Memory: 512
          PortMappings:
            - ContainerPort: 80
              HostPort: 80
          Environment:
            - Name: MY_ENV_VAR
              Value: my-env-value
  ECSALB:
    Type: AWS::ElasticLoadBalancingV2::LoadBalancer
    Properties:
      Name: my-alb
      Scheme: internet-facing
      Subnets:
        - !Ref PublicSubnet1
        - !Ref PublicSubnet2
      SecurityGroups:
        - !Ref ECSALBSecurityGroup
      Type: application
  ECSALBListener:
    Type: AWS::ElasticLoadBalancingV2::Listener
    Properties:
      LoadBalancerArn: !Ref ECSALB
      Port: 80
      Protocol: HTTP
      DefaultActions:
        - Type: forward
          TargetGroupArn: !Ref ECSALBTargetGroup
  ECSALBTargetGroup:
    Type: AWS::ElasticLoadBalancingV2::TargetGroup
    Properties:
      Name: my-target-group
      Port: 80
      Protocol: HTTP
      TargetType: ip
      VpcId: !Ref VPC

#Create a MongoDB Atlas cluster
  MongoDBCluster:
    Type: AWS::CloudFormation::Stack
    Properties:
      TemplateURL: https://s3.amazonaws.com/my-bucket/mongodb.yaml
      Parameters:
        ClusterName: my-mongodb-cluster
        Username: my-mongodb-user
        Password: my-mongodb-password
        Region: us-east-1
```

