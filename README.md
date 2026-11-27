<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/system-mobile-dark.svg">
  <source media="(max-width: 600px)" srcset="assets/system-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/system-dark.svg">
  <img src="assets/system-light.svg" alt="System diagram of Ronack Kumar: you send POST /hire to the ronack-kumar service, which lists his role, location, studies and status, calls his four projects (expertsfor, mockprep, offersafe, finance-workspace) and answers 200 OK." width="100%">
</picture>

Full-stack developer working mostly on AI products. I build the whole app, Next.js on the front and Python or Node on the back, and most of my time goes into the LLM parts: picking the right model for a question, checking what comes in, and logging what happened.

```json
{
  "name": "Ronack Kumar",
  "role": "Full-stack and AI engineer",
  "based_in": "Chennai, India",
  "studying": "MCA, SRM Institute of Science and Technology, 2025 to 2027, CGPA 9.12",
  "stack": {
    "frontend": ["TypeScript", "Next.js", "React"],
    "backend": ["Python", "FastAPI", "LangGraph", "SQLAlchemy", "Node.js", "PostgreSQL"],
    "ops": ["Docker", "GitHub Actions"]
  },
  "open_to": "full-stack and AI internships, full-time roles from 2027",
  "email": "raunackbhardwaj1307@gmail.com"
}
```

## Projects

| Repo | What it does | Built with | Live |
| --- | --- | --- | --- |
| [expertsfor](https://github.com/Ronack-Kumar/expertsfor) | Sends each question to the right expert persona and model. 84% routing accuracy on a held-out benchmark, six LLM providers, 96 backend tests in CI. | Python, FastAPI, LangGraph | [expertsfor.me](https://expertsfor.me/) |
| [mockprep](https://github.com/Ronack-Kumar/mockprep) | Mock interviews by text, voice or webcam, with each answer scored on accuracy, clarity, depth and confidence. | Next.js, Groq, Supabase | [mockprep.app](https://www.mockprep.app/) |
| [OfferSafe](https://github.com/Ronack-Kumar/OfferSafe) | Checks job offers for scam signs using 19 weighted risk signals and an LLM review. | TypeScript, Next.js, Supabase | [offer-safe.vercel.app](https://offer-safe.vercel.app/) |
| [finance-workspace](https://github.com/Ronack-Kumar/finance-workspace) | Shared finance workspaces with team roles and exact INR records, covered by 12 test scenarios. | TypeScript, Express, Prisma | |

<details>
<summary><b>How ExpertsFor routes a question</b></summary>
<br>

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/expertsfor-mobile-dark.svg">
  <source media="(max-width: 600px)" srcset="assets/expertsfor-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/expertsfor-dark.svg">
  <img src="assets/expertsfor-light.svg" alt="Inside ExpertsFor: a question, the conversation context and a model catalog go to a router that picks a persona and model in about 1 ms, the chosen LLM runs, and every step is saved to a trace." width="100%">
</picture>

I built this during my internship at 8 Queens Software, when it was still called GRID07. The router picks a persona and a model in about a millisecond, provider API keys are stored encrypted, and every step of a run is saved so an answer can be traced back later.

</details>

## Experience

- **8 Queens Software**, Software Developer Intern, Chennai, Aug to Sep 2026. Built GRID07, now ExpertsFor.
- **B2World**, Software Developer Intern, remote, Jul to Aug 2026. Worked on DriveLearn India in React, Node.js and PostgreSQL.
- **IT Developer**, MERN Full Stack Intern, Rourkela, Aug to Oct 2024. Built a result management system.

[LinkedIn](https://www.linkedin.com/in/ronackkumar/) / [Resume](assets/Ronack_Kumar_Resume.pdf) / [Portfolio](https://ronack-portfolio.netlify.app/)
