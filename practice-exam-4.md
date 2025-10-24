---
layout: exam
---

# Practice Exam 4

1. A developer needs to set up an SSL security certificate for a client's eCommerce website in order to use the HTTPS protocol. Which of the following AWS services can be used to deploy the required SSL server certificates? (Choose TWO)
    - A. Amazon Route 53.
    - B. AWS ACM.
    - C. AWS Directory Service.
    - D. AWS Identity & Access Management.
    - E. AWS Data Pipeline.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
        ACM은 인증서를 만들고 관리하며, Route 53는 도메인 연동에 필수적입니다.
    </details>

2. Which of the following AWS services scale automatically without your intervention? (Choose TWO)
    - A. Amazon EC2.
    - B. Amazon S3.
    - C. AWS Lambda.
    - D. Amazon EMR.
    - E. Amazon EBS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        S3는 무제한 스토리지이고, Lambda는 이벤트에 따라 컴퓨팅 용량을 자동으로 확장합니다.
    </details>

4. How do ELBs improve the reliability of your application?
    - A. By distributing traffic across multiple S3 buckets.
    - B. By replicating data to multiple availability zones.
    - C. By creating database Read Replicas.
    - D. By ensuring that only healthy targets receive traffic.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        ELB는 **상태 확인(Health Checks)**을 통해 문제가 있는 인스턴스는 제외하고 정상 인스턴스로만 트래픽을 보냅니다.
    </details>

6. A customer is planning to move billions of images and videos to be stored on Amazon S3. The customer has approximately 60 Petabytes of data to move. Which of the following AWS Services is the best choice to transfer the data to AWS?
    - A. Snowball.
    - B. S3 Transfer Acceleration.
    - C. Snowmobile.
    - D. Amazon VPC.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        60 PB는 10 PB 이상의 초 대규모 데이터 전송에 사용되는 Snowmobile의 대상입니다.
    </details>

9. Which support plan includes AWS Support Concierge Service?
    - A. Premium Support.
    - B. Business Support.
    - C. Enterprise Support.
    - D. Standard Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        Concierge Service는 청구 및 계정 관리를 위해 Enterprise Support 고객에게 제공됩니다.
    </details>

11. What are the benefits of using an AWS-managed service? (Choose TWO)
    - A. Provides complete control over the virtual infrastructure.
    - B. Allows customers to deliver new solutions faster.
    - C. Lowers operational complexity.
    - D. Eliminates the need to encrypt data.
    - E. Allows developers to control all patching related activities.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        AWS가 인프라를 관리하여 고객의 운영 부담을 덜고 출시 속도를 높입니다.
    </details>

12. Which of the following are use cases for Amazon S3? (Choose TWO)
    - A. Hosting static websites.
    - B. Hosting websites that require sustained high CPU utilization.
    - C. Cost-effective database and log storage.
    - D. A media store for the CloudFront service.
    - E. Processing data streams at any scale.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
        S3는 정적 콘텐츠 및 CDN(CloudFront)의 원본으로 사용됩니다.
    </details>

16. A company is planning to migrate a database with high read/write activity to AWS. What is the best storage option to use?
    - A. AWS Storage Gateway.
    - B. Amazon S3.
    - C. Amazon EBS.
    - D. Amazon Glacier.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        EBS는 데이터베이스에 필요한 높은 IOPS와 낮은 지연 시간을 제공하는 블록 스토리지입니다.
    </details>

17. How can AWS customers track and avoid over-spending on underutilized reserved instances?
    - A. Customers can add all AWS accounts to an AWS Organization, enable Consolidated Billing, and turn off Reserved Instance sharing.
    - B. Customers can use Amazon Neptune to track and analyze their usage patterns, detect underutilized reserved instances, and then sell them on the Amazon EC2 Reserved Instance Marketplace.
    - C. Customers can use the AWS Budgets service to track the reserved instances usage and set up alert notifications when their utilization drops below the threshold that they define.
    - D. Customers can use Amazon CloudTrail to automatically check for unused reservations and get recommendations to reduce their bill.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        AWS Budgets를 사용하여 RI 활용률에 대한 경고를 설정하여 비용 낭비를 방지합니다.
    </details>

19. What does AWS Service Catalog provide?
    - A. It enables customers to quickly find descriptions and use cases for AWS services.
    - B. It enables customers to explore the different catalogs of AWS services.
    - C. It simplifies organizing and governing commonly deployed IT services.
    - D. It allows developers to deploy infrastructure on AWS using familiar programming languages.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        Service Catalog는 조직에서 승인된 IT 서비스를 쉽게 배포하고 거버넌스를 관리할 수 있도록 돕습니다.
    </details>

