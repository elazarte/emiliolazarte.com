# emiliolazarte.com

The source of [emiliolazarte.com](https://emiliolazarte.com/): guides, experiments and notes by **Emilio Lazarte**, a senior data analyst in Brasília, on digital analytics and on using AI well.

Topics include measurement plans and tagging (Google Tag Manager, GA4), data on Google Cloud (BigQuery), dashboards (Data Studio, Power BI), and practical, evidence-checked findings about AI tools.

## Published so far

| Piece | What it is | Link |
|---|---|---|
| **Operating AI** | A practical guide to using AI models, with every claim tagged by strength of evidence and linked to its source | [Read](https://emiliolazarte.com/operating-ai/) · [v2.1, fixed for citation](https://emiliolazarte.com/operating-ai/v2.1/) · [v2.0](https://emiliolazarte.com/operating-ai/v2.0/) |

## Corrections, questions and ideas

Everything here is meant to be checked and improved. Use the forms under [Issues](../../issues/new/choose):

- **Suggest a correction** — something is wrong, outdated, overstated, or didn't hold up in your work.
- **Ask a question** — something is unclear, or you want to know how it applies to your case.
- **Suggest a topic** — something you'd like to see tested or explained.

Corrections are more useful than endorsements.

## How the site is organized

The site is plain HTML, with no build step. Each folder is a page:

```
index.html                 home page
404.html                   "page not found"
operating-ai/index.html    Operating AI, latest version
operating-ai/v2.1/         Operating AI, version 2.1, frozen
operating-ai/v2.0/         Operating AI, version 2.0, frozen
```

Conventions:

- **One folder per piece**, named for its address: `/topic-name/index.html` is served at `emiliolazarte.com/topic-name/`.
- **Guides that change are versioned.** The folder's own `index.html` is always the latest; each release is also frozen in a subfolder (`v2.0/`, `v2.1/`, …) and never edited afterwards, so citations keep working.
- **New pieces are added to the list on the home page**, newest first.

## License

Written content is licensed under [CC BY 4.0](LICENSE.md): you may share and adapt it, including commercially, with credit and a link to the source.

## A personal project

This is a personal site, driven by the author's own curiosity and interest in sharing. What is published here reflects his own views. It is not connected to, reviewed by or endorsed by any organization he works or has worked for, or by their clients, and it is not part of his work for any of them.
