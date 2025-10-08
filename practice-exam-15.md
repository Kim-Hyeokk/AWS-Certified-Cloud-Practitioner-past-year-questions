---
layout: exam
---

# Practice Exam 15

3. Which of the following common IT tasks can AWS cover to free up company IT resources? (Select TWO.)
    - A. Patching databases software
    - B. Testing application releases
    - C. Backing up databases
    - D. Creating database schema
    - E. Running penetration tests

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC</br>
    AWS는 관리형 서비스 제공으로 DB 패치(A)와 백업(C) 같은 반복적 IT 업무를 자동화할 수 있어 기업 IT 팀의 부담을 줄임.

    </details>

6. Which is the minimum AWS Support plan that includes Infrastructure Event Management without additional costs?
    - A. Enterprise
    - B. Business
    - C. Developer
    - D. Basic

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation: <https://aws.amazon.com/premiumsupport/plans/></br>
    엔터프라이즈 플랜은 추가 비용 없이 인프라 이벤트 관리를 지원.

    </details>

17. Under the shared responsibility model, which of the following is a shared control between a customer and AWS?
    - A. Physical controls
    - B. Patch management
    - C. Zone security
    - D. Data center auditing

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:

    - Shared Controls Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives.
    - In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services.
    - Examples include:
    - Patch Management AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.
    - Configuration Management AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.
    - Awareness & Training AWS trains AWS employees, but a customer must train their own employees.
    - Customer Specific Controls which are solely the responsibility of the customer based on the application they are deploying within AWS services.
    - Service and Communications Protection or Zone Security which may require a customer to route or zone data within specific security environments.

    Reference: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    AWS는 인프라 패치, 고객은 OS/앱 패치 관리, 일부 영역은 공유 책임.

    </details>

20. Which AWS services are defined as global instead of regional? (Select TWO.)
    - A. Amazon Route 53
    - B. Amazon EC2
    - C. Amazon S3
    - D. Amazon CloudFront
    - E. Amazon DynamoDB

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation: <http://jayendrapatil.com/aws-global-vs-regional-vs-az-resources/></br>
    일부 AWS 서비스는 전 세계 단일 관리(global)이며, 대부분 리전 단위로 운영되지 않음.

    </details>

22. Under the shared responsibility model, which of the following tasks are the responsibility of the AWS customer? (Select TWO.)
    - A. Ensuring that application data is encrypted at rest
    - B. Ensuring that AWS NTP servers are set to the correct time
    - C. Ensuring that users have received security training in the use of AWS services
    - D. Ensuring that access to data centers is restricted
    - E. Ensuring that hardware is disposed of properly

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    애플리케이션 데이터 암호화(A)와 사용자 보안 교육(C)은 고객 책임.

    </details>

27. Which AWS service allows companies to connect an Amazon VPC to an on-premises data center? (Select TWO)
    - A. AWS VPN
    - B. Amazon Redshift
    - C. API Gateway
    - D. Amazon Direct Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A, D

    Explanation:

    - AWS Direct Connect enables you to securely connect your AWS environment to your on-premises data center or office location over a standard 1 gigabit or 10 gigabit Ethernet fiber-optic connection.
    - AWS Direct Connect offers dedicated high speed, low latency connection, which bypasses internet service providers in your
    network path.
    - An AWS Direct Connect location provides access to Amazon Web Services in the region it is associated with, as well as access to other US regions.
    - AWS Direct Connect allows you to logically partition the fiber-optic connections into multiple logical connections called Virtual Local Area Networks (VLAN).
    - You can take advantage of these logical connections to improve security, differentiate traffic, and achieve compliance requirements.

    Reference: <https://aws.amazon.com/getting-started/projects/connect-data-center-to-aws/></br>
    VPN과 Direct Connect로 안전하게 사내와 AWS VPC 연결 가능.

    </details>

29. Which AWS service provides alerts when an AWS event may impact a company's AWS resources?
    - A. AWS Personal Health Dashboard
    - B. AWS Service Health Dashboard
    - C. AWS Trusted Advisor
    - D. AWS Infrastructure Event Management

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: A

    Explanation:

    - AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you.
    - While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view into the performance and availability of the AWS services underlying your AWS resources.

    Reference: <https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/></br>
    개인화된 리소스 영향 알림과 대응 가이드를 제공.

    </details>

30. Which of the following are categories of AWS Trusted Advisor? (Select TWO.)
    - A. Fault Tolerance
    - B. Instance Usage
    - C. Infrastructure
    - D. Performance
    - E. Storage Capacity

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AD

    Explanation:

    - Like your customized cloud expert, AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: cost optimization, performance, security, fault tolerance and service limits.

    Reference: <https://aws.amazon.com/premiumsupport/technology/trusted-advisor/></br>
    비용, 성능, 보안, 내결함성, 서비스 한도 등 최적화 권고 제공.

    </details>

