---
layout: exam
---

# Practice Exam 11

2. Which options does AWS make available for customers who want to learn about security in the cloud in an instructor-led setting? (Select TWO)
    - A. AWS Trusted Advisor.
    - B. AWS Online Tech Talks.
    - C. AWS Blog.
    - D. AWS Forums.
    - E. AWS Classroom Training.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      A, C, D 옵션은 자기주도적 학습(Self-paced) 또는 참조용 자료에 해당합니다.
    </details>

3. Which of the following will enhance the security of access to the AWS Management Console’? (Select TWO)
    - A. AWS Secrets Manager.
    - B. AWS Certificate Manager.
    - C. AWS Multi-Factor Authentication (AWS MFA).
    - D. Security groups.
    - E. Password policies.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E</br>
      AWS Secrets Manager (A) → 애플리케이션과 서비스 간 비밀번호/키 관리용</br>
      AWS Certificate Manager (B) → SSL/TLS 인증서 관리용</br>
      Security groups (D) → 네트워크 접근 제어용</br>
    </details>

5. For which auditing process does AWS have sole responsibility?
    - A. AWS IAM policies.
    - B. Physical security.
    - C. Amazon S3 bucket policies.
    - D. AWS CloudTrail Logs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      **물리적 보안(Physical security)**은 고객이 직접 관여할 수 없고, AWS가 단독으로 책임집니다.
    </details>

10. Which is the MINIMUM AWS Support plan that allows for one-hour target response time for support cases?
    - A. Enterprise.
    - B. Business.
    - C. Developer
    - D. Basic

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      응답 시간 1시간 이내 지원을 제공하는 최소 AWS Support 플랜은 Business Support이다.
    </details>

11. What is the lowest-cost, durable storage option for retaining database backups for immediate retrieval?
    - A. Amazon S3.
    - B. Amazon Glacier.
    - C. Amazon EBS.
    - D. Amazon EC2 Instance Store.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      Glacier는 장기 아카이브용, EBS/Instance Store는 블록 스토리지로 사용 목적이 다르다.
    </details>

14. If a customer needs to audit the change management of AWS resources, which of the following AWS services should the customer use?
    - A. AWS Config.
    - B. AWS Trusted Advisor.
    - C. Amazon CloudWatch.
    - D. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      AWS Config는 AWS 자원 변경 내역을 추적하고 감사할 수 있어, **변경 관리(change management)**를 검증하는 서비스다.</br>
      CloudWatch는 모니터링, Inspector는 취약점 점검용이다.
    </details>

15. How does AWS Trusted Advisor provide guidance to users of the AWS Cloud? (Select TWO)
    - A. It identifies software vulnerabilities in applications running on AWS.
    - B. It provides a list of cost optimization recommendations based on current AWS usage.
    - C. It detects potential security vulnerabilities caused by permissions settings on account resources.
    - D. It automatically corrects potential security issues caused by permissions settings on account resources.
    - E. It provides proactive alerting whenever an Amazon EC2 instance has been compromised.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      현재 사용량 기반 비용 최적화 권고(B)</br>
      권한 설정으로 인한 보안 취약점 감지(C)
    </details>

18. Under the shared responsibility model, which of the following is the customer responsible for?
    - A. Ensuring that disk drives are wiped after use.
    - B. Ensuring that firmware is updated on hardware devices.
    - C. Ensuring that data is encrypted at rest.
    - D. Ensuring that network cables are category six or higher.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      공유 책임 모델에서 고객은 데이터 암호화, 접근 제어 등 클라우드 내 데이터 보호를 책임진다.
    </details>

19. Which AWS service provides a simple and scalable shared file storage solution for use with Linux-based AWS and on-premises servers?
    - A. Amazon S3.
    - B. Amazon Glacier.
    - C. Amazon EBS.
    - D. Amazon EFS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      Linux 기반 AWS와 온프레미스 서버에서 사용할 수 있는 공유 파일 스토리지는 Amazon EFS이다.
    </details>

21. Which of the following is a shared control between the customer and AWS?
    - A. Providing a key for Amazon S3 client-side encryption.
    - B. Configuration of an Amazon EC2 instance.
    - C. Environmental controls of physical AWS data centers.
    - D. Awareness.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      공유 책임 모델에서 Awareness는 고객과 AWS가 공동으로 관리하는 영역이다.
    </details>

23. Which of the following is an advantage of consolidated billing on AWS?
    - A. Volume pricing qualification.
    - B. Shared access permissions.
    - C. Multiple bills per account.
    - D. Eliminates the need for tagging.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      Consolidated Billing의 장점은 여러 계정 사용량을 합산하여 볼륨 할인을 받을 수 있다는 점이다.
    </details>

24. Which services are parts of the AWS serverless platform?
    - A. Amazon EC2, Amazon S3, Amazon Athena.
    - B. Amazon Kinesis, Amazon SQS, Amazon EMR.
    - C. AWS Step Functions, Amazon DynamoDB, Amazon SNS.
    - D. Amazon Athena, Amazon Cognito, Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      AWS 서버리스 플랫폼 서비스에는 Step Functions, DynamoDB, SNS 등이 포함된다.
    </details>

