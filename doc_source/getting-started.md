# Getting started with Amazon Elastic File System<a name="getting-started"></a>

In this Getting Started exercise, you can learn how to quickly create an Amazon Elastic File System \(Amazon EFS\) file system\. As part of this process, you mount your file system on an Amazon Elastic Compute Cloud \(Amazon EC2\) instance in your virtual private cloud \(VPC\)\. You also test the end\-to\-end setup\.

There are four steps that you need to perform to create and use your first Amazon EFS file system:
+ Create your Amazon EFS file system\.
+ Create your Amazon EC2 resources, launch your instance, and mount the file system\.
+ Transfer files to your EFS file system using AWS DataSync\.
+ Clean up your resources and protect your AWS account\.

**Topics**
+ [Assumptions](#gs-assumptions)
+ [Related topics](#gs-related-topics)
+ [Step 1: Create your Amazon EFS file system](gs-step-two-create-efs-resources.md)
+ [Step 2: Create your EC2 resources and launch your EC2 instance](gs-step-one-create-ec2-resources.md)
+ [Step 3: Transfer files to Amazon EFS using AWS DataSync](gs-step-four-sync-files.md)
+ [Step 4: Clean up resources and protect your AWS account](gs-step-five-cleanup.md)

## Assumptions<a name="gs-assumptions"></a>

For this exercise, we assume the following:
+ You're already familiar with using the Amazon EC2 console to launch instances\.
+ Your Amazon VPC, Amazon EC2, and Amazon EFS resources are all in the same AWS Region\. This guide uses the US West \(Oregon\) Region \(us\-west\-2\)\.
+ You have a default VPC in the AWS Region that you're using for this Getting Started exercise\. If you don't have a default VPC, or if you want to mount your file system from a new VPC with new or existing security groups, you can still use this Getting Started exercise\. To do so, configure [Using VPC security groups for Amazon EC2 instances and mount targets](network-access.md)\.
+ You haven't changed the default inbound access rule for the default security group\.

You can use your AWS account root user credentials to sign in to the console and try the Getting Started exercise\. However, AWS Identity and Access Management \(IAM\) recommends that you do not use the account root user credentials\. Instead, create an administrator user in your account and use those credentials to manage resources in your account\. For more information, see [Setting Up](setting-up.md)\.

## Related topics<a name="gs-related-topics"></a>

This guide also provides a walkthrough to perform a similar Getting Started exercise using AWS Command Line Interface \(AWS CLI\) commands to make the Amazon EFS API calls\. For more information, see [Walkthrough: Create an Amazon EFS file system and mount it on an Amazon EC2 instance using the AWS CLI](wt1-getting-started.md)\.