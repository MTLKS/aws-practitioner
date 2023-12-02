Amazon Elastic Block Store (Amazon EBS) is a service that provides block-level storage volumes that you can use with Amazon EC2 instances. The data on the EBS volume remains available even if you stop or terminate the EC2 instance it is attached to.

Because EBS volumes are for data that needs to persist, it is important to backup the data. You can take incremental backups of EBS volumes by creating Amazon EBS snapshots.

### Amazon EBS snapshot
An EBS snapshot is an incremental backup. The first backup copies all the data in the volume, but subsequent backups, only blocks of data that have changed are saved.