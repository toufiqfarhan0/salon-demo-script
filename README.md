# AURA Studio — Universal Script Embed Demo

This standalone salon website demonstrates how any static website, Webflow, Shopify, WordPress, or HTML page can embed the **OmniDesk Autonomous Voice Receptionist** with a single `<script>` tag.

---

## ⚡ The Embed Snippet

Paste this snippet right before the closing `</body>` tag on any website:

```html
<!-- OmniDesk Autonomous Voice Receptionist -->
<script
  src="https://cdn.jsdelivr.net/npm/omnidesk-voice@0.1.17/dist/widget.global.global.js"
  onerror="this.onerror=null;this.src='https://omni-desk-rho.vercel.app/widget.js';"
  data-host="https://omni-desk-rho.vercel.app"
  data-business-id="biz_demo_dental"
  data-agent="agent_118183fec8b04d99ac3702e5327ef544"
  data-position="bottom-right"
  data-theme="light"
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
