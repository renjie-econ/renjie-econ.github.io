# Jie Ren — academic website

A lightweight static academic website, migrated from https://jie-ren.weebly.com/ on 29 September 2026.

## Publish on GitHub Pages

Repository: `renjie-econ/renjie-econ.github.io`
Website: https://renjie-econ.github.io/

In repository **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**, and save. Keep HTTPS enabled.

## Edit the website

- `index.html`: biography, research, abstracts, contact details, and links.
- `style.css`: typography, colors, spacing, and mobile layout.
- `jie-ren.jpg`: original portrait.
- `cv-jie-ren.pdf`: public CV download. The 17 November 2026 update uses `cv_JieREN.pdf`, which displays “Sep 2026” in the page header.
- `within-marriage-age-gap.pdf` and `gender-education-gap.pdf`: original paper PDFs downloaded from Weebly.

To replace a PDF or ZIP: open the repository, choose **Add file → Upload files**, upload the updated file with exactly the same filename, and commit to **main**. You do not need to delete the old file first. For example, replace `cv-jie-ren.pdf` to update your CV.

To update biography, paper titles, or publication status: open `index.html`, click the pencil button, edit the text, and commit to **main**. The website updates automatically after GitHub Pages finishes deployment; this can take several minutes. If a PDF filename changes, also update its link in `index.html`. No installation or build is needed. Preview locally with `python3 -m http.server 8765` and open http://localhost:8765.

## Migration notes

The biography, publication list, and working-paper status were migrated from the old website. The work-in-progress list follows the three selected projects in the latest CV, followed by “Marriage, Parenthood and development: cross-country evidence” with Ying Feng. The paper PDFs, coauthor links, and media links were retained during migration. The replication package is hosted locally as `replication-package.zip`, copied unchanged from the original public Dropbox archive on 29 September 2026. Third-party link availability in mainland China varies.

## Mainland China access

The page renders without JavaScript, Google Fonts, external stylesheets, analytics, or CDNs. The portrait, CV, paper PDFs, and replication ZIP are served by the same host as the site. This removes unnecessary external loading dependencies, but cannot guarantee GitHub Pages connectivity from mainland China.

Test the published URL and each PDF without a VPN on both mobile data and home/university broadband. If access is unreliable, keep GitHub as the source and publish the same files to an alternative host with an appropriate custom domain. A custom domain alone does not guarantee connectivity.

References: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site and https://en.greatfire.org/domain/github.io
