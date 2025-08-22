# Scaling

## What is Scaling?
* Scaling in distributed systems means making a system bigger so it can handle more work as needed. As more users, data, and tasks are added, the system needs to grow to keep working well.
* Goal : maintain performance when user requests increase.

## Types of Scaling

### Vertical Scaling
* This means making a single server more powerful by adding more CPU, memory, or storage.
* Easy to do but limited by hardware capacity.
* Example: upgrading from 8 GB RAM to 32 GB RAM.

### Horizontal Scaling
* Add more servers to share the work.
* Increases total system capacity.
* Needs a load balancer to distribute requests.
* Example: if a website starts getting a lot of visitors, you can add more web servers to manage the increased traffic.

## Load Balancers
* Spread traffic across multiple servers.
* Prevent a single server from being overloaded.
* Improve reliability and availability.

## When to Use
* Vertical scaling : quick boost for small apps.
* Horizontal scaling + load balancer : best for large apps with high traffic.

## Key Points
* Scaling helps systems grow without slowing down.
* Vertical scaling = bigger single server.
* Horizontal scaling = more servers working together.
* Load balancer = keeps traffic balanced.  

## References
* [System Design Basics - Scaling](https://www.geeksforgeeks.org/system-design/scaling-distributed-systems/)
* [AWS: Elastic Load Balancing](https://www.w3schools.com/aws/aws_cloudessentials_ec2elasticloadbalancing.php)
* [Wikipedia Documentation](https://en.wikipedia.org/wiki/Scalability)
