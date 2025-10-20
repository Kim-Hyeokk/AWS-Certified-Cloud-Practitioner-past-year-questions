---
layout: exam
---

# Practice Exam 22

1. A company operating in the AWS Cloud requires separate invoices for specific environments, such as development, testing, and production. <br/> How can this be achieved?
    - A. Use multiple AWS accounts
    - B. Use resource tagging
    - C. Use multiple VPCs
    - D. Use Cost Explorer

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A</br>
    AWS에서 환경별로 개별적인 청구서를 받으려면, 각 환경(개발, 테스트, 프로덕션)에 대해 별도의 AWS 계정을 생성하는 것이 가장 기본적인 방법입니다. AWS Organizations를 사용하여 이 계정들을 통합 관리할 수 있습니다.

    </details>

2. Which AWS service can be used in the application deployment process?
    - A. AWS AppSync
    - B. AWS Batch
    - C. AWS CodePipeline
    - D. AWS DataSync

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    AWS CodePipeline은 애플리케이션 및 인프라 업데이트를 위한 릴리스 프로세스를 자동화하는 지속적 전달(Continuous Delivery) 서비스로, 애플리케이션 배포에 핵심적으로 사용됩니다.

    </details>

13. Which components are required to build a successful site-to-site VPN connection on AWS? (Choose two.)
    - A. Internet gateway
    - B. NAT gateway
    - C. Customer gateway
    - D. Transit gateway
    - E. Virtual private gateway

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CE</br>
    Site-to-Site VPN 연결은 AWS VPC 측의 **가상 프라이빗 게이트웨이(VGW)**와 온프레미스 네트워크 측의 장치를 나타내는 **고객 게이트웨이(CGW)**가 쌍을 이루어야 설정할 수 있습니다.

    </details>

17. Which AWS service offers persistent storage for a file system?
    - A. Amazon S3
    - B. Amazon EC2 instance store
    - C. Amazon Elastic Block Store (Amazon EBS)
    - D. Amazon ElastiCache

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    **Amazon Elastic Block Store (Amazon EBS)**는 Amazon EC2 인스턴스에 연결하여 사용하는 블록 스토리지 볼륨을 제공합니다. 이 볼륨은 인스턴스가 종료되어도 데이터가 유지되는 지속적인 스토리지이며, 파일 시스템으로 포맷되어 사용됩니다.

    </details>

20. Which of the following AWS services are serverless? (Choose two.)
    - A. AWS Lambda
    - B. Amazon Elasticsearch Service
    - C. AWS Elastic Beanstalk
    - D. Amazon DynamoDB
    - E. Amazon Redshift

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD</br>
    서버리스 서비스는 고객이 서버를 프로비저닝하거나 관리할 필요가 없습니다. AWS Lambda는 서버리스 컴퓨팅 서비스이며, Amazon DynamoDB는 서버리스 NoSQL 데이터베이스 서비스입니다.

    </details>

21. Which AWS managed services can be used to extend an on-premises data center to the AWS network? (Choose two.)
    - A. AWS VPN
    - B. NAT gateway
    - C. AWS Direct Connect
    - D. Amazon Connect
    - E. Amazon Route 53

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC</br>
    AWS VPN은 공용 인터넷을 통한 암호화된 터널을 제공하며, AWS Direct Connect는 AWS와 온프레미스 간의 전용 사설 네트워크 연결을 제공하여 데이터 센터를 AWS로 확장하는 데 사용됩니다.

    </details>

22. Which requirement must be met for a member account to be unlinked from an AWS Organizations account?
    - A. The linked account must be actively compliant with AWS System and Organization Controls (SOC).
    - B. The payer and the linked account must both create AWS Support cases to request that the member account be unlinked from the organization.
    - C. The member account must meet the requirements of a standalone account.
    - D. The payer account must be used to remove the linked account from the organization.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    멤버 계정은 연결이 해제된 후에도 자체적으로 운영될 수 있도록, 독립 계정으로서 자체 결제 정보 설정 및 조직의 SCP(Service Control Policies) 제거 등의 요구 사항을 충족해야 합니다.

    </details>

23. What AWS benefit refers to a customer's ability to deploy applications that scale up and down the meet variable demand?
    - A. Elasticity
    - B. Agility
    - C. Security
    - D. Scalability

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D</br>
    수요에 따라 리소스를 동적으로 늘리고 줄이는 능력은 **탄력성(Elasticity)**에 더 가깝지만, 주어진 선택지 중에서는 **확장성(Scalability)**이 가장 광범위하게 사용되는 개념이며, 유연한 확장을 포함하는 의미로 사용됩니다.

    </details>

