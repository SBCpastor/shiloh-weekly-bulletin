SHILOH BAPTIST CHURCH — WEEKLY INTERACTIVE BULLETIN

FILES
index.html   Interactive booklet viewer
page-1.jpg ... page-8.jpg   Individual bulletin pages
bulletin.pdf   Downloadable version

ONE-TIME SETUP (free GitHub Pages hosting)
1. Sign in to GitHub (or create a free account).
2. Create a PUBLIC repository named shiloh-weekly-bulletin. Public means all uploaded files are visible to anyone; upload only public bulletin content.
3. Upload ALL the files in this folder to the root of the repository, not the ZIP itself.
4. In repository Settings > Pages, under Build and deployment choose Deploy from a branch; select main and /(root), then Save.
5. Wait for GitHub to show the published site URL. Usually: https://YOUR-USERNAME.github.io/shiloh-weekly-bulletin/
6. In Squarespace, add a Code Block with:
   <iframe src="https://YOUR-USERNAME.github.io/shiloh-weekly-bulletin/" title="Shiloh Weekly Bulletin" style="width:100%;height:850px;border:0" loading="lazy"></iframe>
   Replace YOUR-USERNAME with your GitHub username. Check mobile view and adjust height as needed.

EACH WEEK
1. Optimize the new bulletin PDF (or have ChatGPT prepare a new set of pages).
2. Replace page-1.jpg through page-8.jpg and bulletin.pdf in the SAME GitHub repository, keeping their names. Changes will publish automatically, and Squarespace code remains unchanged.
3. IMPORTANT: This example viewer expects EXACTLY eight pages. For a bulletin with a different number of pages, update the number 8 in index.html: Array.from({length:8}...)
4. Update the date shown in the header of index.html (or remove the date for zero weekly HTML changes).

NOTES
- This uses the free open-source page-flip JavaScript library via jsDelivr CDN. Internet access to jsDelivr is required.
- GitHub Pages public hosting is free for public repositories, subject to GitHub policies and service limits. It is not intended for confidential files.
- This does NOT automatically read the Google Drive PDF. It is a different hosting workflow.
- The original bulletin page images are downsampled for faster mobile loading.
