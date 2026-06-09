# Thinking in a Complex World

A personal website exploring how young people can learn to think in an age of AI, complexity, and uncertainty.

## About

**Thinking in a Complex World** is a static site that presents ideas at the intersection of complex systems research, scientific modelling, and future-oriented education. It is not a résumé—it is a reflective, editorial space for questions about how young people learn to frame problems, build models, exercise judgment, and collaborate thoughtfully with AI.

The site asks a central question:

> How should young people learn to think when AI can generate answers?

## Site Structure

| Page | Description |
|------|-------------|
| `index.html` | Main landing page — ideas, projects, evidence, personal journey, and Why Yungu |
| `about.html` | Extended narrative — from modelling forests to modelling learning |
| `model-thinking.html` | Can children learn to build models, not just memorize facts? |
| `problem-framing.html` | What if defining the problem matters more than solving it? |
| `human-ai-collaboration.html` | When AI can think with us, what remains uniquely human? |
| `learning-through-modelling.html` | Can scientific thinking become a learning practice? |
| `why-education-must-change.html` | Why education must change in an age of abundant answers |

## Tech Stack

- Plain HTML & CSS — no build step, no dependencies
- Responsive, editorial layout with warm off-white tones
- SVG hero illustration and portrait integration on the About section

## Local Preview

Clone the repository and open `index.html` in a browser, or serve the folder locally:

```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder.
5. Save. The site will be available at `https://<username>.github.io/<repository>/`.

## Customization

Before publishing, update placeholder content in:

- `index.html` — contact email (`#invitation`) and footer name
- `about.html` — personal narrative sections marked with `TODO` comments

## License

Content and design © 2026. All rights reserved unless otherwise noted.
