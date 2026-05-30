# 🧠 AWS Resume Analyzer (S3 + Textract)

A simple cloud-based Resume Analyzer built using **Amazon S3** and **Amazon Textract**.  
This project demonstrates how AWS services can be used to extract and analyze text from resumes (PDF/Image) using OCR technology.

---

## 🚀 Project Overview

This project allows users to upload resumes to AWS S3 and automatically extract key information such as:

- Name
- Email
- Phone number
- Skills
- Work experience

Using **Amazon Textract**, the system reads and processes documents like a real-world Applicant Tracking System (ATS).

---

## 🏗️ Architecture

- Amazon S3 → Stores uploaded resumes  
- Amazon Textract → Extracts text from resumes  
- AWS Console → Used to run and view results  

---

## 📊 System Workflow

1. User uploads resume (PDF/Image) to S3 bucket  
2. Resume is selected in Amazon Textract  
3. Textract performs OCR (Optical Character Recognition)  
4. Extracted text is returned in a structured format  
5. Data can be used for analysis or HR screening  

---

## 🖼️ Architecture Diagram
