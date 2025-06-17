<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

This tutorial outlines the post-installation configuration process of the open-source help desk ticketing system **osTicket**. These steps are crucial for tailoring the platform to your organization’s structure, workflows, and support needs.

---


---

## 🧰 Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

---

## 💻 Operating System Used

- Windows 10 (21H2)

---

## ✅ Post-Install Configuration Objectives

- Configure Roles (Group permissions)
- Create Departments (Control ticket visibility)
- Set up Teams (Cross-department collaboration)
- Allow/Restrict anonymous ticket creation
- Add Agents (Support staff)
- Add Users (End-users/customers)
- Configure SLAs (Service Level Agreements)
- Create Help Topics (User-facing ticket categories)

---

## 🛠️ Configuration Steps

### 1. Configure Roles
- Navigate to: `Admin Panel → Agents → Roles`
- Example Role: `Supreme Admin`

![Roles](https://github.com/user-attachments/assets/450ebc5d-0c11-4145-b6c2-5de9c7bf4b3d)

---

### 2. Configure Departments
- Navigate to: `Admin Panel → Agents → Departments`
- Example: `SysAdmins`

![Departments](https://github.com/user-attachments/assets/cf801e06-e980-478b-9d2a-1c222e4bc59c)

---

### 3. Set Up Teams
- Navigate to: `Admin Panel → Agents → Teams`
- Teams can include agents from multiple departments.
- Example Team: `Online Banking`

![Teams](https://github.com/user-attachments/assets/051c2e00-8a8a-4006-bbff-9cdbeb0e246e)

---

### 4. Allow Anyone to Create Tickets
- Navigate to: `Admin Panel → Settings → User Settings`
- **Uncheck**: “Require registration/login to create tickets”

![User Settings](https://github.com/user-attachments/assets/5f3441ab-819d-4845-8ccb-af28de47ff9f)

---

### 5. Configure Agents (Support Staff)
- Navigate to: `Admin Panel → Agents → Add New`
- Assign agents to appropriate departments, e.g., SysAdmins or Support.

![Add Agent](https://github.com/user-attachments/assets/c8d1b251-76c6-4734-aa77-450c245a5bd4)

---

### 6. Configure Users (Customers)
- Navigate to: `Agent Panel → Users → Add New`

![Users](https://github.com/user-attachments/assets/ea9c8cc7-bd92-44b2-8f31-331bc65f409f)

---

### 7. Set Up SLAs (Service Level Agreements)
- Navigate to: `Admin Panel → Manage → SLA`
- Examples:
  - **Sev-A**: 1 hour, 24/7
  - **Sev-B**: 4 hours, 24/7
  - **Sev-C**: 8 hours, Business Hours

![SLAs](https://github.com/user-attachments/assets/5f165f17-1c1c-4d92-8ca2-b930bdd2fb61)

---

### 8. Configure Help Topics
- Navigate to: `Admin Panel → Manage → Help Topics`
- Examples:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other

![Help Topics](https://github.com/user-attachments/assets/a6f94032-6380-42dd-8975-c1bc6d72fddd)

---

## 🏁 Final Notes

Once complete, osTicket is fully customized for your support needs. You can now:
- Assign tickets based on roles, departments, or help topics.
- Track ticket resolution times with SLAs.
- Give end-users a structured way to request support.

---
