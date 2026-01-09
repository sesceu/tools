# Antigravity Tools System Instructions

## Repo Overview
This repository contains a collection of simple, everyday web-based tools.
Each tool is self-contained in its own subdirectory.
The tools are hosted on GitHub Pages.

## Tech Stack & Design Philosophy
- **Hosting**: GitHub Pages (Static site hosting).
- **Languages**: Vanilla JavaScript (ES6+) is preferred for simplicity. TypeScript is allowed but only if it doesn't require complex build steps (e.g. via JSDoc type checking or simple transpilation if strictly necessary, but prefer raw JS).
- **Frameworks**: NONE. Use native DOM APIs. If a library is absolutely needed, use a lightweight CDN link (e.g. Alpine.js or Vue via CDN) but prefer Vanilla JS.
- **Dependencies**: ZERO build steps. The code should run directly in the browser.
- **Aesthetics**: "Vibe-coded".
    - Clean, modern, vibrant but not bloated.
    - User WOW factor required (rich colors, smooth gradients, nice typography).
    - No generic browser defaults.
    - Responsive and alive (hover effects, micro-animations).

## Creating a New Tool
1.  **Structure**: Create a new subdirectory for the tool (e.g., `word-counter/`).
2.  **Isolation**: The tool should be self-contained. It shouldn't depend on shared local code that complicates deployment.
3.  **Registration**: Add the new tool to the root `index.html` list.
4.  **Implementation**:
    - Input -> Action -> Output flow.
    - Focus on a single distinct purpose.

## Deployment
- GitHub Pages expects static content.
- If using a build step (like Vite for TypeScript), ensure the output is deployable or set up a GitHub Action to build and deploy.
- For now, we aim for simplicity.

## Workflow
- When asked to "start a new tool", initialize the folder and implementation.
- Verify everything described is working.
