# 💸 Smart Expense Splitter

An intelligent, modern web application to effortlessly split group expenses, track balances, and gain AI-powered financial insights. Built with Angular, .NET Core, SQL Server, and a dedicated Notifications Microservice.

---

## 🚀 Project Overview

**Smart Expense Splitter** helps friends, roommates, and teams manage shared expenses, settle up, and understand their spending habits with the help of AI. The platform features a modular architecture, clean UI, robust backend, and scalable microservices.

---

## 🏗️ Architecture
Frontend (Angular) <----> Backend API (.NET Core) <----> SQL Server Database | +----> Notifications Microservice (.NET Core)

- **Frontend:** Angular SPA, Material UI, responsive design
- **Backend:** ASP.NET Core Web API, RESTful endpoints, JWT Auth
- **Database:** SQL Server, normalized schema, soft deletes, ERD included
- **Notifications:** Separate microservice for scalable, async notifications

---

## 📦 Repositories

| Component                | Repository Link                                                                 |
|--------------------------|--------------------------------------------------------------------------------|
| Frontend (Angular)       | [smart-expense-splitter-ui](https://github.com/Aman-Keshri/smart-expense-splitter-ui) |
| Backend API (.NET Core)  | [smart-expense-splitter-api](https://github.com/Aman-Keshri/smart-expense-splitter-api) |
| Notifications Service    | [smart-expense-splitter-notifications](https://github.com/Aman-Keshri/smart-expense-splitter-notifications) |
| Database & Diagrams      | [smart-expense-splitter-db](https://github.com/Aman-Keshri/smart-expense-splitter-db) |

---

## ✨ Features

- **User Authentication:** Secure registration, login, JWT-based sessions
- **Groups:** Create, join, and manage groups for trips, events, or households
- **Expense Management:** Add, edit, split, and track expenses with receipts
- **Settlements:** Real-time balance calculation and easy settle-up flows
- **AI Insights:** Personalized spending analytics and smart tips
- **Notifications:** Real-time alerts for expenses, settlements, and reminders
- **Data Visualization:** Interactive charts for spending trends
- **Responsive UI:** Works seamlessly on desktop and mobile

---

## 🖥️ UI/UX

- **Modern, intuitive dashboard**
- **Group details with tabs:** Expenses, Balances, Settlements, Receipts, Insights
- **Modals:** Add/Edit Expense, Settle Up, Invite Member, Upload Receipt
- **Side Panels:** Notifications, Group Members
- **Insights Page:** AI-powered analytics and export options

> **See UI wireframes and prototypes in the [UI Design folder](./ui-design/)**

---

## 🔗 API

- **RESTful endpoints** for all core features
- **OpenAPI/Swagger documentation** included
- **Versioned API:** `/api/v1/`
- **Notifications** handled by a dedicated microservice

> **See full API docs in the [API repo](https://github.com/Aman-Keshri/smart-expense-splitter-api)**

---

## 🗄️ Database

- **SQL Server** with normalized schema
- **Soft deletes** (`IsActive` flags) for auditability
- **ER diagrams** and migration scripts included

> **See schema, ERD, and scripts in the [DB repo](https://github.com/Aman-Keshri/smart-expense-splitter-db)**

---

## 🔔 Notifications Microservice

- **Decoupled microservice** for notifications
- **REST API** for sending, listing, and managing notifications
- **Scalable** and ready for async/message queue integration

> **See implementation in the [Notifications repo](https://github.com/Aman-Keshri/smart-expense-splitter-notifications)**

---

## 🛠️ Tech Stack

- **Frontend:** Angular, TypeScript, Material UI
- **Backend:** ASP.NET Core, C#, Entity Framework Core
- **Database:** SQL Server
- **Microservices:** .NET Core Web API
- **DevOps:** Docker, GitHub Actions, Azure/AWS/Netlify/Vercel
- **Documentation:** Swagger, dbdiagram.io, Markdown

---

## 📋 Getting Started

1. **Clone the repositories** (see links above)
2. **Set up the database** using scripts in the DB repo
3. **Configure environment variables** for API and UI
4. **Run the backend API and notifications microservice**
5. **Serve the Angular frontend**
6. **Access the app at `http://localhost:4200` (default)**

> Detailed setup instructions in each repo’s README.

---

## 📊 Documentation

- **System Design:** [docs/system-design.md](./docs/system-design.md)
- **ER Diagram:** [dbdiagram.io code](./db/er-diagram.dbml)
- **API Reference:** [OpenAPI/Swagger](https://github.com/Aman-Keshri/smart-expense-splitter-api/swagger)
- **UI Wireframes:** [Figma/Uizard/Excalidraw links](./ui-design/)

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## 📄 License

This project is licensed under the MIT License.

---

**Built with ❤️ by Aman-Keshri**
