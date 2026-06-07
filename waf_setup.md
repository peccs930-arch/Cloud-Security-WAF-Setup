# AWS WAF Setup Steps

1. Login to AWS Console.
2. Open AWS WAF Service.
3. Create a Web ACL.
4. Add Rules:
   - SQL Injection Protection
   - XSS Protection
   - Rate Limiting
   - IP Blocking
5. Associate the Web ACL with:
   - Application Load Balancer
   - CloudFront Distribution
6. Monitor traffic using CloudWatch.
