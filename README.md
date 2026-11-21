<div align="center">

<img src="assets/hero.svg" alt="Sreeja Sunkeswaram: AI engineer, MS Data Science student at ASU" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-E8A0B8?style=for-the-badge&logo=linkedin&logoColor=0B0B0E&labelColor=0B0B0E)](https://www.linkedin.com/in/sreeja-sunkeswaram-275208241/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-E8A0B8?style=for-the-badge&logo=googlescholar&logoColor=0B0B0E&labelColor=0B0B0E)](https://scholar.google.com/citations?hl=en&user=s_hU8_UAAAAJ)
[![Email](https://img.shields.io/badge/Email-E8A0B8?style=for-the-badge&logo=gmail&logoColor=0B0B0E&labelColor=0B0B0E)](mailto:sunkeswaramsreeja@gmail.com)

</div>

<img src="assets/h-about.svg" alt="About" width="100%"/>

Hi, I'm Sreeja. I'm doing my MS in Data Science, Analytics and Engineering at [Arizona State University](https://www.asu.edu/) (May 2027, 4.0 GPA). Before that I did a B.Tech in AI & Data Science in Hyderabad, where I finished as the [Best Outgoing Student](https://drive.google.com/file/d/1NDh1yyRwMtNftQhL-cTiECLDM1uoQr0p/view?usp=sharing) of the program.

Looking back at what I've built, there's a pattern: it usually starts with messy text or messy operations data. Job postings, customer complaints, delivery orders, fund mandates. What I enjoy most is the last step, where the model disappears behind something a non-technical team can actually use. At IIT Madras that was an email classifier for courier operations. At BDSR it's CustomNER, a tool where reviewing the model's predictions is what retrains it.

**Right now**

- 🛠️ AI Engineer and Python Full Stack intern at BDSR Solutions
- 📚 Grading graduate Information Systems assignments at ASU
- ♟️ Building [**MandateIQ**](https://github.com/sreejasun/MandateIQ), a multi-agent system that reviews fund nominations (below)

I'm looking for software engineering, AI/ML and data science roles.

<img src="assets/h-building.svg" alt="Currently building" width="100%"/>

<a href="https://github.com/sreejasun/MandateIQ"><img src="assets/card-mandateiq.svg" alt="MandateIQ: Proponent and Challenger agents debate, an evidence ledger and hallucination firewall check every claim, and a Trust Score decides the outcome" width="100%"/></a>

**[MandateIQ](https://github.com/sreejasun/MandateIQ)** reviews one fund at a time against an investment mandate. A Proponent agent builds the case for approval and a Challenger agent attacks it, for up to three rounds. Every claim has to cite an evidence ledger, and a hallucination firewall blocks anything that cites missing or misquoted evidence. Policy, cost and suitability rules run next to the agents, and a Trust Score decides whether a case is finalized, sent back for rework, or handed to a person. One rule it never bends: a high Trust Score cannot override a failed control.

Under the hood it's a FastAPI + SQLite backend with a React/TypeScript interface. AWS Bedrock is the main model provider, through the Converse API with a bounded tool-use loop for each agent. There's also a Groq adapter for when I don't have AWS access, and a mock provider so the whole test suite runs offline. It's an educational prototype on synthetic data, not investment advice.

<table>
<tr>
<td width="50%"><a href="https://github.com/sreejasun/MandateIQ"><img src="https://raw.githubusercontent.com/sreejasun/MandateIQ/main/docs/screenshots/committee.png" alt="MandateIQ committee transcript" width="100%"/></a><br/><sub><b>Committee:</b> the debate, round by round. Withdrawn claims are struck through.</sub></td>
<td width="50%"><a href="https://github.com/sreejasun/MandateIQ"><img src="https://raw.githubusercontent.com/sreejasun/MandateIQ/main/docs/screenshots/trust.png" alt="MandateIQ trust and governance view" width="100%"/></a><br/><sub><b>Trust and governance:</b> how the score was built, and every rule that fired.</sub></td>
</tr>
</table>

👉 **[Code, architecture and setup on GitHub →](https://github.com/sreejasun/MandateIQ)**

<img src="assets/h-projects.svg" alt="Projects" width="100%"/>

<table>
<tr>
<td width="50%"><img src="assets/card-customner.svg" alt="CustomNER: entity F1 from 0.59 to 0.93 over 18 iterations" width="100%"/></td>
<td width="50%"><a href="https://drive.google.com/file/d/1v_k7RDhcDrZIFxkG2X88pN_TKJix34Hd/view?usp=drive_link"><img src="assets/card-delivery.svg" alt="Delivery optimization: 95% on-time fulfillment across 500K+ weekly orders" width="100%"/></a></td>
</tr>
<tr>
<td width="50%"><img src="assets/card-rag.svg" alt="Multi-document RAG question answering" width="100%"/></td>
<td width="50%"><a href="https://drive.google.com/file/d/1lOrfOd4O5sxYROFxYkp2dERLhaXOOSNO/view?usp=drive_link"><img src="assets/card-ondc.svg" alt="AI product cataloging for ONDC: 40% less manual effort" width="100%"/></a></td>
</tr>
</table>

- **CustomNER** (BDSR Solutions): a Python and spaCy pipeline for pulling structured entities out of unstructured job postings, wrapped in a Flask human-in-the-loop app that combines annotation, active learning and iterative retraining. Entity F1 went from 0.59 to 0.93 over 18 iterations while the manual labeling effort dropped. It's an internal tool, so there's no public repo.
- **Delivery optimization** (IIT Madras): a dynamic delivery-assignment system for 500K+ weekly orders, using clustering and distance-based allocation with SQL integration for reporting. It reached 95% on-time fulfillment. Supervised by Prof. C. Rajendran and Dr. G. Viswanath (TCS) at DoMS, IIT Madras. [Read the paper →](https://drive.google.com/file/d/1v_k7RDhcDrZIFxkG2X88pN_TKJix34Hd/view?usp=drive_link)
- **Multi-document RAG**: a question-answering pipeline over several documents, using Hugging Face embeddings and FAISS for retrieval and Gemini Pro (through LangChain) to write the answer.
- **AI product cataloging** (UdyamWell, on the ONDC network): object detection plus description generation to automate product images in the onboarding flow, at 92% detection accuracy. [Details →](https://drive.google.com/file/d/1lOrfOd4O5sxYROFxYkp2dERLhaXOOSNO/view?usp=drive_link)

<img src="assets/h-experience.svg" alt="Experience" width="100%"/>

| When | Role | What I did |
|---|---|---|
| **Jun 2026 – now** | AI Engineer, Python Full Stack Intern · BDSR Solutions LLP | Designed and deployed CustomNER from scratch, then built the Flask human-in-the-loop app around it. |
| **Mar 2026 – now** | Information Systems Grader · [Arizona State University](https://www.asu.edu/) | Grading graduate-level work in Python, information systems and analytics, with technical feedback students can act on. |
| **Jun 2024 – Apr 2025** | ML Research Intern · [IIT Madras](https://www.iitm.ac.in/) | NLP pipeline over 1,000+ customer-feedback records scraped from public sites, to find operational patterns in courier services. A two-level classifier that sorts feedback and routes it into 6 departments. A real-time email classification app for non-technical ops teams. |
| **Sep – Oct 2024** | AI Developer Intern · [UdyamWell](https://drive.google.com/file/d/1lOrfOd4O5sxYROFxYkp2dERLhaXOOSNO/view?usp=drive_link) (ONDC) | Computer-vision cataloging system, integrated into ONDC product onboarding: 92% detection accuracy, 40% less manual cataloging. |

<img src="assets/h-research.svg" alt="Research" width="100%"/>

- 📄 **[GenAI-Driven Intelligent Email Ticketing: An End-to-End Architecture for Automated Sentiment-Aware Customer Support](https://link.springer.com/chapter/10.1007/978-3-032-22114-8_29)**. ICACECS 2025, *Smart Innovation, Systems and Technologies* vol. 488, Springer. ([DOI](https://doi.org/10.1007/978-3-032-22114-8_29))
- 📄 **[Optimizing Delivery Operations in Dynamic Urban Environments: A Comprehensive Model](https://drive.google.com/file/d/1v_k7RDhcDrZIFxkG2X88pN_TKJix34Hd/view?usp=drive_link)**. *Sustainable Paradigms in Operations and Supply Chain Management*.

More on [Google Scholar](https://scholar.google.com/citations?hl=en&user=s_hU8_UAAAAJ).

<img src="assets/h-stack.svg" alt="Stack" width="100%"/>

**Languages** &nbsp; <img src="https://skillicons.dev/icons?i=py,java,cpp,c,r,js,ts,bash&theme=dark" height="34" align="center"/> &nbsp; SQL

**AI / ML** &nbsp; <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" height="34" align="center"/>
![spaCy](https://img.shields.io/badge/spaCy-0B0B0E?style=flat-square&logo=spacy&logoColor=E8A0B8) ![LangChain](https://img.shields.io/badge/LangChain-0B0B0E?style=flat-square&logo=langchain&logoColor=E8A0B8) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-0B0B0E?style=flat-square&logo=huggingface&logoColor=E8A0B8) ![Multi-agent systems](https://img.shields.io/badge/Multi--agent_systems-0B0B0E?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-0B0B0E?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-0B0B0E?style=flat-square&logo=ollama&logoColor=E8A0B8)

**Backend & cloud** &nbsp; <img src="https://skillicons.dev/icons?i=fastapi,flask,react,docker,githubactions,git,linux,aws,azure&theme=dark" height="34" align="center"/>

**Data** &nbsp; ![Qdrant](https://img.shields.io/badge/Qdrant-0B0B0E?style=flat-square&logo=qdrant&logoColor=E8A0B8) ![FAISS](https://img.shields.io/badge/FAISS-0B0B0E?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-0B0B0E?style=flat-square&logo=pandas&logoColor=E8A0B8) ![NumPy](https://img.shields.io/badge/NumPy-0B0B0E?style=flat-square&logo=numpy&logoColor=E8A0B8) ![Power BI](https://img.shields.io/badge/Power_BI-0B0B0E?style=flat-square&logo=powerbi&logoColor=E8A0B8) ![Tableau](https://img.shields.io/badge/Tableau-0B0B0E?style=flat-square&logo=tableau&logoColor=E8A0B8) ![ETL · EDA · Statistics](https://img.shields.io/badge/ETL_·_EDA_·_Statistics-0B0B0E?style=flat-square)

<img src="assets/h-education.svg" alt="Education and courses" width="100%"/>

- 🎓 **[Arizona State University](https://www.asu.edu/)**: MS in Data Science, Analytics and Engineering (Computing and Decision Analytics), GPA 4.0/4.0, May 2027
- 🎓 **CMR College of Engineering and Technology**: B.Tech in AI & Data Science (GPA 9.16/10) with a minor in Computer Science Engineering, Cyber Security (9.5/10), May 2025. [Best Outgoing Student](https://drive.google.com/file/d/1NDh1yyRwMtNftQhL-cTiECLDM1uoQr0p/view?usp=sharing) and one of the [first-year academic toppers](https://drive.google.com/file/d/16-Z9SnqzkgTgc2GrFDG9Rm_S8_B7JZvX/view?usp=sharing)
- 📜 [Generative AI with DeepLearning.AI and AWS](https://drive.google.com/file/d/1wrTWFeftnjDZos39qpECiu2liryaChHT/view?usp=sharing) (Coursera, 2024)
- 📜 [AI Agents course by Hugging Face](https://drive.google.com/drive/folders/1ekVstwvd5-r92gxp9pOPnrz4_lL3cUni?usp=sharing) (2025)

<img src="assets/h-activity.svg" alt="GitHub activity" width="100%"/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sreejasun&show_icons=true&hide_border=true&bg_color=0B0B0E&title_color=E8A0B8&icon_color=E8A0B8&text_color=C9C9D1" height="160" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sreejasun&layout=compact&hide_border=true&bg_color=0B0B0E&title_color=E8A0B8&text_color=C9C9D1" height="160" alt="Top languages"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sreejasun/sreejasun/output/github-snake-dark.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/sreejasun/sreejasun/output/github-snake.svg" width="100%">
</picture>

<br/>

If something here fits a role you're hiring for, I'd love to hear from you: [sunkeswaramsreeja@gmail.com](mailto:sunkeswaramsreeja@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0B0E,100:E8A0B8&height=110&section=footer&animation=twinkling" width="100%" alt=""/>

</div>
