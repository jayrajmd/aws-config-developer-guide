# lambda\-concurrency\-check<a name="lambda-concurrency-check"></a>

Checks whether the AWS Lambda function is configured with function\-level concurrent execution limit\. The rule is NON\_COMPLIANT if the Lambda function is not configured with function\-level concurrent execution limit\. 

**Identifier:** LAMBDA\_CONCURRENCY\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\), Middle East \(UAE\), Asia Pacific \(Osaka\), Europe \(Spain\), China \(Ningxia\), Europe \(Zurich\) Region

**Parameters:**

ConcurrencyLimitLow \(Optional\)Type: String  
Minimum concurrency execution limit

ConcurrencyLimitHigh \(Optional\)Type: String  
Maximum concurrency execution limit

## AWS CloudFormation template<a name="w2aac12c31c27b9d361c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.