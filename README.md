<div align="center">

<br />

<img src="public/Dashboard.png" alt="Credixa" width="100%" />

<br />
<br />

# Credixa

**A modern Bank Management System built with HTML, CSS, JavaScript and Supabase**

<p>
  <a href="https://bank-management-system-ldfz.onrender.com">
    <img src="https://img.shields.io/badge/Live%20Demo-Visit%20Now-0F4C81?style=for-the-badge&logo=render&logoColor=white" alt="Live Demo" />
  </a>
  &nbsp;
  <a href="https://github.com/PriyankaChoudhary9877/bank-management-system">
    <img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" />
</p>

</div>

---

## Overview

Credixa is a responsive web-based Bank Management System that allows users to securely manage their bank accounts online. It provides authentication, account creation, deposits, withdrawals, balance inquiry, and transaction history — all through a clean banking dashboard.

Built using HTML, CSS, JavaScript, and Supabase, Credixa demonstrates modern web application development with cloud-based authentication, PostgreSQL database integration, and a responsive user interface.

---

## Highlights

- Secure user authentication using Supabase
- Cloud-based PostgreSQL database for real-time data storage
- Responsive banking dashboard with a clean, modern UI
- Real-time account and transaction management
- Built with HTML, CSS, and JavaScript — no backend framework required

---

## Screenshots

<table>
  <tr>
    <td align="center" width="50%">
      <b>Dashboard</b><br /><br />
      <img src="public/Dashboard.png" width="100%" alt="Dashboard" />
    </td>
    <td align="center" width="50%">
      <b>Create Account</b><br /><br />
      <img src="public/Create Account.png" width="100%" alt="Create Account" />
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <b>Deposit Money</b><br /><br />
      <img src="public/Deposit Money.png" width="100%" alt="Deposit Money" />
    </td>
    <td align="center" width="50%">
      <b>Withdraw Money</b><br /><br />
      <img src="public/Withdraw Money.png" width="100%" alt="Withdraw Money" />
    </td>
  </tr>
</table>

<details>
<summary><b>More Screenshots</b></summary>

<br />

**Authentication**

<table align="center">
  <tr>
    <td align="center"><b>Login Page</b><br /><br /><img src="public/Login Page.png" width="340" alt="Login Page" /></td>
    <td align="center"><b>Register Page</b><br /><br /><img src="public/Register Page.png" width="340" alt="Register Page" /></td>
  </tr>
</table>

<br />

**Account Created**

<p align="center">
  <img src="public/Account Created.png" width="75%" alt="Account Created" />
</p>

**Balance Inquiry**

<p align="center">
  <img src="public/Balance Inquiry.png" width="75%" alt="Balance Inquiry" />
</p>

**Transaction History**

<p align="center">
  <img src="public/Transaction History.png" width="75%" alt="Transaction History" />
</p>

**Particular Transaction History**

<p align="center">
  <img src="public/Particular Transaction History.png" width="75%" alt="Particular Transaction History" />
</p>

</details>

---

## Features

| Feature | Description |
|---|---|
| Secure Authentication | User registration, login, and logout via Supabase Authentication |
| Personal Dashboard | View account statistics, total balance, and recent activity |
| Create Bank Account | Open a new bank account with an initial deposit |
| Deposit Money | Add funds to any existing account |
| Withdraw Money | Prevents withdrawals when the account has insufficient balance |
| Balance Inquiry | Check the real-time balance of any account |
| Transaction History | Track all deposits and withdrawals with timestamps |
| Particular Transaction History | View detailed transaction records per account |
| Delete Account | Remove an existing bank account |
| Cloud Database | Accounts and transactions stored securely in Supabase PostgreSQL |
| Responsive Web Interface | Modern banking interface optimized for desktop and mobile |

---

## Tech Stack

<table>
  <tr>
    <td valign="top" width="25%">
      <b>Frontend</b><br /><br />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" /><br />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" /><br />
      <img src="https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
    </td>
    <td valign="top" width="25%">
      <b>Backend & Auth</b><br /><br />
      <img src="https://img.shields.io/badge/Supabase_Auth-3ECF8E?style=flat-square&logo=supabase&logoColor=white" /><br />
      <img src="https://img.shields.io/badge/Supabase_Database-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <b>Database</b><br /><br />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <b>Deployment</b><br /><br />
      <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" /><br />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /><br />
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
    </td>
  </tr>
</table>

---

## Database Schema

### `accounts`

| Column | Type |
|---|---|
| accnum | bigint |
| name | text |
| balance | numeric |
| user_id | uuid |

### `transactions`

| Column | Type |
|---|---|
| id | bigint |
| accnum | bigint |
| description | text |
| amount | numeric |
| type | text |
| date | text |
| user_id | uuid |

---

## Getting Started

<details>
<summary><b>Prerequisites</b></summary>

<br />

- A modern web browser
- A Supabase account and project
- Render account (optional, for deployment)

</details>

<details open>
<summary><b>Installation</b></summary>

<br />

**1. Clone the repository**

```bash
git clone https://github.com/PriyankaChoudhary9877/bank-management-system.git
cd bank-management-system
```

**2. Set up Supabase**

- Create a new Supabase project
- Create the `accounts` and `transactions` tables using the schema above
- Enable Email/Password authentication in the Supabase dashboard

**3. Configure Supabase keys**

Replace the placeholder values in your JavaScript files:

```javascript
const SUPABASE_URL = "YOUR_SUPABASE_URL";
const SUPABASE_ANON_KEY = "YOUR_SUPABASE_ANON_KEY";
```

**4. Run the project**

Open `login.html` directly in your browser, or deploy to Render.

</details>

---

## Project Structure

```
bank-management-system/
│
├── index.html                 # Dashboard
├── login.html                 # Login Page
├── register.html              # Registration Page
├── README.md
│
└── public/                    # Screenshots
```

---

## Future Enhancements

- Money Transfer Between Users
- User Profile Management
- Email Notifications
- Monthly Statement Download (PDF)
- Search Transactions
- Dark Mode
- Admin Dashboard
- Interest Calculator
- Loan Management
- QR Payment Support

---

## Author

<table>
  <tr>
    <td align="center">
      <b>Priyanka Choudhary</b><br />
      Computer Science Engineering Student<br /><br />
      <a href="https://github.com/PriyankaChoudhary9877">
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
      </a>
      &nbsp;
      <a href="https://www.linkedin.com/in/priyanka-choudhary-58b048312/">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
      </a>
      &nbsp;
      <a href="https://bank-management-system-ldfz.onrender.com">
        <img src="https://img.shields.io/badge/Live%20Demo-0F4C81?style=flat-square&logo=render&logoColor=white" />
      </a>
      &nbsp;
      <a href="mailto:priyankachoudhary9877@gmail.com">
        <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
      </a>
    </td>
  </tr>
</table>

---

## License

This project is intended for educational purposes.

---

<div align="center">

⭐ If you found this project useful, please consider giving it a star on GitHub.

<br />

Designed and developed by Priyanka Choudhary.

</div>
