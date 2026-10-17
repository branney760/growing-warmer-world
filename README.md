# Growing in a Warmer World

A climate-connected experimental-design sandbox for introductory, non-majors biology.

## Publish with GitHub Pages (no coding or installation required)

1. Extract this ZIP on your computer. Do not upload the ZIP itself.
2. Sign in at https://github.com and create a new repository named `growing-warmer-world`. Choose Public for the simplest GitHub Free setup. Initialize it with a README if prompted.
3. In the repository, select Add file → Upload files. If the repository is empty, use the “uploading an existing file” link instead.
4. Upload the extracted files directly into the repository's top level: index.html, style.css, app.js, README.md, and .nojekyll. If your file picker hides .nojekyll, the other four files are sufficient for this simple site. Replace the initial README with this one if necessary. Do not upload a containing folder.
5. Commit the uploaded files to the main branch.
6. Open Settings → Pages. Under Build and deployment, select Deploy from a branch. Select main and / (root), then Save.
7. Wait for deployment. Settings → Pages will show the published address and a Visit site button. It usually follows https://YOUR-USERNAME.github.io/growing-warmer-world/ . Copy the actual address shown by GitHub.
8. Open the published site and complete a practice trial. Check a plant pod, finish a trial, revise, and download the notebook and CSV.
9. In your Canvas assignment HTML, replace https://growing-warmer-world.ranney-beverly.chatgpt.site with your actual GitHub Pages address. Students should use the Pages website, not the repository's file listing.

GitHub's current documentation:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## What is included

- index.html — growing bench, notebook, and instructional text
- style.css — responsive biology-blue design
- app.js — simulation, results, browser saving, trial archive, and downloads
- .nojekyll — bypasses Jekyll processing
- README.md — these setup and teaching notes

The three website files must stay together in the same directory. All asset paths are relative, so the simulation works under a GitHub repository path. No build step, API keys, external libraries, or server is required. You can also open index.html locally to try the simulation; browser storage behavior can differ for local files.

## Teaching and student work

Each independent pod contains one plant. Students control temperature, water, light, plants per group, and assignment. Two trials can be compared through the archive. The notebook captures questions, predictions, design reasoning, observations, conclusions, and revisions. Results display individual growth, means, and ranges.

Student notes and trials remain in the current browser's local storage when available. They are not sent to GitHub or Canvas. Students must download and submit their notebooks separately. Work does not move between devices or browsers; moving from the earlier hosted site to this GitHub site also starts separate browser storage. Download previous work first. Students should avoid entering sensitive personal information in notebooks on a shared device.

## Model limits

The fictional seedling model is instructional and is not calibrated to a real crop. All seedlings begin at 3 cm. A curved temperature response is multiplied by water, light, and individual growth-potential factors, with daily variation. There is no mortality, acclimation, nutrient limitation, or temperature–water interaction. See the in-app Research briefing for the formula. These simulated data are not empirical evidence about real crops or global climate trends. No statistical significance test is performed.

## Troubleshooting

- A 404 page: confirm Pages uses main and / (root), and index.html is directly at that location. Allow deployment time.
- Plain text or file listing: use the GitHub Pages address, not the github.com repository address.
- Missing styling or interactions: confirm style.css and app.js are beside index.html with exactly these lowercase filenames.
- An old version: check the Pages deployment status, then refresh the browser.
- Missing notes: return to the same browser, device, and website address. Use downloaded notebooks as your backup.
- The hidden .nojekyll file is not visible: this application also works with standard Pages processing; you may create an empty .nojekyll file using Add file → Create new file.

## Validation

JavaScript syntax, generated trial data, results rendering, design-feedback cases, and preservation of trial history were checked during development. The package's relative asset references and ZIP contents were checked. Visual browser QA was unavailable; review the deployed site before assigning it.
