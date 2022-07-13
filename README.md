# AWS Static Website Deployment

This repository was done to demonstrate the steps needed to deploy a static website using amazon web services. Done for Udacity Cloud DevOps Nanodegree

## Final Result

Website now available through cloudfront (content delivery network) and through s3 URLs

![gif](/screenshots/website_final_result.gif)

## How to do it?

### Step 1: Create and configure public s3 bucket

The bucket is set to public for static website access.

![gif](/screenshots/create_public_s3_bucket.gif)

### Step 2: Upload the website to the bucket

This was done using AWS CLI on windows

![gif](/screenshots/uploading_files_to_bucket.gif)

### Step 3: Secure the bucket and configure static website option

Setting IAM Policies

![gif](/screenshots/securing_bucket_iam.gif)

Enabling Static hosting

![gif](/screenshots/configuring_static_hosting_bucket.gif)

### Step 4: Create a cloudfront distribution

![gif](/screenshots/creating_cloudfront_cdn.gif)