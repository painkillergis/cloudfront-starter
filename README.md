# cloudfront-starter
Creates an SSL-terminating Cloudfront distribution backed by an S3 bucket

## Setup

```
./eject
devops/aws:s3/create-bucket
devops/aws:acm/request-certificate
devops/aws:cloudfront/create-distribution
devops/aws:route53/create-cname
```
