# Prakash Gouda

SDET working with Playwright, TypeScript, UI and API automation, and CI/CD.

I care about whether a test catches a useful problem and whether someone can understand the failure. That shapes how I write tests, handle data, and structure automation.

## Featured project

### [Playwright Starter](https://github.com/PrakashgoudaAI/playwright-starter)

A runnable test project with its own local task-board application and public demo accounts. It covers sign-in and sign-out, viewer permissions, task creation, and completing tasks through the UI and API.

- Fresh sessions and separate datasets keep parallel tests independent.
- Page objects and a task-table component keep interactions readable.
- Playwright HTML, JUnit, and Allure reports support failure investigation.
- GitHub Actions runs strict TypeScript checks and the Chromium and API tests with retries disabled.

[Read the setup and design decisions](https://github.com/PrakashgoudaAI/playwright-starter#readme) · [View test runs](https://github.com/PrakashgoudaAI/playwright-starter/actions/workflows/verify.yml)

## How I work

Keep test intent clear. Use the simplest design that handles the problem. Investigate unstable tests before adding retries. Treat test code with the same care as application code.

I’m continuing to develop the starter, with broader permission checks and browser coverage next. The repository documents what is implemented and what still needs work.

All examples here use synthetic applications and data. Employer, customer, and confidential material stay out of these repositories.