27. Which AWS service can run a managed PostgreSQL database that provides online transaction processing (OLTP)?
    - A. Amazon DynamoDB
    - B. Amazon Athena
    - C. Amazon RDS
    - D. Amazon EMR

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/rds/postgresql/></br>
    **Amazon RDS (Relational Database Service)**는 PostgreSQL을 포함하여 다양한 관계형 데이터베이스 엔진을 위한 완전 관리형 서비스를 제공하며, 이는 트랜잭션 처리가 중요한 OLTP 워크로드에 사용됩니다.

    </details>

29. A company wants to allow full access to an Amazon S3 bucket for a particular user. <br/> Which element in the S3 bucket policy holds the user details that describe who needs access to the S3 bucket?
    - A. Principal
    - B. Action
    - C. Resource
    - D. Statement

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://docs.aws.amazon.com/AmazonS3/latest/dev/walkthrough1.html></br>
    IAM 정책에서 Principal 요소는 해당 정책의 액세스 주체(누구에게 권한을 부여하거나 거부할지), 즉 IAM 사용자, 역할 또는 AWS 계정을 지정합니다.

    </details>

31. A company is piloting a new customer-facing application on Amazon Elastic Compute Cloud (Amazon EC2) for one month. <br/> What pricing model is appropriate?
    - A. Reserved Instances
    - B. Spot Instances
    - C. On-Demand Instances
    - D. Dedicated Hosts

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/ec2/pricing/></br>
    단기적인(1개월) 기간 동안 약정 없이 중단 없이 실행되어야 하는 고객 대면 애플리케이션에는 On-Demand Instance가 가장 적합합니다.

    </details>

32. Which AWS tools automatically forecast future AWS costs?
    - A. AWS Support Center
    - B. AWS Total Cost of Ownership (TCO) Calculator
    - C. AWS Simple Monthly Calculator
    - D. Cost Explorer

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-forecast.html></br>
    Cost Explorer는 사용자의 과거 비용 및 사용량 데이터를 기반으로 미래 12개월 동안의 예상 AWS 비용을 예측하는 기능을 제공합니다.

    </details>

36. Which design principle is achieved by following the reliability pillar of the AWS Well-Architected Framework?
    - A. Vertical scaling
    - B. Manual failure recovery
    - C. Testing recovery procedures
    - D. Changing infrastructure manually

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/blogs/apn/the-5-pillars-of-the-aws-well-architected-framework/></br>
    안정성 기둥은 시스템이 오류 발생 시 정상적으로 복구될 수 있도록 보장하는 것을 목표로 합니다. 이를 위해 복구 절차를 정기적으로 테스트하는 것이 주요 설계 원칙 중 하나입니다.

    </details>

37. What is a characteristic of Convertible Reserved Instances (RIs)?
    - A. Users can exchange Convertible RIs for other Convertible RIs from a different instance family with an equal or higher value than the Convertible Reserved Instances that you are exchanging.
    - B. Users can exchange Convertible RIs for other Convertible RIs in different AWS Regions.
    - C. Users can sell and buy Convertible RIs on the AWS Marketplace.
    - D. Users can shorten the term of their Convertible RIs by merging them with other Convertible RIs.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ri-convertible-exchange.html></br>
    Convertible RI는 약정 기간 동안 인스턴스 유형(제품군)을 변경할 수 있는 유연성을 제공하지만, 교환되는 RI는 기존 RI와 동일하거나 더 높은 가치를 가져야 합니다.

    </details>

40. Which are benefits of using Amazon RDS over Amazon EC2 when running relational databases on AWS? (Choose two.)
    - A. Automated backups
    - B. Schema management
    - C. Indexing of tables
    - D. Software patching
    - E. Extract, transform, and load (ETL) management

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html></br>
    Amazon RDS는 관리형 서비스이므로, AWS가 자동화된 백업 및 데이터베이스 엔진과 운영 체제에 대한 소프트웨어 패치와 같은 일상적인 관리 작업을 대신 처리합니다.

    </details>

43. Which AWS service can be used to track resource changes and establish compliance?
    - A. Amazon CloudWatch
    - B. AWS Config
    - C. AWS CloudTrail
    - D. AWS Trusted Advisor

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config.html></br>
    AWS Config는 리소스 구성의 변경 사항을 기록하고 규정 준수 규칙에 대해 평가하는 데 사용됩니다.

    </details>

48. A developer has been hired by a large company and needs AWS credentials. <br/> Which are security best practices that should be followed? (Choose two.)
    - A. Grant the developer access to only the AWS resources needed to perform the job.
    - B. Share the AWS account root user credentials with the developer.
    - C. Add the developer to the administrator's group in AWS IAM.
    - D. Configure a password policy that ensures the developer's password cannot be changed.
    - E. Ensure the account password policy requires a minimum length.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AE</br>
    최소 권한의 원칙을 따르는 것(A)과 강력한 IAM 암호 정책을 설정하는 것(E)은 기본적인 보안 모범 사례입니다. 루트 사용자 자격 증명 공유는 금지됩니다.

    </details>