# AWS IAM Custom Policy Project

##  Project Overview

Created and implemented a custom IAM policy to provide read-only access to Amazon S3 resources. Attached the policy to an IAM user and verified permission boundaries by testing access restrictions.

##  AWS Services Used

* AWS Identity and Access Management (IAM)
* Amazon S3
  
##  Project Objectives

* Create a custom IAM policy
* Grant least-privilege permissions
* Attach policies to IAM users
* Validate access restrictions

##  Steps Followed

1. Opened the IAM console
2. Created a custom policy using the Visual Editor
3. Selected Amazon S3 as the service
4. Allowed the following actions:

   * `s3:ListBucket`
   * `s3:GetObject`
5. Applied the policy to all S3 resources
6. Created a new IAM user
7. Attached the custom policy to the user
8. Enabled AWS Management Console access
9. Logged in as the IAM user
10. Tested permissions by attempting S3 operations

##  Permissions Granted

* View S3 buckets
* List bucket contents
* Read objects from S3

##  Restricted Actions

* Create buckets
* Upload objects
* Delete buckets
* Modify bucket settings

##  Outcome

Successfully implemented a custom IAM policy and verified that the user could only perform read-only operations on Amazon S3 resources.

##  Key Learnings

* IAM Policies
* IAM Users
* Principle of Least Privilege
* Access Control
* AWS Security Best Practices
* Permission Boundaries
