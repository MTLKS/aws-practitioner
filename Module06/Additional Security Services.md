### AWS KMS
AWS Key Management Service (AWS KMS) enables you to perform encryption operations through the use of cryptographic keys. You can use AWS KMS to create, manage, and use cryptographic keys.

With AWS KMS, you can choose the specific levels of access control that you need for your keys, for example, which [[IAM users]] and [[IAM roles|roles]] are able to manage keys. Alternatively, you can temporarily disable keys so that they are no longer in use by anyone.

### AWS WAF
AWS Web Application Firewall (AWS WAF) lets you monitor network requests that come into your web applications. AWS WAF works together with [[Edge Locations#Amazon CloudFront|Amazon CloudFront]] and an Application Load Balancer. AWS WAF works in a similar way as [[Network ACL|network ACLs]] to block or allow traffic.

### Amazon Inspector
Amazon Inspector helps to improve the security and compliance of applications by running automated security assessments. It checks applications for security vulnerabilities and deviations from security best practices. After it has performed an assessment, it provides you with a list of security findings, prioritized by severity level, and includes a detailed description and a recommendation for how to fix it.

### Amazon GuardDuty
Amazon GuardDuty is a service that provides intelligent threat detection for your AWS infrastructure and resources. GuardDuty continously analyzes data from multiple AWS sources, including VPC Flow Logs and DNS logs.

If GuardDuty detects any threats, you can review detailed findings about them from the AWS Management Console. You can also configure [[AWS Lambda]] functions to take remediation steps automatically in response to GuardDuty's security findings.