## Create bucket
aws s3 mb s3://aws-examples-bucket-policy-522841335262

## Create bucket policy
aws s3api put-bucket-policy --bucket aws-examples-bucket-policy-522841335262 --policy file://policy.json