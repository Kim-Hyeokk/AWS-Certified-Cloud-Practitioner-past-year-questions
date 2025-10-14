---
layout: exam
---

# Practice Exam 2

6. Which of the following is NOT correct regarding Amazon EC2 On-demand instances?
    - A. You have to pay a start-up fee when launching a new instance for the first time.
    - B. The on-demand instances follow the AWS pay-as-you-go pricing model.
    - C. With on-demand instances, no longer-term commitments or upfront payments are needed.
    - D. When using on-demand Linux instances, you are charged per second based on an hourly rate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      온디맨드 인스턴스는 시작 비용이 없으며, 사용한 만큼만 지불합니다.
    </details>

7. A company has moved to AWS recently. Which of the following AWS Services will help ensure that they have the proper security settings? (Choose TWO)
    - A. AWS Trusted Advisor.
    - B. Amazon Inspector.
    - C. Amazon SNS.
    - D. Amazon CloudWatch.
    - E. Concierge Support Team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B</br>
      AWS Trusted Advisor는 모범 사례에 따른 보안 구성 검사를 제공하며, Amazon Inspector는 EC2 인스턴스에 배포된 애플리케이션의 보안 및 규정 준수를 자동으로 평가합니다.
    </details>

9. A company is introducing a new product to their customers, and is expecting a surge in traffic to their web application. As part of their Enterprise Support plan, which of the following provides the company with architectural and scaling guidance?
    - A. AWS Knowledge Center.
    - B. AWS Health Dashboard.
    - C. Infrastructure Event Management.
    - D. AWS Support Concierge Service.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      **Infrastructure Event Management (IEM)**는 Enterprise 및 Enterprise On-Ramp Support 플랜의 일부로 제공되며, 출시, 마이그레이션 등 주요 이벤트 전에 AWS 엔지니어가 아키텍처 및 운영 준비 상태를 검토하고 지침을 제공합니다.
    </details>

12. According to the AWS Acceptable Use Policy, which of the following statements is true regarding penetration testing of EC2 instances?
    - A. Penetration testing is not allowed in AWS.
    - B. Penetration testing is performed automatically by AWS to determine vulnerabilities in your AWS infrastructure.
    - C. Penetration testing can be performed by the customer on their own instances without prior authorization from AWS.
    - D. The AWS customers are only allowed to perform penetration testing on services managed by AWS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
       EC2 인스턴스, RDS, CloudFront 등 특정 서비스에 대한 침투 테스트는 AWS의 사전 승인 없이 고객이 자체적으로 수행할 수 있습니다. (단, AWS가 명시적으로 허용하지 않는 다른 서비스에 대한 테스트는 여전히 금지됩니다.)
    </details>

14. The principle “design for failure and nothing will fail” is very important when designing your AWS Cloud architecture. Which of the following would help adhere to this principle? (Choose TWO)
    - A. Multi-factor authentication.
    - B. Availability Zones.
    - C. Elastic Load Balancing.
    - D. Penetration testing.
    - E. Vertical Scaling.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      **Elastic Load Balancing (ELB)**은 트래픽을 여러 인스턴스/AZ에 분산하고, 비정상 인스턴스로의 트래픽을 자동으로 라우팅하지 않아 내결함성을 제공합니다.
    </details>

16. According to the AWS Shared responsibility model, which of the following are the responsibility of the customer? (Choose TWO)
    - A. Managing environmental events of AWS data centers.
    - B. Protecting the confidentiality of data in transit in Amazon S3.
    - C. Controlling physical access to AWS Regions.
    - D. Ensuring that the underlying EC2 host is configured properly.
    - E. Patching applications installed on Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      고객은 '클라우드 내의 보안'을 책임지며, 여기에는 고객 데이터의 암호화(B)와 EC2 인스턴스에 설치된 운영체제 및 애플리케이션의 패치 관리(E)가 포함됩니다.
    </details>

19. Which of the following is equivalent to a user name and password and is used to authenticate your programmatic access to AWS services and APIs?
    - A. Instance Password.
    - B. Key pairs.
    - C. Access Keys.
    - D. MFA.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      액세스 키는 AWS CLI, SDK 및 API 호출에 사용되는 보안 자격 증명으로, 액세스 키 ID(사용자 이름)와 보안 액세스 키(암호)로 구성됩니다.
    </details>

20. What does Amazon ElastiCache provide?
    - A. In-memory caching for read-heavy applications.
    - B. An Ehcache compatible in-memory data store.
    - C. An online software store that allows Customers to launch pre-configured software with just few clicks.
    - D. A domain name system in the cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      Amazon ElastiCache는 관리형 인메모리 캐싱 서비스로, 데이터베이스 및 애플리케이션 계층의 지연 시간을 줄여 성능을 향상시킵니다.
    </details>

22. Which of the following EC2 instance purchasing options supports the Bring Your Own License (BYOL) model for almost every BYOL scenario?
    - A. Dedicated Instances.
    - B. Dedicated Hosts.
    - C. On-demand Instances.
    - D. Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      Dedicated Hosts는 고객의 계정에 전용으로 할당된 물리적 서버로, 기존 서버별/소켓별 라이선스를 가져와 사용할 수 있는 통제권을 제공합니다.
    </details>

