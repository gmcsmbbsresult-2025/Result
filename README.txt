UNIVERSITY OF KASHMIR-STYLE RESULTS PORTAL (UNOFFICIAL REPRODUCTION)

Files:
- index.html: search page
- result.html: individual result page
- style.css: styling
- app.js / result.js: search and result-page logic
- results.json: extracted records from the provided CollegeResult PDF

LOCAL TESTING:
Do not open index.html directly as a file because browsers may block fetch() for results.json. Run a local web server from this folder, for example:
  python -m http.server 8000
Then open http://localhost:8000

FREE HOSTING:
Upload these files to a GitHub repository and enable GitHub Pages. Keep all files in the published root folder.

IMPORTANT PRIVACY / ACCURACY:
This is an unofficial replica and is not affiliated with or endorsed by the University of Kashmir. Records are extracted automatically from a provided PDF and must be verified against the original before use. The static JSON file is public to anyone who can access the website; do not publish private or restricted student data. For confidential records, use a backend with authentication and access controls.

Subject marks are shown in the same compact notation used in the source PDF because the precise meaning of each comma/semicolon component should be confirmed before relabeling it as theory/practical/internal marks.
