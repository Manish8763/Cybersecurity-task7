# Task 7 – Browser Security: Identifying & Removing Suspicious Extensions

## 🎯 Objective
To learn how to identify and remove potentially harmful browser extensions and understand their security implications.

---

## 🛠 Tools Used
- Web Browser: **Google Chrome**

---

## 🔍 Extensions Reviewed

| Extension Name          | Description                                 | Status     | Action Taken                     |
|-------------------------|---------------------------------------------|------------|----------------------------------|
| Google Docs Offline     | Official extension by Google                | Trusted    | **Kept**                         |
| McAfee WebAdvisor       | Security extension by McAfee                | Trusted    | **Kept**                         |
| 360 Internet Protection | Unknown publisher, high permissions (read/change all data), inactive | **Suspicious** | **Removed**                     |

---

## 🚨 Suspicious Extension Analysis

### 🔹 360 Internet Protection
- **Version**: 2.1.57  
- **Size**: < 1 MB  
- **Permissions**:  
  - Can read and change data on all websites.  
  - Automatically allowed on all sites.  
- **Issues**:
  - Not in use (turned off).
  - Overly broad permissions without clear need.
  - Unknown trust rating.

🧹 **Action**: Removed due to unnecessary site-wide permissions and inactive use.

---

## ✅ Results
- Removed one suspicious extension: **360 Internet Protection**.
- Verified no unusual behavior in remaining extensions.
- Improved awareness of extension permissions and browser hygiene.

---

## 📸 Screenshots

### 1. All Installed Extensions  
![All Extensions](./Screenshot%202025-07-03%20131637.png)

### 2. Details of Suspicious Extension (360 Internet Protection)  
![360 Details](./Screenshot%202025-07-03%20131856.png)

---

## 📚 Key Learnings
- Extensions with excessive permissions can pose serious privacy risks.
- Even antivirus add-ons should be evaluated based on active use and permissions.
- Always disable or remove unused extensions for better performance and security.

---

## 📁 Repo Info
This repo includes:
- `README.md` (this file)
- Screenshots of the browser extensions reviewed

---