21. Which of the following AWS Services helps with planning application migration to the AWS Cloud?
    - A. AWS Snowball Migration Service.
    - B. AWS Application Discovery Service.
    - C. AWS DMS.
    - D. AWS Migration Hub.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        온프레미스 환경을 분석하고 검색하여 마이그레이션 계획을 위한 데이터를 수집합니다.
    </details>

22. A company is trying to analyze the costs applied to their AWS account recently. Which of the following provides them the most granular data about their AWS costs and usage?
    - A. Amazon Machine Image.
    - B. AWS Cost Explorer.
    - C. AWS Cost & Usage Report.
    - D. Amazon CloudWatch.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        CUR은 AWS 비용 데이터 중 가장 상세한 보고서를 제공합니다.
    </details>

29. Which of the below are responsibilities of the customer when using Amazon EC2? (Choose TWO)
    - A. Protecting sensitive data.
    - B. Patching of the underlying infrastructure.
    - C. Setup and operation of managed databases.
    - D. Maintaining consistent hardware components.
    - E. Installing and configuring third-party software.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
        EC2(IaaS)에서 데이터와 게스트 OS/애플리케이션 관리는 고객의 책임입니다.
    </details>

32. Which of the following is NOT a characteristic of Amazon Elastic Compute Cloud (Amazon EC2)?
    - A. Amazon EC2 is considered a Serverless Web Service.
    - B. Amazon EC2 eliminates the need to invest in hardware upfront.
    - C. Amazon EC2 can launch as many or as few virtual servers as needed.
    - D. Amazon EC2 offers scalable computing.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        EC2는 IaaS이며 서버리스가 아닙니다 (Lambda가 서버리스).
    </details>

34. Both AWS and traditional IT distributors provide a wide range of virtual servers to meet their customers’ requirements. What is the name of these virtual servers in AWS?
    - A. Amazon EBS Snapshots.
    - B. Amazon VPC.
    - C. AWS Managed Servers.
    - D. Amazon EC2 Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        AWS의 가상 서버는 EC2 인스턴스입니다.
    </details>

37. Which of the following activities supports the Operational Excellence pillar of the AWS Well-Architected Framework?
    - A. Using AWS Trusted Advisor to find underutilized resources.
    - B. Using AWS CloudTrail to record user activities.
    - C. Using AWS CloudFormation to manage infrastructure as code.
    - D. Deploying an application in multiple Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        **IaC (CloudFormation)**를 사용하는 것은 운영의 자동화 및 일관성을 확보하는 운영 우수성 모범 사례입니다.
    </details>

39. What are the benefits of using DynamoDB? (Choose TWO)
    - A. Automatically scales to meet required throughput capacity.
    - B. Provides resizable instances to match the current demand.
    - C. Supports both relational and non-relational data models.
    - D. Offers extremely low (single-digit millisecond) latency.
    - E. Supports the most popular NoSQL database engines such as CouchDB and MongoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
        DynamoDB는 자동 확장되며 일관된 낮은 지연 시간을 제공하는 NoSQL DB입니다.
    </details>

42. AWS recommends some practices to help organizations avoid unexpected charges on their bill. Which of the following is NOT one of these practices?
    - A. Deleting unused EBS volumes after terminating an EC2instance.
    - B. Deleting unused AutoScaling launch configuration.
    - C. Deleting unused Elastic Load Balancers.
    - D. Releasing unused Elastic IPs after terminating an EC2instance.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        시작 구성 자체는 비용이 발생하지 않습니다.
    </details>

45. Which AWS service can be used to send promotional text messages (SMS) to more than 200 countries worldwide?
    - A. Amazon Simple Email Service (Amazon SES).
    - B. Amazon Simple Storage Service (Amazon S3).
    - C. Amazon Simple Notification Service (Amazon SNS).
    - D. Amazon Simple Queue Service (Amazon SQS).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        SNS는 대규모 SMS 전송을 지원합니다.
    </details>

47. One of the major advantages of using AWS is cost savings. What does AWS provide to reduce the cost of running Amazon EC2 instances?
    - A. Low monthly instance maintenance costs.
    - B. Low-cost instance tagging.
    - C. Per-second instance billing.
    - D. Low instance start-up fees.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        초 단위 청구는 사용한 만큼만 지불하게 하여 비용 효율성을 높입니다.
    </details>
