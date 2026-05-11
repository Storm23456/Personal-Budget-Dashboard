# Personal Budget Dashboard 📊

An advanced Excel-based financial management system designed to move beyond simple expense tracking into proactive wealth management. This tool implements the **Zero-Based Budgeting** method, ensuring every dollar of your income is assigned a specific purpose.

## 🚀 Key Features

- **Zero-Based Budgeting:** Plan your income, expenses, and savings until your remaining balance is exactly zero [00:01:12].
- **Dynamic Categories:** Fully customizable sections for Income, Expenses (Needs vs. Wants), and Savings [00:01:39].
- **Multi-Period Planning:** Plan for the entire year with support for one-time annual payments, quarterly bills, and monthly variations [00:03:33].
- **Automated Dashboard:** Interactive visual analysis of budget performance, including:
  - Total Income vs. Total Expenses vs. Total Savings [00:12:59].
  - Savings Rate KPI: "You are saving X% of your income" [06:00:39].
  - Month-over-month performance breakdowns.
- **Smart Tracking:** Advanced date-handling features that align paychecks with the correct budget month [00:10:20].

## 🛠️ Technical Details

- **Named Ranges:** Utilizes dynamic named calculations (e.g., `Income_Header_Row`) for robust data referencing [00:31:18].
- **Excel Functions:** Leverages `ADDRESS`, `INDIRECT`, and `SUMIFS` for dynamic data aggregation [00:35:38].
- **Conditional Formatting:** Visual cues to highlight budget status (e.g., over-budget or fully allocated) [00:52:15].
- **Data Integrity:** Separate calculation and data sheets to ensure front-end performance and back-end security [06:04:26].

## 📖 How to Use

1. **Setup Categories:** Define your custom categories in the Budget Planning worksheet.
2. **Plan Your Year:** Enter your expected income and fixed expenses.
3. **Track Transactions:** Record your actual spending and income in the Data Entry sheet.
4. **Analyze:** Use the Dashboard to review your performance and adjust your habits.

## 🙏 Credits

This project was built following the detailed tutorial by **The Office Lab**.
- **Video Tutorial:** [How to create Ultimate Personal Budget in Excel](https://www.youtube.com/watch?v=eKyAOjH3Crk)
- **Source Inspiration:** [The Office Lab YouTube Channel](https://www.youtube.com/@TheOfficeLab)
