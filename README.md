<!-- Language Tabs -->
<p align="center">
  <a href="./README.md">
    <img src="https://img.shields.io/badge/한국어-2d333b?style=for-the-badge" alt="한국어" />
  </a>
  <a href="./README.en.md">
    <img src="https://img.shields.io/badge/English-20c997?style=for-the-badge" alt="English" />
  </a>
</p>

<!-- Wavy Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=20c997&height=180&section=header&text=Junny%20the%20Web%20Engineer&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Dozn%20·%20Firm%20Banking%20·%20AI%20Research&descAlignY=58&descSize=14" width="1000" alt="Junny header" />
</p>

<!-- Typing -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=22&duration=3200&pause=900&color=20C997&center=true&vCenter=true&width=920&lines=Building+overseas+VA+firm-banking+rails.;Frontend+first.+Full-stack+when+it+matters.;Researching+valuation+models+at+KMU.;It's+been+1448+days+since+I+started+coding+for+that+dream." alt="typing" />
  </a>
</p>

<p align="center">
  <a href="https://verbena-toque-2ec.notion.site/FE-Engineer-8f20a4924d21487d937b46a50d33e251">
    <img src="https://img.shields.io/badge/Portfolio-20c997?style=for-the-badge&logo=Notion&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:dpwns108@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.instagram.com/ch_ye_jun">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

---

```ts
const junny = {
  name: "Choi Ye-jun",
  aka: "Junny",
  role: "Web Engineer",
  company: "Dozn",
  building: "Overseas virtual-account firm-banking relay platform",
  studying: "AI · Kookmin University Graduate School of Software Convergence",
  now: "Valuation prediction models — currently real estate",
  stack: ["React", "TypeScript", "Spring Boot", "PostgreSQL", "Python"],
  dream: "Build something useful.",
} as const;
```

---

## Now

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏢 Dozn</h3>
      <p>
        I build an <b>overseas virtual-account · firm-banking relay</b> platform.<br/>
        I design the BSS admin that operators use every day in React 19 —
        inquiry, settlement, and excel exports that have to hold up on one screen.
      </p>
      <p>
        <code>Funds Transfer FT</code> · <code>Virtual Account VA</code> · <code>Ledger / Settlement</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎓 KMU · AI</h3>
      <p>
        I study AI at Kookmin University Graduate School of Software Convergence.<br/>
        Right now I research <b>valuation prediction models</b> — turning jeonse / sale structures into data.
      </p>
      <p>
        <code>XGBoost</code> · <code>Embedding MLP</code> · <code>Transaction time series</code>
      </p>
    </td>
  </tr>
</table>

---

## Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🖥️ BSS Admin Front</h3>
      <p>
        Admin console for overseas virtual accounts and funds transfer.<br/>
        React 19 / Vite / TypeScript / Tailwind 4 / TanStack Query·Table / Zustand.
      </p>
      <ul>
        <li>One admin for transactions, status, fees, ledger, and settlement</li>
        <li>Browser-side excel for 100k rows: <b>56s → 24s</b></li>
        <li>Dropped per-cell style cost, rewrote format hot paths, offloaded freeze to a Web Worker</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ BSS Admin API</h3>
      <p>
        Admin API for the same domain.<br/>
        Spring Boot 3 / QueryDSL / PostgreSQL.
      </p>
      <ul>
        <li>Rebuilt master-data query patterns that collapsed on transaction history (up to ~2M rows)</li>
        <li>Last page <b>32s → 1.6s</b>, search <b>6s → 0.8s</b></li>
        <li>Excel 100k rows <b>11s → 3s</b> · PK-first paging / semi-join filters</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🏠 Valuation Model — Jeonse Price Prediction</h3>
      <p>
        A research project that joins apartment sale and jeonse transactions to predict
        <b>jeonse price / jeonse-to-sale ratio</b>.
        I split the train window on the assumption that the market is non-stationary,
        and replaced apartment-name one-hot dependence with embeddings.
      </p>
      <p>
        <code>Python</code> · <code>XGBoost</code> · <code>Embedding MLP</code> · <code>Time-series split</code>
      </p>
    </td>
  </tr>
</table>

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,js,vite,tailwind,redux,spring,java,postgres,python,pytorch&theme=dark" alt="tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=react&logoColor=white" alt="Zustand" />
  <img src="https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="TanStack" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white" alt="React Hook Form" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vanilla_Extract-DDC2FF?style=flat-square" alt="Vanilla Extract" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
</p>

<details>
  <summary><b>What I actually use day to day</b></summary>
  <br/>

  | Layer | Tools |
  | --- | --- |
  | UI | React 19, TypeScript, Vite, Tailwind 4, Radix, Vanilla Extract |
  | State / Data | Zustand, Recoil, TanStack Query, TanStack Table |
  | Form | React Hook Form, Zod |
  | Backend | Java, Spring Boot 3, QueryDSL |
  | Data | PostgreSQL, Oracle, Firebase |
  | Research | Python, XGBoost, Embedding MLP |

</details>

---

## Focus

```text
[■■■■■■■■■■■■□□]  Firm-banking admin that operators can trust
[■■■■■■■■□□□□□□]  Valuation models that survive a real market regime
[■■■■□□□□□□□□□□]  Something useful enough to outlive a job title
```

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=20c997&height=120&section=footer" width="1000" alt="footer" />
</p>
