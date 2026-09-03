# Investor brief, retired

The living document is now at **https://letafricabuild.com/brief**, served from
the website's own repository (`cliqueengagements/lab-site`, `public/brief/`).

`index.html` here is a signpost that forwards to it.

## Why it moved

Two copies of the same document drift. On 2026-09-03 this one was three weeks
stale: it still said the sponsor-match pool was $20K when it was $38K, listed
"five revenue streams" and described four, and gave the Founding Circle entry as
$10,000 in one section and $5,000 in another.

It also loaded its fonts from Google, which the website no longer does.

## What is still here

`brief-2026-09-final.html` is the last full version served from this repository,
kept so the history is readable. **Do not edit it.** Edits go to `lab-site`.

## Editing the brief now

    cd ~/lab-site
    # edit public/brief/index.html
    npm run typecheck        # checks the site, not the brief
    LAB_PUBLISH=1 npm run build

The brief is unlisted: it carries a noindex tag and `/brief` is disallowed in
robots.txt, because the document says "Confidential for named recipient" on
every page and a search result pointing at it would contradict that.
