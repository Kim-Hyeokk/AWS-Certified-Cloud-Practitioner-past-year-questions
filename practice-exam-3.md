---
layout: exam
---

# Practice Exam 3

4. A company is migrating its on-premises database to Amazon RDS. What should the company do to ensure Amazon RDS costs are kept to a minimum?
    - A. Right-size before and after migration.
    - B. Use a Multi-Region Active-Passive architecture.
    - C. Combine On-demand Capacity Reservations with Saving Plans.
    - D. Use a Multi-Region Active-Active architecture.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        클라우드 비용을 최소화하는 가장 기본적인 방법은 워크로드에 필요한 최소한의 리소스만 사용하도록 인스턴스 크기를 **적절하게 조정(Right-sizing)**하는 것입니다.
    </details>

5. What is the primary storage service used by Amazon RDS database instances?
    - A. Amazon Glacier.
    - B. Amazon EBS.
    - C. Amazon EFS.
    - D. Amazon S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        Amazon RDS는 EC2 인스턴스에서 실행되며, 데이터베이스 파일 저장을 위해 EBS 볼륨을 주 스토리지로 사용합니다.
    </details>

6. A company is developing a new application using a microservices framework. The new application is having performance and latency issues. Which AWS Service should be used to troubleshoot these issues?
    - A. AWS CodePipeline.
    - B. AWS X-Ray.
    - C. Amazon Inspector.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        AWS X-Ray는 애플리케이션이 구성된 개별 서비스 간의 호출을 추적하고 분석하여 애플리케이션의 성능 병목 현상 및 지연 시간을 시각적으로 문제 해결하는 데 사용됩니다.
    </details>

7. Which of the following AWS services is designed with native Multi-AZ fault tolerance in mind? (Choose TWO)
    - A. Amazon Redshift.
    - B. AWS Snowball.
    - C. Amazon Simple Storage Service.
    - D. Amazon EBS.
    - E. Amazon DynamoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E
        Amazon S3는 데이터를 여러 시설과 여러 AZ에 자동으로 복제하여 높은 내구성과 가용성을 제공합니다.

Amazon DynamoDB는 데이터를 여러 AZ에 자동으로 복제하는 완전 관리형 NoSQL 데이터베이스입니다.
    </details>

8. What are the Amazon RDS features that can be used to improve the availability of your database? (Choose TWO)
    - A. AWS Regions.
    - B. Multi-AZ Deployment.
    - C. Automatic patching.
    - D. Read Replicas.
    - E. Edge Locations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
        Read Replicas는 비동기식 복제본을 생성하여 읽기 트래픽을 분산하고(성능 향상), 재해 복구 시 승격될 수 있어 가용성 향상에 기여합니다.
    </details>

12. Which of the below is a best-practice when building applications on AWS?
    - A. Strengthen physical security by applying the principle of least privilege.
    - B. Ensure that the application runs on hardware from trusted vendors.
    - C. Use IAM policies to maintain performance.
    - D. Decouple the components of the application so that they run independently.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        AWS Well-Architected 프레임워크의 안정성 원칙에 따라, 시스템 구성 요소를 **느슨하게 결합(Decouple)**하고 독립적으로 실행되도록 설계하면 한 구성 요소의 장애가 전체 애플리케이션에 영향을 미치는 것을 방지하여 탄력성을 높입니다.
    </details>

20. Savings Plans are available for which of the following AWS compute services? (Choose TWO)
    - A. AWS Batch.
    - B. AWS Outposts.
    - C. Amazon Lightsail.
    - D. Amazon EC2.
    - E. AWS Lambda.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
        AWS Savings Plans는 Amazon EC2 (EC2 Instance Savings Plans) 및 AWS Fargate, AWS Lambda (Compute Savings Plans) 사용량에 대해 할인을 제공하는 유연한 가격 모델입니다.
    </details>

22. Which statement is correct with regards to AWS service limits? (Choose TWO)
    - A. You can contact AWS support to increase the service limits.
    - B. Each IAM user has the same service limit.
    - C. There are no service limits on AWS.
    - D. You can use the AWS Trusted Advisor to monitor your service limits.
    - E. The Amazon Simple Email Service is responsible for sending email notifications when usage approaches a service limit.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
        대부분의 **서비스 한도(Service Limits)**는 요청 시 AWS 지원팀에 연락하여 늘릴 수 있습니다(A).

