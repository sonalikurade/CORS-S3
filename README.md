# Using cross-origin resource sharing (CORS)
* Cross-Origin Resource Sharing (CORS) is a security feature that allows web applications running at one origin (domain) to make requests to resources at another origin. Here’s how it works in the context of AWS S3:
## What is CORS?
By default, web browsers enforce the Same-Origin Policy. This policy restricts how a web page can request resources from another domain, providing a level of security against certain types of attacks. However, sometimes web applications need to access resources from different origins. This is where CORS comes in.
## CORS in AWS S3
Amazon S3 (Simple Storage Service) is a storage service that can store and retrieve any amount of data at any time from anywhere on the web. S3 supports CORS to enable web applications to securely interact with S3 resources across different origins.