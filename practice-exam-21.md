---
layout: exam
---

# Practice Exam 21

1. A user needs to quickly deploy a non-relational database on AWS. The user does not want to manage the underlying hardware or the database software. <br/> Which AWS service can be used to accomplish this?
    - A. Amazon RDS
    - B. Amazon DynamoDB
    - C. Amazon Aurora
    - D. Amazon Redshift

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SQLtoNoSQL.html></br>
    Amazon DynamoDB는 완전 관리형, 서버리스 NoSQL 데이터베이스 서비스입니다. 하드웨어 프로비저닝, 설정, 패치, 확장을 포함한 모든 관리 작업을 AWS가 처리하므로 관리 부담 없이 비관계형 데이터베이스를 배포하는 데 가장 적합합니다.

    </details>

3. Which features and benefits does the AWS Organizations service provide? (Choose two.)
    - A. Establishing real-time communications between members of an internal team
    - B. Facilitating the use of NoSQL databases
    - C. Providing automated security checks
    - D. Implementing consolidated billing
    - E. Enforcing the governance of AWS accounts

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: DE

    Explanation: <https://aws.amazon.com/organizations/></br>
    AWS Organizations는 다중 계정 환경을 중앙에서 관리하고 거버넌스를 적용하는 서비스입니다. 주요 이점으로는 여러 계정의 비용을 합치는 통합 결제와 **서비스 제어 정책(SCP)**을 사용하여 계정 전체의 권한을 제어하는 거버넌스 시행이 있습니다.

    </details>

8. Under the AWS shared responsibility model, which of the following are customer responsibilities? (Choose two.)
    - A. Setting up server-side encryption on an Amazon S3 bucket
    - B. Amazon RDS instance patching
    - C. Network and firewall configurations
    - D. Physical security of data center facilities
    - E. Compute capacity availability

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    고객은 클라우드 내의 보안을 책임집니다. 이는 데이터 암호화(A)와 보안 그룹 또는 네트워크 ACL과 같은 네트워크 트래픽 제어 구성(C)을 포함합니다. (B, D, E는 AWS의 책임입니다.)

    </details>

11. A company wants to use Amazon Elastic Compute Cloud (Amazon EC2) to deploy a global commercial application. The deployment solution should be built with the highest redundancy and fault tolerance. <br/> Based on this situation, the Amazon EC2 instances should be deployed:
    - A. in a single Availability Zone in one AWS Region
    - B. with multiple Elastic Network Interfaces belonging to different subnets
    - C. across multiple Availability Zones in one AWS Region
    - D. across multiple Availability Zones in two AWS Regions

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://jayendrapatil.com/aws-high-availability-fault-tolerance-architecture-certification/></br>
    단일 지리적 영역 내에서 최고의 가용성과 내결함성을 얻으려면 리소스가 **여러 가용 영역(AZ)**에 분산되어야 합니다. AZ는 독립적인 오류 도메인이므로 단일 데이터 센터 오류로부터 보호합니다.

    </details>

14. Which AWS dashboard displays relevant and timely information to help users manage events in progress, and provides proactive notifications to help plan for scheduled activities?
    - A. AWS Service Health Dashboard
    - B. AWS Personal Health Dashboard
    - C. AWS Trusted Advisor dashboard
    - D. Amazon CloudWatch dashboard

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/></br>
    AWS Personal Health Dashboard는 사용자 계정에 특화된 AWS 서비스의 상태와 예정된 유지 관리, 리소스에 영향을 미치는 진행 중인 이벤트를 알려주는 개인화된 알림판입니다.

    </details>

15. Which AWS hybrid storage service enables a user's on-premises applications to seamlessly use AWS Cloud storage?
    - A. AWS Backup
    - B. Amazon Connect
    - C. AWS Direct Connect
    - D. AWS Storage Gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/storagegateway/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc></br>
    AWS Storage Gateway는 온프레미스 소프트웨어 어플라이언스를 AWS 클라우드 스토리지에 연결하는 하이브리드 스토리지 서비스입니다. 이를 통해 사내 애플리케이션은 클라우드 스토리지(Amazon S3, Amazon EBS)를 마치 로컬 스토리지처럼 사용할 수 있습니다.

    </details>

