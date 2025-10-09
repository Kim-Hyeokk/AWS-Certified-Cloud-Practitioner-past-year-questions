---
layout: exam
---

# Practice Exam 16

4. A company is designing an application hosted in a single AWS Region serving end-users spread across the world. The company wants to provide the end-users low latency access to the application data. <br/> Which of the following services will help fulfill this requirement?
    - A. Amazon CloudFront
    - B. AWS Direct Connect
    - C. Amazon Route 53 global DNS
    - D. Amazon Simple Storage Service (Amazon S3) transfer acceleration

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:
    - Amazon CloudFront is a content delivery network (CDN) service that distributes data from multiple locations worldwide, providing low-latency access to end-users.</br>
    Amazon CloudFront는 전 세계 엣지 로케이션을 사용하는 콘텐츠 전송 네트워크(CDN)로, 사용자에게 가장 가까운 위치에서 데이터를 제공하여 지연 시간을 줄입니다.

    </details>

6. How is asset management on AWS easier than asset management in a physical data center?
    - A. AWS provides a Configuration Management Database that users can maintain.
    - B. AWS performs infrastructure discovery scans on the customer's behalf.
    - C. Amazon EC2 automatically generates an asset report and places it in the customer's specified Amazon S3 bucket.
    - D. Users can gather asset metadata reliably with a few API calls.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - AWS assets are centrally managed through an inventory management system that stores and tracks owner, location, status, maintenance, and descriptive information for AWS-owned assets.
    - Following procurement, assets are scanned and tracked, and assets undergoing maintenance are checked and monitored for
    ownership, status, and resolution.

    Reference: <https://aws.amazon.com/compliance/data-center/controls/></br>
    AWS는 모든 인프라를 API로 관리하므로, 고객은 복잡한 물리적 인벤토리 스캔 없이도 프로그래밍 방식으로 자산 정보를 쉽게 얻을 수 있습니다.

    </details>

13. Under the AWS shared responsibility model, customers are responsible for which aspects of security in the cloud? (Choose two.)
    - A. Visualization management
    - B. Hardware management
    - C. Encryption management
    - D. Facilities management
    - E. Firewall management

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CE

    Explanation:
    - With the basic Cloud infrastructure secured and maintained by AWS, the responsibility for what goes into the cloud falls on you. This covers both client and server side encryption and network traffic protection, security of the operating system, network, and firewall configuration, followed by application security and identity and access management.
    - Firewall configuration remains the responsibility of the end user, which integrates at the platform and application management level. For example, RDS utilizes security groups, which you would be responsible for configuring and implementing.

    Reference: <https://cloudacademy.com/blog/aws-shared-responsibility-model-security/></br>
    고객은 데이터의 암호화(클라이언트/서버 측)와 방화벽(보안 그룹 및 네트워크 ACL) 설정을 포함한 클라우드 내의 보안을 담당합니다.

    </details>

14. Which AWS hybrid storage service enables on-premises applications to seamlessly use AWS Cloud storage through standard file-storage protocols?
    - A. AWS Direct Connect
    - B. AWS Snowball
    - C. AWS Storage Gateway
    - D. AWS Snowball Edge

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - The AWS Storage Gateway service enables hybrid cloud storage between on-premises environments and the AWS Cloud.
    - It seamlessly integrates on-premises enterprise applications and workflows with Amazon's block and object cloud storage services through industry standard storage protocols.
    - It provides low-latency performance by caching frequently accessed data on premises, while storing data securely and durably in Amazon cloud storage services.
    - It provides an optimized data transfer mechanism and bandwidth management, which tolerates unreliable networks and minimizes the amount of data being transferred.
    - It brings the security, manageability, durability, and scalability of AWS to existing enterprise environments through native integration with AWS encryption, identity management, monitoring, and storage services. Typical use cases include backup and archiving, disaster recovery, moving data to S3 for in-cloud workloads, and tiered storage.

    Reference: <https://aws.amazon.com/storagegateway/faqs/></br>
    AWS Storage Gateway는 온프레미스와 AWS 클라우드 간의 하이브리드 스토리지를 제공하며, 온프레미스 애플리케이션이 파일, 볼륨, 테이프 형식으로 AWS 스토리지를 사용할 수 있게 합니다.

    </details>

