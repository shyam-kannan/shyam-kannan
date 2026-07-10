<div align="center">
Show Image

<a href="https://github.com/shyam-kannan">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=MS+Artificial+Intelligence+%40+SJSU;Building+Full-Stack+%2B+ML+%2B+Agentic+AI+Systems;Open+to+SWE+%2F+ML+%2F+AI+Engineer+Roles" alt="Typing SVG" />
</a>
<br/>
Show Image
Show Image
Show Image

<br/>
Show Image
Show Image
Show Image
Show Image

<br/>
Show Image
Show Image
Show Image

</div>

About Me

I'm a Master's in Artificial Intelligence graduate from San Jose State University (May 2026), with a B.S. in Computer Science from Arizona State University. I build production-grade systems across the full stack — from AWS-deployed computer vision pipelines to multi-agent LLM orchestration platforms — with a product engineering mindset that prioritizes shipping working systems over isolated proofs of concept.

My work spans full-stack development, ML/CV pipelines in production, and agentic AI systems, backed by hands-on internship experience deploying real inference services on AWS.

yamlrole: Software / ML / AI Engineer
focus: [Full-Stack Engineering, Applied AI, Multi-Agent Systems, ML Infrastructure]
mindset: Ship end-to-end, measure everything, no fabricated metrics

Open To: Software Engineer · ML Engineer · AI Engineer · Backend Engineer · Applied AI Engineer (US-based)


Tech Stack

Languages
Show Image
Show Image
Show Image
Show Image
Show Image

Frontend
Show Image
Show Image
Show Image
Show Image
Show Image

Backend & Databases
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image

Cloud, DevOps & Tooling
Show Image
Show Image
Show Image
Show Image
Show Image


AI / ML Expertise

