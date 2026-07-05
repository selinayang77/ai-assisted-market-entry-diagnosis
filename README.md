[README.md](https://github.com/user-attachments/files/29669952/README.md)
# From Festival Curiosity to Market Understanding

## What this case page is

This is a standalone consulting-style web case page for an anonymized selected work sample: a market-entry diagnosis for a premium mezcal brand in China, combining AI-assisted hypothesis development with human-led evidence evaluation.

## Why it was built

The page translates the selected work sample into a 60-90 second web reading experience. It helps viewers quickly understand the business context, the competing hypotheses, the evidence-to-diagnosis logic, and the role of AI-assisted hypothesis generation.

## What the case demonstrates

- Hypothesis-led market-entry diagnosis
- Evidence synthesis from logged transactions, product-level sales records, visitor questions, and field observations
- Consumer insight and journey diagnosis
- AI-assisted hypothesis generation
- Human-led evidence evaluation
- Testable recommendation design

## How to run locally

From this folder, start a static local server:

```bash
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173
```

For the most accurate local preview, use the local server URL above instead of double-clicking `index.html`. Some in-app or file-based browser previews can show a blank PDF screen when opening local PDF files directly.

The PDF download button points to a relative local asset path:

```text
./assets/market-entry-diagnosis.pdf
```

For public deployment, make sure this PDF is also redacted. Do not upload a PDF that contains exact financial figures or client-sensitive details to a public GitHub repository.

## How to deploy on GitHub Pages or Vercel

For GitHub Pages:

1. Push `index.html`, `styles.css`, `README.md`, and a redacted `assets/` folder to a GitHub repository.
2. In repository settings, enable Pages from the main branch or a dedicated deployment branch.
3. Use the repository root as the site source.

For Vercel:

1. Import the repository into Vercel.
2. Use the default static site settings.
3. Deploy from the repository root.

If deploying as a GitHub Pages project site under a repository subpath, confirm that the PDF path resolves in the final hosted URL.

## Privacy note

The case uses anonymized and summarized content only. Raw client materials, exact financial figures, transaction-level data, internal reports, and confidential brand documents are not included.