25. Which of the following Amazon EC2 pricing models allow customers to use existing server-bound software licenses?
    - A. Spot Instances.
    - B. Reserved Instances.
    - C. Dedicated Hosts.
    - D. On-Demand Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      Dedicated Hosts를 사용하면 기존 서버 라이선스를 AWS에서 그대로 사용할 수 있다.
    </details>

26. Which of the following security measures protect access to an AWS account? (Select TWO)
    - A. Enable AWS CloudTrail.
    - B. Grant least privilege access to IAM users.
    - C. Create one IAM user and share with many developers and users.
    - D. Enable Amazon CloudFront.
    - E. Activate multi-factor authentication (MFA) for privileged users.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      최소 권한 원칙 적용(B)</br>
      중요 사용자에 대한 MFA 활성화(E)
    </details>

28. What is an advantage of deploying an application across multiple Availability Zones?
    - A. There is a lower risk of service failure if a natural disaster causes a service disruption in a given AWS Region.
    - B. The application will have higher availability because it can withstand a service disruption in one Availability Zone.
    - C. There will be better coverage as Availability Zones are geographical^ distant and can serve a wider area.
    - D. There will be decreased application latency that will improve the user experience.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      여러 Availability Zone(AZ)에 애플리케이션 배포 시, 단일 AZ 장애에도 애플리케이션이 계속 동작해 가용성이 향상된다.</br>
      자연 재해로 인한 전체 리전 영향은 AZ 분산만으로는 보호되지 않는다.
    </details>

29. A customer needs to run a MySQL database that easily scales. Which AWS service should they use?
    - A. Amazon Aurora.
    - B. Amazon Redshift.
    - C. Amazon DynamoDB.
    - D. Amazon ElastiCache.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      MySQL과 호환되며 쉽게 확장 가능한 데이터베이스는 Amazon Aurora이다.
    </details>

33. When performing a cost analysis that supports physical isolation of a customer workload, which compute hosting model should be accounted for in the Total Cost of Ownership (TCO)?
    - A. Dedicated Hosts
    - B. Reserved Instances
    - C. On-Demand Instances
    - D. No Upfront Reserved Instances

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      물리적 격리(Dedicated Hosts) 환경은 비용 분석 시 TCO에 포함해야 한다.
    </details>

34. Which AWS service should be used for long-term, low-cost storage of data backups?
    - A. Amazon RDS.
    - B. Amazon Glacier.
    - C. AWS Snowball.
    - D. AWS EBS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      장기적 저비용 백업 스토리지로 Amazon Glacier가 적합하다.
    </details>

37. Which of the following AWS services can be used to serve large amounts of online video content with the lowest possible latency? (Select TWO)
    - A. appGateway.
    - B. Amazon S3.
    - C. Amazon Elastic File System (EFS).
    - D. Amazon Glacier.
    - E. Amazom CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      대량 온라인 영상 서비스를 **최저 지연(Low latency)**으로 제공하려면</br>
      객체 스토리지 S3</br>
      콘텐츠 배포 CDN CloudFront
    </details>

38. What can AWS edge locations be used for? (Select TWO)
    - A. Hosting applications.
    - B. Delivering content closer to users.
    - C. Running NoSQL database caching services.
    - D. Reducing traffic on the server by caching responses.
    - E. Sending notification messages to end users.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D</br>
      사용자에게 가까운 위치에서 콘텐츠 전달(B)</br>
      서버 부하 감소를 위한 캐싱(D)
    </details>

39. A company is planning to migrate from on-premises to the AWS Cloud. When AWS tool or service provides detailed reports on estimated cost savings after migration?
    - A. AWS Total Cost of Ownership (TCO) Calculator.
    - B. Cost Explorer.
    - C. AWS Budgets.
    - D. AWS Migration Hub.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      AWS TCO Calculator는 클라우드 이전 후 비용 절감 추정 보고서를 제공한다.
    </details>

40. Which AWS service provides a customized view of the health of specific AWS services that power a customer’s workloads running on AWS?
    - A. AWS Service Health Dashboard.
    - B. AWS X-Ray.
    - C. AWS Personal Health Dashboard.
    - D. Amazon CloudWatch.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      Service Health Dashboard는 전체 서비스 상태, X-Ray는 트레이싱, CloudWatch는 모니터링용이다.
    </details>

44. Which activity is a customer responsibility in the AWS Cloud according to the AWS shared responsibility model?
    - A. Ensuring network connectivity from AWS to the internet.
    - B. Patching and fixing flaws within the AWS Cloud infrastructure.
    - C. Ensuring the physical security of cloud data centers.
    - D. Ensuring Amazon EBS volumes are backed up.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      고객 책임 영역: EBS 볼륨 백업 등 클라우드 내 자원 관리
    </details>

47. Which AWS service provides alerts when an AWS event may impact a company’s AWS resources?
    - A. AWS Personal Health Dashboard.
    - B. AWS Service Health Dashboard.
    - C. AWS Trusted Advisor.
    - D. AWS Infrastructure Event Management.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      Service Health Dashboard는 전체 서비스 상태를 보여준다.
    </details>