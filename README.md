# Setting-up-two-websites-on-a-single-domain-AWS

Hosting several subdomains in the same S3 bucket can be a great solution if you want to save time and money. Using only one S3 bucket means saving money because Amazon charges you for the size and amount of buckets, so fewer buckets mean fewer expenses. Besides that, it’s simpler and easier to configure just one AWS Cloudfront, instead of setting it up a few times.

Document in this repository will explain to you step-by-step how to host multiple sites with just one s3 bucket + Lambda@Edge.

Requirements:
- Access to AWS console
- Access to s3, Cloudfront, Certificate Manager, and Lambda
- Own a domain
