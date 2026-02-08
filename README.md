# 🌐 Static Website Hosting on AWS S3

## 📌 Project Overview
This project demonstrates the deployment of a **static portfolio website** using **Amazon Web Services (AWS) S3**.  
The website is hosted using **S3 Static Website Hosting** and is publicly accessible over the internet.

---

## 🧰 Technologies Used
- Amazon Web Services (AWS)
- Amazon S3 (Simple Storage Service)
- HTML
- CSS
- JavaScript
- GitHub

---

## 🌍 AWS Configuration Details
- **AWS Region:** Asia Pacific (Singapore) – `ap-southeast-1`
- **Service Used:** Amazon S3
- **Hosting Type:** Static Website Hosting
- **Access Control:** Public Read Access Enabled

---

## 📁 Project File Structure
website-project-naimur/
- index.html
- style.css
- script.js
- profile.png
- profile1.png
- CVofNaimurRashid.pdf

---

## 🚀 Step-by-Step Deployment Process

### Step 1: Create an S3 Bucket
- Logged in to AWS Management Console
- Navigated to **Amazon S3**
- Created a new bucket named: your_bucket_name
- Selected region: your_nearest_region
- Disabled **Block all public access**
- Created the bucket successfully

---

### Step 2: Upload Website Files
- Opened the created S3 bucket
- Uploaded all website files:
- HTML, CSS, JavaScript
- Images
- PDF CV file

---

### Step 3: Enable Static Website Hosting
- Navigated to the **Properties** tab
- Enabled **Static website hosting**
- Selected **Bucket hosting**
- Set: Index document: index.html
- Saved the configuration

---

### Step 4: Make Objects Public
- Selected all uploaded objects
- Chose **Actions → Make public**
- Confirmed public read access

---

### Step 5: Access the Website
After enabling static website hosting, AWS generated a website endpoint.

🔗 **Live Website URL:**
http://website-project-naimur.s3-website-ap-southeast-1.amazonaws.com/


---

## ✅ Final Output
- Website loads successfully
- All assets (CSS, JS, images, PDF) are accessible
- Portfolio is publicly available via AWS S3

---

## 📚 Key Learnings
- Creating and configuring S3 buckets
- Managing public access permissions
- Hosting static websites on AWS
- Understanding cloud-based web deployment

---

## 👨‍💻 Author
**MD Naimur Rashid**  
Student of Internet of Things & Robotics Engineering  
Bangladesh Digital University  

---

## 📜 License
This project is created for **educational purposes**.
