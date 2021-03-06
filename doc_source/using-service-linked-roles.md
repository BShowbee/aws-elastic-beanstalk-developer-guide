# Using Service\-Linked Roles for Elastic Beanstalk<a name="using-service-linked-roles"></a>

AWS Elastic Beanstalk uses AWS Identity and Access Management \(IAM\)[ service\-linked roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_terms-and-concepts.html#iam-term-service-linked-role)\. A service\-linked role is a unique type of IAM role that is linked directly to Elastic Beanstalk\. Service\-linked roles are predefined by Elastic Beanstalk and include all the permissions that the service requires to call other AWS services on your behalf\. 

Elastic Beanstalk defines two types of service\-linked roles:
+ *Monitoring service\-linked role* – Allows Elastic Beanstalk to monitor the health of running environments and publish health event notifications\.
+ *Maintenance service\-linked role* – Allows Elastic Beanstalk to perform regular maintenance activities for your running environments\.

**Topics**
+ [The Monitoring Service\-Linked Role](using-service-linked-roles-monitoring.md)
+ [The Maintenance Service\-Linked Role](using-service-linked-roles-maintenance.md)