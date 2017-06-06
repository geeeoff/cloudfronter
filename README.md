# cloudfronter
### A simple yet robust AWS Cloud Formation Template (CFT) to get your website up and running on AWS CloudFront.

#### Features:

1. Redirect from http to https
2. Redirect from the www domain to the zone apex / root / naked domain name
3. Creates SSL certificates
5. Creates and configures S3 buckets
6. Creates hosted zone (if necessary) and adds appropriate record sets

#### Usage:

1. Install AWS CLI
2. Configure your AWS CLI credentials
3. Type the following: ```aws cloudformation create-stack --stack-name <name-for-your-stack>  --template-body <path-to-cloudFront.json-file> --parameters ParameterKey=RootDomainName,ParameterValue=<your-root-domain>```


contribute. live. thrive.  
:rocket: :smile: :muscle:
