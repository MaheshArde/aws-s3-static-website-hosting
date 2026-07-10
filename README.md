# aws-s3-static-website-hosting
Host a static website on Amazon S3 with public access, bucket policies, and server-side encryption (SSE-S3). This project demonstrates static website hosting, cloud storage, AWS security, and troubleshooting common HTTP 403/404 errors.
# AWS S3 Static Website Hosting

This project shows how to host a static website using **Amazon S3**. The website is publicly accessible through the S3 Static Website Hosting feature.

---

## Project Overview

In this project, I:

- Created an Amazon S3 bucket
- Uploaded website files
- Enabled Static Website Hosting
- Configured a Bucket Policy for public access
- Enabled Server-Side Encryption (SSE-S3)
- Hosted a static website successfully

---

## Architecture

```
User
  │
  ▼
S3 Website Endpoint
  │
  ▼
Amazon S3 Bucket
```

---

## Technologies Used

- Amazon S3
- AWS IAM
- HTML
- CSS
- JavaScript

---

## Project Structure

```
aws-s3-static-website-hosting/
│
├── website/
│   ├── index.html
│   ├── error.html
│   ├── css/
│   ├── js/
│   └── images/
│
├── screenshots/
│
├── architecture/
│
└── README.md
```

---

## Steps Performed

1. Created an Amazon S3 bucket
2. Disabled Block Public Access
3. Enabled Server-Side Encryption (SSE-S3)
4. Uploaded website files
5. Enabled Static Website Hosting
6. Added a Bucket Policy
7. Opened the Website Endpoint
8. Verified that the website was working

---

## Bucket Policy

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::YOUR_BUCKET_NAME/*"
    }
  ]
}
```

Replace **YOUR_BUCKET_NAME** with your actual S3 bucket name.

---

## Screenshots

Add screenshots of:

- S3 Bucket Creation
- Upload Website Files
- Static Website Hosting
- Bucket Policy
- Live Website

---

## Skills Learned

- Amazon S3
- Static Website Hosting
- Bucket Policy
- Server-Side Encryption (SSE-S3)
- Cloud Storage
- AWS Basics

---

## Project Outcome

Successfully hosted a static website on Amazon S3 and made it publicly accessible using Static Website Hosting.

---

## Author

**Mahesh**

BCA Final Year Student

Aspiring Linux System Administrator | AWS Cloud | DevOps Engineer
