ASHWIN K. SESHADRI - PERSONAL WEBSITE (GitHub Pages)
====================================================

Live at: https://akseshadri.github.io/
This is the main, regularly updated site. The IISc page
(http://dccc.iisc.ac.in/aks/aks.html) is a short summary that points here.

FILES INCLUDED
--------------
  index.html                  Landing page (entry point)
  publications.html           Full publications list (filterable)
  group.html                  Research group: current students and alumni
  highlights.html             Research highlights (filterable by theme)
  working_papers.html         Selected working papers / preprints
  teaching.html               Teaching (AS 210 and AS 313)
  opportunities.html          Opportunities for prospective students/postdocs
  photo.jpg                   Profile photograph (used on landing page)
  AS210_2026_syllabus.pdf     Syllabus for AS 210 (linked from teaching page)
  AS313_2026.pdf              Syllabus for AS 313 (linked from teaching page)
  robots.txt, sitemap.xml     Help search engines find every page
  favicon.svg, favicon-32.png, favicon.ico, apple-touch-icon.png
                              Browser-tab and home-screen icons
  aks.html                    Forwards akseshadri.github.io/aks.html to the home page

ROUTINE UPDATES
---------------
  New paper:    add a <li class="pub-item"> at the top of the right year in
                publications.html, renumber, and add a news item in index.html
                (keep about 5-6 news items; drop the oldest).
  New preprint: add a <li class="paper-item"> in working_papers.html.
                Status label: "Under review" (badge-review) while in first
                review, without naming the journal; "In revision"
                (badge-revision) once revisions are requested, adding
                "In revision for <Journal>" to the venue line.
                On acceptance, move it to publications.html with the DOI.
  After any edit, change <lastmod> in sitemap.xml for the pages you touched.

NOTES
-----
  - All pages share the same sidebar navigation and are interlinked.
  - Fonts (Spectral, Fira Sans) load from Google Fonts; the site falls back
    to Georgia / system sans-serif offline.
  - No server-side components; all files are static HTML.
  - The .docx copies of the syllabi are kept for editing; only the PDFs are
    linked from the site.
