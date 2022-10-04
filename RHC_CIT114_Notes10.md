# CIT 114 Notes 10: Automatic Scaling and Monitoring
### AWS CloudWatch
* Cloudwatch allows you to record metrics for EBS, EC2, ELB, and S3
* You can set alarms for activity
### CloudWatch Terminology
* Metric is short for how something is measurred. Helps things get managed best
* A Dimension describes the metric and what data it stores.
* Units of Measurement. 
* Time periods can range from 1 minute to 15 months
### Elastic Load Balancing
* Load balancing spreads out network traffic among multiple servers.
* If one server goes down, no break in services.
* AWS services come with automatic load balancing.
* ELB is redundant
### Auto Scaling
* EC2 auto scaling lets us launch or terminate instances controlled by CloudWatch alarms. Metrics come with auto-scaling group metrics like the min and max group size in service.

