---
layout: exam
---

# Practice Exam 18

1. Under the AWS shared responsibility model, which of the following is an example of security in the AWS Cloud?
    - A. Managing edge locations
    - B. Physical security
    - C. Firewall configuration
    - D. Global infrastructure

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/compliance/shared-responsibility-model/></br>
    방화벽 구성 (보안 그룹, 네트워크 ACL)은 고객이 직접 리소스를 보호하기 위해 설정하는 부분으로, 클라우드 내부 보안에 해당합니다.

    </details>

3. Which of the following are pillars of the AWS Well-Architected Framework? (Choose two.)
    - A. Multiple Availability Zones
    - B. Performance efficiency
    - C. Security
    - D. Encryption usage
    - E. High availability

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BC

    Explanation: <https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf></br>
    Well-Architected Framework는 운영 우수성, 보안, 안정성, 성능 효율성, 비용 최적화의 다섯 가지 기둥으로 구성됩니다.

    </details>

5. What is an advantage of deploying an application across multiple Availability Zones?
    - A. There is a lower risk of service failure if a natural disaster causes a service disruption in a given AWS Region.
    - B. The application will have higher availability because it can withstand a service disruption in one Availability Zone.
    - C. There will be better coverage as Availability Zones are geographically distant and can serve a wider area.
    - D. There will be decreased application latency that will improve the user experience.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html></br>
    단일 가용 영역의 서비스 중단에도 애플리케이션이 높은 가용성을 유지할 수 있기 때문입니다.

    </details>

8. A web application running on AWS has been spammed with malicious requests from a recurring set of IP addresses. <br/> Which AWS service can help secure the application and block the malicious traffic?
    - A. AWS IAM
    - B. Amazon GuardDuty
    - C. Amazon Simple Notification Service (Amazon SNS)
    - D. AWS WAF

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - AWS WAF is a web application firewall that helps protect web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources.
    - You can use AWS WAF to define customizable web security rules that control which traffic accesses your web applications.
    - If you use AWS Shield Advanced, you can use AWS WAF at no extra cost for those protected resources and can engage the DRT to create WAF rules.

    Reference: <https://aws.amazon.com/answers/networking/aws-ddos-attack-mitigation/></br>

    </details>

10. A company requires a dedicated network connection between its on-premises servers and the AWS Cloud. <br/> Which AWS service should be used?
    - A. AWS VPN
    - B. AWS Direct Connect
    - C. Amazon API Gateway
    - D. Amazon Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC, providing you with a private, high bandwidth network connection between your network and your VPC.
    - With multiple virtual interfaces, you can even establish private connectivity to multiple VPCs while maintaining network isolation.

    Reference: <https://aws.amazon.com/directconnect/></br>
    AWS Direct Connect는 고객의 데이터 센터와 AWS 간에 전용의 사설 네트워크 연결을 설정합니다.

    </details>

17. How can a company isolate the costs of production and non-production workloads on AWS?
    - A. Create Identity and Access Management (IAM) roles for production and non-production workloads.
    - B. Use different accounts for production and non-production expenses.
    - C. Use Amazon EC2 for non-production workloads and other services for production workloads.
    - D. Use Amazon CloudWatch to monitor the use of services.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/answers/account-management/aws-multi-account-billing-strategy/></br>
    프로덕션 및 비프로덕션 환경에 대해 별도의 AWS 계정을 사용하는 것이 비용을 가장 명확하게 격리하고 관리하는 모범 사례입니다.

    </details>

21. Which security service automatically recognizes and classifies sensitive data or intellectual property on AWS?
    - A. Amazon GuardDuty
    - B. Amazon Macie
    - C. Amazon Inspector
    - D. AWS Shield

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - Amazon Macie is a security service that uses machine learning to automatically discover, classify, and protect sensitive data in AWS.
    - Macie recognizes sensitive data such as personally identifiable information (PII) or intellectual property.
    - It provides you with dashboards and alerts that give visibility into how this data is being accessed or moved.

    Reference: <https://docs.aws.amazon.com/macie/latest/userguide/what-is-macie.html></br>

    </details>

29. How does AWS charge for AWS Lambda usage once the free tier has been exceeded? (Choose two.)
    - A. By the time it takes for the Lambda function to execute.
    - B. By the number of versions of a specific Lambda function.
    - C. By the number of requests made for a given Lambda function.
    - D. By the programming language that is used for the Lambda function.
    - E. By the total number of Lambda functions in an AWS account.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: AC

    Explanation: <https://aws.amazon.com/lambda/pricing/></br>
    Lambda 함수에 대한 요청 수와 **함수가 실행되는 시간(기간)**에 따라 요금이 청구됩니다.

    </details>

35. Which AWS service allows users to identify the changes made to a resource over time?
    - A. Amazon Inspector
    - B. AWS Config
    - C. AWS Service Catalog
    - D. AWS IAM

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://docs.aws.amazon.com/config/latest/developerguide/view-manage-resource.html></br>
    AWS Config는 리소스 구성의 변경 사항을 지속적으로 기록하고 추적하여 **구성 기록(history)**을 제공합니다.

    </details>

37. Which activity is a customer responsibility in the AWS Cloud according to the AWS shared responsibility model?
    - A. Ensuring network connectivity from AWS to the internet
    - B. Patching and fixing flaws within the AWS Cloud infrastructure
    - C. Ensuring the physical security of cloud data centers
    - D. Ensuring Amazon EBS volumes are backed up

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/blogs/security/the-aws-shared-responsibility-model-and-gdpr/></br>

    </details>

40. Which AWS feature allows a company to take advantage of usage tiers for services across multiple member accounts?
    - A. Service control policies (SCPs)
    - B. Consolidated billing
    - C. All Upfront Reserved Instances
    - D. AWS Cost Explorer

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/tco-calculator/></br>
    **통합 결제(Consolidated billing)**는 조직 내 모든 계정의 사용량을 합산하여 볼륨 할인 또는 사용량 계층 혜택을 받을 수 있도록 합니다.

    </details>

44. Which AWS service provides a quick and automated way to create and manage AWS accounts?
    - A. AWS QuickSight
    - B. Amazon Lightsail
    - C. AWS Organizations
    - D. Amazon Connect

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation: <https://aws.amazon.com/blogs/mt/automate-account-creation-and-resource-provisioning-using-aws-service-catalog-aws-organizations-and-aws-lambda/></br>
    AWS Organizations는 여러 AWS 계정을 중앙 집중식으로 관리하고 새 계정을 쉽게 생성할 수 있도록 합니다.

    </details>