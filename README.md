# DocuMind — Document Intelligence Workspace

A responsive, local-first document organization and evidence-search application. No account or backend required.

## Live demo

After enabling GitHub Pages, open your published site and select **Load demo documents** on the Overview page. The seven fictional technical documents are loaded into browser storage, with three collections. You can also start with an empty workspace.

## Features

- Create collections and import TXT or Markdown documents (up to 300 KB per document)
- Full-text keyword search, document tagging and source excerpts
- Evidence retrieval assistant (keyword retrieval only; **not** a generative AI model)
- Browser-local storage, JSON backup export/import and clear-data controls
- Optional, user-triggered sample data, never automatically added

## Run locally

Open `index.html` in a modern browser. No installation required.

## Publish with GitHub Pages

Upload `index.html`, `styles.css`, `app.js`, `demo-data.js`, `README.md` and the `demo-data/` folder to the **root** of a public GitHub repository. Open **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/(root)` and Save. After publishing, test the live site.

## Recruiter test checklist

1. Click **Load demo documents** on Overview. Expect **7 documents** and **3 collections**.
2. Search for `photolithography`, `calibration`, `authentication`, and `embeddings`.
3. Open search results and review source excerpts.
4. Add your own collection and TXT document.
5. Export a JSON backup; clear data; import the exported backup.

The same data is available as `demo-data/documind-demo-backup.json`. The `demo-data/documents/` folder contains the individual TXT documents.

## Limitations

This static frontend uses localStorage in each browser. It does not sync devices, authenticate users, parse PDFs, run a backend, or connect to a generative AI service. Do not store confidential information.
