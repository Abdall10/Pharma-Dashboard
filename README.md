# 💊 Pharma Dashboard

A **Pharmacy Inventory Management System** built with **ASP.NET Core (.NET 8)**, **Blazor**, and **Microsoft SQL Server**.  
The system provides an interactive dashboard to manage stock, track expiry dates, and visualize sales analytics for pharmacies.

---

## 🧠 Project Overview
Pharma Dashboard aims to address the challenges of manual pharmacy inventory management by providing a reliable digital solution that:

- Tracks and manages medicine inventory.
- Sends automatic alerts for low-stock and near-expiry medicines.
- Generates analytical reports and charts for better insights.
- Enhances operational efficiency and decision-making.

---

## 🧩 Features
- 🔐 **Secure Login System** (Admin / Pharmacist / Sales Staff)
- 💊 **Drug Management** (Add, Edit, Delete, Search)
- ⚠️ **Automatic Alerts** for low stock & expiry
- 📊 **Interactive Dashboard** (Sales, Items, Trends)
- 📁 **Export Reports** (PDF / Excel)
- 🗄 **Database Integration** with Microsoft SQL Server

---

## ⚙️ Technologies Used
| Category | Technology |
|-----------|-------------|
| Framework | ASP.NET Core / .NET 8 |
| Frontend  | Blazor + Bootstrap |
| Database  | Microsoft SQL Server |
| UI Design | Figma / Canva |
| IDE       | Visual Studio 2022 |
| OS        | Windows 10+ |

---

## 👥 Team Members
| Name | Role | ID |
|------|------|----|
| **Abdullah Raafat Madi Abdul Ghafour** | Project Manager & System Analyst | 202300489 |
| **Eslam Mohamed Mohamed Ibraheem** | Frontend Developer | 202402099 |

---

## 🗂️ Repository Structure
```
Pharma-Dashboard/
│
├── backend/        # ASP.NET Core logic & API
├── frontend/       # Blazor UI components
├── database/       # SQL scripts and schema
├── docs/           # Proposal, diagrams, documentation
└── README.md       # Project overview
```

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Pharma-Dashboard.git
   ```
2. Open the solution in **Visual Studio 2022**.
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Set up **SQL Server** using scripts from `/database/`.
5. Update the connection string in `appsettings.json`.
6. Run the project:
   ```bash
   dotnet run
   ```
7. Access the dashboard at:
   ```
   http://localhost:5000
   ```

---

## 📅 Project Phases
| Phase | Duration | Description |
|--------|-----------|-------------|
| Requirements Analysis | 2 weeks | Collect and analyze requirements |
| System Design | 2 weeks | Design database and UI |
| Development | 4 weeks | Implement the core system |
| Testing | 2 weeks | Debug and fix issues |
| Final Delivery | 1 week | Prepare final report and presentation |

---

## 🧩 Contributing Rules (Team Workflow)
To keep our work organized and consistent, every team member should follow these basic rules:

### 🔹 1. Branch Workflow
Each member has their own branch:
```
main        → managed by the leader (Abdullah)
backend     → Eslam and Abdullah
frontend    → Eslam and Abdullah
testing     → Abdullah
docs        → Abdullah
```

### 🔹 2. Pushing Code
Always **pull** the latest version before pushing:
```bash
git pull origin main
```
Then add your changes:
```bash
git add .
git commit -m "Added new feature"
git push origin your-branch-name
```

### 🔹 3. Creating a Pull Request (PR)
1. Go to **GitHub → Pull Requests → New Pull Request**.  
2. Select your branch (e.g., `frontend`) → merge into `main`.  
3. Add a description (what you added or fixed).  
4. Wait for the **leader’s review (Abdullah)** before merging.

### 🔹 4. Code Style
- Use clear and consistent naming (`camelCase`, `PascalCase`).
- Add comments for major functions or logic.
- Keep commits small and meaningful.
- Test your part before pushing.

### 🔹 5. Communication
- Use GitHub Issues or team chat for updates.
- Inform the leader before merging large changes.
- Weekly team check-in to review progress.

---

## 📚 References
- [Microsoft Learn: ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core)
- [W3Schools: C# Tutorial](https://www.w3schools.com/cs/index.php)
- [freeCodeCamp: Learn .NET](https://www.freecodecamp.org/news/tag/net/)
- [GitHub Example: Pharmacy Management System](https://github.com/OmarrSakr/Pharmacy-Management)

---

## 🏁 Acknowledgment
We would like to express our sincere gratitude to  
**Dr. Nermeen Hamza** – Project Supervisor  
for their guidance, support, and encouragement throughout this project.

---

## 📜 License (MIT)
```
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
---

🧪 *Cairo University – Faculty of Graduate Studies for Statistical Research*  
**Department of Computer Science – 2025**
