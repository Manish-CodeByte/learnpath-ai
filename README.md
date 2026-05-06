<div align="center">
  <img src="image.png" alt="StudyBoard Logo" width="300" />
  <p><strong>The ultimate AI-powered command center for academic excellence.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Status-Beta-orange?style=for-the-badge" alt="Status" />
    <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />
    <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" alt="PRs Welcome" />
    <img src="https://img.shields.io/badge/Free-Forever-purple?style=for-the-badge" alt="Free Forever" />
  </p>

  <p>
    <a href="#-features">Features</a> •
    <a href="#-architecture">Architecture</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-setup">Setup</a> •
    <a href="#-project-structure">Structure</a>
  </p>
</div>

---

## 🚀 Overview

**StudyBoard** is a sophisticated, student-centric productivity platform that leverages artificial intelligence to streamline academic workflows. It unifies task management, focus tracking, and grade analytics into a single, cohesive dashboard designed to eliminate cognitive load and maximize student performance.

> [!IMPORTANT]
> **Free Forever Core**: StudyBoard is committed to providing its essential features for free to students everywhere.

---

## ✨ Features

### 🤖 AI-Powered Intelligence
*   **Daily Strategic Briefings**: Wake up to a generated summary of your day, highlighting critical deadlines and recommended focus blocks.
*   **Adaptive Scheduling**: AI-driven task prioritization based on your current energy levels and mood.

### ⏱️ Performance & Focus
*   **Deep Work Timer**: Integrated Pomodoro timer with streak tracking and ambient sound support.
*   **Focus Analytics**: Visualize your "Deep Work" hours and productivity trends.

### � Academic Excellence
*   **Grade Forecasting**: Real-time GPA calculations and predictive analytics for upcoming exams.
*   **Syllabus Management**: Keep track of subject requirements and progress in one place.

### 🎮 Behavioral Design
*   **Gamified Achievement System**: Earn XP for task completion and maintain daily streaks to level up your "Scholar Profile."

  <img src="image.png" alt="LearnPath AI Logo" width="300" />
  <p><strong>Build Your Future with AI-Powered Learning Paths.</strong></p>
---

## 📐 Architecture

The following diagram illustrates how StudyBoard processes your academic data to provide AI-driven insights:

```mermaid
graph TD
    User([Student User]) --> Dashboard[Frontend Dashboard]
    Dashboard --> Auth{NextAuth.js}
    Auth --> |Authorized| DB[(Supabase DB)]
    DB --> |Academic Data| AIService[AI Briefing Engine]
    AIService --> |Groq LLM| Insights[Personalized Insights]
    Insights --> |Briefing| Dashboard
    User --> |Focus Session| Analytics[Focus Analytics]
```

---
**LearnPath AI** is a modern AI-powered smart curriculum designer that generates personalized learning roadmaps, recommends courses, and tracks progress for students. It combines AI recommendations, progress analytics, and skill tracking into a polished dashboard for focused learning.
## 🛠️ Tech Stack

| Layer | Technology |
> [!IMPORTANT]
> **Free Forever Core**: LearnPath AI is committed to providing its essential features for learners everywhere.
| :--- | :--- |
| **UI Components** | [Shadcn UI](https://ui.shadcn.com/), [Framer Motion](https://www.framer.com/motion/) |
| **Backend/API** | Next.js App Router, [Groq SDK](https://groq.com/) |
| **Database/ORM** | [Prisma](https://www.prisma.io/), [Supabase/PostgreSQL](https://supabase.com/) |
| **Authentication** | [NextAuth.js](https://next-auth.js.org/) |
| **Communications** | [Resend](https://resend.com/) |

---

## 🏗️ Project Structure

```text
study_board/
├── app/                  # Next.js App Router (Pages & API)
│   ├── api/              # AI, Auth, and Database endpoints
│   ├── (auth)/           # Authentication flows
│   └── (dashboard)/      # Protected dashboard routes
├── components/           # Reusable UI components (Shadcn + Custom)
<div align="center">
  <img src="image.png" alt="LearnPath AI Logo" width="300" />
  <p><strong>Build Your Future with AI-Powered Learning Paths</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Status-Beta-orange?style=for-the-badge" alt="Status" />
    <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />
    <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" alt="PRs Welcome" />
    <img src="https://img.shields.io/badge/Free-Forever-purple?style=for-the-badge" alt="Free Forever" />
  </p>

  <p>
    <a href="#-features">Features</a> •
    <a href="#-architecture">Architecture</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-setup">Setup</a> •
    <a href="#-project-structure">Structure</a>
  </p>
</div>

---

## 🚀 Overview

**LearnPath AI** is a modern AI-powered smart curriculum designer that generates personalized learning roadmaps, recommends courses, and tracks progress for students. It combines AI recommendations, progress analytics, and skill tracking into a polished dashboard for focused learning.

**Main Heading:** Build Your Future with AI-Powered Learning Paths

**Subheading:** Generate personalized curriculum roadmaps, track progress, and discover the best learning journey tailored to your goals.

---

## ✨ Features

- AI Course Recommendations
- Personalized Learning Path
- Progress Dashboard
- Skill Tracking
- Learning Roadmap
- Weekly Goals
- AI Mentor Suggestions
- Completion Analytics

---

## 📐 Architecture

```mermaid
graph TD
    User([Student User]) --> Dashboard[Frontend Dashboard]
    Dashboard --> Auth{NextAuth.js}
    Auth --> |Authorized| DB[(Supabase DB)]
    DB --> |Academic Data| AIService[Gemini / AI Engine]
    AIService --> |Recommendations| Insights[Personalized Roadmaps]
    Insights --> |Display| Dashboard
    User --> |Progress| Analytics[Recharts]
```

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | Next.js, Tailwind CSS |
| **AI** | Gemini API (placeholder) |
| **Database** | Supabase / PostgreSQL |
| **ORM** | Prisma |
| **Charts** | Recharts |
| **Emails** | Resend |

---

## 🏗️ Project Structure

```text
study_board/
├── app/                  # Next.js App Router (Pages & API)
├── components/           # UI components
├── lib/                  # Shared utilities (Prisma, AI helpers)
├── prisma/               # Database schema & migrations
└── public/               # Static assets & icons
```

---

## 🛠️ Setup & Local Development

### Prerequisites
- Node.js 18.x or later
- A PostgreSQL instance (Supabase recommended)

### 1. Installation
```bash
git clone https://github.com/tripathiji1312/study_board.git
cd study_board
npm install
```

### 2. Configuration
Copy the `.env.example` into a `.env` file and add values for Supabase, Resend and Gemini API keys.

### 3. Initialization
```bash
npx prisma generate
npx prisma db push
npm run dev
```

---

## 🤝 Contributing

PRs welcome — fork, branch, implement, and open a PR.

---

## 📄 License

LearnPath AI is released under the [MIT License](LICENSE).

<p align="center">Made with 🖤 by <a href="https://github.com/tripathiji1312">tripathiji1312</a></p>
