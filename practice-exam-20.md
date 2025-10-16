---
layout: exam
---

# Practice Exam 20

1. Which AWS service helps identify malicious or unauthorized activities in AWS accounts and workloads?
    - A. Amazon Rekognition
    - B. AWS Trusted Advisor
    - C. Amazon GuardDuty
    - D. Amazon CloudWatch

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/guardduty/></br>
    Amazon GuardDuty는 AWS 환경에서 악성 활동 및 무단 동작을 지속적으로 모니터링하여 위협을 탐지하는 지능형 위협 탐지 서비스입니다.

    </details>

7. Which actions represent best practices for using AWS IAM? (Choose two.)
    - A. Configure a strong password policy
    - B. Share the security credentials among users of AWS accounts who are in the same Region
    - C. Use access keys to log in to the AWS Management Console
    - D. Rotate access keys on a regular basis
    - E. Avoid using IAM roles to delegate permissions

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html></br>
    IAM 모범 사례는 강력한 비밀번호 정책을 사용하여 자격 증명 보안을 강화하고, 프로그래밍 방식 액세스에 사용되는 액세스 키를 정기적으로 교체하여 잠재적 보안 위험을 최소화하는 것을 포함합니다.

    </details>

9. A company wants to use an AWS service to monitor the health of application endpoints, with the ability to route traffic to healthy regional endpoints to improve application availability. <br/> Which service will support these requirements?
    - A. Amazon Inspector
    - B. Amazon CloudWatch
    - C. AWS Global Accelerator
    - D. Amazon CloudFront

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - AWS Global Accelerator uses the AWS global network to optimize the path from your users to your applications, improving the performance of your traffic by as much as 60%.
    - AWS Global Accelerator continually monitors the health of your application endpoints and redirects traffic to healthy endpoints in less than 30 seconds.

    Reference: <https://aws.amazon.com/global-accelerator/?blogs-global-accelerator.sort-by=item.additionalFields.createdDate&blogs-global-accelerator.sort-order=desc&aws-global-accelerator-wn.sort-by=item.additionalFields.postDateTime&aws-global-accelerator-wn.sort-order=desc></br>
    AWS Global Accelerator는 AWS 글로벌 네트워크를 사용하여 사용자 성능을 개선하고, 등록된 애플리케이션 엔드포인트의 상태를 지속적으로 모니터링하며, 정상적인 엔드포인트로만 트래픽을 라우팅하여 가용성을 향상시킵니다.

    </details>

10. According to the AWS Well-Architected Framework, what change management steps should be taken to achieve reliability in the AWS Cloud? (Choose two.)
    - A. Use AWS Config to generate an inventory of AWS resources
    - B. Use service limits to prevent users from creating or making changes to AWS resources
    - C. Use AWS CloudTrail to record AWS API calls into an auditable log file
    - D. Use AWS Certificate Manager to whitelist approved AWS resources and services
    - E. Use Amazon GuardDuty to validate configuration changes made to AWS resources

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: Ac</br>
    안정적인 변경 관리를 위해서는 시스템의 모든 변경 사항을 추적하고 감사할 수 있어야 합니다. AWS Config는 리소스 구성을 기록하고, AWS CloudTrail은 모든 API 활동을 로그로 기록합니다.

    </details>

13. Which AWS services can be used to move data from on-premises data centers to AWS? (Choose two.)
    - A. AWS Snowball
    - B. AWS Lambda
    - C. AWS ElastiCache
    - D. AWS Database Migration Service (AWS DMS)
    - E. Amazon API Gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://aws.amazon.com/snowball/></br>
    AWS Snowball은 물리적인 대규모 데이터 전송 서비스이고, AWS DMS는 데이터베이스를 온프레미스에서 AWS로 마이그레이션하는 데 사용됩니다.

    </details>

15. Each department within a company has its own independent AWS account and its own payment method. New company leadership wants to centralize departmental governance and consolidate payments. <br/> How can this be achieved using AWS services or features?
    - A. Forward monthly invoices for each account. Then create IAM roles to allow cross-account access.
    - B. Create a new AWS account. Then configure AWS Organizations and invite all existing accounts to join.
    - C. Configure AWS Organizations in each of the existing accounts. Then link all accounts together.
    - D. Use Cost Explorer to combine costs from all accounts. Then replicate IAM policies across accounts.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_accounts.html></br>
    AWS Organizations는 여러 AWS 계정을 하나로 통합하고 관리할 수 있도록 해주며, 통합 결제(Consolidated Billing) 기능을 통해 모든 계정의 요금을 한 곳에서 중앙 집중식으로 관리하고 결제할 수 있습니다.

    </details>

