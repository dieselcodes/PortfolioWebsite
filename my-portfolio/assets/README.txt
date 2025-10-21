Place your resume PDF in this folder with the filename `resume.pdf`.

- Recommended path: assets/resume.pdf
- If you have a different filename, either rename it to `resume.pdf` or update the <iframe> src and the download links in index.html to match.
- Example (Windows PowerShell):

  Move-Item -Path "C:\Users\danie\Downloads\danielresume2025 (7).pdf" -Destination "d:\git\my-portfolio\assets\resume.pdf"

After placing the file, refresh `index.html` in your browser. Some browsers block embedding local PDFs; if embedding doesn't work, use the Download Resume button which will still serve the file.