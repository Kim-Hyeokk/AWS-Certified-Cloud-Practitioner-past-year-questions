---
layout: exam
---

# Practice Exam 12

1. Which of the following components of the AWS Global Infrastructure consists of one or more discrete data centers interconnected through low latency links?
    - A. Availability Zone
    - B. Edge location
    - C. Region
    - D. Private networking

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      가용 영역은 하나 이상의 데이터 센터로 이루어져 있고, 저지연 네트워크로 연결됩니다. Region은 여러 AZ를 포함하고, Edge location은 CDN용입니다.
    </details>

3. What can assist in evaluating an application for migration to the cloud? (Select TWO)
    - A. AWS Trusted Advisor.
    - B. AWS Professional Services.
    - C. AWS Systems Manager.
    - D. AWS Partner Network (APN).
    - E. AWS Secrets Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D</br>
      마이그레이션 평가는 AWS Professional Services와 AWS Partner Network(APN)가 지원합니다. Trusted Advisor는 최적화 점검, Systems Manager는 운영 관리용입니다.
    </details>

6. What is a value proposition of the AWS Cloud?
    - A. AWS is responsible for security in the AWS Cloud.
    - B. No long-term contract is required.
    - C. Provision new servers in days.
    - D. AWS manages user applications in the AWS Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      해설: AWS는 장기 계약이 필요 없습니다. 필요할 때 사용하고 중단할 수 있는 유연성이 핵심 가치입니다.
    </details>

7. A company is migrating an application that is running non-interruptible workloads for a three-year time frame. Which pricing construct would provide the MOST cost-effective solution?
    - A. Amazon EC2 Spot Instances.
    - B. Amazon EC2 Dedicated Instances.
    - C. Amazon EC2 On-Demand Instances.
    - D. Amazon EC2 Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      해설: 3년간 지속적으로 사용한다면 Reserved Instance가 가장 저렴합니다. Spot은 중단될 수 있어 부적합합니다.
    </details>

10. How can one AWS account use Reserved Instances from another AWS account?
    - A. By using Amazon EC2 Dedicated Instances.
    - B. By using AWS Organizations consolidated billing.
    - C. By using the AWS Cost Explorer tool.
    - D. By using AWS Budgets.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      해설: AWS Organizations의 통합 결제(Consolidated Billing)를 통해 RI 혜택을 계정 간 공유할 수 있습니다.
    </details>

11. What are the benefits of developing and running a new application in the AWS Cloud compared to on-premises? (Select TWO)
    - A. AWS automatically distributes the data globally for higher durability.
    - B. AWS will take care of operating the application.
    - C. AWS makes it easy to architect for high availability.
    - D. AWS can easily accommodate application demand changes.
    - E. AWS takes care of application security patching.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D</br>
      해설: AWS는 고가용성 아키텍처를 쉽게 설계할 수 있고, 수요 변화에 탄력적으로 대응할 수 있습니다.
    </details>

12. Which of the following services falls under the responsibility of the customer to maintain operating system configuration, security patching, and networking?
    - A. Amazon RDS.
    - B. Amazon EC2.
    - C. Amazon ElastiCache.
    - D. AWS Fargate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      해설: EC2는 OS 보안 패치, 네트워킹 등 고객이 관리해야 합니다. RDS/Fargate는 관리형 서비스입니다.
    </details>

14. Which service provides a hybrid storage service that enables on-premises applications to seamlessly use cloud storage?
    - A. Amazon Glacier
    - B. AWS Snowball
    - C. AWS Storage Gateway
    - D. Amazon Elastic Block Storage (Amazon EBS)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      해설: 온프레미스와 클라우드 스토리지를 연결하는 하이브리드 스토리지 서비스입니다.
    </details>

17. Which Amazon EC2 pricing model adjusts based on supply and demand of EC2 instances?
    - A. On-Demand Instances.
    - B. Reserved Instances.
    - C. Spot Instances.
    - D. Convertible Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      해설: 스팟 인스턴스는 공급·수요에 따라 가격이 변동됩니다.
    </details>

19. A Cloud Practitioner must determine if any security groups in an AWS account have been provisioned to allow unrestricted access for specific ports. What is the SIMPLEST way to do this?
    - A. Review the inbound rules for each security group in the Amazon EC2 management console to check for port 0.0.0.0/0.
    - B. Run AWS Trusted Advisor and review the findings.
    - C. Open the AWS IAM console and check the inbound rule filters for open access.
    - D. In AWS Config, create a custom rule that invokes an AWS Lambda function to review firewall rules for inbound access.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B</br>
      해설: Trusted Advisor는 보안 그룹에서 0.0.0.0/0 오픈 여부 등을 자동으로 점검합니다.
    </details>

