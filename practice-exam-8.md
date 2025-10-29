---
layout: exam
---

# Practice Exam 8

2. A company wants to use Amazon Elastic Container Service (Amazon ECS) to run its containerized applications. For compliance reasons, the company wants to retain complete visibility and control over the underlying server cluster. Which Amazon ECS launch type will satisfy these requirements?
    - A. EC2 launch type.
    - B. Fargate launch type.
    - C. Lightsail launch type.
    - D. Lambda launch type.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        EC2 유형은 고객이 기반 EC2 인스턴스를 직접 관리하고 제어합니다.
    </details>

4. You have been tasked with auditing the security of your VPC. As part of this process, you need to start by analyzing what inbound and outbound traffic is allowed on your EC2 instances. What two parts of the VPC do you need to check to accomplish this task?
    - A. Network ACLs and Traffic Manager.
    - B. Network ACLs and Subnets.
    - C. Security Groups and Internet Gateways.
    - D. Security Groups and Network ACLs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        보안 그룹은 인스턴스 수준, 네트워크 ACL은 서브넷 수준에서 트래픽을 제어합니다.
    </details>

8. Amazon EC2 instances are conceptually very similar to traditional servers. However, using Amazon EC2 server instances in the same manner as traditional hardware server instances is only a starting point. What are the main benefits of using the AWS EC2 instances instead of traditional servers? (Choose TWO)
    - A. Improves Fault-Tolerance.
    - B. Provides your business with a seamless remote accessibility.
    - C. Prevents unauthorized users from getting into your network.
    - D. Provides automatic data backups.
    - E. Can be scaled manually in a shorter period of time.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
        EC2는 **빠른 확장(E)**이 가능하고, 다중 AZ 배포를 통해 **내결함성(A)**을 높입니다.
    </details>

9. Which statement is true regarding AWS pricing? (Choose TWO)
    - A. With the AWS pay-as-you-go pricing model, you don't have to pay any upfront fee.
    - B. You have no responsibility for third-party software license costs.
    - C. You only pay for the individual services that you need with no long-term contracts.
    - D. For some services, you have to pay a startup fee in order to get the service running.
    - E. There are no reservations on AWS, you only pay for what you use.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        종량제(Pay-as-you-go) 모델의 특징입니다.
    </details>

11. A company is running a large web application that needs to always be available. The application tends to slow down when CPU usage is greater than 60%. How can they track when CPU usage goes above 60% for any of the EC2 Instances in their account?
    - A. Use CloudFront to monitor the CPU usage.
    - B. Set the AWS Config CPU threshold to 60% to receive a notification when EC2 usage exceeds that value.
    - C. Use CloudWatch Alarms to monitor the CPU and alert when the CPU usage is >= 60%.
    - D. Use SNS to monitor the utilization of the server.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        CloudWatch는 메트릭을 모니터링하고 경보를 설정하는 데 사용됩니다.
    </details>

12. What is the recommended storage option when hosting an often-changing database on an Amazon EC2 instance?
    - A. Amazon EBS.
    - B. Amazon RDS.
    - C. You can't run a database inside an Amazon EC2 instance.
    - D. Amazon DynamoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        EBS는 영구적인 블록 스토리지를 제공하며 EC2 인스턴스에 마운트하여 DB 저장소로 사용됩니다.
    </details>

15. What are the main differences between an IAM user and an IAM role in AWS? (Choose TWO)
    - A. An IAM user is uniquely associated with only one person, however a role is intended to be assumable by anyone who needs it.
    - B. An IAM user has permanent credentials associated with it, however a role has temporary credentials associated with it.
    - C. IAM users are more cost effective than IAM roles.
    - D. A role is uniquely associated with only one person, however an IAM user is intended to be assumable by anyone who needs it.
    - E. An IAM user has temporary credentials associated with it, however a role has permanent credentials associated with it.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
        사용자는 영구 자격 증명을 가진 한 사람을 나타내고, 역할은 임시 자격 증명을 가진 엔티티에 할당됩니다.
    </details>

16. Which of the following actions may reduce Amazon EBS costs? (Choose TWO)
    - A. Deleting unused buckets.
    - B. Using reservations.
    - C. Deleting unnecessary snapshots.
    - D. Changing the type of the volume.
    - E. Distributing requests to multiple volumes.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
        **스냅샷(C)**은 스토리지 비용을 발생시키며, **볼륨 유형(D)**은 성능/비용에 영향을 줍니다.
    </details>

26. A company needs to host a big data application on AWS using EC2 instances. Which of the following AWS Storage services would they choose to automatically get high throughput to multiple compute nodes?
    - A. Amazon Elastic Block Store.
    - B. AWS Storage Gateway.
    - C. Amazon Elastic File System.
    - D. S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        EFS는 여러 EC2 인스턴스에서 동시에 접근 가능하며, 높은 처리량을 제공하는 파일 시스템입니다.
    </details>

27. Which of the following Cloud Computing deployment models eliminates the need to run and maintain physical data centers?
    - A. On-premises.
    - B. IaaS.
    - C. PaaS.
    - D. Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        클라우드 모델은 물리적 인프라 관리를 AWS에 아웃소싱합니다.
    </details>

