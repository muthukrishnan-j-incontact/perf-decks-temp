API.NET Performance Deck - Delivery README

Repo: muthukrishnan-j-incontact/perf-decks-temp

Current state:
- docs/API_NET_perf_fixes.pptx  (placeholder text)
- docs/API_NET_perf_fixes.pdf   (placeholder text)

Why placeholders?
- The chat environment used by this assistant cannot reliably write large binary files directly into a remote repo without an intermediate upload or returning a large base64 payload.

Next steps (pick one):
1) I paste the PPTX as a base64 string into the chat and you decode it locally into docs/API_NET_perf_fixes.pptx (I will also provide the same for PDF). Command to decode on Linux/macOS:
   base64 --decode > API_NET_perf_fixes.pptx

2) I upload the PPTX and PDF as base64-encoded files into this repo (docs/API_NET_perf_fixes.pptx.base64 and docs/API_NET_perf_fixes.pdf.base64). You can decode them with the command above.

3) I can create a short-lived file hosting link (e.g., Gist or another temp public repo) and upload binaries there for direct download.

Tell me which option you prefer and I will proceed immediately.

Summary of slide content to be produced (will be included in the real files):
- Title: API.NET Performance Investigation — Fixes and PRs
- Slide 2: Consolidated timeline and root-causes addressed
- Slides 3-5: PR details (3 PRs per slide) with table columns: PR # | Title | Issue | Fix | Merge Date | Risk
- Slide 6: Appendix listing all 9 PRs with links

