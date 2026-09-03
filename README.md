# Activity-audit
## NAME : S Madhumitha

## REG.NO : 212225040217

## DATE : 28/08/2026



ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS AND AZURE

## Objective

To identify storage assets in AWS S3 and Microsoft Azure Blob Storage, identify possible vulnerabilities and threats, and assess their likelihood, impact, and risk level.

Software / Cloud Services Required
• AWS Account

• Microsoft Azure Account

• Web Browser

• Internet Connection

Cloud Services Used

Cloud Platform Storage Service

AWS Amazon S3

Microsoft Azure Azure Blob Storage

PART A — AWS S3 STORAGE ASSESSMENT

Step 1: Login to AWS

Open the AWS Management Console.

Sign in using your AWS account.

Search for S3.

Select Amazon S3.

Step 2: Select the S3 Bucket

Click Buckets.

Select the S3 bucket created in the previous experiment.

Record:

o Bucket name

o AWS Region

o Number/type of objects



Open the S3 bucket.

Select Permissions.

Locate Block public access (bucket settings).

Check Block all public access.
<img width="1920" height="1020" alt="Screenshot 2026-09-03 150508" src="https://github.com/user-attachments/assets/1d5f454c-df75-49e6-9f2a-59c446f3a2b2" />

Record:

• ON → Secure configuration

• OFF → Potential public-access risk

Step 4: Check Bucket Versioning

Select the Properties tab.

Locate Bucket Versioning.

Record whether it is:

o Enabled

o Disabled
<img width="1920" height="1020" alt="Screenshot 2026-09-03 124153" src="https://github.com/user-attachments/assets/fef89301-a315-47e9-a815-729b9dd5a22d" />

Security purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.


Step 5: Check Default Encryption

Stay in the Properties tab.

Locate Default encryption.

Record the encryption type.

Possible configurations include:

• SSE-S3

• SSE-KMS

• DSSE-KMS

Security purpose

Encryption protects stored data from unauthorized disclosure.


Step 6: Check Bucket Policy

Select Permissions.

Locate Bucket policy.

Check whether a bucket policy exists.

Record:

• Policy exists

• No policy

Note

A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.

Step 7: Check Object Ownership and ACL

In Permissions, locate Object Ownership. Record the current configuration. A common secure configuration is:

Bucket owner enforced

This means:

• ACLs are disabled.

• Objects are owned by the bucket owner.

• Access is controlled using policies.


Step 8: Check Server Access Logging

Go to Properties.

Locate Server access logging.

Record whether it is:

o Enabled

o Disabled

Security purpose

Logging helps investigate suspicious or unauthorized access to the bucket.

PART B — AWS RISK ASSESSMENT

After checking the S3 configuration, identify possible vulnerabilities and threats.

Risk Formula

Risk Score = Likelihood × Impact

Use the following scale.

Likelihood


Sample AWS Risk Assessment

<img width="1920" height="1020" alt="Screenshot 2026-09-03 122734" src="https://github.com/user-attachments/assets/9fc4bf08-962d-47b1-9cab-1b93560a91fa" />

## RESULT

The storage assets in AWS S3 were identified and analyzed. Various security configurations, vulnerabilities, threats, likelihood, and impacts were evaluated. Risk scores were calculated using the Likelihood × Impact method, and appropriate security mitigation measures were recommended.

About No description, website, or topics provided. Resources Readme Activity Stars 0 stars Watchers 0 watching Forks 0 forks Report repository Releases No releases published Packages No packages published Contributors No contributors Footer
