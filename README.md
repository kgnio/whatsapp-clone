# 📱 WhatsApp Clone – Full Stack Real-Time Chat App

![License](https://img.shields.io/github/license/kgnio/Whatsapp-clone?style=flat-square)
![Stars](https://img.shields.io/github/stars/kgnio/Whatsapp-clone?style=social)
![Issues](https://img.shields.io/github/issues/kgnio/Whatsapp-clone)
![Last Commit](https://img.shields.io/github/last-commit/kgnio/Whatsapp-clone)

A modern **WhatsApp Clone** built using **Next.js**, **Clerk**, **Convex**, and **ZEGOCLOUD**. Includes features such as secure authentication, real-time messaging, video/group calls, dark/light themes, and responsive UI.

> ⚡ This project showcases an advanced real-time chat system with cloud-native backend and UI integrations.

---

## 📚 Table of Contents 

- [✨ Features](#-features)  
- [🛠️ Technologies Used](#-technologies-used)  
- [📦 Installation](#-installation)  
- [🚀 Usage](#-usage)  
- [🖼️ Screenshots](#-screenshots)  
- [🤝 Contributing](#-contributing)  
- [📄 License](#-license)

---

## ✨ Features

- 🔐 **Authentication** via [Clerk.dev](https://clerk.dev)
- 💬 **Real-time messaging** powered by Convex
- 📞 **1:1 and group video calls** with [ZEGOCLOUD](https://www.zegocloud.com/)
- 🎨 **Light/Dark theme toggle**
- 👥 **Group management** (kick/ban users)
- 🧑‍💼 **User profile updates** (avatar, bio, etc.)
- 📩 **Webhooks** for real-time presence and notifications
- 📱 **Mobile-first responsive UI**

---

## 🛠️ Technologies Used

| Tech             | Role                      |
|------------------|---------------------------|
| Next.js          | Frontend / SSR            |
| React.js         | UI layer                  |
| Clerk            | Authentication & sessions |
| Convex           | Serverless backend logic  |
| ZEGOCLOUD        | Video call SDK            |
| Tailwind CSS     | Styling                   |
| DaisyUI          | UI components             |
| Radix UI         | Accessibility-first UI    |
| Webhooks         | Real-time syncing         |

---

## 📦 Installation

### Prerequisites
- Node.js (v18+)
- Convex CLI

### 1. Convex Setup
```bash
npx convex dev
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Variables

Create a `.env.local` file in the root directory:

```env
CONVEX_DEPLOYMENT=dev:friendly-lion-123
NEXT_PUBLIC_CONVEX_URL=https://friendly-lion-123.convex.cloud

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_your_publishable_key
CLERK_SECRET_KEY=sk_test_your_secret_key

ZEGO_APP_ID=123456789
ZEGO_SERVER_SECRET=your_zego_server_secret
```

---

## 🚀 Running the App

```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## 🖼️ Screenshots

| 🖼️ Feature | Image |
|-----------|-------|
| **Main Page (Light)** | ![light](https://github.com/user-attachments/assets/c806a5dc-f9ff-40d2-9f57-15d6b175d7a2) |
| **Main Page (Dark)** | ![dark](https://github.com/user-attachments/assets/f45664d9-477e-4817-a116-abe6dd6dff19) |
| **Group Video Call** | ![videocall](https://github.com/user-attachments/assets/6b1fb577-5dd8-4a32-85cc-8ffe8604e35a) |
| **Profile Page** | ![profile](https://github.com/user-attachments/assets/f1d196f2-c596-4e14-8664-6dc670186bb6) |
| **Group Members** | ![members](https://github.com/user-attachments/assets/3f4c04e2-790e-4c25-bdc2-e716b0680a9d) |
| **Emoji Bar** | ![emoji](https://github.com/user-attachments/assets/2a2412e1-cdf2-4e59-b975-bbae839887a3) |

---

## 🤝 Contributing

1. 🍴 Fork this repo  
2. 🌿 Create your feature branch: `git checkout -b feature/feature-name`  
3. 💾 Commit your changes: `git commit -m 'Add feature'`  
4. 📤 Push to the branch: `git push origin feature/feature-name`  
5. 🔁 Open a pull request   

We welcome contributions of all kinds!

---

## 📄 License

Licensed under the MIT License.  
See [`LICENSE`](./LICENSE) for more information.

---

## 📬 Contact

**Project Maintainer**: [@kgnio](https://github.com/kgnio)
