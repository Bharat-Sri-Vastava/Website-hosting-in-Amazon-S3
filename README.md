# Host a Website on Amazon S3
This project demonstrates how I hosted a static website using **Amazon S3**, a scalable cloud storage service by AWS.  
It’s a beginner-friendly project that helped me learn the essentials of hosting static content in the cloud.

---

## What is Amazon S3?
Amazon S3 (Simple Storage Service) is a secure, durable, and highly available **object storage service**.  
It’s commonly used to store and retrieve data from anywhere on the web.  
A lesser-known but powerful feature is **static website hosting**, which allows you to serve HTML, CSS, and images directly from an S3 bucket.

---

## Project Highlights
- **Duration:** ~45 minutes  
- **Hosting Type:** Static website hosting from an S3 bucket  
- **Outcome:** Successfully hosted a simple webpage (`index.html`) with CSS and images

---

## Steps to Host a Website on Amazon S3

### 1. Set Up an S3 Bucket
- Logged in to the AWS Management Console and navigated to **S3**.
- Created a new bucket with a **globally unique name**.
- Selected **Mumbai** as the closest AWS region to reduce latency and cost.
- Understood **ACLs** (Access Control Lists) and public access settings.

### 2. Upload Website Files
- Uploaded `index.html`, CSS, and image files to the bucket.
- Ensured all files were placed at the root of the bucket.

### 3. Enable Static Website Hosting
- Opened **Bucket Properties** and enabled **Static Website Hosting**.
- Set `index.html` as the **index document**.

### 4. Update Permissions
- Initially got a **403 Forbidden Error** due to private object permissions.
- Fixed it by making the uploaded files public via **ACLs**.

---

## Accessing the Website
Once static hosting was enabled, S3 generated a **bucket endpoint URL**.  
Using this URL, I was able to access the website from any device connected to the internet.

---

## Lessons Learned
- **Error Handling:** Learned how to fix the 403 Forbidden error by updating access permissions.  
- **Public Accessibility:** Realized the importance of proper permissions for public content.  
- **AWS Concepts:** Understood how ACLs, bucket policies, and regions impact hosting.

---

## Project Outcomes
- Successfully deployed a CSS Art Playground website on Amazon S3.  
- Gained hands-on experience with AWS cloud storage and website hosting.  
- Understood how permissions and configurations affect website accessibility.

---

## PDF Documentation
The complete step-by-step documentation can be found here: [S3 hosting.pdf](./S3%20hosting.pdf)

---

## Want to Explore More?
Check out [NextWork.org](https://nextwork.org) for more projects and resources.
