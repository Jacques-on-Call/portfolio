# Portfolio Image Assets

To ensure absolute lightning-fast speed, high Core Web Vitals scores, and perfect SEO optimization, we are leveraging Astro's native `src/assets/` folder and the `<Image />` component. This automatically optimizes, resizes, and converts your images to modern formats like `.webp` at build time!

## How to replace the placeholder images:

Simply replace the placeholder files in this directory (`src/assets/images/`) with your actual files, keeping the exact same filenames:

1. **Your Headshot / Profile Pic:**
   - **Filename:** `headshot.jpg` (or `.png` / `.webp` / `.jpeg`. If you use a different format, remember to update the import extension in `src/pages/index.astro`).

2. **n8n Main Workflow Canvas:**
   - **Filename:** `n8n-workflow-main.png` (The overall high-level n8n canvas displaying the full data integration flow).

3. **n8n Webhook Router Node Detail:**
   - **Filename:** `n8n-webhook-router.png` (Focused screenshot showing the incoming webhook configurations and routing setup).

4. **n8n Item-Level Iteration Logic:**
   - **Filename:** `n8n-item-iteration.png` (Showing the JSON payload mapping/manipulation mapping with `.item` instead of `.first()`).

---

*Note: For the best visual alignment, try to use high-quality, clear screenshots with blurred/cropped credentials as suggested by Gemini.*