16. Which of the following acts as a virtual firewall at the Amazon EC2 instance level to control traffic for one or more instances?
    - A. Access keys
    - B. Virtual private gateways
    - C. Security groups
    - D. Access Control Lists (ACL)

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html></br>
    **보안 그룹(Security Groups)**은 Amazon EC2 인스턴스에 대한 인스턴스 수준의 가상 방화벽 역할을 합니다. 인스턴스에 들어오고 나가는 트래픽을 허용 또는 거부하는 규칙을 정의하여 트래픽을 제어합니다. (반면, 네트워크 ACL은 서브넷 수준의 방화벽 역할을 합니다.)

    </details>

17. What is the most efficient way to establish network connectivity from on-premises to multiple VPCs in different AWS Regions?
    - A. Use AWS Direct Connect
    - B. Use AWS VPN
    - C. Use AWS Client VPN
    - D. Use an AWS Transit Gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf></br>
    AWS Transit Gateway는 클라우드 라우터처럼 작동하여 수천 개의 Amazon VPC와 온프레미스 네트워크를 중앙 집중식으로 연결할 수 있게 해줍니다. 특히 여러 리전에 걸쳐 다수의 VPC를 연결하는 경우, 복잡한 피어링 연결 대신 Transit Gateway를 사용하는 것이 가장 효율적이고 확장 가능한 방법입니다.

    </details>

19. Which AWS service or feature helps restrict the AWS services, resources, and individual API actions the users and roles in each member account can access?
    - A. Amazon Cognito
    - B. AWS Organizations
    - C. AWS Shield
    - D. AWS Firewall Manager

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html></br>
    AWS Organizations는 서비스 제어 정책(SCPs)을 사용하여 여러 AWS 계정을 중앙에서 관리하고 통제할 수 있게 해줍니다. SCP는 계정의 사용자 및 역할이 사용할 수 있는 최대 권한을 제한하는 데 사용됩니다.

    </details>

27. What credential components are required to gain programmatic access to an AWS account? (Choose two.)
    - A. An access key ID
    - B. A primary key
    - C. A secret access key
    - D. A user ID
    - E. A secondary key

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html></br>
    AWS CLI, API, SDK 등을 사용하여 AWS에 프로그래밍 방식으로 액세스하려면 액세스 키 ID와 그에 상응하는 보안 액세스 키 쌍이 필요합니다.

    </details>

28. Which of the following are AWS compute services? (Select two.)
    - A. Amazon Lightsail
    - B. AWS Systems Manager
    - C. AWS CloudFormation
    - D. AWS Batch
    - E. Amazon Inspector

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html></br>
    Amazon Lightsail은 가상 서버(EC2 인스턴스)를 포함하는 간소화된 클라우드 플랫폼이므로 컴퓨팅 서비스입니다. AWS Batch는 수천 개의 컴퓨팅 작업을 효율적으로 실행할 수 있도록 일괄 처리 워크로드를 동적으로 프로비저닝하고 관리하는 컴퓨팅 서비스입니다.

    </details>

29. How can a company separate costs for network traffic, Amazon EC2, Amazon S3, and other AWS services by department?
    - A. Add department-specific tags to each resource
    - B. Create a separate VPC for each department
    - C. Create a separate AWS account for each department
    - D. Use AWS Organizations

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    비용을 부서별로 가장 명확하게 분리하고 관리하는 가장 좋은 방법은 각 부서별로 별도의 AWS 계정을 생성하고 이를 AWS Organizations로 통합하여 관리하는 것입니다. 이를 통해 비용 청구, 보안 및 액세스 제어를 독립적으로 유지할 수 있습니다. (태그도 사용되지만, 계정 분리가 가장 강력한 분리 방법입니다.)

    </details>

33. Which tool can be used to monitor AWS service limits?
    - A. AWS Total Cost of Ownership (TCO) Calculator
    - B. AWS Trusted Advisor
    - C. AWS Personal Health Dashboard
    - D. AWS Cost and Usage report

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/blogs/mt/monitoring-service-limits-with-trusted-advisor-and-amazon-cloudwatch/></br>
    AWS Trusted Advisor는 서비스 한도 확인을 포함하여 AWS 환경을 최적화하기 위한 모범 사례 검사를 수행합니다. 서비스 한도 사용률이 80%를 초과할 경우 알림을 제공하여 잠재적인 운영 문제를 방지할 수 있게 돕습니다.

    </details>