20. Which of the following security-related services does AWS offer? (Select TWO)
    - A. Multi-factor authentication physical tokens.
    - B. AWS Trusted Advisor security checks.
    - C. Data encryption.
    - D. Automated penetration testing.
    - E. Amazon S3 copyrighted content detection.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      해설: AWS는 Trusted Advisor 보안 점검과 데이터 암호화 기능을 제공합니다.
    </details>

21. Which of the following services have Distributed Denial of Service (DDoS) mitigation features? (Select TWO)
    - A. AWS WAF.
    - B. Amazon DynamoDB.
    - C. Amazon EC2.
    - D. Amazon CloudFront.
    - E. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D</br>
      해설: AWS WAF와 CloudFront는 DDoS 방어 기능을 제공합니다.
    </details>

24. Which AWS Cloud benefit eliminates the need for users to try estimating future infrastructure usage?
    - A. Easy and fast deployment of applications in multiple Regions around the world.
    - B. Security of the AWS Cloud.
    - C. Elasticity of the AWS Cloud.
    - D. Lower variable costs due to massive economies of scale.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C</br>
      해설: 탄력성으로 인해 미래 사용량을 예측할 필요 없이 필요할 때 확장/축소가 가능합니다.
    </details>

25. What can users access from AWS Artifact?
    - A. AWS security and compliance documents.
    - B. A download of configuration management details for all AWS resources.
    - C. Training materials for AWS services.
    - D. A security assessment of the applications deployed in the AWS Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      해설: 보안·컴플라이언스 문서(SOC 보고서 등)를 다운로드할 수 있습니다.
    </details>

26. Compared with costs in traditional and virtualized data centers, AWS has:
    - A. Greater variable costs and greater upfront costs.
    - B. Fixed usage costs and lower upfront costs.
    - C. Lower variable costs and greater upfront costs.
    - D. Lower variable costs and lower upfront costs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      해설: AWS는 낮은 변동 비용과 낮은 초기 비용을 제공합니다. 선투자(CapEx)가 거의 필요 없습니다.
    </details>

33. Under the shared responsibility model which of the following areas are the customer’s responsibility? (Select TWO)
    - A. Firmware upgrades of network infrastructure.
    - B. Patching of operating systems.
    - C. Patching of the underlying hypervisor.
    - D. Physical security of data centers.
    - E. Configuration of the security group.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E</br>
      해설: 고객은 OS 패치와 보안 그룹 설정을 책임집니다. 물리 보안, 하이퍼바이저는 AWS 책임입니다.
    </details>

35. Which AWS services provide a way to extend an on-premises architecture to the AWS Cloud? (Select TWO)
    - A. Amazon EBS.
    - B. AWS Direct Connect.
    - C. Amazon CloudFront.
    - D. AWS Storage Gateway.
    - E. Amazon Connect.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D</br>
      해설: Direct Connect와 Storage Gateway는 온프레미스 확장에 사용됩니다.
    </details>

37. How can the AWS Cloud increase user workforce productivity after migration from an on-premises data center?
    - A. Users do not have to wait for infrastructure provisioning.
    - B. The AWS Cloud infrastructure is much faster than an on-premises data center infrastructure.
    - C. AWS takes over application configuration management on behalf of users.
    - D. Users do not need to address security and compliance issues.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A</br>
      해설: 클라우드에서는 인프라를 빠르게 프로비저닝할 수 있어 대기 시간이 줄어듭니다.
    </details>

38. Which of the following services could be used to deploy an application to servers running on-premises? (Select TWO)
    - A. AWS Elastic Beanstalk.
    - B. AWS OpsWorks.
    - C. AWS CodeDeploy.
    - D. AWS Batch.
    - E. AWS X-Ray.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C</br>
      해설: OpsWorks와 CodeDeploy는 온프레미스 서버에도 배포 가능합니다.
    </details>

40. Which AWS security service protects applications from distributed denial of service attacks with always-on detection and automatic inline mitigations?
    - A. Amazon Inspector.
    - B. AWS Web Application Firewall (AWS WAF).
    - C. Elastic Load Balancing (ELB).
    - D. AWS Shield.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
    </details>

42. A company is considering using AWS for a self-hosted database that requires a nightly shutdown for maintenance and cost-saving purposes. Which service should the company use?
    - A. Amazon Redshift.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic Compute Cloud (Amazon EC2) with Amazon EC2 instance store.
    - D. Amazon EC2 with Amazon Elastic Block Store (Amazon EBS).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D</br>
      해설: 자체 호스팅 DB를 운영하면서 정기적 종료/재시작이 필요하다면 EC2+EBS 조합을 사용합니다.
    </details>

