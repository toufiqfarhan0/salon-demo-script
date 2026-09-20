# AURA Studio — Universal Script Embed Demo

This standalone salon website demonstrates how any static website, Webflow, Shopify, WordPress, or HTML page can embed the **OmniDesk Autonomous Voice Receptionist** with a single `<script>` tag.

---

## ⚡ The Embed Snippet

Paste this snippet right before the closing `</body>` tag on any website:

```html
<!-- OmniDesk Autonomous Voice Receptionist -->
<script
  src="https://omni-desk-rho.vercel.app/widget.js"
  data-agent="agent_6e8ae0f0f2a24f8e88bf8c6f74e7c794"
  data-position="bottom-right"
  data-theme="dark"
  data-accent="#18181b"
  data-label="Talk to Receptionist"
  defer>
</script>
```

---

## 🚀 Running Locally

```bash
npm run dev
# or
npx serve . -l 3001
```

Open [http://localhost:3001](http://localhost:3001) in your browser. The floating voice receptionist widget will appear in the bottom-right corner!

---

## ☁️ Deploying to Vercel

```bash
npx vercel
```
Or connect this repository directly to Vercel / Netlify / GitHub Pages. Zero build configuration is required.
