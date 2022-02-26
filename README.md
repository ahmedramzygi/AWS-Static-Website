# AWS-Static-Website

Manually deploy static website into S3 bucket with HTTP hosting and CloudFront

Deploy a static website to AWS. 

Create a S3 bucket, configure the bucket for website hosting, and secure it using IAM policies

Upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront. Lastly, access your website in a browser using the unique S3 endpoint.

Files included(screenshots):

bucket_created.png - The S3 bucket is created

files_uploaded.png - All the website files uploaded to the newly created S3 bucket

static_website_hosting.png - The S3 bucket is configured to support static website hosting

Bucket_publicPolicy.png - The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.

cloud_frontDomainName.png - CloudFront has been configured to retrieve and distribute website files

Website.png - The website is accessible to anyone on the Internet via a web browser
