# AWS Mini Projects

This repository contains my **AWS-related mini projects** showcasing practical hands-on experience with Amazon Web Services.  
Currently, it includes:

1. **Static Website Hosting on Amazon S3**
2. **Data Visualization using Amazon S3 and QuickSight**

---

## 📂 Project 1: Host a Website on Amazon S3

This project demonstrates how I hosted a static website using **Amazon S3**, a scalable cloud storage service by AWS.  
It’s a beginner-friendly project that helped me learn the essentials of hosting static content in the cloud.

### What is Amazon S3?
Amazon S3 (Simple Storage Service) is a secure, durable, and highly available **object storage service**.  
It’s commonly used to store and retrieve data from anywhere on the web.  
A lesser-known but powerful feature is **static website hosting**, which allows you to serve HTML, CSS, and images directly from an S3 bucket.

### Project Highlights
- **Duration:** ~45 minutes  
- **Hosting Type:** Static website hosting from an S3 bucket  
- **Outcome:** Successfully hosted a simple webpage (`index.html`) with CSS and images

### Steps to Host a Website on Amazon S3
1. **Set Up an S3 Bucket**  
   - Created a new bucket with a **globally unique name** in the **Mumbai** region.  
   - Understood **ACLs** (Access Control Lists) and public access settings.

2. **Upload Website Files**  
   - Uploaded `index.html`, CSS, and images to the bucket.

3. **Enable Static Website Hosting**  
   - Enabled static website hosting and set `index.html` as the index document.

4. **Update Permissions**  
   - Resolved 403 Forbidden Error by making files public via **ACLs**.

### Lessons Learned
- Fixing permission-related errors for public hosting.  
- Understanding AWS ACLs, bucket policies, and hosting settings.

📄 **Documentation:** [S3 hosting.pdf](./S3%20hosting.pdf)

---

## 📂 Project 2: Data Visualization with Amazon S3 and QuickSight

This project demonstrates how to integrate **Amazon S3** with **Amazon QuickSight** to create interactive data visualizations.  
The dataset used is `netflix_titles.csv`.

### Tools & Concepts Learned
- **Amazon S3**: Creating buckets, uploading datasets, managing permissions.
- **manifest.json**: Modified to include actual S3 bucket URL so QuickSight can interpret the dataset.
- **Amazon QuickSight**: Creating an account, importing datasets, building visualizations, applying filters, and publishing dashboards.

### Steps
1. **Upload Files to S3**  
   - Uploaded `netflix_titles.csv` and updated `manifest.json` with S3 bucket path.

2. **Connect S3 to QuickSight**  
   - Linked QuickSight to the dataset using the manifest file.

3. **Create Visualizations**  
   - **Donut Chart**: Number of Netflix titles by country.  
   - **Horizontal Bar Chart**: TV Shows vs Movies by release year.  
   - **Filtered Genre Analysis**: Thrillers, TV Comedies, Action & Adventure, filtered after 2015.

4. **Publish & Export Dashboard**  
   - Published the dashboard for team access.  
   - Exported the dashboard as PDF.

### Lessons Learned
- How QuickSight uses `manifest.json` to interpret S3 data.
- Data filtering for focused insights.
- Dashboard publishing and export workflow.

📄 **Documentation:** [QuickSight Visualization.pdf](./QuickSight%20Visualization.pdf)

---

## 🚀 Future Work
- Add more AWS-based mini projects (Lambda, DynamoDB, CloudFront, etc.).
- Explore advanced QuickSight features like calculated fields.
- Experiment with new visualization types (treemaps, heatmaps).

---

## 📢 Acknowledgments
These projects were completed as part of learning activities on [NextWork](https://nextwork.org).
