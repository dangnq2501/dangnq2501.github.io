# Nguyen Quy Dang — Personal Website

A responsive, research-focused personal website. Built with plain HTML, CSS, and JavaScript: no package installation, build step, framework, tracking, or API keys.

## Preview

Open `index.html` in a browser. For a local server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Files

- `index.html` — all page content, styles, and interactive behavior.
- `resume.pdf` — the September 14, 2026 research CV provided for this project.
- `NguyenQuyDang.bib` — both ICASSP 2026 publications, with paper, PDF, and code links.

## Publish with GitHub Pages

1. Create a public repository named `dangnq2501.github.io` under the `dangnq2501` account, or use it if it already exists. Do not overwrite an existing website without reviewing it first.
2. Upload `index.html`, `resume.pdf`, and `NguyenQuyDang.bib` to the repository root, not inside a nested folder.
3. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. After deployment finishes, the intended address is `https://dangnq2501.github.io/`. This package does not create the repository or publish the site for you.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Before publishing

- Review every biography, role, date, publication, and project description.
- The included CV contains your phone number and email address. Replace or remove it before publishing if you do not want those details public; also remove the Download CV link if you remove the PDF.
- No portrait is included. The geometric research illustration is decorative, not a scientific result or benchmark.
- External links point to the supplied resume's project repositories, the authors' paper PDFs, IEEE, and MBZUAI. Their continuing availability is controlled by those sites.

## Update the website

Edit text directly in `index.html`; its sections have descriptive IDs (`about`, `publications`, `projects`, `experience`, `contact`). Replace `resume.pdf` when your CV changes, and update the footer's content date.

The publications are rendered directly in HTML so that they remain visible without third-party scripts or JavaScript. Keep the visible entries, expandable BibTeX citations, and `NguyenQuyDang.bib` synchronized when adding or changing a paper. This new standalone website does not change the AVITECH profile's BibBase setup.

To use BibBase on this personal site instead, host your bibliography at a public URL, replace the two publication articles with the BibBase embed, and point its `bib` parameter to that URL. See https://bibbase.org/help.

Colors and fonts are controlled by the CSS variables at the beginning of `index.html`. Dark mode is optional and remembered locally. Project filters, the mobile navigation, and citation-copy buttons are progressive enhancements; the core content and links remain available without JavaScript. Copying uses the browser clipboard when available, with text selection as a fallback.

## Sources

- Resume: `Nguyen_Quy_Dang_XTX_AI_Research_CV.pdf`, September 14, 2026, plus the supplied longer resume for the translation project.
- Publication author lists and exact titles: https://thanhle88.github.io/publications/
- RE-LL1: https://thanhle88.github.io/files/ICASSP_2026_Re_LL1_Robust_Block_Term_Decomposition.pdf
- Triple decomposition: https://thanhle88.github.io/files/ICASSP_2026__Robust_Triple_Decomposition.pdf

The RE-LL1 title follows the paper's wording, “Video Background Modeling and Foreground Separation,” rather than the earlier resume's abbreviated wording.
