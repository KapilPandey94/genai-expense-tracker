![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
[View License](https://www.gnu.org/licenses/gpl-3.0)

# 📊 GenAI Expense Tracker App

A smart and modern mobile app built using **Android (Java/XML)** and **Firebase** to help users track their income and expenses, analyze spending patterns, and receive AI-generated financial insights in real time.

---

## 🚀 Features

- 📥 Add & categorize expenses and income
- 📊 Overview screen with custom BarChart (income vs expense vs savings)
- 🔐 Firebase Authentication (Email/Google/Facebook)
- ☁️ Data synced using Cloud Firestore
- 📁 Optional receipt/image upload to Firebase Storage
- 🧠 AI-driven insights & alerts (via Gemini AI + Firebase Extensions)
- 📆 Filter by week, month, or 6 months using ChipGroup
- 🎨 Modern UI/UX using custom design and icon sets
- 📲 Built for native Android devices

---

## 🛠 Tech Stack

- **Language:** Java
- **UI:** XML + Material 3 Components, Custom Views with Canvas
- **Architecture:** MVVM (ViewModel, LiveData)
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Extras:** OpenAI API, Lottie Animations, Glide, 

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0**.  
You may use, modify, and distribute this code under the terms of the GPL-3.0.  
**Any modified version must also be open-source and under the same license.**

See full license: [LICENSE](./LICENSE)

---

## 📸 Screenshots

### 🔐 Authentication

| Welcome Screen | Sign In | Signing In (Loading) | Sign In Failed |
|----------------|---------|-----------------------|----------------|
| ![Welcome](screenshots/Welcome_UI.jpg) | ![Sign In](screenshots/Signin_UI.jpg) | ![Loading](screenshots/SignIn_Progress_SecureLogin_UI.jpg) | ![Failed](screenshots/SignIn_Error_Invalid_Credentials_UI.jpg) |

| Google Sign-In | Sign Up | Reset Password |
|----------------|-------------------|---------|
| ![Google](screenshots/SignIn_GoogleAccount_Selection_UI.jpg) | ![Sign Up](screenshots/SignUp_UI.jpg) | ![Reset Password](screenshots/Forgot_UI.jpg) |

---

### 🏠 Home & Navigation

| Home (With Data) | Home (No Data Found) | Navigation Drawer |
|------------------|----------------------|-------------------|
| ![Home](screenshots/Alert_NewCategory_Grocery_Notification.jpg) | ![No Data](screenshots/NoDataFound_Weekly_Home_UI.jpg) | ![Nav](screenshots/NavDrawer_Menu_UI.jpg) |

---

### ➕ Income & Expense

| Add Expense (FAB) | Expense (Monthly) | Expense (Weekly) | Income (Weekly) |
|-------------------|-------------------|------------------|------------------|
| ![Add Expense](screenshots/Expense_UI_AddExpense_FAB_Button.jpg) | ![Expense Month](screenshots/Expense_UI_Monthly.jpg) | ![Expense Week](screenshots/Expense_UI_Weekly.jpg) | ![Income Week](screenshots/Income_UI_Weekly.jpg) |


---

### 📊 Overview & AI Insights

| Overview (May Chart) | Overview (June Summary) | AI Insights (Generate) | AI Insights (Generating PDF) |
|----------------------|--------------------------|-------------------------|------------------------------|
| ![Overview May](screenshots/Overview_BarChart_May_Summary.jpg) | ![Overview June](screenshots/Overview_BarChart_Summary.jpg) | ![Generate AI](screenshots/AIInsights_Generate_PDF_UI.jpg) | ![Generating PDF](screenshots/AIInsights_GeneratingPDF_Status_UI.jpg) |

---

### 📥 Reports & Notifications

| Notifications | System Notification (Financial Alert) | Download PDF |
|---------------|----------------------------------------|----------------|
| ![Notifications](screenshots/Notifications_UI.jpg) | ![System Alert](screenshots/System_Notification_Financial_Alert_Grocery.jpg) | ![Download](screenshots/AIInsights_Generate_PDF_UI.jpg) |


---

### 👤 Profile & Legal

| Profile (Edit Info) | Privacy Policy |
|---------------------|----------------|
| ![Profile](screenshots/ProfileScreen_Edit_Save_UI.jpg) | ![Policy](screenshots/PrivacyPolicy_UI_DataInfo.jpg) |

---

>  📁 Screenshots are stored in the /screenshots folder within the project repository.
---

### 🧠 AI Generated PDF of GenAI Expense Tracker App

📄 [View Sample AI Insights PDF Report](screenshots/AI_Insights_Report.pdf)

This professionally styled PDF was generated using **Gemini AI (by Google)** and Firebase data integration. It provides users with intelligent, data-driven financial feedback.

**Key Features of the Report:**
- 📊 **Monthly Expense Summary** with income, expense, and savings breakdown
- 🍽️ **Categorized Spending Insights** (e.g., Food, Grocery, Transport)
- 💡 **AI-Based Financial Overview** with smart suggestions per category
- 📈 **Auto-Generated Donut Chart** showing expense distribution
- 📅 **Time-Based Filtering** (Weekly/Monthly)
- ✅ **Overall Summary** with savings feedback and budget recommendations
- 🧠 Powered by **Gemini AI** for personalized insight generation
- 📥 Easily downloadable for offline reference

---

## 📦 How to Run

1. Clone this repo:  
   `git clone https://github.com/KapilPandey94/genai-expense-tracker.git`

2. Open in **Android Studio**

3. Connect Firebase via Firebase Assistant

4. Add your `google-services.json` file

5. Run on emulator or physical Android device

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome!  
If you'd like to contribute, please fork the repository and submit a pull request.  
For significant changes, kindly open an issue first to discuss your ideas.

---

## 📬 Contact

📧 [LinkedIn – Kapil Pandey](https://www.linkedin.com/in/kapil-pandey-568353318)  
🌐 [GitHub – KapilPandey94](https://github.com/KapilPandey94)

---

### 🔖 #android #firebase #mvvm #expense-tracker #openai #mobileapp #firebaseauth #cloudfirestore
