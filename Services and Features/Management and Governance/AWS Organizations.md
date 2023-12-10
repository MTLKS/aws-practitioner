# AWS Organizations

#essentials 

[AWS Organizations](https://aws.amazon.com/organizations/) lets you create new AWS accounts at no additional charge. With accounts in an organization, you can easily allocate resources, group accounts, and apply governance policies to accounts or groups.

#### Essentials description:
AWS Organizations are used to consolidate and manage multiple AWS accounts within a central location. When you create an organization, a root is automatically created, which is the parent container for all the accounts in your organization.

In AWS Organizations, you can centrally control permissions for the accounts in your organization by using Service Control Policies (SCPs). SCPs enable you to place restrictions on the AWS services, resources, and individual API actions that users and roles in each account can access.

### Organizational units
You can group accounts into organizational units (OUs) to make it easier to manage accounts with similar business or security requirements. When you apply a policy to an OU, all the accounts in the OU automatically inherit the permissions specified in the policy.