AWS Trusted Advisor는 Service Limits Check를 제공하여 사용량 및 한도를 모니터링하고 임박한 한도 초과를 경고합니다(D).
    </details>

31. Which of the following will impact the price paid for an EC2 instance? (Choose TWO)
    - A. Instance type.
    - B. The Availability Zone where the instance is provisioned.
    - C. Load balancing.
    - D. Number of buckets.
    - E. Number of private IPs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
        정답 (B)는 혼란의 여지가 있으나, AWS Pricing Calculator를 보면 리전별 가격은 다릅니다. 가용 영역(AZ) 내에서는 일반적으로 가격이 동일하지만, 일부 특별한 상황(예: AZ ID의 차이)이나 AWS의 공식 클라우드 프랙티셔너 시험에서는 리전 또는 AZ가 가격에 영향을 미치는 요소로 간주됩니다. 따라서 여기서는 인스턴스 유형과 리전/AZ를 선택합니다.
    </details>

33. A company uses AWS Organizations to manage all of its AWS accounts. Which of the following allows the company to restrict what services and actions are allowed in each individual account?
    - A. IAM Principals.
    - B. AWS Service Control Policies (SCPs).
    - C. IAM policies.
    - D. AWS Fargate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        **SCP (Service Control Policy)**는 AWS Organizations의 기능으로, 조직의 계정에서 최대 권한을 지정하여 사용할 수 있는 AWS 서비스 및 작업을 제한하는 데 사용됩니다. 이는 보안 경계 역할을 합니다.
    </details>

35. What are the benefits of using the Amazon Relational Database Service? (Choose TWO)
    - A. Lower administrative burden.
    - B. Complete control over the underlying host.
    - C. Resizable compute capacity.
    - D. Scales automatically to larger or smaller instance types.
    - E. Supports the document and key-value data structure.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        고객은 워크로드에 따라 DB 인스턴스의 **크기(컴퓨팅 용량)**를 쉽게 조정할 수 있습니다(C).
    </details>

36. What is the connectivity option that uses Internet Protocol Security (IPSec) to establish encrypted connectivity between an on-premises network and the AWS Cloud?
    - A. Internet Gateway.
    - B. AWS IQ.
    - C. AWS Direct Connect.
    - D. AWS Site-to-Site VPN.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
      AWS Site-to-Site VPN은 IPSec 암호화 터널을 사용하여 공용 인터넷을 통해 VPC와 온프레미스 네트워크 사이에 안전하고 사설적인 연결을 생성합니다.
        
    </details>

38. Which of the following is used to control network traffic in AWS? (Choose TWO)
    - A. Network Access Control Lists (NACLs).
    - B. Key Pairs.
    - C. Access Keys.
    - D. IAM Policies.
    - E. Security Groups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
        보안 그룹(Security Groups): 인스턴스 수준의 허용 규칙을 갖는 가상 방화벽.

네트워크 ACLs (NACLs): 서브넷 수준의 허용 및 거부 규칙을 갖는 선택적 방화벽.
    </details>

39. A company has developed a media transcoding application in AWS. The application is designed to recover quickly from hardware failures. Which one of the following types of instance would be the most cost-effective choice to use?
    - A. Reserved instances.
    - B. Spot Instances.
    - C. On-Demand instances.
    - D. Dedicated instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        Spot Instances는 EC2 인스턴스 유형 중 가장 저렴하며, 작업이 중단되어도 무방하거나 장애로부터 쉽게 복구할 수 있는 일괄 처리(Batch) 작업이나 트랜스코딩과 같은 유연한 워크로드에 가장 적합합니다.
    </details>

40. Which AWS Service provides the current status of all AWS Services in all AWS Regions?
    - A. AWS Service Health Dashboard.
    - B. AWS Management Console.
    - C. Amazon CloudWatch.
    - D. AWS Personal Health Dashboard.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        AWS Service Health Dashboard는 AWS의 전역적인 서비스 상태를 표시하는 공용 웹 페이지입니다. (개인 계정별 서비스 상태는 AWS Personal Health Dashboard에서 확인합니다.)
    </details>
