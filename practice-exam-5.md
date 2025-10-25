---
layout: exam
---

# Practice Exam 5

3. What features does AWS offer to help protect your data in the Cloud? (Choose TWO)
    - A. Access control.
    - B. Physical MFA devices.
    - C. Data encryption.
    - D. Unlimited storage.
    - E. Load balancing.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        암호화는 데이터를 보호하고, **접근 통제 (IAM)**는 무단 접근을 방지합니다.
    </details>

4. An AWS customer has used one Amazon Linux instance for 2 hours, 5 minutes and 9 seconds, and one CentOS instance for 4 hours, 23 minutes and 7 seconds. How much time will the customer be billed for?
    - A. 3 hours for the Linux instance and 5 hours for the CentOS instance.
    - B. 2 hours, 5 minutes and 9 seconds for the Linux instance and 4 hours, 23 minutes and 7 seconds for the CentOS instance.
    - C. 2 hours, 5 minutes and 9 seconds for the Linux instance and 5 hours for the CentOS instance.
    - D. 3 hours for the Linux instance and 4 hours, 23 minutes and 7 seconds for the CentOS instance.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Explanation:
      - Pricing is per instance-hour consumed for each instance, from the time an instance is launched until it is terminated or stopped.
      - Each partial instance-hour consumed will be billed per-second for Linux, Windows, Windows with SQL Enterprise, Windows with SQL Standard, and Windows with SQL Web Instances, and as a full hour for all other instance types.
      - Amazon Linux는 대부분의 경우 초 단위(Per-second) 청구됩니다. CentOS는 Red Hat Enterprise Linux(RHEL) 기반일 수 있으며, 일반적으로 최소 1시간 후 시간 단위 청구됩니다.
    </details>

6. Which methods can be used by customers to interact with AWS Identity and Access Management (IAM)? (Choose TWO)
    - A. AWS CLI.
    - B. AWS Security Groups.
    - C. AWS SDKs.
    - D. AWS Network Access Control Lists.
    - E. AWS CodeCommit.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        서비스는 콘솔, CLI, SDK (API 호출) 세 가지 방법으로 상호 작용합니다.
    </details>

7. Which of the following are types of AWS Identity and Access Management (IAM) identities? (Choose TWO)
    - A. AWS Resource Groups.
    - B. IAM Policies.
    - C. IAM Roles.
    - D. IAM Users.
    - E. AWS Organizations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
        IAM의 주요 ID는 사용자, 그룹, 역할입니다.
    </details>

8. Which of the following Amazon RDS features facilitates offloading of database read activity?
    - A. Database Snapshots.
    - B. Multi-AZ Deployments.
    - C. Automated Backups.
    - D. Read Replicas.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        읽기 전용 복제본을 생성하여 기본 인스턴스의 부하를 줄이고 읽기 성능을 높입니다.
    </details>

9. How does AWS notify customers about security and privacy events pertaining to AWS services?
    - A. Using the AWS ACM service.
    - B. Using Security Bulletins.
    - C. Using the AWS Management Console.
    - D. Using Compliance Resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        AWS는 공식적인 보안 게시판을 통해 중요한 보안 및 개인 정보 보호 업데이트를 공지합니다.
    </details>

15. Which of the following factors should be considered when determining the region in which AWS Resources will be deployed? (Choose TWO)
    - A. The AWS Region’s security level.
    - B. Data sovereignty.
    - C. Cost.
    - D. The planned number of VPCs.
    - E. Geographic proximity to the company's location.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        데이터 주권/레지던시와 **리전별 가격(비용)**은 리전을 선택하는 주요 고려 사항입니다.
    </details>

16. You are running a financial services web application on AWS. The application uses a MySQL database to store the data. Which of the following AWS services would improve the performance of your application by allowing you to retrieve information from fast in-memory caches?
    - A. Amazon EFS.
    - B. Amazon Neptune.
    - C. Amazon ElastiCache.
    - D. DAX.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        ElastiCache는 Redis 또는 Memcached를 사용하여 데이터베이스 부하를 줄이고 인메모리 캐싱을 통해 응답 속도를 향상시킵니다.
    </details>

18. The TCO gap between AWS infrastructure and traditional infrastructure has widened over the recent years. Which of the following could be the reason for that?
    - A. AWS helps customers invest more in capital expenditures.
    - B. AWS automates all infrastructure operations, so customers save more on human resources costs.
    - C. AWS continues to lower the cost of cloud computing for its customers.
    - D. AWS secures AWS resources at no additional charge.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        AWS의 규모의 경제 및 지속적인 가격 인하 정책이 TCO 격차 확대의 주요 원인입니다.
    </details>

