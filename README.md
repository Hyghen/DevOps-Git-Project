# DevOps Git Project

In this repository i have focused on managing a DevOps project using Git best practices such as branching strategies, commit management, pull requests, markdown documentation, and more.

## 🔧 Objective
To implement version control workflows using **Git** and **GitHub**, applying standard DevOps practices for collaborative development.

---

## ✅ What I Did — Step-by-Step


### 1. 🗂️ Project Initialization

- Created a new repository: [DevOps-Git-Project](https://github.com/Hyghen/DevOps-Git-Project)

- Cloned it to my local system using:

  
       -- git clone https://github.com/Hyghen/DevOps-Git-Project.git


2. 🌱 Branching Strategy
Created the following branches:

main → production-ready code

dev → integration branch

feature/<feature-name> → feature-specific work

Example:

      -- git checkout -b dev

      -- git push -u origin dev

      -- git checkout -b feature/login

      -- git push -u origin feature/login



3. 📝 Pull Request Workflow
Worked in feature/ branches.

Created Pull Requests to merge into dev.



<img width="1192" height="265" alt="Screenshot 2025-08-08 133622" src="https://github.com/user-attachments/assets/1dd2f23e-7e2b-4233-862f-2027302fce50" />




Merged dev into main after testing and review.



<img width="1221" height="613" alt="Screenshot 2025-08-08 133706" src="https://github.com/user-attachments/assets/241afb3f-cc45-4560-bac2-e7a833ef46dd" />




4. 📁 Git Best Practices Used
.gitignore added to avoid pushing unnecessary files.

Used commit messages that are clean, descriptive, and atomic.

Tagged major milestones using:

     -- git tag -a v1.0 -m "Initial release"


<img width="1028" height="142" alt="Screenshot 2025-08-08 134355" src="https://github.com/user-attachments/assets/996ba8c7-9ec8-42d4-a7c4-fb6e32481f10" />


     
     --git push origin v1.0


5. 📄 Documentation

Updated this README.md to explain the entire process for visibility and collaboration.

📂 Files Included

README.md → Project explanation

.gitignore → Ignored files and folders

feature/, dev/, main → Properly structured branches for clean Git flow



🚀 Tools Used

-- Git

-- GitHub

-- VS Code / Git bash


👨‍💻 Author

Chitransh Jangid
DevOps Engineer



📌 Repository Link

🔗 GitHub - https://github.com/Hyghen/DevOps-Git-Project