32. A company will be moving from an on-premises data center to the AWS Cloud. <br/> What would be one financial difference after the move?
    - A. Moving from variable operational expense (opex) to upfront capital expense (capex).
    - B. Moving from upfront capital expense (capex) to variable capital expense (capex).
    - C. Moving from upfront capital expense (capex) to variable operational expense (opex).
    - D. Elimination of upfront capital expense (capex) and elimination of variable operational expense (opex)

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C</br>
    초기 자본 지출(capex)을 줄이고 사용량 기반 운영비용(opex)으로 전환.

    </details>

34. Which is the MINIMUM AWS Support plan that provides technical support through phone calls?
    - A. Enterprise
    - B. Business
    - C. Developer
    - D. Basic

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:

    <https://aws.amazon.com/premiumsupport/plans/></br>
    Developer Plan은 채팅만, Business Plan 이상에서 전화 지원 제공

    </details>

38. Which of the following can a customer use to enable single sign-on (SSO) to the AWS Console?
    - A. Amazon Connect
    - B. AWS Directory Service
    - C. Amazon Pinpoint
    - D. Amazon Rekognition

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:

    - Single sign-on only works when used on a computer that is joined to the AWS Directory Service directory.
    - It cannot be used on computers that are not joined to the directory.

    Reference: <https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_single_sign_on.html></br>
    디렉터리에 조인된 PC에서만 SSO 사용 가능.

    </details>

40. Which of the following benefits does the AWS Compliance program provide to AWS customers? (Choose two.)
    - A. It verifies that hosted workloads are automatically compliant with the controls of supported compliance frameworks.
    - B. AWS is responsible for the maintenance of common compliance framework documentation.
    - C. It assures customers that AWS is maintaining physical security and data protection.
    - D. It ensures the use of compliance frameworks that are being used by other cloud providers.
    - E. It will adopt new compliance frameworks as they become relevant to customer workloads.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation: <https://d0.awsstatic.com/whitepapers/compliance/AWS_Risk_and_Compliance_Whitepaper.pdf></br>
    호스팅 워크로드 자동 준수 검증(A), 공통 컴플라이언스 문서 유지(B) 제공.

    </details>

42. As part of the AWS shared responsibility model, which of the following operational controls do users fully inherit from AWS?
    - A. Security management of data center
    - B. Patch management
    - C. Configuration management
    - D. User and access management

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>\
    사용자 및 접근 관리(User & Access Management)는 AWS가 제공.

    </details>

43. When comparing AWS Cloud with on-premises Total Cost of Ownership, which expenses must be considered? (Choose two.)
    - A. Software development
    - B. Project management
    - C. Storage hardware
    - D. Physical servers
    - E. Antivirus software license

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CD

    Explanation: <https://aws.amazon.com/blogs/aws/the-new-aws-tco-calculator/></br>
    스토리지 하드웨어(C)와 물리적 서버(D) 등 초기 자본 비용 포함.

    </details>

45. Which scenarios represent the concept of elasticity on AWS? (Choose two.)
    - A. Scaling the number of Amazon EC2 instances based on traffic.
    - B. Resizing Amazon RDS instances as business needs change.
    - C. Automatically directing traffic to less-utilized Amazon EC2 instances.
    - D. Using AWS compliance documents to accelerate the compliance process.
    - E. Having the ability to create and govern environments using code.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AB

    Explanation: <https://wa.aws.amazon.com/wat.concept.elasticity.en.html></br>
    트래픽 기반 EC2 인스턴스 스케일링(A)과 RDS 인스턴스 크기 조정(B) 사례.

    </details>

47. A company is considering moving its on-premises data center to AWS. What factors should be included in doing a Total Cost of Ownership (TCO) analysis? (Choose two.)
    - A. Amazon EC2 instance availability
    - B. Power consumption of the data center
    - C. Labor costs to replace old servers
    - D. Application developer time
    - E. Database engine capacity

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BC</br>
    데이터센터 전력(B)과 서버 교체 인건비(C) 포함.

    </details>

50. Which disaster recovery scenario offers the lowest probability of down time?
    - A. Backup and restore
    - B. Pilot light
    - C. Warm standby
    - D. Multi-site active-active

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:

    - Backup and Restore: a simple, straightforward, cost-effective method that backs up and restores data as needed.
    - Keep in mind that because none of your data is on standby, this method, while cheap, can be quite time-consuming.
    - Pilot Light: This method keeps critical applications and data at the ready so that it can be quickly retrieved if needed.
    - Warm Standby: This method keeps a duplicate version of your business' core elements running on standby at all times, which makes for a little downtime and an almost seamless transition.
    - Multi-Site Solution: Also known as a Hot Standby, this method fully replicates your company's data/ applications between two or more active locations and splits your traffic/usage between them.
    - If a disaster strikes, everything is simply rerouted to the unaffected area, which means you'll suffer almost zero downtime.
    - However, by running two separate environments simultaneously, you will obviously incur much higher costs.

    Reference: <https://cloudranger.com/best-practices-aws-disaster-recovery-planning/></br>
    Multi-site active-active 구성으로 거의 다운타임 없이 복구 가능.
    </details>

