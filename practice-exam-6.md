---
layout: exam
---

# Practice Exam 6

1. Which of the following is true regarding the AWS availability zones and edge locations?
    - A. Edge locations are located in separate Availability Zones worldwide to serve global customers.
    - B. An availability zone exists within an edge location to distribute content globally with low latency.
    - C. An Availability Zone is a geographic location where AWS provides multiple, physically separated and isolated edge locations.
    - D. An AWS Availability Zone is an isolated location within an AWS Region, however edge locations are located in multiple cities worldwide.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        AZ는 컴퓨팅/스토리지 리소스를 위한 리전 내 격리된 데이터 센터이고, 엣지 로케이션은 CDN을 위한 글로벌 거점입니다.
    </details>

3. A company is developing a mobile application and wants to allow users to use their Amazon, Apple, Facebook, or Google identities to authenticate to the application. Which AWS Service should the company use for this purpose?
    - A. Amazon GuardDuty.
    - B. Amazon Personalize.
    - C. Amazon Cognito.
    - D. AWS IAM.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        Cognito는 사용자 인증 및 권한 부여를 관리하며 **소셜 ID 연동(Federation)**을 지원합니다.
    </details>

6. A customer is planning to migrate their Microsoft SQL Server databases to AWS. Which AWS Services can the customer use to run their Microsoft SQL Server database on AWS? (Choose TWO)
    - A. AWS Fargate.
    - B. Amazon Elastic Compute Cloud.
    - C. Amazon RDS.
    - D. AWS Database Migration service (DMS).
    - E. AWS Lambda.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        MSSQL은 EC2에서 직접 설치하거나 RDS에서 관리형으로 실행할 수 있습니다.
    </details>

7. Which AWS Service can perform health checks on Amazon EC2 instances?
    - A. AWS CloudFormation.
    - B. Amazon Route 53.
    - C. Amazon Chime.
    - D. Amazon Aurora.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        Route 53는 DNS 기반 상태 확인을 수행하여 비정상 엔드포인트로 트래픽이 전달되지 않도록 합니다.
    </details>

12. You need to migrate a large number of on-premises workloads to AWS. Which AWS service is the most appropriate?
    - A. AWS File Transfer Acceleration.
    - B. AWS Server Migration Service.
    - C. AWS Database Migration Service.
    - D. AWS Application Discovery Service.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        SMS는 온프레미스 서버를 AWS로 **이전(Lift and Shift)**하는 프로세스를 자동화합니다.
    </details>

19. What does AWS Cost Explorer provide to help manage your AWS spend?
    - A. Cost comparisons between AWS Cloud environments and on-premises environments.
    - B. Accurate estimates of AWS service costs based on your expected usage.
    - C. Consolidated billing.
    - D. Highly accurate cost forecasts for up to 12 months ahead.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        Cost Explorer는 과거 비용 분석과 함께 미래 비용 예측 기능을 제공합니다.
    </details>

21. You are using several on-demand EC2 Instances to run your development environment. What is the best way to reduce your charges when these instances are not in use?
    - A. Deleting all EBS volumes attached to the instances.
    - B. You cannot minimize charges for on-demand instances.
    - C. Terminating the instances.
    - D. Stopping the instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        중지하면 컴퓨팅 요금이 부과되지 않습니다. (스토리지(EBS) 요금은 계속 부과됩니다.)
    </details>

22. Which of the following strategies helps protect your AWS root account?
    - A. Delete root user access keys if you do not need them.
    - B. Apply MFA for the root account and use it for all of your work.
    - C. Access the root account only from your personal Mobile Phone.
    - D. Only share your AWS account password or access keys with trusted persons.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        보안 모범 사례는 루트 액세스 키를 생성하지 않거나 삭제하고, IAM 사용자만 사용하는 것입니다.
    </details>

23. Which of the following are factors should be considered for Amazon EBS pricing? (Choose TWO)
    - A. The size of volumes provisioned per month.
    - B. The compute capacity you consume.
    - C. The amount of data you have stored in snapshots.
    - D. The compute time you consume.
    - E. The number of Snowball storage devices you request.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        EBS 요금은 볼륨 크기와 스냅샷 저장 공간에 따라 부과됩니다.
    </details>

