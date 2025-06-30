# AWS-documents
secure copy form local --> aws instance
```
scp -i /home/mobaxterm/testing/main.tf ubuntu@ip_instance:/home/destination
```

lets learn aws
#topics
aws vpc
vpc peering
vpn
gateways.

## How can you give a s3 object permission to an external user?
1.using a console you can find a presigned url on the object action drop down.
2. using aws CLI $ aws s3 pre-signurl s3://bucket_name/object --expires-3600 ## the object access will expires in 30min to external user      
