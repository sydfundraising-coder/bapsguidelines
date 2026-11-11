# BAPS Australia Seva Library

Static portal for seva Roles & Responsibilities and Guidelines.

## Publish on GitHub Pages
1. Create a new public repository (e.g. `seva-library`) on github.com.
2. Upload everything in this folder (index.html, .nojekyll, the files folder) via "Add file > Upload files".
3. Settings > Pages > Source: "Deploy from a branch", Branch: main, folder: / (root). Save.
4. After about a minute the portal is live at https://<your-username>.github.io/seva-library/

## Add or update a document
- Put the .docx (or .pdf) in files/ and a PDF copy with the same name for in-browser viewing.
- Add one line to the DOCS list near the bottom of index.html:
  {"s":"Shayona","k":"R","t":"Document title","v":"v1.0","view":"files/Name.pdf","dl":"files/Name.docx","ext":"DOCX","p":4,"kb":120}
  s = seva group, k = "R" (Roles & Responsibilities) or "G" (Guideline), p = pages, kb = file size.
- To replace an existing document, upload the new file with the same name.
