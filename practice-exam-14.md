---
layout: exam
---

# Practice Exam 14

9. Which of the following AWS services can be used to serve large amounts of online video content with the lowest possible latency? (Select TWO.)
    - A. AWS Storage Gateway
    - B. Amazon S3
    - C. Amazon Elastic File System (EFS)
    - D. Amazon Glacier
    - E. Amazon CloudFront

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BE

    Explanation:
    - <https://aws.amazon.com/getting-started/tutorials/deliver-content-faster/>
    - <https://aws.amazon.com/cloudfront/></br>
    S3에 콘텐츠 저장 + CloudFront로 엣지에서 전달하면 지연 최소화 가능.

    </details>

10. Web servers running on Amazon EC2 access a legacy application running in a corporate data center. <br/> What term would describe this model?
    - A. Cloud-native
    - B. Partner network
    - C. Hybrid architecture
    - D. Infrastructure as a service

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/enterprise/hybrid/></br>
    클라우드와 온프레가 혼합된 구조는 하이브리드 아키텍처라 부른다.

    </details>

14. Which of the following security-related services does AWS offer? (Select TWO.)
    - A. Multi-factor authentication physical tokens
    - B. AWS Trusted Advisor security checks
    - C. Data encryption
    - D. Automated penetration testing
    - E. Amazon S3 copyrighted content detection

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BC

    Explanation:
    - Penetration testing is not correct, because it can be done by customers on their own resources.</br>
    Trusted Advisor는 보안 점검을 제공하고, AWS는 암호화 기능(키·TLS 등)을 제공한다.

    </details>

18. Which AWS service should be used for long-term, low-cost storage of data backups?
    - A. Amazon RDS
    - B. Amazon Glacier
    - C. AWS Snowball
    - D. AWS EBS

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - Amazon S3 Glacier is a secure, durable, and low-cost storage class of S3 for data archiving and long-term backup. Customers can store large or small amounts of data for as little as $0.004 per gigabyte per month.
    - The S3 Glacier storage class is ideal for archives where data is regularly retrieved and some of the data may be needed in minutes.
    - Amazon RDS is a relational database service that hosts databases. It helps you create and manage databases.
    - Amazon Snowball is a petabyte-scale data transfer service that provides cost efficient data transfer to AWS from tamper proof physical devices. Similarly, Elastic block storage offers persistent block storage volumes for EC2 instances.

    Reference: <https://aws.amazon.com/backup-restore/services/></br>
    Glacier(또는 S3 Glacier)는 장기 아카이브용 저비용 스토리지다.

    </details>

28. Which Amazon EC2 pricing model adjusts based on supply and demand of EC2 instances?
    - A. On-Demand Instances
    - B. Reserved Instances
    - C. Spot Instances
    - D. Convertible Reserved Instances

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - In the new model, the Spot prices are more predictable, updated less frequently, and are determined by supply and demand for Amazon EC2 spare capacity, not bid prices.

    Reference: <https://aws.amazon.com/blogs/compute/new-amazon-ec2-spot-pricing/></br>
    Spot 가격은 여유 용량에 따라 변동하므로 공급·수요 기반이다.

    </details>

34. Which of the following steps should be taken by a customer when conducting penetration testing on AWS?
    - A. Conduct penetration testing using Amazon Inspector, and then notify AWS support.
    - B. Request and wait for approval from the customer's internal security team, and then conduct testing.
    - C. Notify AWS support, and then conduct testing immediately.
    - D. Request and wait for approval from AWS support, and then conduct testing.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - AWS customers are welcome to carry out security assessments or penetration tests against their AWS infrastructure without prior approval for 8 services.

    Reference: <https://aws.amazon.com/security/penetration-testing/></br>
    특정 범위의 침투테스트는 사전 승인 절차가 필요하므로 AWS에 요청하고 승인을 받아야 한다(정책 확인 필수).

    </details>

37. Which AWS Cost Management tool allows you to view the most granular data about your AWS bill?
    - A. AWS Cost Explorer
    - B. AWS Budgets
    - C. AWS Cost and Usage report
    - D. AWS Billing dashboard

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - The Cost & Usage Report is your one-stop-shop for accessing the most granular data about your AWS costs and usage.
    - You can also load your cost and usage information into Amazon Athena, Amazon Redshift, AWS QuickSight, or a tool of your choice.

    Reference: <https://aws.amazon.com/aws-cost-management/></br>
    Cost & Usage Report는 가장 상세한 비용·사용량 데이터를 제공한다.

    </details>

41. Which service provides a hybrid storage service that enables on-premises applications to seamlessly use cloud storage?
    - A. Amazon Glacier
    - B. AWS Snowball
    - C. AWS Storage Gateway
    - D. Amazon Elastic Block Storage (Amazon EBS)

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases.
    - These include moving tape backups to the cloud, reducing on-premises storage with cloud-backed file shares, providing low latency access to data in AWS for on- premises applications, as well as various migration, archiving,
    processing, and disaster recovery use cases.

    Reference: <https://aws.amazon.com/storagegateway/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc></br>
    Storage Gateway는 온프레와 클라우드 간 파일/테이프/블록 워크로드를 연결한다.

    </details>

45. Amazon Relational Database Service (Amazon RDS) offers which of the following benefits over traditional database management?
    - A. AWS manages the data stored in Amazon RDS tables.
    - B. AWS manages the maintenance of the operating system.
    - C. AWS automatically scales up instance types on demand.
    - D. AWS manages the database type.
    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B</br>
    RDS는 DB 엔진 패치·백업 등 운영 작업을 대신해 관리 부담을 줄여준다.

    </details>

46. Which service is best for storing common database query results, which helps to alleviate database access load?
    - A. Amazon Machine Learning
    - B. Amazon SQS
    - C. Amazon ElastiCache
    - D. Amazon EC2 Instance Store

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - Amazon ElastiCache for Redis is a great choice for implementing a highly available, distributed, and secure in-memory cache to decrease access latency, increase throughput, and ease the load off your relational or NoSQL databases and applications.
    - ElastiCache can serve frequently requested items at sub- millisecond response times, and enables you to easily scale for higher loads without growing the costlier backend databases.
    - Database query results caching, persistent session caching, and full-page caching are all popular examples of caching with ElastiCache for Redis.

    Reference: <https://aws.amazon.com/products/databases/real-time-apps-elasticache-for-redis/></br>
    ElastiCache(Redis/Memcached)는 인메모리 캐시로 DB 부하를 줄이고 응답 속도를 개선한다.

    </details>