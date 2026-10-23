# Tesco Customer Signal AI — interview demo

An independent, browser-based concept prototype for a fictional grocery-retail customer scenario. It demonstrates a possible workflow for turning shopper feedback into evidence-led themes, prioritised investigations, and a human-reviewed hand-off.

## Live demo

After publishing with GitHub Pages, the URL will be:

`https://YOUR-GITHUB-USERNAME.github.io/tesco-customer-signal-ai/`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username. The URL will work only after you create the repository and enable GitHub Pages.

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

## Publish as a public website with GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `tesco-customer-signal-ai`.
2. Upload the contents of this folder to the repository root. Make sure `index.html` is at the root, not inside another nested folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to finish publishing. The site URL will appear on the Pages settings screen.

GitHub's interface can change slightly; follow the current labels shown in repository Settings → Pages.

## Demo flow (about five minutes)

1. Frame the fictional grocery customer problem.
2. Filter the sample feedback and run the analysis.
3. Inspect the comments behind a theme.
4. Review and edit the human hand-off draft.
5. Discuss validation, governance and business KPIs.

## Important limitations and interview transparency

- All feedback is invented. It is not Tesco data and does not imply any claim about Tesco's actual performance.
- This is an independent concept prototype, not a Sprinklr product demonstration.
- The analysis uses deterministic rules to simulate an AI-assisted workflow. It does **not** call a live LLM or connect to Tesco systems.
- The prototype makes no external network calls and requires no API keys.
- Before a production build, validate the use case and access permissions; connect approved sources; ground generated insights in source records; evaluate against human-reviewed examples; and retain human approval for consequential decisions.

## Suggested measures

- Time to identify a recurring issue
- Investigation and resolution time
- Repeat contacts and customer outcomes
- Evidence coverage and factual accuracy
- Human correction / escalation rate
- Adoption by customer-care and operations teams

## Repository structure

```text
tesco-customer-signal-ai/
├── index.html
├── README.md
├── LICENSE
└── .nojekyll
```

## License

The code in this repository is provided under the MIT License. The Tesco name is used only to describe a fictional interview scenario; this project is not affiliated with or endorsed by Tesco or Sprinklr.
