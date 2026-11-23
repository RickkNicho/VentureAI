# VentureAI
**Think Bigger. Build Smarter.**

VentureAI is a polished, browser-based entrepreneurship toolkit that helps aspiring founders turn early ideas into structured business opportunities. It brings idea development, business planning, market research frameworks, branding, marketing and financial modelling into one connected experience.

## Product capabilities
- Guided business plan builder and business model canvas
- Idea discovery, opportunity scorecard and local idea workspace
- Customer persona, SWOT, competitor and research-question frameworks
- Brand positioning, naming directions, campaign and content planners
- Financial calculators for revenue, operating profit, break-even, startup costs, expenses, pricing and scenarios
- Prompt builder and transparent local assistant tools
- Responsible AI guidance and browser-local idea persistence

## Technology
- Semantic HTML5
- CSS3 with responsive layouts and reusable design tokens
- Vanilla JavaScript (no build step or runtime framework)
- Browser `localStorage` for saved ideas

## Run locally
Open `index.html` in a modern browser, or serve the repository root with any static file server. No package installation or build process is required.

## Publish with GitHub Pages
1. Create a GitHub repository and add the contents of this project to the repository root.
2. Confirm `index.html` and the `assets/` directory are at the root level.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select your publishing branch (usually `main`) and the `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish and open the URL shown in the Pages settings.

All internal page and asset links are relative, so the site works from a GitHub Pages project path.

## Important product notes
- The guided assistants use local templates and deterministic logic. No live AI model or external AI API is connected.
- Saved ideas use this browser's `localStorage`; there is no login, cloud database or cross-device sync.
- Research examples and generated frameworks are starting points, not verified market research.
- Financial outputs are planning calculations, not accounting, tax, investment or legal advice.


## Adaptive prompt programmes (updated edition)
The Idea Development, Business Planning, Market Research, Branding & Marketing, Financial Planning and Prompt Generator pages include an adaptive prompt programme. Enter a business profile once; it is saved in the current browser and reused across those pages. Each section offers eight long-form prompts designed for a different stage of work. Prompts adapt to the user's business description, industry, location, customers, resources, stage and current uncertainty. Users can preview and copy prompts individually or copy the complete sequence.

**Important:** This is a prompt-generation and guidance system, not a connected AI product. Prompts are assembled locally in the browser. Users must paste them into an external AI service for model-generated analysis. The site does not independently verify AI outputs or conduct live market research.
