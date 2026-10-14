WitWarp Free PYQs setup
=======================

Files:
- free-pyqs.html: exam category/year selection page.
- index-insert-snippet.html: small snippet for adding the Free PYQs tab above the Notes section on the homepage.

IMPORTANT: PDFs were not provided, so no question-paper PDFs are included. The page lists years 2020–2025 and checks whether a PDF exists before starting a download.

To publish:
1. Upload free-pyqs.html to the repository root beside index.html.
2. Open index-insert-snippet.html and copy its snippet into index.html immediately before:
   <section class="wrap section" id="notes">
3. Commit both files to GitHub.
4. Upload each real PDF using this exact path pattern:
   pyqs/<exam-slug>/<year>.pdf

Exam slugs:
SSC CGL      ssc-cgl
SSC CHSL     ssc-chsl
SSC CPO      ssc-cpo
SSC GD       ssc-gd
SSC MTS      ssc-mts
SSC STENO    ssc-steno
RRB GROUP D  rrb-group-d
RRB NTPC     rrb-ntpc
UPSC CDS     upsc-cds

Example: pyqs/ssc-cgl/2024.pdf

The links will show a message until the corresponding PDF is uploaded. Only upload PDFs you have the right to distribute.
