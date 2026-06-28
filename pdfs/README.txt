PDFs FOLDER — where your documents go
=====================================

Drop your real documents in this folder, then link them from the site.
Anything in public/ is served from the site root, e.g.:

  public/pdfs/bsc-thesis-stf1434.pdf   ->   https://chalakafernando4.github.io/pdfs/bsc-thesis-stf1434.pdf

Suggested files to add:
  - cern-summer-student-report.pdf      (CERN/ATLAS technical report)
  - cern-final-presentation.pdf         (summer student final talk slides)
  - bsc-thesis-stf1434.pdf              (your BSc thesis)
  - thesis-defence-slides.pdf
  - teaching/  (a subfolder for tutorial sheets, if you want to share them)

Where to link them:
  1. Research projects: edit the `links:` block in the matching file in
     src/content/projects/*.md   (instructions are in each file)
  2. Publications page: edit the arrays at the top of src/pages/publications.astro
  3. Teaching resources: see the TODO comment in src/pages/teaching.astro

Your CV goes in the separate folder:  public/cv/  (replace the placeholder PDF there).

NOTE: Do not commit private or sensitive documents — everything in public/ is, well, public.
