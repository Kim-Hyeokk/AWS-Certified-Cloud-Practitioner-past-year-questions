---
layout: exam
---

# Practice Exam 19

10. When designing a typical three-tier web application, which AWS services and/or features improve availability and reduce the impact failures? (Choose two.)
    - A. AWS Auto Scaling for Amazon EC2 instances
    - B. Amazon VPC subnet ACLs to check the health of a service
    - C. Distributed resources across multiple Availability Zones
    - D. AWS Server Migration Service (AWS SMS) to move Amazon EC2 instances into a different Region
    - E. Distributed resources across multiple AWS points of presence

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf></br>
    여러 가용 영역에 걸쳐 리소스를 분산하여, 한 AZ에 장애가 발생해도 서비스가 계속 실행되도록 합니다.</br>
    AWS Auto Scaling을 사용하여 수요에 따라 인스턴스를 자동으로 추가하거나 교체함으로써, 장애가 발생한 인스턴스를 신속하게 복구하고 트래픽 증가에 대응합니다.

13. A company is migrating from on-premises data centers to the AWS Cloud and is looking for hands-on help with the project. <br/> How can the company get this support? (Choose two.)
    - A. Ask for a quote from the AWS Marketplace team to perform a migration into the company's AWS account.
    - B. Contact AWS Support and open a case for assistance
    - C. Use AWS Professional Services to provide guidance and to set up an AWS Landing Zone in the company's AWS account
    - D. Select a partner from the AWS Partner Network (APN) to assist with the migration
    - E. Use Amazon Connect to create a new request for proposal (RFP) for expert assistance in migrating to the AWS Cloud.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CD

    Explanation: <https://aws.amazon.com/solutions/aws-landing-zone/></br>
    마이그레이션 프로젝트에 대한 실질적인 도움과 전문적인 지침을 제공하는 공식 채널은 AWS의 내부 팀인 Professional Services와 광범위한 APN 파트너입니다.

    </details>

14. How does the AWS Enterprise Support Concierge team help users?
    - A. Supporting application development
    - B. Providing architecture guidance
    - C. Answering billing and account inquires
    - D. Answering questions regarding technical support cases

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/premiumsupport/plans/enterprise/></br>
    Concierge Team은 AWS Enterprise Support 플랜의 일부로, 비즈니스 및 계정 지원(결제, 계정 관리 등)을 전담하는 전문 팀입니다. 기술적인 문제 해결은 AWS Support 엔지니어의 역할입니다.

    </details>

17. Which AWS tool is used to compare the cost of running an application on-premises to running the application in the AWS Cloud?
    - A. AWS Trusted Advisor
    - B. AWS Simple Monthly Calculator
    - C. AWS Pricing Calculator
    - D. Cost Explorer

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/tco-calculator/></br>
    AWS Pricing Calculator는 AWS 서비스 사용에 대한 예상 비용을 모델링하는 데 사용됩니다. 

    </details>

18. A company has multiple AWS accounts within AWS Organizations and wants to apply the Amazon EC2 Reserved Instances benefit to a single account only. <br/> Which action should be taken?
    - A. Purchase the Reserved Instances from master payer account and turn off Reserved Instance sharing.
    - B. Enable billing alerts in the AWS Billing and Cost Management console.
    - C. Purchase the Reserved Instances in individual linked accounts and turn off Reserved Instance sharing from the payer level.
    - D. Enable Reserved Instance sharing in the AWS Billing and Cost Management console.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/premiumsupport/knowledge-center/ec2-ri-consolidated-billing/></br>
    개별 계정에서 혜택을 제한하려면 마스터 결제 계정에서 RI 공유 기능을 비활성화해야 합니다.

    </details>

20. A company is planning to launch an ecommerce site in a single AWS Region to a worldwide user base. <br/> Which AWS services will allow the company to reach users and provide low latency and high transfer speeds? (Choose two.)
    - A. Application Load Balancer
    - B. AWS Global Accelerator
    - C. AWS Direct Connect
    - D. Amazon CloudFront
    - E. AWS Lambda

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BD

    Explanation: <https://aws.amazon.com/cloudfront/faqs/></br>
    AWS Global Accelerator는 AWS 글로벌 네트워크를 활용하여 사용자의 트래픽을 가장 가까운 AWS 엣지 로케이션으로 라우팅하고, 트래픽을 퍼블릭 인터넷 대신 AWS 백본 네트워크를 통해 애플리케이션 리전으로 전송하여 성능을 개선합니다.

    </details>

