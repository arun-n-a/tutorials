# App on AWS S3 with  static hosting using cloudfront
1. Create an s3 bucket with the domain name we wish to host and make the bucket public.
2. Create second s3 bucket with the same domain but with www. at the starting and make the bucket public .
3. Upload the front end code  to the www.<domain> bucket.
4. Add bucket policy in WWW.<domain> bucket permission tab.
  ```
 {
	"Version": "2012-10-17",
	"Statement": [
		{
			"Sid": "AddPerm",
			"Principal": "*",
			"Effect": "Allow",
			"Action": ["s3:GetObject"],
			"Resource": ["arn:aws:s3:::abc.quintezsence.com/*"]
		}
	]
}
```
Replace {domain} with www.domain.com
5. Enable www.<domain> bucket static website hosting in properties tab. Here the Hosting Type should be 'Host a static website'. There you can see index docment and error document fportion in both  text boxes add index.html itself.
6. Enable statuc website hosting for the domain name bucket and here the hosting type should be 'Redirect requests for an object'. and the host name should be www.<domain> . Select protocol http or https.
7. Click properties tab at the bottom copy Bucket website endpoint and add it is a CNAME record in the domain purchased service.
8. Next use AWS certificate manager and request a certificate for the domain and www.domain. Select DNS Validation. copy the cname to the domain service provider.
 
  Ref: https://youtu.be/mls8tiiI3uc
