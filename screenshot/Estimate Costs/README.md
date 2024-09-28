## Budget Estimate
### Cost Reduction Changes
Changes:

- Use more small EC2 instances
- Reduce S3 Standard storage
- Use smaller RDS instances

Reason:
- Using smaller EC2 instances allows for more granular auto-scaling but may reduce performance.
- Reducing S3 Standard storage allows for cost savings but will reduce storage capacity
- Using smaller RDS instances allows for significant cost savings but will reduce database performance.

Changes:

- Use larger EC2 instances
- Use larger RDS instances
- Reduce S3 Standard storage
- Set up a third availability zone in us-east-2

Reason:
- Larger EC2 instances improve application performance and prepare for platform growth over time.
- A third availability zone within the second zone allows failover if the entire us-east-1 zone goes down.
- Larger RDS instances improve database performance and prepare for platform growth over time.