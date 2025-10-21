---
layout: exam
---

# Practice Exam 23

2. Which services can be used to deploy applications on AWS? (Choose two.)
    - A. AWS Elastic Beanstalk
    - B. AWS Config
    - C. AWS OpsWorks
    - D. AWS Application Discovery Service
    - E. Amazon Kinesis

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://d0.awsstatic.com/whitepapers/overview-of-deployment-options-on-aws.pdf></br>
    AWS Elastic Beanstalk은 코드 업로드만으로 인프라 프로비저닝, 배포, 로드 밸런싱 등을 자동으로 처리해주는 서비스입니다.

AWS OpsWorks는 Chef 및 Puppet을 사용하여 인프라를 구성 및 배포하는 관리형 서비스입니다.

    </details>

3. Which AWS service can be used to provide an on-demand, cloud-based contact center?
    - A. AWS Direct Connect
    - B. Amazon Connect
    - C. AWS Support Center
    - D. AWS Managed Services

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/connect/customers/></br>
    Amazon Connect는 몇 분 만에 설정할 수 있는 클라우드 기반 컨택 센터 서비스입니다.

    </details>

4. What tool enables customers without an AWS account to estimate costs for almost all AWS services?
    - A. Cost Explorer
    - B. TCO Calculator
    - C. AWS Budgets
    - D. AWS Pricing Calculator

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://calculator.aws/#/></br>
    AWS Pricing Calculator는 AWS 계정이 없는 사용자도 예상 아키텍처를 기반으로 월별 AWS 비용을 추정할 수 있도록 설계된 도구입니다.

    </details>

5. Which component must be attached to a VPC to enable inbound Internet access?
    - A. NAT gateway
    - B. VPC endpoint
    - C. VPN connection
    - D. Internet gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://d1.awsstatic.com/whitepapers/aws-security-whitepaper.pdf></br>
    **Internet Gateway (IGW)**는 VPC의 인스턴스가 인터넷에 연결될 수 있도록 하는 VPC 구성 요소입니다. 인스턴스가 인터넷으로부터 트래픽을 수신(인바운드)하거나 외부로 트래픽을 전송(아웃바운드)하려면 IGW가 필요합니다.

    </details>

6. Which pricing model would result in maximum Amazon Elastic Compute Cloud (Amazon EC2) savings for a database server that must be online for one year?
    - A. Spot Instance
    - B. On-Demand Instance
    - C. Partial Upfront Reserved Instance
    - D. No Upfront Reserved Instance

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html></br>
    예측 가능한 장기 워크로드(1년)의 경우, **Reserved Instance (RI)**가 가장 큰 할인을 제공합니다. RI 옵션 중에서는 **전액 선결제(All Upfront)**가 가장 큰 할인을 제공하지만, 그 다음으로 **부분 선결제(Partial Upfront)**가 선결제 없는(No Upfront) 옵션보다 더 큰 할인을 제공합니다.

    </details>

12. AnyCompany recently purchased Example Corp. Both companies use AWS resources, and AnyCompany wants a single aggregated bill.  <br/> Which option allows AnyCompany to receive a single bill?
    - A. Example Corp. must submit a request to its AWS solutions architect or AWS technical account manager to link the accounts and consolidate billing.
    - B. AnyCompany must create a new support case in the AWS Support Center requesting that both bills be combined.
    - C. Send an invitation to join the organization from AnyCompany's AWS Organizations master account to Example Corp.
    - D. Migrate the Example Corp. VPCs, Amazon EC2 instances, and other resources into the AnyCompany AWS account.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/awsaccountbilling-aboutv2.pdf></br>
    AWS Organizations는 여러 AWS 계정을 하나로 통합하고, **통합 결제(Consolidated Billing)**를 통해 마스터 계정에서 조직 내 모든 계정에 대해 단일 청구서를 받도록 할 수 있습니다.

    </details>

14. A user has limited knowledge of AWS services, but wants to quickly deploy a scalable Node.js application in the AWS Cloud. <br/> Which service should be used to deploy the application?
    - A. AWS CloudFormation
    - B. AWS Elastic Beanstalk
    - C. Amazon EC2
    - D. AWS OpsWorks

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/elasticbeanstalk/></br>
    AWS Elastic Beanstalk은 애플리케이션 코드를 업로드하는 것 외에는 인프라 관리가 거의 필요 없으므로 AWS 지식이 제한적인 사용자에게 적합하며, 자동 확장(scalability) 및 로드 밸런싱을 자동으로 설정합니다.

    </details>

15. Which AWS Trusted Advisor check is available to all AWS users?
    - A. Core checks
    - B. All checks
    - C. Cost optimization checks
    - D. Fault tolerance checks

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://www.amazonaws.cn/en/support/trustedadvisor/faq/#checks></br>
    AWS Trusted Advisor는 비용 최적화, 보안, 내결함성, 성능 및 서비스 한도 검사를 제공합니다. 이 중 **핵심 검사(Core checks)**는 모든 AWS 고객에게 제공됩니다. 다른 전체 검사는 Business 또는 Enterprise Support 플랜이 필요합니다.

    </details>

