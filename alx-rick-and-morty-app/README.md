# ALX Rick and Morty App

## Description
This project is a **Next.js + TypeScript** application that uses **Apollo Client** and **GraphQL** to fetch data from the [Rick and Morty API](https://rickandmortyapi.com/graphql).  
It also integrates **ESLint** and **TailwindCSS** for a modern development workflow.

---

## 🚀 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/<your-username>/alx-graphql-0x01.git
cd alx-graphql-0x01/alx-rick-and-morty-app

### Install Dependencies

npm install
npm install @apollo/client graphql
npm install -D @types/graphql

```
---
## 📂 Project Structure
```bash
alx-rick-and-morty-app/
├── graphql/
│   ├── apolloClient.ts   # Apollo Client setup
│   └── queries.ts        # GraphQL queries
├── pages/
│   └── _app.tsx          # ApolloProvider setup
├── styles/
│   └── globals.css       # Tailwind CSS
├── package.json
└── README.md
