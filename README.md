<h1>Ashween Ramakrishnan</h1>

**Software engineer who ships full-stack products and fine-tunes the models behind them.**

I have 4+ years of experience building production software. At EduBrite (later acquired by LinkedIn) I worked on a SaaS LMS used by Apple, Salesforce, MuleSoft and VMware. During my Master's at the University of Adelaide I trained LLMs to find vulnerabilities in smart contracts. Now I build **full-stack apps on Next.js and TypeScript, local-first LLM tools, and AI for security.**

📍 Adelaide, Australia · 🟢 Open to SWE / AI-ML roles anywhere in Australia · ✈️ Ready to relocate immediately · Hybrid or remote

🌐 [ashween.space](https://ashween.space "Ctrl/Cmd-click to open in a new tab") · [LinkedIn](https://www.linkedin.com/in/ashween-ramakrishnan "Ctrl/Cmd-click to open in a new tab") · [Resume](https://ashween.space/docs/Ashween_Ramakrishnan_Resume.pdf "Ctrl/Cmd-click to open in a new tab") · [Google Scholar](https://scholar.google.com.au/citations?user=c0TcfWIAAAAJ&hl=en "Ctrl/Cmd-click to open in a new tab") · [Email](mailto:ashween.ramakrishnan@gmail.com)

<sub>💡 Tip: Ctrl/Cmd-click any link to open it in a new tab.</sub>

---

### 🔬 Research: the numbers

| Project | What it does | Result |
|---|---|---|
| [**Reentrancy Vulnerability Detection**](https://ashween.space/projects/smart-contract-reentrancy "Ctrl/Cmd-click to open in a new tab") <br><sub>Master's thesis · shipped on [CyberLab](https://maennel.ai/cyberlab/ "Ctrl/Cmd-click to open in a new tab")</sub> | LoRA fine-tuned LLM classifier for Solidity smart contracts, packaged as a containerised tool | **91.6% accuracy**, up from 70% with classical ML |
| [**RLHF for Small Language Models**](https://ashween.space/projects/rlhf-small-language-models "Ctrl/Cmd-click to open in a new tab") | End-to-end SFT → reward model → PPO for models under 2B parameters, on consumer GPUs | Reward **24.25 → 41.25** with drift controlled and safety refusals intact |
| [**MITRE ATT&CK RAG Assistant**](https://ashween.space/projects/mitre-attack-rag "Ctrl/Cmd-click to open in a new tab") | RAG over all 697 ATT&CK Enterprise techniques with 4-bit Mistral-7B | **0.816 faithfulness**, and every answer is traceable to a technique ID |

### 🚀 Full-stack, in production

- **[Next Stop Adelaide](https://ashween.space/projects/next-stop-adelaide "Ctrl/Cmd-click to open in a new tab")** · [live ↗](https://next-stop-zeta-nine.vercel.app "Ctrl/Cmd-click to open in a new tab"): pick your bus or tram stop and lock your phone. A Cloudflare Worker follows the vehicle on Adelaide Metro's live feeds and sends push notifications 2–5 minutes before you arrive.
- **[TracePay](https://ashween.space/projects/tracepay "Ctrl/Cmd-click to open in a new tab")** · [live ↗](https://tracepay-eight.vercel.app "Ctrl/Cmd-click to open in a new tab"): every Apple Pay tap goes to a webhook through iOS Shortcuts. A Next.js dashboard breaks spending down by category and merchant, flags duplicate taps, and exports statements in 5 languages.
- **[Splitkit](https://ashween.space/projects/splitkit "Ctrl/Cmd-click to open in a new tab")** · [live ↗](https://splitkit-gray.vercel.app "Ctrl/Cmd-click to open in a new tab"): group expense splitting with no sign-up wall, multi-currency support, and a debt-simplification algorithm that settles a group in at most n − 1 payments.
- **[MigraTrack AU](https://ashween.space/projects/migratrack-au "Ctrl/Cmd-click to open in a new tab")**: tracks SkillSelect EOI invitations by occupation, points and state, with points calculators for every state and territory.
- **[MyOrbit](https://ashween.space/projects/myorbit "Ctrl/Cmd-click to open in a new tab")**: a $0 self-hosted cloud drive that runs on one Mac. I hand-wrote the WebDAV server so it mounts in Finder, Explorer and Linux. It sits behind Cloudflare Tunnel and Access.

### 🧠 Local-first LLM apps

- **[AI Marker](https://github.com/achu1998/ai-marker "Ctrl/Cmd-click to open in a new tab")**: rubric-based grading and handwriting OCR that run entirely on-device (Llama 3.1 and 3.2 Vision). Student data never leaves the machine.
- **[Natural-Language Regex Replace](https://github.com/achu1998/regex-pattern-match-llm "Ctrl/Cmd-click to open in a new tab")**: describe a change to a CSV or Excel file in plain English. Mistral writes the regex and Flan-T5 checks it before anything is applied.
- **[NoveltyAI](https://github.com/achu1998/research-assistant "Ctrl/Cmd-click to open in a new tab")**: scans live literature, flags overlaps, and rewrites a proposal until it finds an original angle.
- **[StudyBuddy](https://github.com/achu1998/study-buddy "Ctrl/Cmd-click to open in a new tab")**: turns course PDFs into offline study sessions with summaries, MCQs and Socratic prompts.

<sub>Also: [LiveWell](https://ashween.space/projects/livewell "Ctrl/Cmd-click to open in a new tab") · [Age-Based Face Anonymisation](https://ashween.space/projects/video-face-anonymization "Ctrl/Cmd-click to open in a new tab") · [Flappy Bird RL Environment](https://ashween.space/projects/flappy-bird-rl "Ctrl/Cmd-click to open in a new tab"). All 15 projects: **[ashween.space/projects](https://ashween.space/projects "Ctrl/Cmd-click to open in a new tab")**</sub>

### 💼 Where I've shipped

- **Allied AU** · SWE Intern (2025): AWS SES notifications, practitioner calendar and search on a Nuxt + Laravel health platform. Fixed NDIS booking and sign-up flows.
- **LinkedIn** · Software Engineer, contingent (2022–24): led enhancements on Salesforce Trailhead Academy. Built QR-code cheat detection for LinkedIn Learning assessments.
- **EduBrite Systems** (acquired by LinkedIn) · Full-Stack Developer (2020–22): built SaaS LMS features for Apple, Salesforce, MuleSoft and VMware.

<sub>Earlier: ICU Medical (raised Pytest coverage from 58% to 90% on an IV infusion pump) · IIT (ISM) Dhanbad research intern · Hundred Plus · [full resume](https://ashween.space/resume "Ctrl/Cmd-click to open in a new tab")</sub>

### 🧰 Stack

**Frontend** TypeScript · React · Next.js · Nuxt · Svelte · Tailwind CSS<br>
**Backend** Java · Spring Boot · REST APIs · Microservices · Python · Django · Node.js · Fastify · PHP/Laravel<br>
**Data** PostgreSQL (Supabase) · MySQL · MongoDB · SQLite<br>
**AI/ML** PyTorch · Hugging Face · LoRA/PEFT · TRL (RLHF) · LangChain · ChromaDB · Ollama · OpenCV<br>
**Cloud & Ops** AWS · Azure · Vercel · Cloudflare Workers · Docker · Ansible · GitHub Actions

<p>
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,svelte,tailwind,java,spring,python,django,nodejs,laravel,postgres,supabase,pytorch,aws,cloudflare,vercel,docker&perline=18" alt="tech stack" />
</p>

---

<sub>MCS, University of Adelaide ('26) · B.Tech CSE, Amrita Vishwa Vidyapeetham · Microsoft Azure Fundamentals · Docker Foundations</sub>