25. The AWS Trusted Advisor checks include recommendations regarding which of the following? (Choose two.)
    - A. Information on Amazon S3 bucket permissions
    - B. AWS service outages
    - C. Multi-factor authentication enabled on the AWS account root user
    - D. Available software patches
    - E. Number of users in the account

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/></br>
    AWS Trusted Advisor는 보안(Security), 비용 최적화, 성능, 내결함성 및 서비스 한도와 관련된 모범 사례에 대한 검사를 수행합니다. 루트 사용자 MFA 확인 및 S3 버킷 권한 확인은 보안 범주에 속합니다.

    </details>

30. Which AWS services provide a user with connectivity between the AWS Cloud and on-premises resources? (Choose two.)
    - A. AWS VPN
    - B. Amazon Connect
    - C. Amazon Cognito
    - D. AWS Direct Connect
    - E. AWS Managed Services

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation:
    - <https://aws.amazon.com/directconnect/>
    - <https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-aws-client-vpn-to-securely-access-aws-and-on-premises-resources/></br>
    AWS Direct Connect는 전용 물리적 연결을 제공하고, AWS VPN은 공용 인터넷을 통한 암호화된 터널을 제공하여 온프레미스 네트워크를 AWS 클라우드에 연결합니다.

    </details>

38. A user must meet compliance and software licensing requirements that state a workload must be hosted on a physical server. <br/> Which Amazon EC2 instance pricing option will meet these requirements?
    - A. Dedicated Hosts
    - B. Dedicated Instances
    - C. Spot Instances
    - D. Reserved Instances

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/ec2/dedicated-hosts/></br>
    Dedicated Hosts는 사용자의 계정에 전용으로 할당된 물리적 서버입니다. 이를 통해 사용자에게 기존 서버별 소프트웨어 라이선스를 가져와 사용할 수 있는 가시성과 통제권을 제공하여, 라이선스 요구 사항을 충족할 수 있도록 합니다.

    </details>

39. Which AWS service will provide a way to generate encryption keys that can be used to encrypt data? (Choose two.)
    - A. Amazon Macie
    - B. AWS Certificate Manager
    - C. AWS Key Management Service (AWS KMS)
    - D. AWS Secrets Manager
    - E. AWS CloudHSM

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CE

    Explanation:
    - <https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-service-hsm.html>
    - <https://docs.aws.amazon.com/kms/latest/developerguide/overview.html></br>
    AWS KMS는 클라우드 기반에서 키를 생성하고 관리하며, AWS CloudHSM은 전용 하드웨어 보안 모듈(HSM) 내에서 암호화 키를 생성하고 저장하는 데 사용됩니다.

    </details>

46. What is a characteristic of Amazon S3 cross-region replication?
    - A. Both source and destination S3 buckets must have versioning disabled
    - B. The source and destination S3 buckets cannot be in different AWS Regions
    - C. S3 buckets configured for cross-region replication can be owned by a single AWS account or by different accounts
    - D. The source S3 bucket owner must have the source and destination AWS Regions disabled for their account

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html></br>
    S3 교차 리전 복제를 구성하려면 소스 및 대상 버킷 모두에 버전 관리가 활성화되어 있어야 합니다. 복제는 단일 계정 내 또는 다른 AWS 계정 간에 설정할 수 있습니다.

    </details>

47. What is a user responsible for when running an application in the AWS Cloud?   - A. Managing physical hardware
    - B. Updating the underlying hypervisor
    - C. Providing a list of users approved for data center access
    - D. Managing application software updates

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    공유 책임 모델에서 고객은 클라우드 내 보안을 담당하며, 여기에는 고객이 EC2 인스턴스에 설치하는 애플리케이션 소프트웨어의 관리 및 업데이트가 포함됩니다.

    </details>

49. Which features or services can be used to monitor costs and expenses for an AWS account? (Choose two.)
    - A. AWS Cost and Usage report
    - B. AWS product pages
    - C. AWS Simple Monthly Calculator
    - D. Billing alerts and Amazon CloudWatch alarms
    - E. AWS Price List API

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html></br>
    AWS Cost and Usage Report는 가장 포괄적인 비용 및 사용량 데이터 집합을 제공합니다.</br>
    CloudWatch 경보를 통해 결제 경보를 설정하여 예상 비용이 정의된 임계값을 초과할 때 알림을 받을 수 있습니다.

    </details>