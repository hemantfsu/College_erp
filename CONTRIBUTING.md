# Contributing to College ERP

Thank you for your interest in contributing to the **College ERP – Integrated Student Management System**!  
This project aims to deliver a modern, open-source, low-cost ERP solution for educational institutions using **React, TypeScript, Supabase, Backblaze B2, Tailwind CSS, Razorpay, Recharts**, and **jsPDF**.

We welcome contributions of all types — features, bug fixes, documentation improvements, UI/UX enhancements, and optimizations.

---

## 🚀 Project Tech Stack

- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS
- **Database & Auth:** Supabase (Postgres, Auth, RLS)    
- **Charts & Dashboards:** Recharts  
- **PDF Generation:** jsPDF  
- **Payments:** Razorpay (Demo Integration)  
- **Tools:** Git, GitHub, Node.js, npm  

---

## 🧩 How to Contribute

### 1. Fork the repository
Click the **Fork** button on GitHub to create your own copy.

### 2. Clone your fork
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```
### 3. Install dependencies
``` bash
npm install
```
### 4. Create a new branch
```bash
git checkout -b feature/your-feature-name
```
### 5. Make your changes
Please follow the existing structure, naming conventions, and coding style.

### 6. Commit your changes
```bash
git add .
git commit -m "feat: your short description"
```
### 7.Push your branch
```bash
git push origin feature/your-feature-name
```
### 8. Open a Pull Request
- Go to your fork
- Click Compare & Pull Request
- Add a clear explanation of your change
- Attach screenshots for UI updates

### 🧪 Coding Guidelines
- Frontend
- Use TypeScript for all files.
- Use functional components + hooks.
- Style only using Tailwind CSS utility classes.
- Keep components modular and reusable.
- Use Context API for authentication and role-based state.

### Supabase (Database)
- Table names must be snake_case.
- Always use foreign keys.
- Enforce RLS (Row Level Security).
- Never commit Supabase keys to Git.

### Payments
- Razorpay demo keys must remain in environment files, not in source control.

### Storage
- Store all documents using Backblaze B2 through secure upload endpoints.

### 📝 Commit Message Format
Follow conventional commits:
```
feat: added hostel allocation workflow
fix: resolved payment receipt generation bug
docs: updated setup instructions
refactor: optimized dashboard rendering performance
style: improved UI spacing in forms
```
### 🐞 Reporting Issues
- Found a bug? Want a feature?
- Go to the Issues tab
- Click New Issue
- Choose Bug Report / Feature Request
- Provide clear steps, screenshots, or expected behavior

### 💡 Areas You Can Contribute
- Admissions workflow improvements
- Faculty & Hostel role enhancements
- Payment integration improvements
- Dashboard analytics & charts
- Export/Import modules
- UI/UX enhancements
- Documentation & diagrams (ER, DFD)
- Performance optimizations

### 🤝 Code of Conduct
Please maintain respectful and constructive communication.
We aim to build a supportive, inclusive, and beginner-friendly open-source community.

### ⭐ Support the Project
If this project helps you or your institution:

- ⭐ Star the repository

- ⬆️ Share it with your network

- 🛠️ Contribute new modules or improvements

Thank you for helping grow the College ERP community!

  
