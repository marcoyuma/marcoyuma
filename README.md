<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Marco%20Yumarafi'i%20Nursaid&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>

<a href="https://github.com/marcoyuma">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=560&lines=Frontend+Engineer+in+the+making;Next.js+%7C+React+%7C+TypeScript;Turning+production+concerns+into+shipped+code" alt="Typing SVG" />
</a>

</div>

<br/>

## 👋 About Me

I'm an undergraduate **Software Engineering** student (7th semester) at **Universitas Bina Sarana Informatika**, focused on **frontend development with React & Next.js**. I like building things that survive contact with production — data integrity at the database layer, auth flows that don't leak, and rendering architecture that actually scales.

- 🎓 B.Sc. Software Engineering — GPA **3.76 / 4.00**
- 🛠️ Currently building **The Seaspace** — a full villa booking platform + admin panel
- 📚 Currently learning **Web Security** (OWASP-based, starting from CSP)
- 💼 **Open to Frontend Engineer internship opportunities**
- 🌐 Reading/listening English proficiency above B1 (Busuu assessed)

<br/>

## 🧰 Tech Stack

**Frontend**
<p> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/> </p>

**State Management & Data Fetching**
<p> <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-433E38?style=for-the-badge&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"/> </p>

**Styling & UI**
<p> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white"/> <img src="https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white"/> <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"/> </p>

**Backend & Database**
<p> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/> <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/> </p>

**Forms, Validation & Auth**
<p> <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white"/> <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white"/> <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white"/> </p>

**Tools & Platforms**
<p> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/> </p>

<br/>

## 🚀 Featured Project — The Seaspace

**Guest-facing villa booking platform** built with Next.js 16, React 19, and Supabase — live availability, simulated payments, self-service check-in (door codes + QR), guest accounts, and reviews.

🔗 [the-seaspace-seven.vercel.app](https://the-seaspace-seven.vercel.app)

| Area | What was done |
|---|---|
| **Rendering** | Combined static prerendering (`generateStaticParams`) with per-request Supabase session data using `cacheComponents` |
| **Architecture** | Three scoped Supabase client instances (server / browser / admin), each with different access levels and caching rules |
| **Data integrity** | Double-booking prevented at the database level with a PostgreSQL **GiST exclusion constraint** |
| **Security** | Access control enforced entirely at the Postgres layer via **Row-Level Security** + `SECURITY DEFINER` RPC functions — no extra ORM needed |
| **Privacy** | Stripped EXIF location metadata from uploaded images with `sharp` before storing in Supabase Storage |
| **UX detail** | Fixed a client-server hydration mismatch in date calculations using `useSyncExternalStore` |
| **Check-in flow** | Server-side QR code generation straight to SVG, error-correction level M |

<p> <img src="https://img.shields.io/badge/Next.js_16-black?style=flat-square&logo=next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> </p>

<br/>

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=marcoyuma&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marcoyuma&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=marcoyuma&theme=tokyonight&hide_border=true" />
</div>

<br/>

## 🎓 Certifications

<details>
<summary>Click to expand</summary>
<br/>

- Advanced React — Meta (2026)
- Learn Next.js — Scrimba (2026)
- Programming with JavaScript — Meta (2026)
- Learn TypeScript — Scrimba (2026)
- React Basics — Meta (2024)
- Belajar Membuat Aplikasi Web dengan React — Dicoding (2024)
- Belajar Membuat Front-End Web untuk Pemula — Dicoding (2024)
- Fundamental Proyek Manajemen — Dicoding (2024)
- Cloud Practitioner Essentials (Belajar Dasar AWS Cloud) — Dicoding (2024)

</details>

<br/>

## 📫 Let's Connect

<p>
<a href="mailto:marcoyumarafi@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/marco-yumarafi-i-nursaid-1711933a5"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/marcoyuma"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=marcoyuma&style=for-the-badge&color=38BDF8" alt="profile views"/>

</div>
