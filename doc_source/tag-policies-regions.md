# Supported Regions<a name="tag-policies-regions"></a>

Tag policy features are available in the following Regions: 


| Region Name | Region Parameter | 
| --- | --- | 
| US East \(Ohio\) Region | `us-east-2` | 
| US East \(N\. Virginia\) Region¹ | **`us-east-1`** | 
| US West \(N\. California\) Region | `us-west-1` | 
| US West \(Oregon\) Region | `us-west-2` | 
| Asia Pacific \(Hong Kong\) Region² | `ap-east-1` | 
| Asia Pacific \(Mumbai\) Region | `ap-south-1` | 
| Asia Pacific \(Osaka\-Local\) Region³ | `ap-northeast-3` | 
| Asia Pacific \(Seoul\) Region | `ap-northeast-2` | 
| Asia Pacific \(Singapore\) Region | `ap-southeast-1` | 
| Asia Pacific \(Sydney\) Region | `ap-southeast-2` | 
| Asia Pacific \(Tokyo\) Region | `ap-northeast-1` | 
| Canada \(Central\) Region | `ca-central-1` | 
| EU \(Frankfurt\) Region | `eu-central-1` | 
| EU \(Ireland\) Region | `eu-west-1` | 
| EU \(London\) Region | `eu-west-2` | 
| EU \(Paris\) Region | `eu-west-3` | 
| EU \(Stockholm\) Region | `eu-north-1` | 
| Middle East \(Bahrain\) Region² | `me-south-1` | 
| South America \(São Paulo\) Region | `sa-east-1` | 

**¹You must specify the `us-east-1` Region when calling the following Organizations operations:**
+ [DeletePolicy](https://docs.aws.amazon.com/organizations/latest/APIReference/API_DeletePolicy.html)
+ [DisablePolicyType](https://docs.aws.amazon.com/organizations/latest/APIReference/API_DisablePolicyType.html)
+ [EnablePolicyType](https://docs.aws.amazon.com/organizations/latest/APIReference/API_EnablePolicyType.html)
+ Any other operations on an organization root, such as [ListRoots](https://docs.aws.amazon.com/organizations/latest/APIReference/API_ListRoots.html)\.

**You must also specify the `us-east-1` Region when calling the following Resource Groups Tagging API operations that are part of the tag policies feature:**
+ [DescribeReportCreation](https://docs.aws.amazon.com//resourcegroupstagging/latest/APIReference/API_DescribeReportCreation.html)
+ [GetComplianceSummary](https://docs.aws.amazon.com//resourcegroupstagging/latest/APIReference/API_GetComplianceSummary.html)
+ [GetResources](https://docs.aws.amazon.com//resourcegroupstagging/latest/APIReference/API_GetResources.html)
+ [StartReportCreation](https://docs.aws.amazon.com//resourcegroupstagging/latest/APIReference/API_StartReportCreation.html)

²These Regions must be manually enabled\. To learn more about enabling and disabling AWS Regions, see [Managing AWS Regions](https://docs.aws.amazon.com/general/latest/gr/rande-manage.html) in the *AWS General Reference*\. The Resource Groups console is not available in these Regions\.

³This Region doesn't support reporting on resources\.