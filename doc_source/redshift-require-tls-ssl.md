# redshift\-require\-tls\-ssl<a name="redshift-require-tls-ssl"></a>

Checks whether Amazon Redshift clusters require TLS/SSL encryption to connect to SQL clients\. The rule is NON\_COMPLIANT if any Amazon Redshift cluster has parameter require\_SSL not set to true\. 

**Identifier:** REDSHIFT\_REQUIRE\_TLS\_SSL

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\), Asia Pacific \(Osaka\), Europe \(Milan\), Europe \(Spain\), Europe \(Zurich\) Region

**Parameters:**

None  

## AWS CloudFormation template<a name="w2aac12c31c27b9d463c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.