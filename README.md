# Agentic AI Acrobat

**Learn AI. Find Your Orbit. Build Something Amazing.**

An interactive, beginner-friendly learning site that helps people understand AI, discover what to build with it, and start creating. The site is a single static page (`index.html`) with no build step and no dependencies beyond two Google Fonts.

## Sections

- **Home** – Three entry points: Learn, Vibe and Build.
- **Learn** – AI fundamentals (expandable cards with sample prompts), the AI tool landscape, a timeline of how AI has evolved, practical use cases, a knowledge check, an FAQ, and links for going deeper.
- **Vibe** – A six-question quiz (interests, goals, experience, approach, time, technical comfort) with a progress bar and a Back button. It ends with three personalized project ideas.
- **Build** – Tool cards (chat assistants, Perplexity, Lovable, GitHub Copilot) and a four-step first-build recipe.

## Design

Light, space-inspired theme: white background, champagne-gold accents, pale lavender and sky-blue highlights, faint stars and planets as decoration. Fonts are Fraunces (headings) and Outfit (body).

## Run locally

Open `index.html` in any browser. No install needed.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `agentic-ai-acrobat`).
2. Upload `index.html`, `README.md` and `.nojekyll` to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two, the site is live at `https://<your-username>.github.io/agentic-ai-acrobat/`.

### Using git from the command line

```bash
git init
git add .
git commit -m "Launch Agentic AI Acrobat"
git branch -M main
git remote add origin https://github.com/<your-username>/agentic-ai-acrobat.git
git push -u origin main
```

Then enable Pages as described in steps 3–5 above.

## Customize

All content lives in `index.html`:

- **Colors:** edit the CSS variables at the top of the `<style>` block (`--gold`, `--bg`, and so on).
- **Learn content:** edit the `fund`, `uses` and `faq` arrays in the script.
- **Quiz questions and ideas:** edit the `Q`, `ideas` and `extra` objects.
- **Tools:** edit the `tools` array.

## License

Add a license of your choice (for example MIT) before sharing the repository publicly.
