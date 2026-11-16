# Rana Usama — DevOps Portfolio

A responsive and professional static portfolio website built using HTML, CSS, and JavaScript. The website is hosted on Amazon S3 and delivered securely over HTTPS using Amazon CloudFront.

## Live Website

**HTTPS Portfolio:** https://d3ejet4eu0iofe.cloudfront.net/

**GitHub Repository:** https://github.com/developmentoperation69/codomax-s3-static-portfolio

## Project Overview

This project demonstrates how to deploy a static website using Amazon S3 and configure Amazon CloudFront for secure HTTPS content delivery.

### AWS Architecture

1. Website files are stored in an Amazon S3 bucket.
2. S3 Static Website Hosting serves the website content.
3. Amazon CloudFront uses the S3 website endpoint as its origin.
4. Visitors access the portfolio through the CloudFront HTTPS URL.

## AWS Configuration

| Configuration | Value |
|---|---|
| AWS Service | Amazon S3 |
| Bucket Name | `usama-s3-portfolio-2026` |
| AWS Region | `ap-southeast-2` (Sydney) |
| Static Website Hosting | Enabled |
| CDN | Amazon CloudFront |
| Distribution ID | `E1Y4SAA0BNHTUD` |
| HTTPS | Enabled through CloudFront |
| AWS WAF | Not enabled |

## Project Files

- `index.html` — Portfolio content and page structure
- `style.css` — Responsive dark theme and layout
- `script.js` — Mobile navigation interaction

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Amazon S3
- Amazon CloudFront
- AWS Bucket Policies
- HTTPS

## Deployment Steps

1. Create an Amazon S3 bucket.
2. Enable static website hosting.
3. Upload `index.html`, `style.css`, and `script.js`.
4. Configure bucket permissions for public website access.
5. Create a CloudFront distribution.
6. Configure the S3 website endpoint as the CloudFront origin.
7. Deploy the distribution and access the website using its HTTPS URL.

## Security Considerations

- Public website access is limited to reading website objects.
- AWS credentials and secret keys are not stored in this repository.
- CloudFront provides HTTPS access to the website.
- AWS WAF was not enabled for this learning project.

## Learning Outcomes

Through this project, I practiced:

- Creating and configuring S3 buckets.
- Uploading and managing S3 objects.
- Understanding bucket policies and public access.
- Hosting a static website on Amazon S3.
- Configuring CloudFront distributions.
- Understanding CDN-based content delivery.
- Deploying a website with HTTPS.

---

**Created by Rana Usama**  
Junior DevOps Engineer | Faisalabad, Pakistan
