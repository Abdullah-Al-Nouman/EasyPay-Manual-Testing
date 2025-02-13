# 📌 EasyPay Manual Testing Project  

## 📖 Project Overview  
EasyPay is a **Mobile Financial Service (MFS) app** that enables customers to **pay merchants and utility bills** and **apply for loans** when their balance is low. This project focuses on **manual testing** to ensure the reliability and accuracy of its core features.

## 🚀 Features Tested  

### 🏦 **Feature 1: Merchant & Utility Bill Payment**  
- Customers can pay **merchants** and **utility bills** using EasyPay.  
- **Service Charge:** 🏷️ 1% of the transaction amount (Min: **5 TK**).  
- **Cashback Offer:**  
  - **10% Cashback** for transactions above **5000 TK**.  
  - **20% Cashback** for transactions above **10,000 TK** (Max cashback: **3000 TK**).  
- ❌ **No cashback** applies to utility bill payments.  

### 💰 **Feature 2: Loan System**  
- Customers with a **balance < 100 TK** can apply for loans up to **20,000 TK**.  
- **Repayment Policy:**  
  - **No interest** if repaid within **30 days**.  
  - **1.8% compound interest per day** if not repaid on time.  
- Customers who **repay 50% of the remaining amount** are eligible to apply for another loan.  

---

## 📝 Testing Scope  

### ✅ **Acceptance Criteria**  
- Defined rule-based **acceptance criteria** for both features.  

### 🔍 **Test Cases**  
- Designed **positive and negative test cases** in standard test case format.  

### 🐞 **Bug Reports**  
- Conducted **UI, functional, and usability testing** to find at least **10 bugs** with priority & severity levels.  

---

## 📂 Project Files  

| 📁 File Name                | 📄 Description |
|----------------------------|------------------------------------------------|
| `📜 Acceptance_Criteria.md` | Rule-based acceptance criteria for features.  |
| `📜 Test_Cases.xlsx`       | Detailed test cases (Positive & Negative).    |
| `📜 Bug_Reports.xlsx`      | Documented bugs with severity & priority.     |
| `📜 Feature_Prioritization.md` | Priority analysis of the features.         |
| `📜 Testing_Checklist.md`  | Checklist for quick verification.             |
| `📜 README.md`             | This project overview and testing details.    |

---

## 🔧 Tools Used  
- **📋 Test Case Management:** Microsoft Excel  
- **🐞 Bug Tracking:** Google Sheets / Jira  
- **📄 Documentation:** Google Docs  

---

## 📌 How to Use This Repository?  
1️⃣ Clone this repository:  
   ```sh
   git clone https://github.com/your-username/EasyPay-Manual-Testing.git

