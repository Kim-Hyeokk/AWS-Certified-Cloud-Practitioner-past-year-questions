---
layout: exam
---

# Practice Exam 17

2. When comparing AWS with on-premises Total Cost of Ownership (TCO), what costs are included?
    - A. Data center security
    - B. Business analysis
    - C. Project management
    - D. Operating system administration

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://www.awstcocalculator.com/Output/Load/f85bbf7e131446643911859504></br>
    TCO 계산기에는 AWS를 도입했을 때 절감할 수 있는 온프레미스의 데이터 센터 보안 및 운영 비용 등이 포함됩니다.

    </details>

3. According to the AWS shared responsibility model, what is AWS responsible for?
    - A. Configuring Amazon VPC
    - B. Managing application code
    - C. Maintaining application traffic
    - D. Managing the network infrastructure

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://cloudacademy.com/blog/aws-shared-responsibility-model-security/></br>
    AWS는 클라우드의 근간이 되는 네트워크 인프라 (하드웨어, 소프트웨어, 시설 등)의 관리를 책임집니다.

    </details>

4. Which service should be used to estimate the costs of running a new project on AWS?
    - A. AWS TCO Calculator
    - B. AWS Simple Monthly Calculator
    - C. AWS Cost Explorer API
    - D. AWS Budgets

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - To forecast your costs, use the AWS Cost Explorer.
    - Use cost allocation tags to divide your resources into groups, and then estimate the costs for each group.

    Reference: <https://aws.amazon.com/premiumsupport/knowledge-center/estimating-aws-resource-costs/></br>
    AWS Cost Explorer는 과거 및 현재의 사용량 데이터를 바탕으로 향후 AWS 비용과 사용량을 **예측(forecast)**하는 기능을 제공합니다.

    </details>

7. Which Amazon EC2 pricing model offers the MOST significant discount when compared to On-Demand Instances?
    - A. Partial Upfront Reserved Instances for a 1-year term
    - B. All Upfront Reserved Instances for a 1-year term
    - C. All Upfront Reserved Instances for a 3-year term
    - D. No Upfront Reserved Instances for a 3-year term

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/ec2/pricing/reserved-instances/></br>
    3년 약정에 모든 금액을 선불로 지불하는 Reserved Instance(RI)가 가장 높은 할인율을 제공합니다.

    </details>

9. Which of the following is an advantage of using AWS?
    - A. AWS audits user data.
    - B. Data is automatically secure.
    - C. There is no guessing on capacity needs.
    - D. AWS manages compliance needs.

    <details markdown=1><summary markdown="span">Answer</summary></br>
    AWS는 필요에 따라 용량을 확장 및 축소할 수 있으므로, 미래의 용량 필요에 대해 추측할 필요가 없습니다.

    Correct Answer: C

    Explanation:
    - AWS allows you to access as much or as little capacity as you need, and scale up or down as required with only a few minutes’ notice

    Reference: <https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html>

    </details>

10. Which AWS service would a customer use with a static website to achieve lower latency and high transfer speeds?
    - A. AWS Lambda
    - B. Amazon DynamoDB Accelerator
    - C. Amazon Route 53
    - D. Amazon CloudFront

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer- friendly environment.
    - CloudFront is integrated with AWS both physical locations that are directly connected to the AWS global infrastructure, as well as other AWS services.

    Reference: <https://aws.amazon.com/cloudfront/></br>
    Amazon CloudFront는 엣지 로케이션을 통해 정적 콘텐츠를 캐싱하고 전송하여 낮은 지연 시간과 높은 속도를 제공하는 CDN 서비스입니다.

    </details>

11. Which services manage and automate application deployments on AWS? (Choose two.)
    - A. AWS Elastic Beanstalk
    - B. AWS CodeCommit
    - C. AWS Data Pipeline
    - D. AWS CloudFormation
    - E. AWS Config

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation:
    - EBS -> automates deploying code and provisioning infrastructure
    - CloudFormation -> Use templates to deploy code and infrastructure</br>
    AWS Elastic Beanstalk와 AWS CloudFormation은 인프라 및 애플리케이션 코드를 배포하고 프로비저닝하는 프로세스를 자동화합니다.

    </details>