DomainProficiencyDetailsComputer VisionAdvancedYOLOv8 + ResNet two-stage detection, TensorRT INT8 quantization, production inference on AWS LambdaMulti-Agent OrchestrationAdvancedLangGraph Supervisor patterns, human-in-the-loop interrupt/resume, ChromaDB long-term memoryLLM Evaluation & SafetyAdvancedFail-closed moderation gateways, hallucination detection, CI regression gating across localesPrompt EngineeringAdvancedPrompt version control, statistical A/B testing (Welch's t-test / Mann-Whitney U), auto-promotion pipelinesRetrieval-Augmented GenerationIntermediateBioGPT + live literature retrieval for domain-specific QAReinforcement LearningGraduate CourseworkSJSU MS AI curriculum


Featured Projects

<details>
<summary><b>🚗 LessGo &mdash; Full-Stack iOS Carpooling Platform</b></summary>
<br/>
SJSU capstone project. Native Swift/SwiftUI app with 40+ screens backed by 8 Node.js microservices. Matching algorithm combines two research papers (He et al. 2014, Tang et al. 2020) in a three-stage pipeline with a Python FastAPI embedding microservice trained on NYC taxi data.

StackSwift, SwiftUI, Node.js, FastAPI, PythonScale40+ screens, 8 microservicesPerformanceThree-stage matching pipeline with embedding-based recommendationSecurityToken-based service auth across microservicesImpactFull-stack capstone shipped end-to-end, frontend to ML matching backendRepositorygithub.com/shyam-kannan/SJSU_Ridesharing

</details>
<details>
<summary><b>📈 StockPulse &mdash; Real-Time Stock Research Dashboard</b></summary>
<br/>
React 19 + Vite frontend, FastAPI + SQLite backend with a scheduled scraper pulling from Yahoo Finance, RSS feeds, ApeWisdom, and StockTwits every 2 hours. Uses the Claude API to generate daily market briefings, per-ticker analysis, and AI-built diversified portfolios.

StackReact 19, Vite, FastAPI, SQLite, APScheduler, Claude APIScale4 live data sources, automated every 2 hoursPerformanceScheduled scraping pipeline with AI-generated analysis on refreshSecurityAPI-key isolated backend, no client-side data exposureImpactDeployed and running on Vercel + RailwayRepositorygithub.com/shyam-kannan/StockPulse

</details>
<details>
<summary><b>🤖 Research-Agent-Orchestration &mdash; Multi-Agent Research Platform</b></summary>
<br/>
LangGraph Supervisor decomposes research requests and routes them to specialized Research/Extraction/Analysis/Writing agents. A Haiku-based Reviewer scores output quality; contradiction detection triggers human escalation via LangGraph interrupt/resume. ChromaDB provides long-term memory across tasks.

StackLangGraph, ChromaDB, FastAPI, Celery, Redis, PostgreSQL, StreamlitScale4 specialized agents + 1 reviewer agent, three-tier model routingPerformancePer-node cost tracking with full execution trace treeSecurityHuman-in-the-loop escalation on contradiction detectionImpactWorking HITL research pipeline with cost-optimized routingRepositorygithub.com/shyam-kannan/Research-Agent-Orchestration

</details>
<details>
<summary><b>🔀 Prompt-Versioning-Platform &mdash; "Git for Prompts"</b></summary>
<br/>
Version control and A/B testing platform for LLM prompts. Content-hash deduplication, production/staging labels, unified diffs, and non-destructive rollback. Statistical A/B testing auto-selects between Welch's t-test and Mann-Whitney U based on normality, with Cohen's d effect size and auto-promotion after a 24-hour significance hold.

StackFastAPI, PostgreSQL, Celery, Redis, Streamlit, Docker ComposeScale41 automated testsPerformanceSticky-session traffic splitting via consistent hashingSecurityAuto-pause on error-rate spikesImpactStatistically rigorous, production-style experimentation engineRepositorygithub.com/shyam-kannan/Prompt-Versioning-Platform

</details>
<details>
<summary><b>🌐 Multilingual GenAI Evaluation &mdash; AI Moderation Gateway</b></summary>
<br/>
Multilingual AI evaluation and moderation gateway across en-US, es-MX, ar-SA, and ja-JP. Scores every output on 4 axes: LLM-judged quality, hallucination detection, fail-closed moderation, and locale-specific validation. A CI regression gate blocks prompt versions that score worse than the production baseline.

StackFastAPI, PostgreSQL, Claude Sonnet/Haiku, React 18, TypeScript, GitHub ActionsScale4 locales, 90 automated testsPerformanceCI-gated regression detection on every prompt changeSecurityFail-closed moderation by designImpactProduction-style AI safety gateway with automated quality enforcementRepositorygithub.com/shyam-kannan/Multilingual_GenAI_Evaluation

</details>
<details>
<summary><b>📄 RepoFriend (Codebase-Documenter) &mdash; AI-Generated Repo Documentation</b></summary>
<br/>
Turns any GitHub repo into AI-generated documentation. Next.js 14 frontend with GitHub OAuth, FastAPI + LangGraph backend workflow (clone → scan → analyze → generate), with optional AI-inserted inline code comments auto-submitted as a pull request.

StackNext.js 14, FastAPI, LangGraph, Claude API, Celery, S3, GitHub OAuthScaleWorks on any public or OAuth-authorized repoPerformanceBackground job processing via CelerySecurityGitHub OAuth for private repo accessImpactAutomated repo-to-docs pipeline with PR-based deliveryRepositorygithub.com/shyam-kannan/codebase-documenter

</details>
<details>
<summary><b>🧬 BioMed-LLM &mdash; Biomedical RAG System</b></summary>
<br/>
Combines BioGPT with live NCBI Entrez API retrieval for biomedical question answering, addressing static-LLM knowledge gaps with real-time literature retrieval.

StackBioGPT, NCBI Entrez API, RAG pipelineScaleLive literature retrieval, not static knowledgePerformancePeak batch accuracy 81.5%, overall system accuracy 78%SecurityN/A (research project)ImpactDemonstrates RAG closing static-LLM knowledge gaps in a specialized domainRepositorygithub.com/shyam-kannan/BioMed-LLM

</details>
<details>
<summary><b>🧾 Finance Tracker &mdash; AI Receipt Intelligence</b></summary>
<br/>
Upload a receipt image and a Gemini LLM extracts vendor, total, date, and category automatically, rejecting non-receipt images. Includes a budgets/transactions dashboard with AI-generated spending insights.

StackNext.js, TypeScript, Supabase, Tesseract.js, Gemini APIScaleOCR + LLM extraction pipeline per uploadPerformanceAutomated categorization with rejection of invalid inputsSecuritySupabase-managed auth and storageImpactAI-driven personal finance automation, end to endRepositorygithub.com/shyam-kannan/finance_tracker

</details>

Experience

AI Engineer Intern · Kashmir World Foundation
Jun 2025 – Aug 2025

Built and deployed a YOLOv8 + custom ResNet two-stage detector on 10K+ drone images, reaching 90%+ detection accuracy and deploying to AWS Lambda for production inference. Drove a 65% reduction in scoring/response time via CloudWatch profiling, TensorRT INT8 quantization, and weight pruning. Closed a cross-region distribution gap through a targeted augmentation strategy, lifting out-of-sample accuracy 20%+ across holdout regions.

Python PyTorch YOLOv8 AWS Lambda TensorRT CloudWatch CI/CD

Software Engineer · Ecological
Jun 2024 – Aug 2024 · Champaign, IL (Remote)

Built a 5-page responsive dashboard in React + Ant Design for small-business carbon footprint tracking, with 15 GraphQL queries on AWS powering premium/basic plan customization. Implemented a 4-step sign-up flow in React + TypeScript.

React TypeScript GraphQL Ant Design AWS


Achievements

<div align="center">
RecognitionDetailsMS in Artificial IntelligenceSan Jose State University, May 20268 Shipped Production ProjectsFull-stack, ML, and multi-agent systems, each with real deploymentAWS Certified Cloud Practitioner2023Deep Learning SpecializationCoursera, completed

</div>

Certifications

AWS
Show Image

Coursera
Show Image


GitHub Analytics

<div align="center">
<img src="https://github-readme-stats-shyam.vercel.app/api?username=shyam-kannan&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=c9d1d9" width="49%" />
<img src="https://streak-stats.demolab.com/?user=shyam-kannan&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%" />
<img src="https://github-readme-stats-shyam.vercel.app/api/top-langs/?username=shyam-kannan&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=c9d1d9" width="49%" />
</div>
Trophies

<div align="center">
<img src="https://github-trophy-shyam.vercel.app/?username=shyam-kannan&theme=algolia&no-frame=true&margin-w=10&row=1" />
</div>
Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=shyam-kannan&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=ffffff" width="90%" />
</div>
Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/shyam-kannan/shyam-kannan/output/github-contribution-grid-snake-dark.svg" width="90%" />
</div>

Current Focus

yamlLearning:   [Agentic AI system design, LLMOps at scale]
Building:   [Multilingual GenAI Evaluation Gateway, portfolio expansion]
Exploring:  [Applied AI Engineer & ML Engineer roles]
Open To:    [Software Engineer, ML Engineer, AI Engineer, Backend Engineer — US-based]


Connect

<div align="center">
Show Image
Show Image
Show Image
Show Image

</div>

<div align="center">
"Ship end-to-end. Measure everything. Never fabricate a metric."

Show Image

</div>