19. A company has a compliance requirement to record and evaluate configuration changes, as well as perform remediation actions on AWS resources. <br/> Which AWS service should the company use?
    - A. AWS Config
    - B. AWS Secrets Manager
    - C. AWS CloudTrail
    - D. AWS Trusted Advisor

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/config/></br>
    AWS Config는 리소스 구성의 변경 사항을 추적 및 기록하고, 설정된 규칙에 대해 구성의 규정 준수 여부를 평가하며, 비준수 리소스에 대한 자동 교정 조치를 설정할 수 있습니다.

    </details>

23. Which of the following is the customer's responsibility when using Amazon RDS?
    - A. Patching the operating system of underlying hardware
    - B. Controlling traffic to and from the database through security groups
    - C. Running backups that enable point-in-time recovery of a DB instance
    - D. Replacing failed DB instances

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.html></br>
    Amazon RDS는 관리형 서비스이지만, **네트워크 보안 제어(Security Groups)**를 구성하여 데이터베이스에 대한 접근을 제어하는 것은 여전히 고객의 책임입니다.

    </details>

24. What is the customer's responsibility when using AWS Lambda?
    - A. Operating system configuration
    - B. Application management
    - C. Platform management
    - D. Code encryption

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/lambda/security-overview-of-aws-lambda/></br>
    Lambda는 서버리스 서비스이므로 AWS가 OS 및 플랫폼 관리를 담당합니다. 고객은 **함수 코드(애플리케이션)**를 작성, 테스트, 배포 및 관리하는 데 전적인 책임이 있습니다.

    </details>

28. Which AWS service or feature requires an internet service provider (ISP) and a colocation facility to be implemented?
    - A. AWS VPN
    - B. Amazon Connect
    - C. AWS Direct Connect
    - D. Internet gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/directconnect/partners/></br>
    AWS Direct Connect는 AWS와 온프레미스 데이터 센터 또는 코로케이션 환경 간에 전용 사설 연결을 설정하여, 공용 인터넷을 우회하는 낮은 지연 시간의 연결을 제공합니다. 이는 ISP 또는 파트너를 통한 물리적 연결 설정이 필요합니다.

    </details>

35. A company is planning to launch an ecommerce site in a single AWS Region to a worldwide user base. <br/> Which AWS services will allow the company to reach users and provide low latency and high transfer speeds? (Choose two.)
    - A. Application Load Balancer
    - B. AWS Global Accelerator
    - C. AWS Direct Connect
    - D. Amazon CloudFront
    - E. AWS Lambda

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BD

    Explanation: <https://aws.amazon.com/cloudfront/faqs/></br>
    **Amazon CloudFront (CDN)**는 엣지 로케이션을 사용하여 이미지, 비디오와 같은 콘텐츠를 사용자에게 가장 가까운 곳에서 캐싱하여 낮은 지연 시간으로 제공합니다.

AWS Global Accelerator는 AWS 글로벌 네트워크를 사용하여 애플리케이션 트래픽을 사용자에게 가장 가까운 AWS 엣지 로케이션으로 라우팅하여 인터넷을 통한 성능을 최적화합니다.

    </details>

38. A company has an AWS-hosted website located behind an Application Load Balancer. The company wants to safeguard the website from SQL injection or cross-site scripting. <br/> Which AWS service should the company use?
    - A. Amazon GuardDuty
    - B. AWS WAF
    - C. AWS Trusted Advisor
    - D. Amazon Inspector

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/waf/faq/></br>
    **AWS WAF (Web Application Firewall)**는 웹 애플리케이션 또는 API를 일반적인 웹 공격(예: SQL 삽입, XSS)으로부터 보호하는 데 사용됩니다.

    </details>

39. How should a web application be deployed to ensure high availability in the AWS Cloud?
    - A. Deploy multiple instances of the application in multiple Availability Zones.
    - B. Deploy multiple instances of the application in a single Availability Zone.
    - C. Deploy the application to a compute-optimized Amazon EC2 instance in a single Availability Zone.
    - D. Deploy the application in one Amazon EC2 instance in an Auto Scaling group.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://www.betsol.com/blog/how-to-make-high-availability-web-applications-on-amazon-web-services/></br>
    고가용성은 단일 실패 지점을 제거하는 것이 핵심입니다. 이는 **여러 가용 영역(AZ)**에 애플리케이션 인스턴스를 분산하여 배포함으로써 달성됩니다.

    </details>

48. A pharmaceutical company operates its infrastructure in a single AWS Region. The company has thousands of VPCs in a various AWS accounts that it wants to interconnect. <br/> Which AWS service or feature should the company use to help simplify management and reduce operational costs?
    - A. VPC endpoint
    - B. AWS Direct Connect
    - C. AWS Transit Gateway
    - D. VPC peering

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf></br>
    AWS Transit Gateway는 수천 개의 VPC 및 온프레미스 네트워크를 중앙 집중식 허브를 통해 연결하는 데 사용됩니다. 이는 복잡한 VPC 피어링 네트워크를 대체하여 관리를 단순화하고 운영 비용을 절감합니다.

    </details>
