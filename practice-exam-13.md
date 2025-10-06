---
layout: exam
---

# Practice Exam 13

1. The use of what AWS feature or service allows companies to track and categorize spending on a detailed level?
    - A. Cost allocation tags
    - B. Consolidated billing
    - C. AWS Budgets
    - D. AWS Marketplace

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html></br>
    태그를 붙여 리소스 단위로 비용을 세부적으로 구분할 수 있음.

    </details>

1. What AWS team assists customers with accelerating cloud adoption through paid engagements in any of several specialty practice area ?
    - A. AWS Enterprise Support
    - B. AWS Solutions Architects
    - C. AWS Professional Services
    - D. AWS Account Managers

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/professional-services/></br>
    Professional Services는 전문 컨설팅(유료)으로 마이그레이션·구현을 지원한다.
    </details>

1. A customer would like to design and build a new workload on AWS Cloud but does not have the AWS-related software technical expertise in-house. <br/>Which of the following AWS programs can a customer take advantage of to achieve that outcome?
    - A. AWS Partner Network Technology Partners
    - B. AWS Marketplace
    - C. AWS Partner Network Consulting Partners
    - D. AWS Service Catalog

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    컨설팅 파트너는 설계·구현 서비스를 제공해 대신 구축해준다.


    </details>

1. Which AWS services can host a Microsoft SQL Server database? (Select TWO)
    - A. Amazon EC2
    - B. Amazon Relational Database Service (Amazon RDS)
    - C. Amazon Aurora
    - D. Amazon Redshift
    - E. Amazon S3

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB</br>
    SQL Server는 EC2(직접관리) 또는 RDS(관리형)에서 운영 가능하다.

    Explanation: <https://aws.amazon.com/sql/>

    </details>

1. Which of the following inspects AWS environments to find opportunities that can save money for users and also improve system performance ?
    - A. AWS Cost Explorer
    - B. AWS Trusted Advisor
    - C. Consolidated billing
    - D. Detailed billing

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B</br>
    Trusted Advisor가 비용·보안·성능 권고를 제공한다.

    </details>

1. Which service enables risk auditing by continuously monitoring and logging account activity, including user actions in the AWS Management Console and AWS SDKs?
    - A. Amazon CloudWatch
    - B. AWS CloudTrail
    - C. AWS Config
    - D. AWS Health

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/cloudtrail/></br>
    CloudTrail은 API 호출(누가·언제)을 기록해 감사에 사용된다.

    </details>

1. Which services can be used across hybrid AWS Cloud architectures? (Select TWO.)
    - A. Amazon Route 53
    - B. Virtual Private Gateway
    - C. Classic Load Balancer
    - D. Auto Scaling
    - E. Amazon CloudWatch default metrics

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation:
    - <https://aws.amazon.com/cloudwatch/>
    - You can also use CloudWatch in hybrid cloud architectures by using the CloudWatch Agent or API to monitor your on-premises resources</br>
    Route 53(글로벌 DNS)과 Virtual Private Gateway(VPN/연결)는 온프레와 연동 가능하다.

    </details>

1. What costs are included when comparing AWS Total Cost of Ownership (TCO) with on-premises TCO?
    - A. Project management
    - B. Antivirus software licensing
    - C. Data center security
    - D. Software development

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://media.amazonwebservices.com/AWS_TCO_Web_Applications.pdf></br>
    온프레 데이터센터의 물리적 보안 비용은 TCO 비교 항목에 포함된다.

    </details>

1. Which AWS tools assist with estimating costs? (Select three.)
    - A. Detailed billing report
    - B. Cost allocation tags
    - C. AWS Simple Monthly Calculator
    - D. AWS Total Cost of Ownership (TCO) Calculator
    - E. Cost Eliminator

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BCD

    Explanation: <https://aws.amazon.com/premiumsupport/knowledge-center/estimating-aws-resource-costs/></br>
    태그·요금 계산기·TCO 계산기는 비용 추정에 사용된다.

    </details>