28. What are the benefits of the AWS Marketplace service? (Choose TWO)
    - A. Protects customers by performing periodic security checks on listed products.
    - B. Per-second billing.
    - C. Provides cheaper options for purchasing Amazon EC2 on-demand instances.
    - D. Provides flexible pricing options that suit most customer needs.
    - E. Provides software solutions that run on AWS or any other Cloud vendor.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
        Marketplace는 다양한 가격 옵션을 제공하며, 소프트웨어는 AWS 또는 온프레미스에서 실행될 수 있습니다.
    </details>

29. What is the benefit of Amazon EBS volumes being automatically replicated within the same availability zone?
    - A. Elasticity.
    - B. Durability.
    - C. Traceability.
    - D. Accessibility.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        복제는 단일 하드웨어 오류 발생 시 데이터 손실을 방지하여 내구성을 보장합니다.
    </details>

30. You are planning to launch an advertising campaign over the coming weekend to promote a new digital product. It is expected that there will be heavy spikes in load during the campaign period, and you can’t afford any downtime. You need additional compute resources to handle the additional load. What is the most cost-effective EC2 instance purchasing option for this job?
    - A. Savings Plans.
    - B. Spot Instances.
    - C. Reserved Instances.
    - D. On-Demand Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        Spot은 중단될 수 있고, RI/Savings Plan은 장기 약정이 필요합니다. 온디맨드는 단기적이고 예측 불가능한 수요에 유연하고 가장 비용 효율적입니다.
    </details>

34. What is the Amazon ElastiCache service used for? (Choose TWO)
    - A. Provide an in-memory data storage service.
    - B. Reduce delivery costs using Edge Locations.
    - C. Improve web application performance.
    - D. Provide a Chef-compatible cache to speed up application response.
    - E. Distribute requests to multiple instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
        ElastiCache는 인메모리 캐싱을 통해 데이터베이스 또는 API 호출에 대한 지연 시간을 줄여 성능을 향상시킵니다.
    </details>

35. The elasticity of the AWS Cloud enables customers to save costs when compared to traditional hosting providers. What can AWS customers do to benefit from the elasticity of the AWS Cloud? (Choose TWO)
    - A. Deploy your resources across multiple Availability Zones.
    - B. Use Amazon EC2 Auto Scaling.
    - C. Deploy your resources in another region.
    - D. Use Elastic Load Balancing.
    - E. Use Serverless Computing whenever possible.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E
        Auto Scaling과 서버리스는 수요 변화에 따라 리소스를 자동으로 확장/축소하여 낭비를 줄입니다.
    </details>

37. Each AWS Region is composed of multiple Availability Zones. Which of the following best describes what an Availability Zone is?
    - A. It is a data center designed to be completely isolated from other data centers in the same region.
    - B. It is a collection of data centers distributed in multiple countries.
    - C. It is a logically isolated network of the AWS Cloud.
    - D. It is a distinct location within a region that is insulated from « failures in other Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        AZ는 논리적으로 분리되어 있으면서도 지리적으로는 가까운 독립된 데이터 센터입니다.
    </details>

39. A financial services company decides to migrate one of its applications to AWS. The application deals with sensitive data, such as credit card information, and must run on a PCI-compliant environment. Which of the following is the company’s responsibility when building a PCI-compliant environment in AWS? (Choose TWO)
    - A. Start the migration process immediately as all AWS services are PCI compliant.
    - B. Ensure that AWS services are configured properly to meet all PCI DSS standards.
    - C. Restrict any access to cardholder data and create a policy that addresses information security for all personnel.
    - D. Configure the underlying infrastructure of AWS services to meet all PCI DSS requirements.
    - E. Ensure that all PCI DSS physical security requirements are met.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        공유 책임 모델에 따라 구성(B) 및 **고객 측 데이터 관리/정책(C)**은 고객의 책임입니다.
    </details>

40. What is the maximum amount of data that can be stored in S3 in a single AWS account?
    - A. 100 PetaBytes.
    - B. Virtually unlimited storage.
    - C. 5TeraBytes.
    - D. 10 Exabytes.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        S3는 무제한 스토리지 용량을 제공합니다.
    </details>

41. Which pillar of the AWS Well-Architected Framework provides recommendations to help customers select the right compute resources based on workload requirements?
    - A. Operational Excellence.
    - B. Security.
    - C. Performance Efficiency.
    - D. Reliability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        성능 효율성 기둥은 리소스 선택 및 최적화에 중점을 둡니다.
    </details>

49. Which is a recommended pattern for designing a highly available architecture on AWS?
    - A. Ensure that components have low-latency network connectivity.
    - B. Run enough Amazon EC2 instances to operate at peak load.
    - C. Ensure that the application is designed to accommodate failure of any single component.
    - D. Use a monolithic application that handles all operations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        단일 장애 지점 제거는 고가용성의 기본 원칙입니다.
    </details>

50. Which AWS characteristics make AWS cost effective for a workload with dynamic user demand? (Select TWO)
    - A. High availability.
    - B. Shared security model.
    - C. Elasticity.
    - D. Pay-as-you-go pricing.
    - E. Reliability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
        탄력성을 통해 필요한 만큼만 사용하고, 종량제를 통해 사용한 만큼만 지불하여 비용 효율성을 높입니다.
    </details>

