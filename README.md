# GDR Construction – Employee & Project Management Portal

**Company:** GDR Construction  
**Head Office:** Capitol, High Street, Jaipur, Rajasthan

---

## 📁 Folder Structure

```
gdr-construction/
│
├── html/                          ← All HTML pages
│   ├── index.html                 ← Main marketing website
│   ├── employee-login.html        ← Employee login / set password
│   ├── employee-dashboard.html    ← Employee self-service dashboard
│   ├── admin-login.html           ← Admin login page
│   └── admin-dashboard.html       ← Full admin management portal
│
├── css/                           ← All stylesheets
│   ├── styles.css                 ← Main website styles
│   └── portal.css                 ← Portal (login/dashboard) styles
│
├── js/                            ← All JavaScript
│   ├── main.js                    ← Main site JS (navbar, animations)
│   ├── employee-portal.js         ← Employee auth, attendance, earnings
│   └── admin-portal.js            ← Admin CRUD, payroll, reports, Excel
│
└── assets/
    └── images/                    ← Add company/project photos here
```

---

## 🚀 How to Open

Simply open `html/index.html` in any modern web browser. No server or installation needed.

---

## 🔐 Login Credentials

### Employee Portal
- **Mobile:** `9876543210` → `9876543217`
- **Password:** `emp1234` (for all sample employees)
- URL: `html/employee-login.html`

### Admin Portal
- **Username:** `admin`
- **Password:** `gdr2024`
- URL: `html/admin-login.html`

---

## ✅ Features

### 🌐 Marketing Website (index.html)
- Hero section with company stats counter animation
- About section with company story
- 6 active/completed project cards
- 6 service cards
- Portal links section
- Contact form
- Footer with address (Capitol, High Street, Jaipur)

### 👷 Employee Portal
- Login with mobile number + password
- First-time password setup
- Personal dashboard with attendance summary
- Monthly attendance calendar (colour-coded)
- Earnings breakdown (gross → deduction → net)
- Full attendance history log
- Profile view
- Change password anytime

### 🔐 Admin Portal
- Secure admin login
- **Employee Management** — Add, Edit, Delete employees; search & filter
- **Attendance** — Mark Present/Absent/Half Day for any date; bulk mark all present
- **Payroll** — Auto-calculate monthly earnings per employee; mark paid
- **Reports** — Department-wise attendance bars, low attendance alerts
- **Excel Import** — Upload CSV to bulk-add employees
- **Excel Export** — Download employee list and attendance sheets as CSV

---

## 📦 Data Storage

All data is stored in the browser's **localStorage** under the key prefix `gdr_`.  
Keys used: `gdr_employees`, `gdr_attendance`, `gdr_emp_session`, `gdr_admin_session`

> To reset all data: Open browser console and run `localStorage.clear()`

---

## 🗺️ Operating Locations

| State       | Cities / Projects          |
|-------------|---------------------------|
| Rajasthan   | Jaipur (HQ), Jodhpur       |
| Delhi       | New Delhi                  |
| Gujarat     | Ahmedabad                  |
| Karnataka   | Bangalore                  |

---

## 🔧 To Customise

1. **Add company logo/photos** → Place images in `assets/images/` and update `<img>` tags in HTML files
2. **Change company name** → Search and replace "GDR Construction" across all files
3. **Add more employees** → Use Admin Portal → Add Employee, or import via CSV template
4. **Change admin password** → Edit `ADMIN_CREDENTIALS` in `js/admin-portal.js`
5. **Add more projects** → Update the project `<option>` lists in `admin-dashboard.html`

---

*Built for GDR Construction | Jaipur, Rajasthan | 2024*
