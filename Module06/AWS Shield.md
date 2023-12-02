AWS Shield is a service that protects applications against [[Denial-of-Service#Distributed Denial-of-Service attacks|DDoS attacks]]. There are two levels of protection:

### AWS Shield Standard
AWS Shield Standard automatically protects all AWS customers at no cost. It protects your AWS resources from the most common, frequently occurring types of DDoS attacks. AWS Shield Standard uses a variety of analysis techniques to detect malicious traffic in real time and automatically mitigates it.

### AWS Shield Advanced
AWS Shield Advanced is a paid service that provides attack diagnostics and the ability to detect and mitigate sophisticated DDoS attacks. It integrates with services such as [[Edge Locations|Amazon CloudFront]], [[Amazon Route 53]], and [[Elastic Load Balancing]]. Additionally, you can integrate AWS Shield with AWS Web Application Firewall (WAF) by writing custom rules to mitigate complex DDoS attacks.