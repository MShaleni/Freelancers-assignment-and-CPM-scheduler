# Freelancer Assignment & CPM Scheduler

This project automates two important project-management steps:
1. Assigning freelancers to tasks using the Hungarian Algorithm  
2. Scheduling tasks using the Critical Path Method (CPM)

The system helps choose the best freelancer for each task based on skill, experience, and cost, and then builds a complete project schedule with the critical path highlighted.

---

## 📌 Features

### ✔ Freelancer–Task Assignment
- Matches freelancers to tasks only when skills match  
- Considers cost per day and experience  
- Builds and optimizes a cost matrix  
- Uses the Hungarian Method for minimum-cost assignment  

### ✔ CPM Scheduling
- Performs forward & backward pass  
- Computes ES, EF, LS, LF, and Slack  
- Identifies all critical tasks  
- Calculates total project duration  

### ✔ Generated Outputs
- Assignment table  
- Cost matrix  
- CPM schedule table  
- Critical path graph  
- Auto-generated Word report  

---

## 📂 Input Files

You need two CSV files:

### **1. Freelancer CSV**
--FreelancerName, Skill, Experience, CostPerDay

### **2. Task CSV**
--TaskID, TaskName, RequiredSkill, Duration, Dependencies

---

## 🚀 How to Run the Application

### **Step 1 — Install Dependencies**
```bash
pip install gradio pandas numpy networkx matplotlib scipy python-docx
```
### **Step 2 — Run the Application**
```bash
python main_notebook.py
```
### **Step 3 — Upload Inputs in the UI**

Upload Freelancer CSV

Upload Task CSV

Enter optional budget

Click Submit

The system will display:

Assignments

Cost matrix

CPM details

Critical path graph

Downloadable Word report

### ** 🎥 Demo Video**
Click below to download and view the project demo:

👉 [Download Demo Video](docs/output_demo.mp4)


### **📌 Summary**

This tool combines the Hungarian Method and CPM to make freelancer assignment and scheduling fast, accurate, and automated.
It is useful for freelance platforms, academic projects, small businesses, and any situation where people and tasks need to be assigned efficiently.
