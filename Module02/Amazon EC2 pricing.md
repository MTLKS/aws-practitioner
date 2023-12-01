### On-Demand
Ideal for short-term, irregular workloads that cannot be interrupted. No upfront costs or minimum contracts apply. The instances run continuously until you stop them, and you pay for only the compute time you use.

### Reserved Instances
A billing discount applied to the use of On-Demand Instances, which are purchasable for a 1-year or 3-year term.

Standard Reserved Instances - good fit if you know the EC2 instance type and size needed. Requires you to state the following qualifications:
- Instance type and size: Eg, m5.xlarge
- Platform description (operating system): Eg, Microsoft Windows Server
- Tenancy: Default tenancy or dedicated tenancy

Convertible Reserved Instances - if the EC2 instances need to run in different Availability Zones or different instance types.

At the end of a Reserved Instance term, you can continue using the Amazon EC2 instance, but are charged On-Demand rates until you:
- terminate the instance.
- purchase a new Reserved Instance.

### EC2 Instance Savings Plans
Reduces your EC2 instance costs when you make an hourly spend commitment to an instance family and Region for a 1-year or 3-year term. Saves up to 72% compared to On-Demand rates. Any usage beyond the commitment is charged at regular On-Demand rates.

Unlike Reserved Instances, you don't need to specify up front what EC2 instance type and size, OS, and tenancy to get a discount.

### Spot Instances
Ideal for workloads with flexible start and end times, or that can withstand interruptions. Spot Instances utilizes unused Amazon EC2 computing capacity and offers up to 90% cost savings.

After launching the instance, if capacity is no longer available or demand for Spot Instances increases, the instance may be interrupted.

### Dedicated Hosts
Physical servers with Amazon EC2 instance capacity that is fully dedicated to your use. Existing per-socket, per-core, or per-VM software licenses to help maintain license compliance. Of all options, Dedicated Hosts are the most expensive.