25. Which of the following has the greatest impact on cost? (Choose TWO)
    - A. Compute charges.
    - B. The number of services used.
    - C. Data Transfer In charges.
    - D. Data Transfer Out charges.
    - E. The number of IAM roles provisioned.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
        일반적으로 컴퓨팅과 데이터 외부 전송이 AWS 비용의 가장 큰 부분을 차지합니다.
    </details>

31. Which tool can a non-AWS customer use to compare the cost of on-premises environment resources to AWS?
    - A. AWS Cost Explorer.
    - B. AWS Pricing Calculator.
    - C. AWS Budgets.
    - D. AWS TCO Calculator.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        TCO 계산기는 AWS와 온프레미스 환경의 총 소유 비용을 비교하는 데 사용됩니다.
    </details>

35. Select the services that are server-based: (Choose TWO)
    - A. Amazon RDS.
    - B. Amazon DynamoDB.
    - C. AWS Lambda.
    - D. AWS Fargate.
    - E. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
        이 서비스들은 AWS가 관리하지만, 기저의 EC2 인스턴스에서 실행되므로 Lambda/DynamoDB 같은 진정한 서버리스 서비스와 구분됩니다.
    </details>

37. Which of the following are use cases for Amazon EMR? (Choose TWO)
    - A. Enables you to backup extremely large amounts of data at very low costs.
    - B. Enables you to move Exabyte-scale data from on-premises datacenters into AWS.
    - C. Enables you to analyze and process extremely large amounts of data in a timely manner.
    - D. Enables you to easily run and scale Apache Spark, Hadoop,and other Big Data frameworks.
    - E. Enables you to easily run and manage Docker containers.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
        EMR은 빅 데이터 처리 및 분석을 위한 Hadoop/Spark 관리형 클러스터 서비스입니다.
    </details>

38. Your CTO has asked you to contact AWS support using the chat feature to ask for guidance related to EBS. However, when you open the AWS support center you can't see a way to contact support via Chat. What should you do?
    - A. There is no chat feature in AWS support.
    - B. The chat feature is available for all plans for an additional fee, but you have to request it first.
    - C. At a minimum, upgrade to Business support plan.
    - D. Upgrade from the Basic Support plan to Developer Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        **채팅 및 전화 지원(24x7)**은 Business Support 플랜부터 제공됩니다.
    </details>

41. For Amazon RDS databases, what does AWS perform on your behalf? (Choose TWO)
    - A. Database setup.
    - B. Network traffic protection.
    - C. Management of the operating system.
    - D. Access management.
    - E. Management of firewall rules.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        RDS는 관리형 서비스이므로 AWS가 기반 OS와 DB 설치/설정을 처리합니다.
    </details>

43. A media company has an application that requires the transfer of large data sets to and from AWS every day. This data is business critical and should be transferred over a consistent connection. Which AWS service should the company use?
    - A. AWS Direct Connect.
    - B. Amazon Comprehend.
    - C. AWS Snowmobile.
    - D. AWS VPN.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        Direct Connect는 전용의 일관된 고대역폭 사설 네트워크 연결을 제공합니다.
    </details>

45. To protect against data loss, you need to backup your database regularly. What is the most cost-effective storage option that provides immediate retrieval of your backups?
    - A. Amazon S3 Glacier Deep Archive.
    - B. Amazon S3 Standard-Infrequent Access.
    - C. Amazon S3 Glacier.
    - D. Instance Store.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        Glacier보다 저렴하지는 않지만, 즉시(밀리초) 검색이 가능하면서도 Standard보다 저렴합니다.
    </details>

49. You want to transfer 200 Terabytes of data from on-premises locations to the AWS Cloud, which of the following can do the job in a cost-effective way?
    - A. AWS Snowmobile.
    - B. AWS Import/Export.
    - C. AWS DMS.
    - D. AWS Snowball.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        Snowball은 **10PB 미만(200TB 포함)**의 대규모 데이터를 물리적 디바이스를 통해 전송하는 데 사용됩니다.
    </details>