1. Which of the following Reserved Instance (RI) pricing models provides the highest average savings compared to On-Demand pricing?
    - A. One-year, No Upfront, Standard RI pricing
    - B. One-year, All Upfront, Convertible RI pricing
    - C. Three-year, All Upfront, Standard RI pricing
    - D. Three-year, No Upfront, Convertible RI pricing

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/></br>
    3년 All Upfront Standard가 가장 큰 할인율을 제공한다.

    </details>

1. Which AWS feature will reduce the customer's total cost of ownership (TCO)?
    - A. Shared responsibility security model
    - B. Single tenancy
    - C. Elastic computing
    - D. Encryption

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    탄력적 컴퓨팅은 자원 최적화로 비용 절감에 기여한다.

    </details>

1. Under the AWS shared responsibility model, which of the following activities are the customer's responsibility? (Select TWO.)
    - A. Patching operating system components for Amazon Relational Database Server (Amazon RDS)
    - B. Encrypting data on the client-side
    - C. Training the data center staff
    - D. Configuring Network Access Control Lists (ACL)
    - E. Maintaining environmental controls within a data center

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BD

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    클라이언트 측 암호화와 네트워크 ACL 설정은 고객의 책임이다.

    </details>

1. Which AWS services should be used for read/write of constantly changing data? (Select TWO.)
    - A. Amazon Glacier
    - B. Amazon RDS
    - C. AWS Snowball
    - D. Amazon Redshift
    - E. Amazon EFS

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BE</br>
    RDS(관계 DB)와 EFS(공유 파일시스템)는 빈번한 읽기/쓰기 작업에 적합하다.

    </details>

1. What is one of the advantages of the Amazon Relational Database Service (Amazon RDS)?
    - A. It simplifies relational database administration tasks.
    - B. It provides 99.99999999999% reliability and durability.
    - C. It automatically scales databases for loads.
    - D. It enabled users to dynamically adjust CPU and RAM resources.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:
    - In the main RDS page though, Lower administrative burden is listed as part of the benefits.
    - <https://aws.amazon.com/rds/></br>
    백업·패치·관리 작업을 AWS가 대행해 관리 부담을 줄여준다.

    </details>

1. A customer needs to run a MySQL database that easily scales.<br/>Which AWS service should they use?
    - A. Amazon Aurora
    - B. Amazon Redshift
    - C. Amazon DynamoDB
    - D. Amazon ElastiCache

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/rds/aurora/serverless/></br>
    Aurora는 MySQL 호환, 고성능·확장형 관계형 DB이다.

    </details>

1. Which of the following components of the AWS Global Infrastructure consists of one or more discrete data centers interconnected through low latency links?
    - A. Availability Zone
    - B. Edge location
    - C. Region
    - D. Private networking

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://docs.aws.amazon.com/whitepapers/latest/aws-overview/global-infrastructure.html></br>
    AZ는 여러 데이터센터(로컬)에 걸쳐 저지연 연결된 단위다.

    </details>

1. Which AWS IAM feature allows developers to access AWS services through the AWS CLI?
    - A. API keys
    - B. Access keys
    - C. User names/Passwords
    - D. SSH keys

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html></br>
    프로그래매틱 액세스는 Access Key ID + Secret Access Key로 한다.

    </details>

1. Which of the following is the customer's responsibility under the AWS shared responsibility model?
    - A. Patching underlying infrastructure
    - B. Physical security
    - C. Patching Amazon EC2 instances
    - D. Patching network infrastructure

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    EC2 인스턴스 OS·애플리케이션 패치는 고객이 수행해야 한다.

    </details>

1. Which of the following are features of Amazon CloudWatch Logs? (Select TWO.)
    - A. Summaries by Amazon Simple Notification Service (Amazon SNS)
    - B. Free Amazon Elasticsearch Service analytics
    - C. Provided at no charge
    - D. Real-time monitoring
    - E. Adjustable retention

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: DE</br>
    실시간 모니터링과 로그 보관 기간 조정 기능을 제공한다.

    </details>
