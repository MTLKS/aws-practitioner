### Scalability
Involves beginning with only the resources you need and designing the architecture to automatically respond to changing demand by scaling in or out. As a result, you pay for only the resources you use.

### Amazon EC2 Auto Scaling
Enables you to automatically add or remove Amazon EC2 instances in response to changing application demand, maintaining a greater sense of application availability. 

Within Amazon EC2 Auto Scaling, you can use two approaches: dynamic scaling and predictive scaling.
- Dynamic scaling responds to changing demand.
- Predictive scaling automatically schedules the right number of Amazon EC2 instances based on predicted demand.

### Example: Amazon EC2 Auto Scaling

#### Configuration 1: Minimum
When you create an Auto Scaling group, you can set the minimum number of Amazon EC2 instances. The minimum capacity is the number of Amazon EC2 instances that launch immediately after you have created the Auto Scaling group.

#### Configuration 2: Desired
Next, you can set the desired capacity of two Amazon EC2 instances even though your application needs a minimum of a single Amazon EC2 instance to run. If the desired number is not specified, it defaults to the minimum capacity.

#### Configuration 3: Maximum
You may set a maximum capacity in the Auto Scaling group, so that the scale out in response to increased demand does not exceed too many instances.