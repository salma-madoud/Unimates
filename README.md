<div align="center">

# 🎓 UniMates

### *Find Your Tribe at Al Akhawayn University*

[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6.2-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Google Gemini](https://img.shields.io/badge/Gemini_AI-Powered-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square" alt="Made with love"/>
  <img src="https://img.shields.io/badge/University-AUI-blue?style=flat-square" alt="University"/>
</p>

<br/>

**UniMates** is a modern social platform designed to help students at **Al Akhawayn University** connect with peers who share similar interests, academic goals, and activities.

*Looking for a study partner? Gym buddy? Project collaborator? UniMates makes it easy to find your people.*

[🚀 Getting Started](#-getting-started) •
[✨ Features](#-features) •
[🛠️ Tech Stack](#️-tech-stack) •
[📖 Documentation](#-api-endpoints)

</div>

---

## 📸 Screenshots

<div align="center">
<table>
  <tr>
    <td align="center"><b>🏠 Discovery Feed</b></td>
    <td align="center"><b>💬 Chat Interface</b></td>
  </tr>
  <tr>
    <td><i>Discover and match with students based on shared interests</i></td>
    <td><i>Real-time messaging with your connections</i></td>
  </tr>
  <tr>
    <td align="center"><b>👤 Profile Setup</b></td>
    <td align="center"><b>⚙️ Admin Dashboard</b></td>
  </tr>
  <tr>
    <td><i>Customize your profile and interests</i></td>
    <td><i>Manage users and moderate content</i></td>
  </tr>
</table>
</div>

---

## 📋 About The Project

**UniMates** is a class project developed for the **Software Engineering Course** (Led by Dr. Hoda) at Al Akhawayn University. The application demonstrates full-stack web development practices including system design, database architecture, API development, and user interface design.

### 🎯 The Problem

University students often struggle to find others who want to collaborate on academics, sports, or social activities. Traditional methods of networking can be time-consuming and ineffective.

### 💡 Our Solution

UniMates streamlines the discovery process through an **intelligent AI-powered matching system** and an **intuitive messaging platform**, making it effortless to find students with aligned goals and interests.

---

## ✨ Features

<table>
<tr>
<td>

### 🔐 Core Features
- **Secure Authentication** — Login/register with @aui.ma email validation
- **Smart Matching** — AI-powered discovery based on shared interests
- **Direct Messaging** — Real-time chat with match partners
- **Profile Customization** — Bio, interests, academic details
- **Interest-Based Filtering** — Study, sports, hobbies & more

</td>
<td>

### 🚀 Advanced Features
- **🤖 AI Insights** — Gemini-powered match reasoning
- **🛡️ Admin Dashboard** — User & content moderation
- **🚨 Report System** — Flag inappropriate behavior
- **🔔 Notifications** — Match & message alerts
- **📊 Match Tracking** — Pending, accepted, declined states

</td>
</tr>
</table>

### Match Purposes

| Purpose | Description |
|---------|-------------|
| 📚 **Study Partner** | Find classmates to study with |
| 💪 **Gym Buddy** | Connect with fitness enthusiasts |
| 🎉 **Social Hangout** | Meet new friends for social activities |
| 💼 **Project Collaborator** | Team up for academic projects |

---

## 🛠️ Tech Stack

<div align="center">

### Frontend
| Technology | Purpose |
|:----------:|:-------:|
| ![React](https://img.shields.io/badge/-React_19-61DAFB?style=flat-square&logo=react&logoColor=black) | UI Library |
| ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Type Safety |
| ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | Build Tool |
| ![Tailwind](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | Styling |
| ![React Router](https://img.shields.io/badge/-React_Router-CA4245?style=flat-square&logo=react-router&logoColor=white) | Navigation |

### AI & Integrations
| Technology | Purpose |
|:----------:|:-------:|
| ![Gemini](https://img.shields.io/badge/-Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white) | AI Match Insights |
| ![Recharts](https://img.shields.io/badge/-Recharts-FF6384?style=flat-square&logo=chart.js&logoColor=white) | Analytics Charts |

</div>

---

## 📁 Project Structure

```
UniMates/
├── 📂 components/              # React UI Components
│   ├── Auth.tsx               # 🔐 Login & Registration
│   ├── Home.tsx               # 🏠 Discovery & Matching
│   ├── ChatRoom.tsx           # 💬 Direct Messaging
│   ├── ChatList.tsx           # 📋 Conversation List
│   ├── Profile.tsx            # 👤 User Profile View
│   ├── ProfileSetup.tsx       # ✏️ Profile Configuration
│   ├── Settings.tsx           # ⚙️ App Settings
│   ├── UserProfile.tsx        # 👥 Other User Profiles
│   ├── AdminDashboard.tsx     # 🛡️ Admin Controls
│   └── Layout.tsx             # 📐 App Layout Wrapper
│
├── 📂 services/
│   ├── dbService.ts           # 🗄️ Database Operations
│   └── geminiService.ts       # 🤖 AI Integration
│
├── App.tsx                    # 🚀 Main App Component
├── types.ts                   # 📝 TypeScript Interfaces
├── index.tsx                  # 📍 Entry Point
├── index.html                 # 🌐 HTML Template
├── vite.config.ts             # ⚡ Vite Configuration
├── tsconfig.json              # 🔧 TypeScript Config
└── package.json               # 📦 Dependencies
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** `v18+` — [Download](https://nodejs.org/)
- **npm** or **yarn** — Package manager
- **Git** — Version control

### ⚡ Quick Start

```bash
# 1️⃣ Clone the repository
git clone https://github.com/RamiR4mi/UniMates.git

# 2️⃣ Navigate to the project
cd UniMates

# 3️⃣ Install dependencies
npm install

# 4️⃣ Start the development server
npm run dev
```

The app will be available at `http://localhost:5173` 🎉

### 🔑 Environment Setup

Create a `.env` file in the root directory:

```env
# Google Gemini API Key (for AI features)
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

> 💡 **Get your Gemini API key** at [Google AI Studio](https://makersuite.google.com/app/apikey)

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
<<<<<<< HEAD
| `npm test` | Run unit tests with Vitest |

---

## 🧪 Testing

UniMates uses **Vitest** for unit testing. Tests are located alongside source files with the `.test.ts` extension.

### Running Tests

```bash
# Run tests in watch mode
npm test

# Run tests once (CI mode)
npm test -- --run
```

### Test Example

The `calculateMatchScore` utility function calculates compatibility between users based on shared interests:

```typescript
// utils.ts
export function calculateMatchScore(interestsA: string[], interestsB: string[]) {
  const shared = interestsA.filter(i => interestsB.includes(i));
  return shared.length * 10; // each shared interest = +10 score
}
```

```typescript
// utils.test.ts
describe('calculateMatchScore', () => {
  it('returns correct score based on shared interests', () => {
    const a = ['Coding', 'Basketball', 'Music'];
    const b = ['Music', 'Cooking', 'Coding'];

    const score = calculateMatchScore(a, b);

    expect(score).toBe(20); // 2 shared interests * 10 = 20
  });
});
```

### Test Results

<div align="center">

![Vitest Test Results](./screenshots/test-results.png)

*All tests passing ✅*

</div>

```
 ✓ utils.test.ts (1 test) 4ms
   ✓ calculateMatchScore
     ✓ returns correct score based on shared interests

 Test Files  1 passed (1)
      Tests  1 passed (1)
```
=======
>>>>>>> 32cb048b345c89d15b5cbf222331cc23af96b1ba

---

## 📝 API Endpoints

<details>
<summary><b>🔐 Authentication</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/auth/register` | Register new user |
| `POST` | `/auth/login` | User login |

</details>

<details>
<summary><b>👥 Users</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/users` | Get all users |
| `GET` | `/users/:id` | Get user by ID |
| `PATCH` | `/users/:id` | Update user profile |

</details>

<details>
<summary><b>💕 Matches</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/matches` | Get all matches |
| `POST` | `/matches` | Create match request |
| `PATCH` | `/matches/:id` | Update match status |

</details>

<details>
<summary><b>💬 Messages</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/messages?matchId=:id` | Get messages for match |
| `POST` | `/messages` | Send a message |

</details>

<details>
<summary><b>🔔 Notifications</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/notifications?userId=:id` | Get user notifications |
| `PATCH` | `/notifications/:id/read` | Mark as read |
| `POST` | `/notifications/read-all` | Mark all as read |

</details>

<details>
<summary><b>🚨 Reports</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/reports` | Get all reports (admin) |
| `POST` | `/reports` | Submit user report |
| `PATCH` | `/reports/:id` | Update report status |

</details>

---

## 🎓 Course Information

<table>
<tr>
<td>

| | |
|---|---|
| **Course** | Software Engineering |
| **Instructor** | Dr. Hoda |
| **Institution** | Al Akhawayn University in Ifrane |
| **Semester** | Fall 2025 |

</td>
<td>

### Skills Demonstrated
- ✅ Requirements Analysis
- ✅ System Architecture Design
- ✅ Database Normalization
- ✅ RESTful API Development
- ✅ Modern Frontend Practices
- ✅ Version Control (Git)

</td>
</tr>
</table>

---

## 👥 Team

<div align="center">

| Role | Name |
|------|------|
| **Project Lead & Developer** | Rami Mazaoui |

</div>

---

## 🤝 Contributing

While this is a course project, feedback and suggestions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is provided as-is for **educational purposes** as part of the Software Engineering course at Al Akhawayn University.

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

<br/>

**Built with ❤️ for the AUI Community**

<br/>

<img src="https://img.shields.io/badge/Al_Akhawayn_University-Ifrane,_Morocco-1a73e8?style=for-the-badge" alt="AUI"/>

</div>
