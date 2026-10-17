# 🎧 SonicAI Podcast Platform

**Discover, listen to, and analyze your favorite podcasts — with AI-powered summaries.**

🔗 **Live demo:** [podcast-discovery-one.vercel.app](https://podcast-discovery-one.vercel.app/)
🎬 **Demo video:** [Watch on Google Drive](https://drive.google.com/file/d/1s0364kgVFkRutL8evgcHaVq3JeNlJCz5/view?usp=drive_link)

> Team graduation project built during the **Digital Egypt Pioneers Initiative (DEPI)**.
> Original team repository: [ItcProjects-R4/GHR4_SWD2_S2_PROJECT2](https://github.com/ItcProjects-R4/GHR4_SWD2_S2_PROJECT2)

![Podcast Platform screenshot](Screenshots/Screenshot%202026-06-26%20215633.png)

---

## About the project

A React web app that brings podcast discovery, playback, and listening analytics into one place. It pulls real podcast data from the **iTunes / Apple Podcasts API** and uses **Google Gemini AI** to summarize episodes so users can preview content before committing their time. Everything runs client-side — no backend needed.

## Key features

- 🔍 **Search & browse** podcasts by title, publisher, or category
- ▶️ **Custom audio player** — play, pause, seek, volume, speed, keyboard shortcuts
- 🤖 **AI summaries** of episodes with Google Gemini
- ❤️ **Favorites** and **listening history** with resume support
- 📊 **Analytics dashboard** — listening time, top categories, personalized insights
- 🔐 **Sign up / login** with form validation
- 🌗 **Dark / light theme** and fully responsive layout (mobile, tablet, desktop)

## Tech stack

| Area | Tools |
| --- | --- |
| Frontend | React 19, Vite, React Router |
| Styling | CSS Modules, Bootstrap 5, Font Awesome |
| Forms | Formik + Yup |
| APIs | iTunes Search API (via Axios), Google Gemini (`@google/generative-ai`) |
| UX | react-hot-toast, react-markdown |
| Deployment | Vercel |

## My role — API Integration Specialist

I was responsible for **researching, evaluating, and integrating the external APIs** the platform depends on, and contributed to the **data retrieval and content display** functionality — fetching podcast data from the API and presenting it in the app.

## Team — SonicAI

| Member | Role |
| --- | --- |
| Adel Abd Elzaher Adel Abuzaid | Team Leader · Front-End Developer · Documentation |
| **Jassy Kamal Naeim Wahba** | **API Integration Specialist** |
| Habiba Mohamed Saleh Ali Keshk | Project Structure & Organization Coordinator |
| Ibrahem Ayman Mohamed Elsawey | Front-End Developer |
| Mahmoud Mohamed AbdElaziz Shaala | Front-End Developer |

Full roles and contributions: [Team_Members_SonicAI.pdf](Team_Members_SonicAI.pdf)

## Run it locally

```bash
cd "Podcast Project"
npm install
```

Create a `.env` file inside `Podcast Project`:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_ITUNES_API_BASE=https://itunes.apple.com/search
```

Then start the dev server:

```bash
npm run dev
```

## Repository contents

| Folder / file | What's inside |
| --- | --- |
| [`Podcast Project/`](Podcast%20Project) | The React application source code |
| [`Project documentations/`](Project%20documentations) | SRS and project planning |
| [`Diagrams/`](Diagrams) · [`DFD/`](DFD) | ER, class, sequence, activity, use-case and data-flow diagrams |
| [`Screenshots/`](Screenshots) | App screenshots |
| [`Presentation/`](Presentation) | Project presentation slides |
| [`README.pdf`](README.pdf) | Full technical documentation |
| [`podcast platform manuals.pdf`](podcast%20platform%20manuals.pdf) | User manual |
