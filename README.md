# Azure Hybrid Identity & Password Sync Project

## Project Overview
This project demonstrates the deployment and configuration of a **Hybrid Identity environment** using **Azure Active Directory (Azure AD)** and **on-premises Active Directory (AD)**. The focus was on **user synchronization**, **password sync**, and **user sign-in validation** across cloud and on-prem environments.

---

## **Project Objectives**
- Integrate on-premises Active Directory with Azure AD.
- Enable secure password synchronization for users.
- Validate hybrid identity functionality with Microsoft 365 and Azure portal logins.
- Demonstrate basic Azure AD Connect configuration and management.

---

## **Project Tasks & Steps**
1. **Azure AD Connect Installation**
   - Downloaded and installed Azure AD Connect on Windows Server.
   - Configured **Password Hash Synchronization** for single forest.
   - Applied **OU filtering** and set the **user sign-in method**.

2. **Verify Synced Users in Azure AD**
   - Confirmed on-prem users synced to Azure AD.
   - Checked sync status in Azure AD Connect.

3. **Password Sync Validation**
   - Reset passwords on-premises and verified synchronization to Azure AD.
   - Ensured users could log in to both Azure portal and Microsoft 365 apps.

4. **Hybrid Identity Sign-In Validation**
   - Successfully tested user sign-in through **portal.azure.com**.
   - Optional: validated access to Microsoft 365 applications.

---

## **Technologies Used**
- **Azure Active Directory (Azure AD)**
- **Active Directory (On-Premises)**
- **Azure AD Connect**
- **Microsoft 365 Apps (Portal, Outlook, Teams, OneDrive)**
- **Windows Server**

---

## **Key Learnings**
- Understanding hybrid identity concepts and benefits.
- Hands-on experience with Azure AD Connect installation and configuration.
- Password synchronization between on-prem and cloud environments.
- Validating seamless single sign-on experience for users.

---

## **Author**
**Hikmatullah Shinwari**  
Cloud Computing Enthusiast | Microsoft 365 & Azure Learner  