14. What tasks should a customer perform when that customer suspects an AWS account has been compromised? (Choose two.)
    - A. Rotate passwords and access keys.
    - B. Remove MFA tokens.
    - C. Move resources to a different AWS Region.
    - D. Delete AWS CloudTrail Resources.
    - E. Contact AWS Support.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AE

    Explanation: <https://aws.amazon.com/premiumsupport/knowledge-center/potential-account-compromise/></br>
    침해를 막기 위해 **암호와 액세스 키를 즉시 변경(Rotate)**하고, 조사를 위해 AWS Support에 연락해야 합니다.

    </details>

19. What are the advantages of Reserved Instances? (Choose two.)
    - A. They provide a discount over on-demand pricing.
    - B. They provide access to additional instance types.
    - C. They provide additional networking capability.
    - D. Customers can upgrade instances as new types become available.
    - E. Customers can reserve capacity in an Availability Zone.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AE

    Explanation: <https://aws.amazon.com/premiumsupport/knowledge-center/ec2-ri-basics/></br>
    Reserved Instance는 온디맨드 요금보다 할인을 제공하며, 특정 가용 영역에 용량을 예약할 수 있습니다.

    </details>

23. Which of the following AWS services provide compute resources? (Choose two.)
    - A. AWS Lambda
    - B. Amazon Elastic Container Service (Amazon ECS)
    - C. AWS CodeDeploy
    - D. Amazon Glacier
    - E. AWS Organizations

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation: <https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html></br>
    AWS Lambda는 서버리스 컴퓨팅을, Amazon ECS는 도커 컨테이너를 실행하기 위한 컴퓨팅 리소스를 제공합니다.

    </details>

25. Which AWS services provide a way to extend an on-premises architecture to the AWS Cloud? (Choose two.)
    - A. Amazon EBS
    - B. AWS Direct Connect
    - C. Amazon CloudFront
    - D. AWS Storage Gateway
    - E. Amazon Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BD

    Explanation: <https://aws.amazon.com/hybrid/></br>
    AWS Direct Connect는 사설 연결을, AWS Storage Gateway는 온프레미스 스토리지 시스템과 클라우드 스토리지의 통합을 제공합니다.

    </details>

26. Which of the following allows users to provision a dedicated network connection from their internal network to AWS?
    - A. AWS CloudHSM
    - B. AWS Direct Connect
    - C. AWS VPN
    - D. Amazon Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - AWS Direct Connect lets you establish a dedicated network connection between your network and one of the AWS Direct Connect locations.
    - Using industry standard 802.1q VLANs, this dedicated connection can be partitioned into multiple virtual interfaces.
    - This allows you to use the same connection to access public resources such as objects stored in Amazon S3 using public IP address space, and private resources such as Amazon EC2 instances running within an Amazon Virtual Private Cloud (VPC) using private IP space, while maintaining network separation between the public and private environments.
    - Virtual interfaces can be reconfigured at any time to meet your changing needs.

    Reference: <https://aws.amazon.com/directconnect/></br>
    AWS Direct Connect는 고객의 데이터 센터와 AWS 간에 전용 사설 연결을 설정하여 일관된 네트워크 성능을 제공합니다.

    </details>

27. Which services use AWS edge locations? (Choose two.)
    - A. Amazon CloudFront
    - B. AWS Shield
    - C. Amazon EC2
    - D. Amazon RDS
    - E. Amazon ElastiCache

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A,B

    Explanation: <https://www.edureka.co/community/600/what-is-an-edge-location-in-aws></br>
    Amazon CloudFront는 엣지 로케이션을 콘텐츠 전송에 사용하며, AWS Shield는 엣지에서 DDoS 보호를 제공합니다.

    </details>

28. Which service would provide network connectivity in a hybrid architecture that includes the AWS Cloud?
    - A. Amazon VPC
    - B. AWS Direct Connect
    - C. AWS Directory Service
    - D. Amazon API Gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:
    - Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated, private section of the AWS Cloud to launch resources in a virtual data center in the cloud.
    - Amazon VPC allows you to leverage multiple Availability Zones (AZ) within a region so that you can build greater fault tolerance within your workloads.
    - You have complete control.

    Reference: <https://aws.amazon.com/blogs/publicsector/aws-networking-capabilities-gives-you-choices-for-hybrid-cloud-connectivity-but-which-service-works-best-for-your-use-case/></br>
    Amazon VPC는 AWS 클라우드 내의 논리적으로 격리된 사설 네트워크 영역으로, 하이브리드 연결의 대상이자 기반이 됩니다.

    </details>

