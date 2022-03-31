# rds\-instance\-default\-admin\-check<a name="rds-instance-default-admin-check"></a>

Checks if an Amazon Relational Database Service \(Amazon RDS\) database has changed the admin username from its default value\. This rule will only run on RDS database instances\. The rule is NON\_COMPLIANT if the admin username is set to the default value\. 

**Identifier:** RDS\_INSTANCE\_DEFAULT\_ADMIN\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

validAdminUserNames \(Optional\)Type: CSV  
Comma\-separated list of admin username\(s\) that Amazon RDS instances can use\. \(Cannot include 'postgres' or 'admin' as valid username\(s\) as these are default values\.\)

## AWS CloudFormation template<a name="w76aac11c31c17b7d379c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.