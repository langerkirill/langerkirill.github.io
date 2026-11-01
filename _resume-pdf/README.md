# Resume PDF source

`resume-print.html` is the source for `../Resume-2026.pdf`. GitHub Pages does not publish
folders that start with an underscore, so this folder stays off the live site.

To regenerate after editing the HTML (needs Node and Playwright with Chromium):

    node _resume-pdf/make-pdf.js "$PWD/_resume-pdf/resume-print.html" Resume-2026.pdf
