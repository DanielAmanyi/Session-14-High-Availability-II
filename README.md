# SnapGallery – Highly Available Web App with Shared Storage and S3 Error Page

Scenario Summary
The DevOps Team has been tasked to provide infrastructure support for one of our clients running a product, SnapGallery, which is preparing for a major product launch. The CTO requires a resilient AWS infrastructure to host their image-sharing web application with high availability, shared storage, and graceful failure handling.
Your task is to build a production-ready web application infrastructure on AWS that meets the following requirements:
• Two EC2 instances (in different Availability Zones) will host the Apache-based web application and serve image content.
• Both EC2 instances must mount a shared Amazon EFS file system to store user- uploaded content, ensuring consistency and availability.
• An Application Load Balancer (ALB) must distribute incoming traffic evenly across the two EC2 instances.
• In the event that both EC2 instances become unavailable, the ALB should automatically redirect users to a static error page hosted on Amazon S3.
Your solution must be robust, scalable, and capable of handling production traffic, even in the face of instance failures or zone outages.


Follow the enclosed pdf for guided Lab
