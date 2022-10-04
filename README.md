# CFn-sample-cloudfront-oac
CloudFormation template for building a static site delivery environment with CloudFront and S3. OAC is used for origin access control.

## static-site-deploy-default.yaml
Template for using the default CloudFront domain name.

## static-site-deploy-cname.yaml
Template for delivery on a custom domain using a TLS certificate issued by AWS Certificate Manager (ACM). You will need to specify the CNAME and ACM identifier when deploying.
