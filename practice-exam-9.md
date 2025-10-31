---
layout: exam
---

# Practice Exam 9

7. Which AWS service or feature can be used to monitor CPU usage?
    - A. AWS CloudTrail.
    - B. VPC Flow Logs.
    - C. Amazon CloudWatch.
    - D. AWS Config.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        CloudWatch는 AWS 리소스에 대한 메트릭을 수집하고 모니터링합니다 (CPU 사용률 포함).
    </details>

12. Which of the following are pillars of the AWS Well-Architected Framework? (Select TWO)
    - A. Multiple Availability Zones.
    - B. Performance efficiency.
    - C. Security.
    - D. Encryption usage.
    - E. High availability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        5가지 기둥: 운영 우수성, 보안, 안정성, 성능 효율성, 비용 최적화입니다.
    </details>

13. Which AWS service identifies security groups that allow unrestricted access to a user’s AWS resources?
    - A. AWS Trusted Advisor.
    - B. Amazon Inspector.
    - C. Amazon CloudWatch.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        Trusted Advisor는 보안 검사를 포함하여 AWS 환경을 모범 사례에 대해 평가합니다.
    </details>

16. A company has deployed several relational databases on Amazon EC2 instances. Every month the database software vendor releases new security patches that need to be applied to the databases. What is the MOST efficient way to apply the security patches?
    - A. Connect to each database instance on a monthly basis and download and apply the necessary security patches from the vendor.
    - B. Enable automate patching for the instances using the Amazon RDS console.
    - C. In AWS Config. configure a rule for the instances and the required patch level.
    - D. Use AWS Systems Manager to automate database patching according to a schedule.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        Systems Manager Patch Manager는 EC2 인스턴스에 대한 OS 및 소프트웨어 패치를 자동화하고 관리합니다.
    </details>

18. Which AWS feature will reduce the customer’s total cost of ownership (TCO)?
    - A. Shared responsibility security model.
    - B. Single tenancy.
    - C. Elastic computing.
    - D. Encryption.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        탄력성을 통해 필요한 만큼만 리소스를 사용하고 비용을 절감하여 TCO를 낮춥니다.
    </details>

23. Under the shared responsibility model, which of the following is a shared control between a customer and AWS?
    - A. Physical controls.
    - B. Patch management.
    - C. Zone security.
    - D. Data center auditing.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        OS/DB 패치는 AWS가 관리형 서비스(RDS)의 기반 OS에 대해 책임지고, 고객은 EC2의 게스트 OS에 대해 책임지므로 공유됩니다.
    </details>

24. Which AWS service is used to pay AWS bills, and monitor usage and budget costs?
    - A. AWS Billing and Cost Management.
    - B. Consolidated billing.
    - C. Amazon CloudWatch.
    - D. Amazon QuickSight.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        이 콘솔은 AWS 청구 및 비용 관련 기능의 중앙 허브입니다.
    </details>

28. Which of the following services will automatically scale with an expected increase in web traffic?
    - A. AWS CodePipeline.
    - B. Elastic Load Balancing.
    - C. Amazon EBS.
    - D. AWS Direct Connect.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        ELB는 자동으로 확장하여 증가된 트래픽을 처리하고 EC2 인스턴스 간에 분산합니다.
    </details>

31. Which AWS service or feature can enhance network security by blocking requests from a particular network for a web application on AWS? (Select TWO)
    - A. AWS WAF.
    - B. AWS Trusted Advisor.
    - C. AWS Direct Connect.
    - D. AWS Organizations.
    - E. Network ACLs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
        WAF는 **L7(애플리케이션 계층)**에서, 네트워크 ACL은 **L4(네트워크 계층)**에서 트래픽을 차단할 수 있습니다.
    </details>

35. The financial benefits of using AWS are: (Select TWO)
    - A. Reduced Total Cost of Ownership (TCO).
    - B. Increased capital expenditure (capex).
    - C. Reduced operational expenditure ( opex ).
    - D. Deferred payment plans for startups.
    - E. Business credit lines for startups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        클라우드는 **선행 자본 지출(Capex)**을 줄이고 **운영 비용(Opex)**으로 전환하여 TCO를 절감합니다.
    </details>
