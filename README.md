# AWS

# MODULE 1

0. **Public, Private and Hybrid Clouds**

Private, Public and Hybrid clouds are three types of cloud computing models that cater to different business needs by balancing factors such as cost, control, scalability and security

In Public cloud environments:
- Resources are shared among multiple users.
- Pay only for what you use.
- Available from anywhere with Internet Access.
- Shared with others, so risk of data breaches.
- Limited control over infrastructure.

In Private Cloud environments:
- Resources are not shared with others.
- More control over data and resources.
- Tailored to specific needs and compliance.
- More expensive to acquire and maintain.
- Limited to serve a specific organization (not scalable).

In Hybrid Cloud environments:
- Combines public and private environments.
- Can run sensitive workloads in a private cloud while using public cloud for less sensitive tasks.
- Optimizes cost and performance (cost efficiency).
- Provides both security and flexibility.

*In simple terms Private clouds provide greater control and security, while Public clouds offer cost efficiency and scalability. Hybrid clouds combine both models, allowing for flexibility and cost optimization.*

1.  **AWS offers pay-as-you-go service and you don't pay anything upfront.**

2. **IaaS, PaaS, SaaS.**
- Infrastructure as a service (IaaS): Raw computer power. You rent entire computers, virtual servers, storage and networking
- Platform as a service (PaaS): You only focus on building and running apps. It gives developers a place to write, test and launch apps without managing the underlying hardware.
- Software as a service (SaaS): Finished software that is ready to use right away. You just login through a web browser.

3. **Elastic balancing.**
- Elastic: dynamically adjusts the traffic load to avoid crashing. 
- Balancing: sends the traffic equally ensuring no single server gets overwhelmed.

3.5 **VPC implements security.**
- VPC stands for (Amazon) Virtual Private Cloud: your own isolated cloud environment inside AWS.
- VPC gives you complete control over your virtual networking environment. Within it, you can define IP address range, create subnets (smaller network segments), configure routing tables (to direct traffic) and set up network gateways (to connect to the internet). Withing VPC you basically control who is allowed in, out and how the servers connect to each other.

4. **Go global in minutes: AWS allows you to deploy your application to users all over the world with just a few clicks.**

5. **Benefit from massive economies of scale**: Since AWS manages infrastructure for millions of active customer simultaneously, they can purchase hardware power and networking at scale, and at a discount, that no individual business could ever match.

6. **Trade capital expense for variable expense**: instead of paying heavily in physical data centers and servers before you can even use them, you only pay for the computing resources you actually consume. It turns large unpredictable upfront costs into a flexible monthly utility bill.

7. **In AWS Security is implemented through Network Access Control Lists (ACLs) and Identity Access Managagement (IAM).**
- Network Access Control Lists handle network security: They act as a firewall at the subnet level to control inbound and outbound traffic.
- Identity and Access Management handles identity security: It controls authentications and authorizations for users, group, and roles.

8. **AWS Compute service include**: EC2 (IaaS), Lambda, Fargate, Elastic Beanstalk (PaaS)

8.5 **AWS Storage methods include**: S3 (Object storage) used for storing files, images, videos and backups. EBS (Block storage) like a virtual hard drive. EFS (shared network drive) multiple EC2 instances can connect to it and share files at the same time.

9. **AWS services are configured with**:
- AWS Management Console: a web-based graphical interface.
- Command Line interface: a tool that lets you control AWS services using text-based commands.
- Software development Kit: a collection of libraries that lets developers interact with AWS services directly inside their application code using languages likes Python, Java or JavaScript.

10. **Migration Evaluator supports an assessment of on-premise costs against a migration to the AWS Cloud.**
By using Migration Evaluator organizations can clearly see how migrating to AWS directly eliminates two massive on-premise expenses:
- Cost of physical server hardware.
- Cost of data center operations.

10.5 **Migration from on-premise to the cloud: The AWS Shared responsibility Model; AWS is responsible for the security "of" the cloud, and the customer is reponsible for security "in" the cloud.**
- AWS's responsibility: Take care of the physical infrastructure; this includes guarding the physical data centers (physical security), keeping the cooling running (power consumption) and maintaining the actual host servers and cables (hardware infrastructure)
- Customer's responsibility: The customer is responsible for their own software, managing application licenses and keeping guest operating systems upated.

*Note*: The example above applies strictly to a migration from on-premises to the cloud. In general cloud deployments, your exact responsibilities will change dynamically based on the specific service model used (IaaS, PaaS, or SaaS).
  
