<p align="center">
  <img src="https://raw.githubusercontent.com/PrakashgoudaAI/PrakashgoudaAI/main/assets/banner.svg" width="100%" alt="Prakash Gouda — SDET. Clear tests. Useful feedback." />
</p>

## Hi, I’m Prakash

I work on test automation with TypeScript, Playwright, API checks and CI pipelines. My projects focus on places where a passing test can still leave a problem: permission boundaries, concurrent writes, incomplete CI results and answers that sound plausible without enough evidence.

Each repository includes a synthetic application or dataset, repeatable checks and the limits of what those checks establish. Start with the browser framework or reservation API for the engineering work; the evaluation projects show how I investigate failures.

## Projects

| Project | Problem explored | Evidence to review |
| :--- | :--- | :--- |
| [Playwright Starter](https://github.com/PrakashgoudaAI/playwright-starter) | Reliable UI and API coverage with useful failure reports | Chromium, Firefox and WebKit; session isolation; selected accessibility checks; two CI shards checked against an expected test-ID plan. [Workflow](https://github.com/PrakashgoudaAI/playwright-starter/actions/workflows/verify.yml) |
| [API Contract & Security Lab](https://github.com/PrakashgoudaAI/api-contract-security-lab) | Correct reservations under retries, permissions and competing writers | PostgreSQL tests through two service processes, signed-token rejection cases, migration integrity and a real dashboard consumer contract. [Workflow](https://github.com/PrakashgoudaAI/api-contract-security-lab/actions/workflows/verify.yml) |
| [RAG & Agent Quality Lab](https://github.com/PrakashgoudaAI/rag-agent-quality-lab) | Grounded answers, refusal behavior and uncertain tool outcomes | Fixed evaluation cases, archived local-model experiments, bounded MCP calls and cancellation tests. [Measured results](https://github.com/PrakashgoudaAI/rag-agent-quality-lab/tree/main/docs/experiments) |
| [Release Evidence Eval](https://github.com/PrakashgoudaAI/release-evidence-eval) | Whether a release recommendation follows the supplied CI evidence | 112 automated tests, repeated model trials, a separate reserved-case study and policy-guard fault checks. [Walkthrough](https://github.com/PrakashgoudaAI/release-evidence-eval/blob/main/docs/walkthrough.md) |
| [Postman API Tests](https://github.com/PrakashgoudaAI/postman-api-tests) | Role permissions and persisted state below the UI | Two data-driven roles, 26 requests and 48 assertions, with local CLI execution and JSON/JUnit reports. [Workflow](https://github.com/PrakashgoudaAI/postman-api-tests/actions/workflows/verify.yml) |

The model experiments have failed quality gates. I keep those failures visible, with development and later author-written cases reported separately. These projects evaluate model behavior; they do not authorize autonomous production releases or establish independently reviewed benchmark performance.

## How I approach the work

Check state after a mutation. Test authorization through the API as well as the interface. Keep tests isolated and investigate instability before adding retries. Check that the complete planned suite ran before trusting a CI summary. Preserve evaluation cases, scoring rules and failed attempts so later results can be assessed fairly.

**Tools used here:** TypeScript, Python, Playwright, Postman CLI, PostgreSQL, Pact, GitHub Actions, Allure, JSON Schema and the MCP SDK. The repositories show the scope of that experience; they use synthetic data and local test targets.

## Connect

<p>
  <a href="https://www.linkedin.com/in/prakashgouda/"><img src="assets/connect-linkedin.svg" alt="LinkedIn" width="160" height="42" /></a>
  <a href="https://www.youtube.com/@PrakashgoudaAI"><img src="assets/connect-youtube.svg" alt="YouTube" width="160" height="42" /></a>
  <a href="https://www.instagram.com/PrakashgoudaAI/"><img src="assets/connect-instagram.svg" alt="Instagram" width="160" height="42" /></a>
  <a href="https://www.facebook.com/PrakashgoudaAI"><img src="assets/connect-facebook.svg" alt="Facebook" width="160" height="42" /></a>
</p>

Employer, customer and confidential material stay out of these repositories.
