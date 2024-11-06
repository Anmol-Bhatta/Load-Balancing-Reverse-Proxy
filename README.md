This repository contains a self-implemented load balancing system centered around a reverse proxy, designed to distribute HTTP requests across multiple application servers. Built using C# in .NET Core and deployed on AWS EC2 instances, this project demonstrates several load balancing algorithms, including Weighted Round Robin, Least Connections, Geolocation Global, and Weighted Fault Avoidance.

The system includes a central server with a reverse proxy, multiple distributed application servers, and an MSSQL RDS instance for caching and logging. This setup enables efficient request distribution, scalability, and enhanced availability for web applications.

Key components:

Load balancing algorithms to optimize server load.
AWS EC2 and RDS integration for distributed server and database management.
Real-time server monitoring to ensure consistent performance and reliability.
Ideal for developers and students exploring load balancing concepts and implementation.






