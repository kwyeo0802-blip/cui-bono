# Cui Bono V6 — Deal-first, research-first

**NEW editorial sequence:** The Deal → The Acquirer → The Target → The Strategic Connection → Why Buy, Why Now → The Economics → Cui Bono Verdict.

The studio now requires **evidence, counterargument, and beneficiary lens in every one of seven stages**, plus an explicit three-part strategic connection map. The public article shows both the map and the evidence/challenge panels.

**IMPORTANT MIGRATION WARNING:** V5 articles use a different seven-stage order. Existing drafts must be exported as a JSON backup from the old Studio, then restructured and retitled *manually* in V6 before publishing. V6 uses a separate browser storage key.

# Cui Bono V5 — English-only website + private writer studio

Start with **使用与研究教程-中文.md** if you want a step-by-step Chinese course, or **ARTICLE-TEMPLATE-EN.md** for writing entirely in English.

## Files you manage

- `index.html` — Public responsive M&A journal.
- `content.js` — Published story content and writer profile.
- `images/` — Optional, author-provided photography and charts. Includes an original conceptual example chart.
- `studio.html` — Private English writer studio. **Do not upload it publicly.**
- `DEAL-RESEARCH-LOG.csv` — Research evidence log, including dated sample rows.
- `ARTICLE-TEMPLATE-EN.md` — Seven-stage English writing framework with the mandatory Cui Bono benefit test.

## Add an image to an article

1. Copy your authorized picture into `images/`, e.g. `images/my-chart.webp`.
2. Open `studio.html`, choose **My deals** and the correct article.
3. For the cover, fill **01B / Article photography → Cover image file path** with `images/my-chart.webp`; include alt text and a caption/credit.
4. For a chapter figure, scroll to **Stage 01–07 → Optional image in this chapter**, paste the same format, and include alt text/caption.
5. Click **Export content.js**; move the downloaded file into this folder and replace the older one.
6. Refresh `index.html` to preview. You must keep the image file in `images/`. The editor cannot move files in your file system.
7. When publishing, upload `index.html`, `content.js`, and the used image files under `images/` to your host; **not** `studio.html`.

## How publishing works

The writer studio stores drafts in your browser, not on a server. Exporting downloads a new content file; it does not change the public website automatically. Back up regularly from **Publish & backups**. The public site does **not** automatically pull current merger news.

To host on GitHub Pages, see https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site .

## About the research examples

Deal facts shown are last reviewed 2026-11-06. Any later publication should re-check whether deals have closed or terms changed, starting with the company's own IR pages and SEC EDGAR. Management synergy forecasts are labeled forecasts, not realized results. This is educational research, not investment advice.

## Cui Bono publication rule (new in V4)

The private studio requires a Cui Bono answer for every one of the seven narrative stages. It also requires a main beneficiary verdict, a buyer shareholder view, a target shareholder view, identification of cost bearers, and an evidence/revision test. You cannot mark a new article published or export published stories when these fields are missing.

When upgrading from V3, open your previous Studio, choose **Publish & backups → Download JSON backup**, then import that file into the new `studio.html` if you have personal edits to preserve. Existing V3 stories that lack Cui Bono fields must be completed before publishing. The new Studio uses a separate local-storage namespace, so it does not overwrite V3 drafts. The public website is in English; this package includes an optional Chinese learner guide.

Names and sample analysis are illustrative and need ongoing source verification; this package is not connected to a live news service.

## New in V5
You can now set the home-page photographic cover from **Writer profile → HOME PAGE COVER / CUSTOM PHOTOGRAPHY**, using the same `images/filename.webp` workflow. See **FIRST-LESSON-中文.md** for a full guided tutorial. You can try `images/sample-home-cover.svg` and clear it to restore the original cover.
