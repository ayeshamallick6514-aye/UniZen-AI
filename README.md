# 📚 UniZen - AI-Powered Exam Preparation Platform

<div align="center">

![UniZen Banner](https://img.shields.io/badge/UniZen-Ace%20Your%20Exams-6366f1?style=for-the-badge&logo=bookstack&logoColor=white)

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=flat-square&logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-Latest-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Cloud-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)

**Your AI-powered study companion for B.Tech exam success across Indian universities**

[Live Demo](https://lovable.dev/projects/d29e6ea7-691f-44d2-af00-d3437471cb8c) • [Report Bug](https://github.com/yourusername/unizen/issues) • [Request Feature](https://github.com/yourusername/unizen/issues)

</div>

---

## ✨ Features

### 🏛️ Multi-University Support
- **13+ Universities** including BEU, RGPV, AKTU, VTU, JNTU, Anna University, GTU, PTU, MDU, MAKAUT, BPUT, RTU, CSVTU
- Complete syllabus for **6 branches**: CSE, ECE, ME, CE, EE, IT
- **8 semesters** of subject-wise curriculum
- University-specific evaluation patterns and grading criteria

### 📝 Previous Year Question Papers (PYQ)
- **400+ question papers** from multiple universities
- Filter by university, branch, semester, and year
- Direct download links to official university portals
- Search functionality across all papers

### 📊 Study Planner
- **Topic-wise progress tracking** for each subject
- Visual progress indicators with completion percentages
- Study streak counter and motivation system
- Local storage persistence for offline access
- Quick navigation from syllabus to study planner

### 🤖 AI-Powered Features
- **AI Chat Assistant** for doubt solving
- University-specific answer evaluation
- Code analysis and optimization suggestions
- Context-aware responses based on syllabus

### 🎯 University DNA System
- Custom evaluation parameters per university
- Keyword weight, theory vs code ratio analysis
- Strictness levels and diagram preferences
- Exam pattern guidelines for 2, 5, and 10-mark questions

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| ![React](https://img.shields.io/badge/-React%2018-61DAFB?style=flat-square&logo=react&logoColor=black) | UI Component Library |
| ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Type-safe JavaScript |
| ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | Build Tool & Dev Server |
| ![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) | Utility-first CSS Framework |
| ![shadcn/ui](https://img.shields.io/badge/-shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white) | UI Component System |

### State & Data Management
| Technology | Purpose |
|------------|---------|
| ![React Query](https://img.shields.io/badge/-TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) | Server State Management |
| ![React Router](https://img.shields.io/badge/-React%20Router%206-CA4245?style=flat-square&logo=reactrouter&logoColor=white) | Client-side Routing |
| ![React Hook Form](https://img.shields.io/badge/-React%20Hook%20Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white) | Form Handling |
| ![Zod](https://img.shields.io/badge/-Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) | Schema Validation |

### Backend & Infrastructure
| Technology | Purpose |
|------------|---------|
| ![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) | Backend as a Service |
| ![Edge Functions](https://img.shields.io/badge/-Deno%20Edge%20Functions-000000?style=flat-square&logo=deno&logoColor=white) | Serverless Functions |
| ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | Database |

### UI & Visualization
| Technology | Purpose |
|------------|---------|
| ![Lucide](https://img.shields.io/badge/-Lucide%20Icons-F56565?style=flat-square&logo=lucide&logoColor=white) | Icon Library |
| ![Recharts](https://img.shields.io/badge/-Recharts-22B5BF?style=flat-square&logo=recharts&logoColor=white) | Data Visualization |
| ![Radix UI](https://img.shields.io/badge/-Radix%20UI-161618?style=flat-square&logo=radixui&logoColor=white) | Headless UI Primitives |
| ![Sonner](https://img.shields.io/badge/-Sonner-000000?style=flat-square&logoColor=white) | Toast Notifications |
| ![date-fns](https://img.shields.io/badge/-date--fns-770C56?style=flat-square&logo=datefns&logoColor=white) | Date Utilities |

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/                    # shadcn/ui components
│   ├── Header.tsx             # Navigation header
│   ├── HeroSection.tsx        # Landing page hero
│   ├── FeaturesSection.tsx    # Features showcase
│   ├── UniversitiesSection.tsx # University cards
│   ├── PYQSection.tsx         # PYQ preview section
│   ├── StudyPlannerSection.tsx # Study planner preview
│   ├── AIChat.tsx             # AI chat interface
│   ├── CodeAnalyzer.tsx       # Code analysis tool
│   └── ...
├── config/
│   ├── syllabus.ts            # University syllabi data
│   ├── previousYearPapers.ts  # PYQ database
│   └── universityDNA.ts       # Evaluation parameters
├── pages/
│   ├── Index.tsx              # Home page
│   ├── Syllabus.tsx           # Syllabus browser
│   ├── PreviousYearPapers.tsx # PYQ page
│   ├── StudyPlanner.tsx       # Study tracking
│   └── NotFound.tsx           # 404 page
├── hooks/                     # Custom React hooks
├── lib/                       # Utility functions
└── integrations/
    └── supabase/              # Supabase client & types

supabase/
└── functions/
    └── unizen-chat/           # AI chat edge function
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ or Bun
- npm, yarn, or bun package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/unizen.git
   cd unizen
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Set up environment variables**
   ```bash
   # Create .env file (auto-generated if using Lovable)
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_PUBLISHABLE_KEY=your_anon_key
   ```

4. **Start development server**
   ```bash
   npm run dev
   # or
   bun dev
   ```

5. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production

```bash
npm run build
# or
bun run build
```

---

## 🎓 Supported Universities

| University | State | Branches | PYQs |
|------------|-------|----------|------|
| BEU (Bihar Engineering University) | Bihar | 6 | 55+ |
| RGPV | Madhya Pradesh | 6 | 90+ |
| AKTU | Uttar Pradesh | 6 | 15+ |
| VTU | Karnataka | 6 | 15+ |
| JNTU | Telangana | 6 | 10+ |
| Anna University | Tamil Nadu | 6 | 10+ |
| GTU | Gujarat | 6 | 10+ |
| PTU | Punjab | 6 | 5+ |
| MDU | Haryana | 6 | 5+ |
| MAKAUT | West Bengal | 6 | - |
| BPUT | Odisha | 6 | - |
| RTU | Rajasthan | 6 | - |
| CSVTU | Chhattisgarh | 6 | - |

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for the beautiful component system
- [Lovable](https://lovable.dev) for the development platform
- All contributing universities for their open syllabus data
- [rgpvonline.com](https://rgpvonline.com) for RGPV question papers

---

<div align="center">

**Made with ❤️ for B.Tech students across India**

[![Built with Lovable](https://img.shields.io/badge/Built%20with-Lovable-ff69b4?style=for-the-badge)](https://lovable.dev)






