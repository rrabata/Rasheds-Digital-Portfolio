# Rashed Rabata | Professional AI Portfolio

GitHub Pages-ready static portfolio. No dependencies, bundler, API keys, or build commands needed.

## Course ownership (important)

- **Artifacts 1–5: AIML-500** (existing prerequisite-course artifacts, preserved)
- **Artifacts 6–8: AIML-501** — Machine Learning Algorithms: A Visual Framework for Real-World Applications

## Repository contents

- `index.html` — landing page and all eight artifact cards
- `artifact-ai-lab.html`, `artifact-siri-ml.html`, `artifact-faceid.html`, `artifact-predictive-text.html`, `artifact-newsletter.html` — AIML-500
- `artifact-ml-algorithms.html` — AIML-501 responsive, interactive infographic with 12 algorithm descriptions, use cases, references, filter buttons, and print-to-PDF support
- `assets/aiml501-algorithm-framework.svg` — downloadable infographic overview
- `assets/` — all preserved illustrations and PDFs for artifacts 1–5
- `AIML501_REFLECTION_DRAFT.md` — reflection draft for Brightspace text entry, review/personalize before submitting

## Upload to GitHub

1. Create a new GitHub repository, or open the repository that currently hosts the portfolio.
2. Unzip the provided package, then upload **the files inside the unzipped folder** to the repository **root** (not an enclosing folder). Preserve the `assets/` folder. If updating a pre-existing repo, replace its corresponding files and commit.
3. In the repository select **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
4. The site URL for a project repository is typically `https://YOUR_USERNAME.github.io/REPO_NAME/`. A user-site repository named `YOUR_USERNAME.github.io` instead publishes at that root domain.
5. Check the published `index.html`, the Artifact 6 link, all existing artifact links, SVG download, and mobile layout in a private browser window to confirm instructor accessibility.
6. Copy the public portfolio URL to Brightspace. Paste your personalized reflection from the draft into the designated text box.

If the repository is already hosted on GitHub Pages, do **not** change its deployment settings unless needed. The entire site uses relative links and works under either site URL pattern.

## Scope and integrity

Artifact 6 is an explanatory framework: business use cases illustrate possibilities; no trained models or business outcomes are represented. Generative AI, BERT and GPT pretraining are not inaccurately classified as simply supervised or unsupervised.

## New: AIML-501 neural network presentation (second AIML-501 artifact)

- `artifact-neural-networks.html` — Artifact 7 detail page
- `assets/aiml501-neural-networks.pdf` — downloadable presentation
- `assets/aiml501-neural-network-preview.svg` — portfolio preview graphic
- `AIML501_NEURAL_NETWORK_REFLECTION.md` — short Brightspace submission reflection

Upload the entire updated site at repository root; retain all assets and existing artifact pages. Confirm links to Artifact 7 and the PDF guide work on the public site. The presentation does not claim measured Playground results; add your own screenshots or metrics after running experiments if required.

## New: AIML-501 LLM training infrastructure and costs (third AIML-501 artifact)

- `artifact-llm-training-costs.html` — Artifact 8 interactive portfolio detail page and PDF embed
- `assets/aiml501-llm-training-costs.pdf` — five-page vector infographic
- `assets/aiml501-llm-training-explanation.pdf` — explanatory document with classification rationale, evidence limits, design choices, learning reflection and sources
- `assets/aiml501-llm-training-preview.svg` — homepage image

The sources identify precise reporting boundaries. Do not interpret the DeepSeek-V3 $5.576M assumed compute rental figure as all-in development cost or compare H800 and H100 GPU-hours as equal monetary units.

To update an existing deployment: replace `index.html` and `README.md`; add the new artifact HTML and the three new assets under `assets/`. All earlier artifacts are preserved.
