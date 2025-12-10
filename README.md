# 🚀 Advanced Node.js Starter Project

> A full-stack starter project using **Node.js, Express, MongoDB, and React**.

---

## ✅ System Requirements

Before starting, make sure your system meets the following requirements:

| Tool                           | Required Version |
| ------------------------------ | ---------------- |
| **Node.js**                    | `v18.x.x` ✅     |
| **npm**                        | `v8+`            |
| **NVM (Node Version Manager)** | Recommended ✅   |

> ⚠️ This project is **NOT compatible with Node.js v24+** due to legacy dependencies used in the client and server.

---

## 🔁 Node Version Setup using NVM (Recommended)

If you already have another Node version installed (like Node 24), **do NOT uninstall it**.  
Use **NVM to safely switch versions for this project**:

````bash
nvm install 18
nvm use 18

## ✅ Verify Node Version

After switching to Node 18, verify using:

```bash
node -v

### ✅ Expected Output

```bash
v18.x.x


📦 Install Dependencies (Important)
This project uses legacy packages, so install all dependencies using:

bash
Copy code
npm install --legacy-peer-deps
✅ This avoids peer dependency conflicts with modern npm versions.

▶️ Run the Project (Client + Server)
Start both backend and frontend together using:

bash
Copy code
npm run dev
✅ Server runs on:
http://localhost:5000

✅ Client starts using:
react-scripts

````
