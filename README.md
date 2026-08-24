# Agentic AI Requirements Toolkit — static site

Deploy: push this folder to a GitHub repo, enable GitHub Pages (Settings > Pages > Deploy from branch, root), or drag the folder into Cloudflare Pages. No build step.

Structure:
- index.html               — landing page (both collections)
- frameworks/*.html        — one page per framework (9), permanent URLs
- templates/*.docx         — downloadable working templates (CC BY 4.0)
- style.css

Before launch (open items):
1. ~~Replace placeholder domain~~ Done: citations point to https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/.
2. ModernAnalyst: obtain written editor confirmation of your right to relicense frameworks F-01..F-05 under CC BY 4.0 before Zenodo deposit.
3. Employer outside-activity preclearance for a public professional site.
4. Zenodo: one record per framework, ORCID 0009-0002-5676-5590, CC BY 4.0, isSupplementTo = source article URL; then replace "DOI pending" on each page.
5. Add Plausible or GoatCounter snippet to the shell (one line in <head>).
6. Insert the CC BY line + disclaimer inside both .docx templates (currently pages only).