36. What can be used to automate and manage secure, well-architected, multi-account AWS environments?
    - A. AWS shared responsibility model
    - B. AWS Control Tower
    - C. AWS Security Hub
    - D. AWS Well-Architected Tool

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - Control Tower automates the process of setting up a new baseline multi-account AWS environment that is secure, well-architected, and ready to use.
    - Control Tower incorporates the knowledge that AWS Professional Service has gained over the course of thousands of successful customer engagements.

    Reference: <https://aws.amazon.com/blogs/aws/aws-control-tower-set-up-govern-a-multi-account-aws-environment/></br>
    AWS Control Tower는 안전하고 잘 구성된 다중 계정 AWS 환경을 설정하고 관리하는 가장 쉽고 빠른 방법을 제공하는 서비스입니다. 이는 조직 내에서 계정을 프로비저닝하고 거버넌스 정책(가드레일)을 적용하는 것을 자동화합니다.

    </details>

37. Which AWS service or feature allows a user to easily scale connectivity among thousands of VPCs?
    - A. VPC peering
    - B. AWS Transit Gateway
    - C. AWS Direct Connect
    - D. AWS Global Accelerator

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/blogs/training-and-certification/explore-the-aws-transit-gateway-networking-and-scaling-digital-course/></br>
    AWS Transit Gateway는 수많은 VPC와 온프레미스 네트워크를 중앙 집중식 허브를 통해 연결하여 복잡성을 줄이고 대규모 네트워크 연결을 쉽게 확장할 수 있도록 설계되었습니다. VPC 피어링은 소수의 VPC에 적합하지만, 수천 개의 VPC에는 관리가 복잡해집니다.

    </details>

38. A company needs protection from expanded distributed denial of service (DDoS) attacks on its website and assistance from AWS experts during such events. <br/> Which AWS managed service will meet these requirements?
    - A. AWS Shield Advanced
    - B. AWS Firewall Manager
    - C. AWS WAF
    - D. Amazon GuardDuty

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html></br>
    AWS Shield Advanced는 표준 Shield 서비스가 제공하는 자동 인라인 완화 외에도, **DDoS 대응팀(DRT)**에 대한 연중무휴 액세스를 제공하여 DDoS 공격 발생 시 AWS 전문가의 직접적인 지원을 받을 수 있도록 합니다.

    </details>

39. A company's application has flexible start and end times. <br/> Which Amazon EC2 pricing model will be the MOST cost-effective?
    - A. On-Demand Instances
    - B. Spot Instances
    - C. Reserved Instances
    - D. Dedicated Hosts

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/ec2/pricing/></br>
    **스팟 인스턴스(Spot Instances)**는 미사용 상태인 Amazon EC2 용량을 요청하는 것으로, 가장 큰 할인을 제공하지만, AWS가 해당 용량을 필요로 할 경우 인스턴스가 중단될 수 있습니다. 따라서 유연한 시작/종료 시간을 가지고 있으며 중단되어도 괜찮은 워크로드(예: 배치 처리, 데이터 분석)에 가장 적합하고 비용 효율적입니다.

    </details>

42. Which AWS container service will help a user install, operate, and scale the cluster management infrastructure?
    - A. Amazon Elastic Container Registry (Amazon ECR)
    - B. AWS Elastic Beanstalk
    - C. Amazon Elastic Container Service (Amazon ECS)
    - D. Amazon Elastic Block Store (Amazon EBS)

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    **Amazon Elastic Container Service (Amazon ECS)**는 컨테이너화된 애플리케이션을 실행, 중지, 관리할 수 있는 확장성이 뛰어난 고성능 컨테이너 관리 서비스입니다. ECS는 클러스터 관리를 단순화하고 자동화하여 사용자가 기본 인프라 관리에 대해 걱정할 필요가 없도록 합니다.
    </details>

44. A company with a Developer-level AWS Support plan provisioned an Amazon RDS database and cannot connect to it. <br/> Who should the developer contact for this level of support?
    - A. AWS Support using a support case
    - B. AWS Professional Services
    - C. AWS technical account manager
    - D. AWS consulting partners

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A</br>
    Developer Support 플랜은 이메일 기반으로 기술 지원을 제공하며, 문제가 발생했을 때 AWS Support에 지원 케이스를 제출하여 도움을 받을 수 있습니다. (TAM은 Enterprise Support에서만 제공됩니다.)

    </details>

50. Fault tolerance refers to:
    - A. the ability of an application to accommodate growth without changing design
    - B. how well and how quickly an application's environment can have lost data restored
    - C. how secure your application is
    - D. the built-in redundancy of an application's components

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D</br>
    **내결함성(Fault tolerance)**은 시스템의 일부 구성 요소에 **오류(fault)**가 발생하더라도 내장된 중복성 덕분에 전체 시스템이 계속 작동할 수 있도록 하는 시스템 설계의 속성입니다.

    </details>