20. Which of the following is a type of MFA device that customers can use to protect their AWS resources?
    - A. AWS CloudHSM.
    - B. U2F Security Key.
    - C. AWS Access Keys.
    - D. AWS Key Pair.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        U2F (Universal 2nd Factor) 보안 키는 AWS에서 지원하는 물리적 MFA 장치 유형입니다.
    </details>

22. Which of the following is NOT a factor when estimating the costs of Amazon EC2? (Choose TWO)
    - A. The amount of time the instances will be running.
    - B. Number of security groups.
    - C. Allocated Elastic IP Addresses.
    - D. Number of Hosted Zones.
    - E. Number of instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
        보안 그룹과 **호스팅 영역(Route 53)**은 직접적인 EC2 인스턴스 실행 비용에 포함되지 않으며, 별도의 AWS 서비스 비용입니다.
    </details>

24. A company is building an online cloud storage platform. They need a storage service that can scale capacity automatically, while minimizing cost. Which AWS storage service should the company use to meet these requirements?
    - A. Amazon Simple Storage Service.
    - B. Amazon Elastic Block Store.
    - C. Amazon Elastic Container Service.
    - D. AWS Storage Gateway.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        S3는 객체 스토리지로서 무제한의 용량을 제공하며 자동으로 확장됩니다.
    </details>

28. A user has opened a "Production System Down" support case to get help from AWS Support after a production system disruption. What is the expected response time for this type of support case?
    - A. 12 hours.
    - B. 15 minutes.
    - C. 24 hours.
    - D. One hour.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        Business Support 및 Enterprise Support 플랜에서 "Production System Down" 케이스는 보통 1시간 이내 응답을 목표로 합니다 (Enterprise의 Business-critical system down은 15분). 이 문제의 "Production System Down"은 일반적인 S1으로 간주하여 1시간입니다.
    </details>

32. Which of the following AWS offerings are serverless services? (Choose TWO)
    - A. Amazon EC2.
    - B. AWS Lambda.
    - C. Amazon DynamoDB.
    - D. Amazon EMR.
    - E. Amazon RDS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        Lambda와 DynamoDB는 서버의 관리, 확장, 패치를 AWS가 전적으로 책임지는 완전 관리형 서버리스 서비스입니다.
    </details>

39. When granting permissions to applications running on Amazon EC2 instances, which of the following is considered best practice?
    - A. Generate new IAM access keys every time you delegate permissions.
    - B. Store the required AWS credentials directly within the application code.
    - C. Use temporary security credentials (IAM roles) instead of long-term access keys.
    - D. Do nothing; Applications that run on Amazon EC2 instances do not need permission to interact with other AWS services or resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        EC2 인스턴스에는 IAM 역할을 사용하여 임시 자격 증명을 부여해야 하며, 장기 액세스 키를 저장하면 안 됩니다.
    </details>

40. Which of the following will help AWS customers save on costs when migrating their workloads to AWS?
    - A. Use servers instead of managed services.
    - B. Use existing third-party software licenses on AWS.
    - C. Migrate production workloads to AWS edge locations instead of AWS Regions.
    - D. Use AWS Outposts to run all workloads in a cost-optimized environment.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        **BYOL (Bring Your Own License)**을 통해 기존 라이선스를 AWS로 가져와 소프트웨어 비용을 절감할 수 있습니다.
    </details>

41. An organization has a legacy application designed using monolithic-based architecture. Which AWS Service can be used to decouple the components of the application?
    - A. Amazon SQS.
    - B. Virtual Private Gateway.
    - C. AWS Artifact.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        SQS는 **메시지 대기열(Queue)**을 제공하여 애플리케이션 구성 요소 간의 느슨한 결합을 가능하게 합니다.
    </details>

45. What should you do if you see resources, which you don’t remember creating, in the AWS Management Console? (Choose TWO)
    - A. Stop all running services and open an investigation.
    - B. Give your root account password to AWS Support so that they can assist in troubleshooting and securing the account.
    - C. Check the AWS CloudTrail logs and delete all IAM users that have access to your resources.
    - D. Open an investigation and delete any potentially compromised IAM users.
    - E. Change your AWS root account password and the passwords of any IAM users.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
        이는 보안 침해 가능성이 있으므로, 비밀번호를 변경하고 침해된 사용자 계정을 조사 및 삭제하여 추가 손상을 방지해야 합니다.
    </details>
