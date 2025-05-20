# 🚀 Implement Deployment Pipelines in Microsoft Fabric

## 📌 Lab Objective

The goal of this lab is to learn how to use **deployment pipelines** in **Microsoft Fabric** to automate the process of moving content between environments — such as Development, Test, and Production. This allows for safe and controlled content promotion before it reaches end users.

---

## 🛠️ Steps Performed

### 1. Create Workspaces
- Created three separate workspaces:
  - `Development`
  - `Test`
  - `Production`

### 2. Create a Deployment Pipeline
- Opened the **Deployment Pipelines** tab from the left-hand menu.
- Created a new pipeline and gave it a unique name.

### 3. Assign Workspaces to Pipeline Stages
- Opened the newly created pipeline.
- Assigned each stage (Development, Test, Production) to its corresponding workspace.

### 4. Create Content in Development Stage
- Navigated to the `Development` workspace.
- Created a new **Lakehouse** and named it `LabLakehouse`.
- Loaded sample data (`NYCTaxi`) into the Lakehouse.

### 5. Deploy Content Between Stages
- Deployed content from:
  - **Development → Test**
  - **Test → Production**
- Verified that each stage was synchronized successfully.

### 6. Verify and Clean Up
- Confirmed the content existed in all three workspaces.
- Deleted the workspaces after completion to clean up resources.

---

## 📘 What I Learned

- Gained hands-on experience with **Microsoft Fabric Deployment Pipelines**.
- Understood the lifecycle of content promotion from development to production.
- Learned how to manage synchronization and track differences between stages.
- Practiced working with Fabric components like Lakehouse and sample datasets.
- Understood best practices for environment isolation and safe deployment.
- Learned how to maintain a clean workspace by properly removing unused resources.

---

This lab helped me build a solid foundation in managing content flows within Microsoft Fabric using deployment pipelines. It demonstrated the power of automation and structured releases in a data environment.

---

## Screenshots


<img width="1405" alt="Screenshot 2025-05-20 at 13 30 38" src="https://github.com/user-attachments/assets/614600f5-3082-4c4b-bf47-597e1959eb95" />

<img width="1396" alt="Screenshot 2025-05-20 at 13 30 14" src="https://github.com/user-attachments/assets/9439d188-1470-4cbe-b606-e476ff9057b8" />

<img width="1244" alt="Screenshot 2025-05-20 at 13 32 38" src="https://github.com/user-attachments/assets/d016501a-2441-40f2-b951-6c3d6dc8c7db" />

<img width="1343" alt="Screenshot 2025-05-20 at 13 33 06" src="https://github.com/user-attachments/assets/0478eacb-fce7-4ba0-ab6f-4ac200b25518" />

<img width="1414" alt="Screenshot 2025-05-20 at 13 33 52" src="https://github.com/user-attachments/assets/aa005c2b-fc49-4eb7-9e8c-41f90d490052" />

<img width="1463" alt="Screenshot 2025-05-20 at 13 34 29" src="https://github.com/user-attachments/assets/a5f2118a-135e-4b5d-b39b-387791bdb225" />

<img width="1481" alt="Screenshot 2025-05-20 at 13 35 00" src="https://github.com/user-attachments/assets/48253169-d83d-4052-bd1a-cad38c3ade3a" />

<img width="1354" alt="Screenshot 2025-05-20 at 13 44 03" src="https://github.com/user-attachments/assets/afdfcfef-3fc1-4096-911a-168878421274" />

<img width="1287" alt="Screenshot 2025-05-20 at 13 44 12" src="https://github.com/user-attachments/assets/6ca206ef-87c5-4fe2-81c9-b644df5136c1" />

<img width="1462" alt="Screenshot 2025-05-20 at 13 45 23" src="https://github.com/user-attachments/assets/8548c92e-dc6d-4b33-a4a9-09d8158c6d7e" />

