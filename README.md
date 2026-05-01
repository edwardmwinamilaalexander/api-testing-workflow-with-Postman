API Automation: Register → Login → Goals

https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white  
https://img.shields.io/badge/Postman_CLI-000000?logo=postman&logoColor=white  
https://img.shields.io/badge/Newman-00B3B3?logo=postman&logoColor=white  
https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white  
https://img.shields.io/badge/Postman_Monitors-FF6C37?logo=postman&logoColor=white  
https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white  
https://img.shields.io/badge/Env_Variables-Secure-green  
https://img.shields.io/badge/GitHub_Secrets-181717?logo=github&logoColor=white

A production‑grade API testing suite built for Postman v12+, designed to validate the complete user lifecycle—from account creation to secure goal management. The workflow uses dynamic authentication, modern CLI tooling, and automated CI/CD pipelines to ensure reliability, repeatability, and continuous visibility across environments.

🏗️ Workflow Overview
The suite executes a stateful, end‑to‑end sequence that mirrors real user behaviour:

Identity — Registers a new user through the public signup endpoint.

Auth — Logs in and programmatically captures a fresh JWT for the session.

Action — Uses the stored token to create, update, retrieve, and delete goals.

This ensures every run validates the full Register → Login → Goals lifecycle under real‑world conditions.

📊 Postman CLI Reporting
Running the suite through the Postman CLI provides deep observability and team‑level reporting:

Real‑time Console Output — Step‑by‑step visibility into assertions, response bodies, timings, and status codes.

Postman Cloud Reports — Automatic syncing to the Postman Dashboard with visual graphs, historical trends, and full request/response inspection.


🛠️ Tech Stack & Tools
Postman UI — Collection design, test scripting, and environment management.

Postman CLI — Primary execution engine with secret masking and cloud‑linked reporting.

Newman — Lightweight runner for local Node.js or Docker‑based execution.

GitHub Actions — Automated test execution on every push or pull request.

Postman Monitors — Scheduled uptime checks and continuous functional monitoring.

🛡️ Security & Environment
Secret Masking — Passwords, tokens, and API keys are stored as encrypted secrets.

Dynamic Auth — JWTs are captured and injected automatically via test scripts, eliminating manual updates between runs.

🚀 Execution
The suite supports multiple execution paths depending on your workflow:

Postman CLI — Real‑time execution with automatic cloud reporting.

Newman — Offline or containerised runs for local development and CI pipelines.

GitHub Actions — Acts as a deployment quality gate, blocking merges on failure.

Postman Monitors — Sends alerts when the workflow breaks, ensuring immediate visibility.

📑 Reports
The suite produces multiple report formats to support debugging, CI visibility, and long‑term quality tracking:

Postman Cloud Reports — Every Postman CLI run automatically syncs to the Postman Dashboard, providing visual timelines, performance graphs, request/response inspection, and historical trends across runs.

HTML Reports — When executed via Newman, a full HTML report is generated for offline review, ideal for local debugging or attaching to CI artifacts.
