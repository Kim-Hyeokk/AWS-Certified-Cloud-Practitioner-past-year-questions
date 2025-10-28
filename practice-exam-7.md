---
layout: exam
---

# Practice Exam 7

3. Which of the following will affect how much you are charged for storing objects in S3? (Choose TWO)
    - A. Using default encryption for any number of S3 buckets.
    - B. The number of EBS volumes attached to your instances.
    - C. The storage class used for the objects stored.
    - D. Creating and deleting S3 buckets.
    - E. The total size in gigabytes of all objects stored.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E
        S3 비용은 **저장된 데이터의 총량(GB)**과 선택한 스토리지 클래스에 따라 달라집니다.
    </details>

9. You manage a blog on AWS that has different environments: development, testing, and production. What can you use to create a custom console for each environment to view and manage your resources easily?
    - A. AWS Resource Groups.
    - B. AWS Placement Groups.
    - C. AWS Management Console.
    - D. AWS Tag Editor.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        리소스 그룹을 사용하여 태그나 다른 기준으로 리소스를 그룹화하고, 이를 기반으로 사용자 지정 콘솔을 만들 수 있습니다.
    </details>

10. Which AWS service collects metrics from running EC2 instances?
    - A. Amazon Inspector.
    - B. Amazon CloudWatch.
    - C. AWS CloudFormation.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        CloudWatch는 AWS 리소스 및 애플리케이션에 대한 모니터링 및 관찰 가능성을 제공합니다.
    </details>

18. Amazon RDS supports multiple database engines to choose from. Which of the following is not one of them?
    - A. PostgreSQL.
    - B. Oracle.
    - C. Microsoft SQL Server.
    - D. Teradata.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        RDS는 MySQL, PostgreSQL, Oracle, SQL Server, MariaDB 및 Aurora를 지원합니다.
    </details>

20. For new AWS customers, what is the EASIEST way to launch a simple WordPress website on AWS?
    - A. Run WordPress on an Amazon Lightsail instance.
    - B. Install WordPress on an Amazon EC2 instance.
    - C. Use the Amazon S3 Web hosting feature.
    - D. Host the website directly on AWS Cloud Development Kit (AWS CDK).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        Lightsail은 가상 서버, DB, 로드 밸런서 등을 포함하는 가장 간단한 인스턴스 기반 환경을 제공하며, 사전 구성된 WordPress 템플릿을 제공합니다.
    </details>

22. Which of the following services allows you to install and run custom relational database software?
    - A. Amazon EC2.
    - B. Amazon Cognito.
    - C. Amazon RDS.
    - D. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        EC2는 가상 서버(IaaS)이므로, 고객은 원하는 모든 소프트웨어(사용자 지정 DB 포함)를 설치할 수 있습니다.
    </details>

24. A company has infrastructure hosted in an on-premises data center. They currently have an operations team that takes care of identity management. If they decide to migrate to the AWS cloud, which of the following services would help them perform the same role in AWS?
    - A. AWS IAM.
    - B. AWS Outposts.
    - C. AWS Federation.
    - D. Amazon Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        IAM은 AWS 리소스에 대한 접근 및 권한을 관리하는 서비스입니다.
    </details>

27. Which of the following services enables you to easily generate and use your own encryption keys in the AWS Cloud?
    - A. AWS Shield.
    - B. AWS Certificate Manager.
    - C. AWS CloudHSM.
    - D. AWS WAF.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        CloudHSM은 고객 전용 **하드웨어 보안 모듈(HSM)**을 제공하여 키 관리에 대한 완전한 제어를 제공합니다.
    </details>

30. Which of the following factors affect Amazon CloudFront cost? (Choose TWO)
    - A. Number of Requests.
    - B. Traffic Distribution.
    - C. Number of Volumes.
    - D. Instance type.
    - E. Storage Class.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
        CloudFront 비용은 전송된 데이터 양, 요청 수 및 **지리적 위치(트래픽 분포)**에 따라 달라집니다.
    </details>

32. Which of the following security resources are available to any user for free? (Choose TWO)
    - A. AWS Bulletins.
    - B. AWS TAM.
    - C. AWS Support APl.
    - D. AWS Security Blog.
    - E. AWS Classroom Training.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
        보안 게시판과 블로그는 공개적으로 제공됩니다.
    </details>

33. How can you protect data stored on Amazon S3 from accidental deletion?
    - A. By enabling S3 Versioning.
    - B. By configuring S3 Bucket Policies.
    - C. By configuring S3 Lifecycle Policies.
    - D. By disabling S3 Cross-Region Replication (CRR).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        버전 관리를 활성화하면 객체가 실수로 삭제되어도 이전 버전을 복구할 수 있습니다.
    </details>

37. How does AWS help customers achieve compliance in the cloud?
    - A. It's not possible to meet regulatory compliance requirements in the Cloud.
    - B. AWS applies the most common Cloud security standards, and is responsible for complying with customers’ applicable laws and regulations.
    - C. AWS has many common assurance certifications such as ISO 9001 and HIPAA.
    - D. Many AWS services are assessed regularly to comply with local laws and regulations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        AWS는 다양한 규정 준수 표준을 준수하며, 고객은 그 위에 자체적인 규정 준수 노력을 구축합니다.
    </details>

45. Which feature enables users to sign into their AWS accounts with their existing corporate credentials?
    - A. Federation.
    - B. Access keys.
    - C. IAM Permissions.
    - D. WAF rules.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        ID 연동을 통해 외부 ID 시스템(Active Directory 등)의 자격 증명으로 AWS에 접근할 수 있습니다.
    </details>

46. According to the AWS shared responsibility model, what are the controls that customers fully inherit from AWS? (Choose TWO)
    - A. Awareness and Training.
    - B. Communications controls.
    - C. Data center security controls.
    - D. Environmental controls.
    - E. Resource Configuration Management.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
        **"클라우드의 보안"**에 해당하는 물리적 인프라 관리는 AWS가 전적으로 책임집니다.
    </details>

49. Which of the following are part of the seven design principles for security in the cloud? (Choose TWO)
    - A. Use manual monitoring techniques to protect your AWS resources.
    - B. Use IAM roles to grant temporary access instead of long-term credentials.
    - C. Scale horizontally to protect from failures.
    - D. Enable real-time traceability.
    - E. Never store sensitive data in the cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
        임시 자격 증명(역할) 사용은 보안 모범 사례이며, **실시간 추적(CloudTrail)**은 감사 및 거버넌스를 가능하게 합니다.
    </details>
