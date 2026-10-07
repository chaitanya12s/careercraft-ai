# CareerCraft AI – AI Resume Tailor & Job Matcher SaaS

CareerCraft is an intelligent full-stack AI SaaS application that empowers job seekers to analyze their resumes against specific job descriptions, calculate an ATS compatibility score, highlight missing keywords, rewrite bullet points with the Google XYZ formula, generate tailored cover letters, and prepare for interviews.

---

## 🌟 Key Features

1. **ATS Compatibility Gauge & Score Breakdown**:
   - Comprehensive score (0-100) assessing Skills Match, Experience Depth, Quantified Impact, and Formatting.
   - Recruiter Red Flags alerting you to missing metrics or layout concerns.
   - Matched vs. Missing keyword badges categorized by importance.

2. **Google XYZ Formula Bullet Rewriter**:
   - Transforms standard resume responsibilities into high-impact accomplishments: *"Accomplished [X] as measured by [Y] by doing [Z]"*.
   - Side-by-side diff comparing the original bullet with the optimized version.
   - Shows recruiter rationale for why each change boosts interview odds.

3. **High-Converting Cover Letter Generator**:
   - Synthesizes your real career achievements with company-specific pain points.
   - Fully editable with 1-click clipboard copy and text download.

4. **Interview Prep Studio**:
   - Generates tailored behavioral and technical questions based on the candidate's gaps.
   - Provides complete **STAR Framework (Situation, Task, Action, Result)** coaching for every question.

5. **Dual Mode (Gemini API & Offline Demo Mode)**:
   - Enter your Google Gemini API key directly in the UI or `.env.local`.
   - Includes full offline demo heuristics and preset test profiles to try without an API key immediately.

---

## 🚀 Quick Start

### 1. Run Development Server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 2. Build for Production
```bash
npm run build
npm start
```

---

## 🛠️ Tech Stack
- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **AI Integration:** Google Gemini 1.5 Flash API with Fallback Heuristics Engine
