Amazon Simple Storage Service (Amazon S3) is a service that provides object-level storage. Amazon S3 stores data as objects in buckets. The maximum file size for an object in Amazon S3 is 5 TB.

You can set permissions to control visibility and access to files. You can also use versioning to track changes to the objects over time.

### Amazon S3 storage classes
With Amazon S3, you pay only for what you use. There are two factors when selecting an Amazon S3 storage class:
- How often you plan to retrieve your data
- How available you need your data to be

#### S3 Standard
- Designed for frequently accessed data
- Stores data in a minimum of three Availability Zones
- Higher costs than other storage classes intended for infrequently accessed data and archival storage.

#### S3 Standard-Infrequent Access (S3 Standard-IA)
- Ideal for infrequently accessed data
- Stores data in a minimum of three Availability Zones
- Lower storage price than S3 Standard
- Higher retrieval price than S3 Standard

#### S3 One Zone-Infrequent Access (S3 One Zone-IA)
- Stores data in a single Availability Zone
- Has a lower storage price than Amazon S3 Standard-IA

#### S3 Intelligent-Tiering
- Ideal for data with unknown or changing access patterns
- Requires a small monthly monitoring and automation fee per object
- Moves objects from S3 Standard to S3 Standard-IA if not accessed for 30 consecutive days.
- Moves objects from S3 Standard-IA to S3 Standard when accessed.

#### S3 Glacier Instant Retrieval
- Works well for archived data that requires immediate access
- Can retrieve objects within a few milliseconds.

#### S3 Glacier Flexible Retrieval
- Low-cost storage designed for data archiving
- Able to retrieve objects within a few minutes to hours

#### S3 Glacier Deep Archive
- Lowest-cost object storage class ideal for archiving
- Able to retrieve objects within 12 to 48 hours

#### S3 Outposts
- Creates S3 buckets on Amazon S3 Outposts
- Makes it easier to retrieve, store, and access data on [[Edge Locations|AWS Outposts]]
