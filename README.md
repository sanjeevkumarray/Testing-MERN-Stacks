
# 🚀 Testing-in-the-MERN-Stack

A structured, incremental guide to testing **Express.js** applications using modern tools such as **Vitest**, **Supertest**, **Zod**, and **Prisma**.
This repository demonstrates a progressive learning path — starting from simple test setups and advancing to full backend integration with database testing.

---

## 📁 Repository Structure

```
Testing-MERN-Stacks/
├── 1-simple-test
├── 2-simple-express-app
├── 3-express-with-zod
├── 4-express-with-vitest
└── 5-express-vitest-prisma
```

Each directory contains an isolated project with its own configuration, dependencies, and test cases.

---

## 🧭 Project Overview

| Level | Project Name                  | Description                                                         | Core Tools                                 |
| :---: | ----------------------------- | ------------------------------------------------------------------- | ------------------------------------------ |
|  1️⃣  | **Simple Test**               | Basic setup for running HTTP tests using Jest and Supertest.        | `ts-jest`, `@jest/globals`, `supertest`    |
|  2️⃣  | **Simple Express App**        | Introduces a basic Express server and API test setup.               | `express`, `supertest`                     |
|  3️⃣  | **Express with Zod**          | Adds schema validation for request data using Zod.                  | `express`, `zod`, `supertest`              |
|  4️⃣  | **Express with Vitest**       | Migrates testing environment to Vitest for faster test execution.   | `vitest`, `zod`, `supertest`               |
|  5️⃣  | **Express + Vitest + Prisma** | Integrates Prisma ORM for database interaction and test automation. | `prisma`, `vitest`, `express`, `supertest` |

---

## ⚙️ Installation & Setup

Navigate to the desired folder before running commands:

```bash
cd <project-folder-name>
```

### 1️⃣ Simple Test

```bash
npm install --save-dev ts-jest @jest/globals @types/express
npm install supertest @types/supertest
npm run test
```

### 2️⃣ Simple Express App

```bash
npm install --save-dev ts-jest @jest/globals @types/express
npm install supertest @types/supertest
npm install express
npm run test
```

### 3️⃣ Express with Zod

```bash
npm install --save-dev ts-jest @jest/globals @types/express
npm install supertest @types/supertest
npm install express
npm install zod
npm run test
```

### 4️⃣ Express with Vitest

```bash
npm install --save-dev ts-jest @jest/globals @types/express
npm install supertest @types/supertest
npm install express
npm install zod
npm run test
```

### 5️⃣ Express + Vitest + Prisma

```bash
npm install --save-dev ts-jest @jest/globals @types/express
npm install supertest @types/supertest
npm install express
npm install prisma
npx prisma generate
npm run test
```

---

## 🧪 Running Tests

To execute tests in any project:

```bash
npm run test
```

All test files are placed under:

```
/__tests__ or /tests
```

Each project contains test examples showcasing API route testing, schema validation, and database queries where applicable.

---

## 🧠 Learning Progression

| Level | Focus Area           | Key Takeaway                                                           |
| :---: | -------------------- | ---------------------------------------------------------------------- |
|  1️⃣  | Basic Testing        | Learn the fundamentals of HTTP testing using Supertest and Jest.       |
|  2️⃣  | Express Integration  | Set up a simple Express server and test API endpoints.                 |
|  3️⃣  | Schema Validation    | Use Zod to validate incoming request bodies and query parameters.      |
|  4️⃣  | Vitest Framework     | Transition to Vitest for faster, modern TypeScript-compatible testing. |
|  5️⃣  | Database Integration | Implement Prisma ORM and test database operations in isolation.        |

---

## 🧰 Technology Stack

* **Node.js** – JavaScript runtime environment
* **Express.js** – Web framework for building REST APIs
* **Supertest** – HTTP assertion library for integration testing
* **Vitest / Jest** – Testing frameworks for JavaScript & TypeScript
* **Zod** – Runtime validation and type inference
* **Prisma ORM** – Type-safe database ORM for Node.js
* **TypeScript** – Adds static typing for reliability and scalability

---

## 🧩 Development Best Practices

✅ Test-driven development (TDD) principles
✅ Type-safe and schema-validated APIs
✅ Isolated test configuration per project
✅ Progressive modularization
✅ Clean and maintainable folder structure

---

## 📄 License

This repository is licensed under the **MIT License**.
You are free to use, modify, and distribute the code for personal or commercial purposes.

---