24. Which of the following are important design principles you should adopt when designing systems on AWS? (Choose TWO)
    - A. Always use Global Services in your architecture rather than Regional Services.
    - B. Always choose to pay as you go.
    - C. Treat servers as fixed resources.
    - D. Automate wherever possible.
    - E. Remove single points of failure.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E</br>
      AWS의 핵심 설계 원칙은 **단일 장애 지점을 제거(고가용성)**하고, 자동화를 통해 변경 및 실험을 용이하게 하는 것입니다.
    </details>

29. Based on the AWS Shared Responsibility Model, which of the following are the sole responsibility of AWS? (Choose TWO)
    - A. Monitoring network performance.
    - B. Installing software on EC2 instances.
    - C. Creating hypervisors.
    - D. Configuring Access Control Lists (ACLs).
    - E. Hardware maintenance.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E
      </br>
      AWS는 '클라우드의 보안'을 책임지며, 여기에는 컴퓨팅, 스토리지, 데이터베이스 및 네트워킹을 실행하는 서비스의 기본 인프라(하드웨어, 소프트웨어, 네트워킹 및 시설)가 포함됩니다. 하드웨어 유지 관리 및 하이퍼바이저는 AWS의 책임입니다.
    </details>

30. What is the AWS service that provides you the highest level of control over the underlying virtual infrastructure?
    - A. Amazon Redshift.
    - B. Amazon DynamoDB.
    - C. Amazon EC2.
    - D. Amazon RDS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      Amazon EC2는 IaaS(Infrastructure as a Service)로, 고객에게 운영 체제 및 애플리케이션 소프트웨어 설치 및 패치 적용을 포함하여 인스턴스에 대한 가장 높은 수준의 제어를 제공합니다.
    </details>

33. What are two advantages of using Cloud Computing over using traditional data centers? (Choose TWO)
    - A. Reserved Compute capacity.
    - B. Eliminating Single Points of Failure (SPOFs).
    - C. Distributed infrastructure.
    - D. Virtualized compute resources.
    - E. Dedicated hosting.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      클라우드의 주요 이점은 여러 가용 영역과 리전에 걸쳐 분산된 인프라를 활용하여 단일 장애 지점(SPOFs)을 제거함으로써 고가용성을 달성하는 것입니다.
    </details>


35. Which statement best describes the operational excellence pillar of the AWS Well-Architected Framework?
    - A. The ability of a system to recover gracefully from failure.
    - B. The efficient use of computing resources to meet requirements.
    - C. The ability to monitor systems and improve supporting processes and procedures.
    - D. The ability to manage datacenter operations more efficiently.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      운영 우수성(Operational Excellence) 기둥은 코드를 통한 인프라 운영, 문서화, 모니터링, 변경 사항에 대한 응답을 포함하여 시스템 운영 및 지원 프로세스를 개선하는 데 중점을 둡니다.
    </details>

39. Which of the following services will help businesses ensure compliance in AWS?
    - A. CloudFront.
    - B. CloudEndure Migration.
    - C. CloudWatch.
    - D. CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      AWS CloudTrail은 AWS 계정의 거버넌스, 규정 준수 및 감사 요구 사항을 지원하며, 모든 API 활동을 기록하여 누가, 언제, 어디서 무엇을 했는지 파악할 수 있도록 합니다.
    </details>

41. What are the AWS services/features that can help you maintain a highly available and fault-tolerant architecture in AWS? (Choose TWO)
    - A. AWS Direct Connect.
    - B. Amazon EC2 Auto Scaling.
    - C. Elastic Load Balancer.
    - D. CloudFormation.
    - E. Network ACLs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      ELB는 트래픽을 정상 인스턴스로 분산하고, Auto Scaling은 비정상 인스턴스를 자동으로 교체하고 수요에 따라 용량을 조정하여 고가용성과 내결함성을 제공합니다.
    </details>

45. Which AWS services can be used to improve the performance of a global application and reduce latency for its users? (Choose TWO)
    - A. AWS KMS.
    - B. AWS Global accelerator.
    - C. AWS Direct Connect.
    - D. AWS Glue.
    - E. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      Amazon CloudFront와 AWS Global Accelerator는 모두 AWS의 글로벌 네트워크 및 엣지 로케이션을 활용하여 트래픽을 최종 사용자에게 더 가깝게 라우팅하고 콘텐츠를 캐시하여 글로벌 애플리케이션의 성능을 개선하고 지연 시간을 줄입니다.
    </details>

48. A company has created a solution that helps AWS customers improve their architectures on AWS. Which AWS program may support this company?
    - A. APN Consulting Partners.
    - B. AWS TAM.
    - C. APN Technology Partners.
    - D. AWS Professional Services.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      APN 컨설팅 파트너는 고객에게 AWS 워크로드에 대한 컨설팅 및 관리 서비스를 제공하고 고객이 솔루션을 설계하고 구축하는 데 도움을 줍니다. 기술 파트너는 고객에게 판매할 수 있는 소프트웨어 제품을 개발합니다.
    </details>