18. Which AWS service enables users to securely connect to AWS resources over the public internet?
    - A. Amazon VPC peering
    - B. AWS Direct Connect
    - C. AWS VPN
    - D. Amazon Pinpoint

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://d1.awsstatic.com/whitepapers/aws-security-whitepaper.pdf></br>
    AWS VPN 서비스는 공용 인터넷을 통해 AWS VPC와 온프레미스 네트워크 또는 독립 실행형 클라이언트 간에 **암호화된 터널(VPN)**을 생성하여 안전하게 연결할 수 있게 합니다.

    </details>

26. Which AWS service or feature can enhance network security by blocking requests from a particular network for a web application on AWS? (Choose two.)
    - A. AWS WAF
    - B. AWS Trusted Advisor
    - C. AWS Direct Connect
    - D. AWS Organizations
    - E. Network ACLs

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AE

    Explanation:
    - <https://aws.amazon.com/waf/>
    - <https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html></br>
    AWS WAF는 웹 애플리케이션 방화벽으로, IP 주소 목록(차단 목록)을 기반으로 웹 요청을 필터링할 수 있습니다. **네트워크 ACL(NACL)**은 서브넷 수준의 방화벽 역할을 하며, 특정 IP 주소/범위에서의 트래픽을 허용하거나 거부하는 규칙을 설정할 수 있습니다.

    </details>

30. The continual reduction of AWS Cloud pricing is due to:
    - A. pay-as-you go pricing
    - B. the AWS global infrastructure
    - C. economies of scale
    - D. reserved storage pricing

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    AWS는 수백만 고객의 방대한 총 사용량을 통해 규모의 경제를 달성하여 운영 효율성을 높이고, 그 결과로 발생하는 비용 절감을 고객에게 환원하여 지속적으로 가격을 인하할 수 있습니다.

    </details>

34. Who is responsible for patching the guest operating system for Amazon RDS?
    - A. The AWS Product team
    - B. The customer Database Administrator
    - C. Managed partners
    - D. AWS Support

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    Amazon RDS는 AWS가 운영 체제 패치 및 데이터베이스 패치 적용을 관리하는 관리형 서비스입니다. 따라서 AWS의 책임하에 있지만, AWS 공유 책임 모델에서는 RDS와 같은 관리형 서비스의 경우 AWS가 기본 인프라를 관리하므로, 고객이 아닌 AWS의 책임입니다. (단, 이 문제의 보기가 RDS에 대한 고객의 DB 관리 책임을 강조하는 맥락이라면 B를 선택할 수도 있지만, 게스트 OS 패치는 AWS 책임이 명확합니다. AWS 서비스가 아닌 일반 EC2의 DB 인스턴스라면 고객 책임이 맞습니다. RDS의 경우 AWS의 책임입니다.)

    </details>

35. Which AWS services may be scaled using AWS Auto Scaling? (Choose two.)
    - A. Amazon EC2
    - B. Amazon DynamoDB
    - C. Amazon S3
    - D. Amazon Route 53
    - E. Amazon Redshift

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation: <https://aws.amazon.com/autoscaling/faqs/></br>
    AWS Auto Scaling은 Amazon EC2 인스턴스뿐만 아니라 Amazon DynamoDB의 읽기/쓰기 용량, Amazon ECS 서비스, Amazon Aurora Replicas 등 다양한 AWS 서비스의 용량을 동적으로 관리할 수 있습니다.

    </details>

38. Which AWS Cloud best practice uses the elasticity and agility of cloud computing?
    - A. Provision capacity based on past usage and theoretical peaks
    - B. Dynamically and predictively scale to meet usage demands
    - C. Build the application and infrastructure in a data center that grants physical access
    - D. Break apart the application into loosely coupled components

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - In a traditional computing environment, you provision capacity based on an estimate of a theoretical maximum peak.
    - This can result in periods where expensive resources are sitting idle or occasions of insufficient capacity.
    - With cloud computing, you can access as much or as little capacity as you need and dynamically scale to meet actual demand, while only paying for what you use.</br>
    해설: 탄력성과 민첩성의 핵심은 수요에 맞춰 IT 리소스를 동적으로 확장/축소하는 능력입니다. 과거의 최대치를 예측하여 선제적으로 프로비저닝하는 것은 온프레미스 방식에 가깝습니다.

    </details>

45. Which AWS service can be used to turn text into life-like speech?
    - A. Amazon Polly
    - B. Amazon Transcribe
    - C. Amazon Rekognition
    - D. Amazon Lex

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/polly/#:~:text=Amazon%20Polly%20is%20a%20service,synthesize%20natural%20sounding%20human%20speech>.</br>
    Amazon Polly는 딥러닝 기술을 사용하여 텍스트를 실제 사람의 음성과 유사하게 합성하는 텍스트-음성 변환(Text-to-Speech) 서비스입니다.

    </details>