15. What is a responsibility of AWS in the shared responsibility model?
    - A. Updating the network ACLs to block traffic to vulnerable ports.
    - B. Patching operating systems running on Amazon EC2 instances.
    - C. Updating the firmware on the underlying EC2 hosts.
    - D. Updating the security group rules to block traffic to the vulnerable ports.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://cloudacademy.com/blog/aws-shared-responsibility-model-security/></br>
    AWS는 컴퓨팅, 스토리지, 네트워킹 등의 기본 인프라(호스트 하드웨어와 펌웨어)의 보안 및 패치를 책임집니다.

    </details>

19. A director has been tasked with investigating hybrid cloud architecture. The company currently accesses AWS over the public internet.<br/>Which service will facilitate private hybrid connectivity?
    - A. Amazon Virtual Private Cloud (Amazon VPC) NAT Gateway
    - B. AWS Direct Connect
    - C. Amazon Simple Storage Service (Amazon S3) Transfer Acceleration
    - D. AWS Web Application Firewall (AWS WAF)

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - Amazon VPC provides multiple network connectivity options for you to leverage depending on your current network designs and requirements.
    - These connectivity options include leveraging either the internet or an AWS Direct Connect connection as the network backbone and terminating the connection into either AWS or user-managed network endpoints.
    - Additionally, with AWS, you can choose how network routing is delivered between Amazon VPC and your networks, leveraging either AWS or user-managed network equipment and routes.

    Reference: <https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/> introduction.html</br>
    AWS Direct Connect는 고객의 온프레미스 데이터 센터와 AWS 간에 사설 전용 네트워크 연결을 설정하여, 공용 인터넷을 통하지 않는 안정적이고 빠른 하이브리드 연결을 제공합니다.

    </details>

29. Which of the following is an AWS-managed compute service?
    - A. Amazon SWF
    - B. Amazon EC2
    - C. AWS Lambda
    - D. Amazon Aurora

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html></br>
    AWS Lambda는 서버리스 컴퓨팅 서비스로, 고객은 서버 운영 체제, 패치, 용량 관리 등을 걱정할 필요 없이 코드를 실행할 수 있습니다.

    </details>

31. Which mechanism allows developers to access AWS services from application code?
    - A. AWS Software Development Kit
    - B. AWS Management Console
    - C. AWS CodePipeline
    - D. AWS Config

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/tools/></br>
    AWS SDK는 다양한 프로그래밍 언어로 AWS 서비스와 상호 작용할 수 있는 API 라이브러리를 제공합니다.

    </details>

32. Which Amazon EC2 pricing model is the MOST cost efficient for an uninterruptible workload that runs once a year for 24 hours?
    - A. On-Demand Instances
    - B. Reserved Instances
    - C. Spot Instances
    - D. Dedicated Instances

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:
    - With On-Demand instances, you pay for compute capacity by the hour or the second depending on which instances you run.
    - No longer-term commitments or upfront payments are needed.
    - You can increase or decrease your compute capacity depending on the demands of your application and only pay the specified per hourly rates for the instance you use.

    Reference: <https://aws.amazon.com/ec2/pricing/></br>
    워크로드가 매우 짧은 기간(1년 중 24시간)만 실행되므로, 선납금이 필요한 RI나 중단될 수 있는 Spot 인스턴스보다 온디맨드가 가장 경제적입니다.

    </details>

34. Which Amazon Virtual Private Cloud (Amazon VPC) feature enables users to connect two VPCs together?
    - A. Amazon VPC endpoints
    - B. Amazon Elastic Compute Cloud (Amazon EC2) ClassicLink
    - C. Amazon VPC peering
    - D. AWS Direct Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses.
    - Instances in either VPC can communicate with each other as if they are within the same network.
    - You can create a VPC peering connection between your own VPCs, or with a VPC in another AWS account.
    - The VPCs can be in different regions (also known as an inter-region VPC peering connection).

    Reference: <https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html></br>
    VPC 피어링은 두 VPC를 사설 네트워크로 연결하여, 마치 동일한 네트워크에 있는 것처럼 인스턴스들이 통신할 수 있게 합니다.

    </details>

35. Which service's PRIMARY purpose is software version control?
    - A. Amazon CodeStar
    - B. AWS Command Line Interface (AWS CLI)
    - C. Amazon Cognito
    - D. AWS CodeCommit

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - AWS CodeCommit is a version control service hosted by Amazon Web Services that you can use to privately store and manage assets (such as documents, source code, and binary files) in the cloud.

    Reference: <https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html></br>
    AWS CodeCommit은 Git을 기반으로 하며, 안전하고 확장 가능한 완전 관리형 소스 제어 서비스입니다.

    </details>

