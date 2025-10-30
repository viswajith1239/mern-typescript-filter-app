# mern-typescript-filter-app
# 🚀 MERN Stack Advanced Filtering, Sorting & Pagination App (TypeScript)



A complete **MERN Stack** application built using **TypeScript**, featuring **advanced filtering**, **sorting**, **pagination**, and **CSV export**.  
This project demonstrates efficient **backend data handling** and a **modern, responsive frontend** using React and TailwindCSS.

---

## 📌 Features

### 🖥️ Frontend (React + TypeScript)
- Real-time filtering, search, date range, sorting, and pagination
- Export filtered results to CSV
- Elegant, responsive UI using **TailwindCSS** and **Lucide Icons**
- Modular and clean component-based structure

### ⚙️ Backend (Express + TypeScript)
- REST API for managing and filtering documents
- **Aggregation pipelines** for efficient MongoDB querying
- Pagination and sorting using query parameters
- CSV export endpoint for easy report generation
- Type-safe with TypeScript and modular controllers

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React, TypeScript, TailwindCSS, Axios |
| **Backend** | Node.js, Express.js, TypeScript, Mongoose |
| **Database** | MongoDB |
| **Utilities** | CSV Writer, Morgan, CORS |

---

## 📁 Folder Structure

project-root/
├── backend/
│ ├── src/
│ │ ├── config/
│ │ │ └── db.ts
│ │ ├── controllers/
│ │ │ └── documentController.ts
│ │ ├── models/
│ │ │ └── Document.ts
│ │ ├── routes/
│ │ │ └── documentRoutes.ts
│ │ ├── utils/
│ │ │ └── csvExport.ts
│ │ └── index.ts
│ ├── package.json
│ ├── tsconfig.json
│ └── .env
│
└── frontend/
├── src/
│ ├── components/
│ │ ├── DocumentsTable.tsx
│ │ ├── FilterBar.tsx
│ │ └── Pageinition.tsx
│ ├── services/
│ │ └── userService.ts
│ ├── App.tsx
│ └── main.tsx
├── package.json
├── tsconfig.json
└── tailwind.config.ts


## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>



##Backend Setup
----------------------

cd backend
npm install


Create a .env file:
---------------------

PORT=5000
MONGO_URI=mongodb://localhost:27017/mern-docs


Start the server (dev mode)
----------------------------

npm run dev


Frontend Setup
-------------------------

cd ../frontend
npm install
npm run dev


Frontend: http://localhost:5173

Backend: http://localhost:5000