30. What is the value of using third-party software from AWS Marketplace instead of installing third-party software on Amazon EC2? (Choose two.)
    - A. Users pay for software by the hour or month depending on licensing.
    - B. AWS Marketplace enables the user to launch applications with 1-Click.
    - C. AWS Marketplace data encryption is managed by a third-party vendor.
    - D. AWS Marketplace eliminates the need to upgrade to newer software versions.
    - E. Users can deploy third-party software without testing.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation: <https://aws.amazon.com/partners/aws-marketplace/></br>
    AWS Marketplace를 통해 소프트웨어 비용을 시간 또는 월 단위로 지불할 수 있으며, 1-Click으로 손쉽게 애플리케이션을 배포할 수 있습니다.

    </details>

34. Which AWS service identifies security groups that allow unrestricted access to a user's AWS resources?
    - A. AWS CloudTrail
    - B. AWS Trusted Advisor
    - C. Amazon CloudWatch
    - D. Amazon Inspector

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B</br>
    AWS Trusted Advisor는 보안 검사를 통해 0.0.0.0/0와 같이 너무 광범위한 접근을 허용하는 보안 그룹을 식별하여 경고합니다.

    </details>

35. According to the AWS shared responsibility model, who is responsible for configuration management?
    - A. It is solely the responsibility of the customer.
    - B. It is solely the responsibility of AWS.
    - C. It is shared between AWS and the customer.
    - D. It is not part of the AWS shared responsibility model.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.

    Reference: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    AWS는 기반 인프라 구성을, 고객은 자신이 배포한 OS, DB, 애플리케이션 구성을 책임지므로 책임을 공유합니다.

    </details>

38. A user is running an application on AWS and notices that one or more AWS-owned IP addresses is involved in a distributed denial-of-service (DDoS) attack. <br/> Who should the user contact FIRST about this situation?
    - A. AWS Premium Support
    - B. AWS Technical Account Manager
    - C. AWS Solutions Architect
    - D. AWS Abuse team

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/premiumsupport/knowledge-center/report-aws-abuse/></br>
    AWS Abuse 팀은 AWS 리소스가 불법적이거나 허용되지 않는 활동에 연루되었을 때 신고하는 전용 창구입니다.

    </details>

41. What is AWS Trusted Advisor?
    - A. It is an AWS staff member who provides recommendations and best practices on how to use AWS.
    - B. It is a network of AWS partners who provide recommendations and best practices on how to use AWS.
    - C. It is an online tool with a set of automated checks that provides recommendations on cost optimization, performance, and security.
    - D. It is another name for AWS Technical Account Managers who provide recommendations on cost optimization, performance, and security.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - AWS Trusted Advisor is an online tool that provides you real time guidance to help you provision your resources following AWS best practices.
    - Whether establishing new workflows, developing applications, or as part of ongoing improvement, take advantage of the recommendations provided by Trusted Advisor on a regular basis to help keep your solutions provisioned optimally.

    Reference: <https://aws.amazon.com/premiumsupport/technology/trusted-advisor/></br>
    Trusted Advisor는 비용 최적화, 성능, 보안 등에 대한 권장 사항을 제공하는 자동화된 온라인 검사 도구입니다.

    </details>

48. The pay-as-you-go pricing model for AWS services:
    - A. reduces capital expenditures.
    - B. requires payment up front for AWS services.
    - C. is relevant only for Amazon EC2, Amazon S3, and Amazon RDS.
    - D. reduces operational expenditures.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://www.10thmagnitude.com/opex-vs-capex-the-real-cloud-computing-cost-advantage/></br>
    종량제 모델은 서버 구매와 같은 자본 지출(CapEx)을 사용한 만큼 지불하는 운영 지출(OpEx)로 전환하여 자본 지출을 줄여줍니다.

    </details>