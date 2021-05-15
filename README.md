# cloudfront-starter
Creates an SSL-terminating Cloudfront distribution backed by an S3 bucket

## Setup

```
./eject
scripts/aws:s3/create-bucket
scripts/aws:acm/request-certificate
scripts/aws:cloudfront/create-distribution
scripts/aws:route53/create-cname
```