37. Which AWS service provides a secure, fast, and cost-effective way to migrate or transport exabyte-scale datasets into AWS?
    - A. AWS Batch
    - B. AWS Snowball
    - C. AWS Migration Hub
    - D. AWS Snowmobile

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - AWS Snowmobile is an exabyte-scale data transfer service that can move extremely large amounts of data to AWS in a fast, secure, and cost-effective manner.
    - You can transfer up to 100PB per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck. - Snowmobile makes it easy to move massive volumes of data to the cloud, including video libraries, image repositories, or even a complete data center migration.
    - All data is encrypted with 256-bit encryption and you can manage your encryption keys with AWS Key Management Service (AWS KMS).
    - Snowmobile includes GPS tracking, alarm monitoring, 24/7 video surveillance and an optional escort security vehicle while in transit.

    Reference: <https://aws.amazon.com/about-aws/whats-new/2016/11/move-exabyte-scale-data-sets-with>- aws-snowmobile/</br>
    AWS Snowmobile은 45피트 길이의 견고한 선적 컨테이너 트럭을 사용하여 엑사바이트 단위의 매우 방대한 데이터를 물리적으로 AWS로 전송하는 서비스입니다.

    </details>

40. Why should a company choose AWS instead of a traditional data center?
    - A. AWS provides users with full control over the underlying resources.
    - B. AWS does not require long-term contracts and provides a pay-as-you-go model.
    - C. AWS offers edge locations in every country, supporting global reach.
    - D. AWS has no limits on the number of resources that can be created.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - AWS offers you a pay-as-you-go approach for pricing for over 160 cloud services.
    - With AWS you pay only for the individual services you need, for as long as you use them, and without requiring long-term contracts or complex licensing.
    - AWS pricing is similar to how you pay for utilities like water and electricity.
    - You only pay for the services you consume, and once you stop using them, there are no additional costs or termination fees.

    Reference: <https://aws.amazon.com/pricing/></br>
    장기적인 계약 없이 실제로 사용한 만큼만 비용을 지불할 수 있다는 것이 AWS 클라우드의 주요 재정적 이점 중 하나입니다.

    </details>

45. How can a user protect against AWS service disruptions if a natural disaster affects an entire geographic area?
    - A. Deploy applications across multiple Availability Zones within an AWS Region.
    - B. Use a hybrid cloud computing deployment model within the geographic area.
    - C. Deploy applications across multiple AWS Regions.
    - D. Store application artifacts using AWS Artifact and replicate them across multiple AWS Regions.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - An AWS Region is a geographic location where AWS provides multiple, physically separated and isolated Availability Zones which are connected with low latency, high throughput, and highly redundant networking.

    Reference: <https://aws.amazon.com/s3/faqs/></br>
    리전은 지리적으로 완전히 분리되어 있으므로, 한 리전 전체에 영향을 미치는 대규모 자연재해에도 서비스의 연속성을 유지할 수 있습니다.

    </details>

46. How does AWS MOST effectively reduce computing costs for a growing start-up company?
    - A. It provides on-demand resources for peak usage.
    - B. It automates the provisioning of individual developer environments.
    - C. It automates customer relationship management.
    - D. It implements a fixed monthly computing budget.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:
    - You can continue to optimize your spend and keep your development costs low by making sure you revisit your architecture often, to adjust to your startup growth.
    - Manage your cost further by leveraging different options such as S3 CloudFront for caching & offloading to reduce cost of EC2 computing, as well as Elastic Load Balancing which prepares you for massive scale, high reliability and uninterrupted growth.
    - Another way to keep costs down is to use AWS Identity and Access Management solutions (IAM) to manage governance of your cost drivers effectively and by the right teams.

    Reference: <https://aws.amazon.com/startups/lean/></br>
    온디맨드 리소스는 필요할 때만 사용하고 사용하지 않을 때는 종료하여 비용을 절감하며, 급격한 성장 시에도 유연하게 대처할 수 있게 합니다.

    </details>

49. Which of the following services have Distributed Denial of Service (DDoS) mitigation features? (Choose two.)
    - A. AWS WAF
    - B. Amazon DynamoDB
    - C. Amazon EC2
    - D. Amazon CloudFront
    - E. Amazon Inspector

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://aws.amazon.com/shield/></br>
    AWS WAF는 웹 트래픽을 필터링하여 DDoS를 완화하고, CloudFront는 엣지 로케이션의 규모를 활용하여 네트워크 레이어의 DDoS 공격을 자동으로 흡수합니다.
    </details>