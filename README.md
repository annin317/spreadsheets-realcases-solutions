# 📊 Spreadsheets Real Case Solutions
This repository is a growing library of **real-world spreadsheet problems** that I’ve solved for teams, clients, and learners.  
# 🌟 About This Repository
Each case includes:

✔ Business context  
✔ The exact problem  
✔ Step-by-step thinking  
✔ Final formula(s)  
✔ Downloadable Excel files  
✔ Google Sheets version  
✔ Screenshots for quick preview  

My goal is to help others learn practical spreadsheet problem-solving while showcasing my ability to break down complex tasks into simple solutions.

# 🧠 Featured Case Studies
## **Case 1️⃣ — VLOOKUP Fix for External Data**
### **Overview**   
This is a common headache: a VLOOKUP that breaks when pulling data from another spreadsheet. The issues here were simple but costly: the wrong column number and a lookup area that was too small!
### **❌ The Problem**  
VLOOKUP was failing due to the wrong result column index and using a static, small cell range for the source data.
### **💡 Solution**
Quickly diagnosed and corrected the column index. Upgraded the range selection to full columns (e.g., `$L:\$M$) to make the formula dynamic, stable, and "future-proof" against data changes.
![Alt text](https://github.com/annin317/spreadsheets-realcases-solutions/blob/e6d3e02c1e50a60e487534f1fff491330ca1977e/Case%201%EF%B8%8F%20%E2%80%94%20VLOOKUP%20Fix%20for%20External%20Data%20Image.png)

## **Case 2️⃣ — Dynamic Reporting vs. Static Columns**
### **Overview**   
is case transformed a static, fragile, and labor-intensive tracking system into a dynamic, scalable, and fully automated reporting tool using a simple change in data structure and powerful array formulas.
### **❌ The Problem**  
Tracking system required manual column insertion and formula adjustment (SUMs) for every new product, making the sheet non-scalable and high-maintenance.
### **💡 Solution**
Redesigned the data input structure from a static "wide" format to a normalized "tall" format. Implemented dynamic aggregation formulas (PIVOT TABLE) to automatically summarize product quantities based on two criteria (Date, Product), entirely eliminating the need for manual formula updates.

[Here's the excel files (Case 2 — Dynamic Reporting vs. Static Columns result.xlsx
)](https://github.com/annin317/spreadsheets-realcases-solutions/blob/0bfe6785370318090891e23649005cda140df12b/Case%202%20%E2%80%94%20Dynamic%20Reporting%20vs.%20Static%20Columns%20result.xlsx)
![Alt text](https://github.com/annin317/spreadsheets-realcases-solutions/blob/0bfe6785370318090891e23649005cda140df12b/Case%202%20%E2%80%94%20Dynamic%20Reporting%20vs.%20Static%20Columns%20image.png)
