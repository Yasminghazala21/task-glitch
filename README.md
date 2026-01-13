# **TASK GLITCH** 📋

**Production-Ready React CRM Task Dashboard**  
*Sales pipeline analytics with live charts, ROI tracking, and full CRUD*

## ✨ **Live Demo**
[[https://task-glitch-six-mu.vercel.app/](https://task-glitch-six-mu.vercel.app/)]

## 📊 **Features**

- **📱 Fully Responsive** 
- **🔄 Full CRUD Operations** - Add/Edit/Delete with Undo
- **✅ TypeScript Strict** - Zero runtime errors
- **🔒 XSS Secure** - Sanitized inputs/outputs

## 🛠 **Tech Stack**

```
Frontend: React 18 -  TypeScript -  Vite -  MUI 5
State: React Context API
Build: Vite + Vercel
```

## 🎮 **Quick Start**

```bash
# Clone & Install
[[https://github.com/Yasminghazala21/task-glitch](https://github.com/Yasminghazala21/task-glitch)]
cd task-glitch
npm install

# Development
npm run dev
```

## 💻 **Project Structure**

```
src/
├── components/     # TaskTable, AnalyticsDashboard, MetricsBar, ...
├── context/        # TasksContext, UserContext  
├── hooks/          # useTasks (core state)
├── utils/          # logic.ts, seed.ts, csv.ts
```

## 🎯 **Key Challenges Solved**

- 🐛 **7 Production Bugs Fixed** - XSS, ROI NaN, duplicate keys, double fetch, undo snackbar, ...
- 🔍 **TypeScript Evolution** - `Task` → `DerivedTask` strict typing  
- 📊 **Chart Data Pipeline** - `roi`, `priorityWeight` derivation
- ♻️ **State Normalization** - Malformed seed data handling


```
