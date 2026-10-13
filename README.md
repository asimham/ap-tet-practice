# AP TET bilingual practice portal

Static GitHub Pages site. Includes an *illustrative* concept-anchor question bank (not 3,000 unique questions, not official SCERT chapter-by-chapter coverage). Do not use as a high-stakes official assessment without editorial review.

## Deploy
1. Create a GitHub repository called `ap-tet-practice` (or use a subdirectory of an existing Pages repository).
2. Upload the contents of this folder to the repository root.
3. In GitHub > repository **Settings > Pages**, set **Build and deployment > Source: Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Your URL is `https://YOUR-USERNAME.github.io/ap-tet-practice/`. For an existing `YOUR-USERNAME.github.io` repo, deploy as a subfolder `ap-tet-practice/` and navigate to that folder URL.

## Add questions
Edit `data/questions.json`. Each question needs a unique string `id`, `subject` (TEL/CDP/BIO/MATH/PHY/ENG), `question_en`, `question_te`, four `options` strings, `answer` (0,1,2,3 index of correct option), and `explanation_en`, `explanation_te`. Optional `class`, `chapter`, `scert_reference` are recommended. Verify all answer keys and SCERT mappings manually. App rejects duplicate IDs and cannot create 500-question tests unless 500 unique IDs are present.

## Important limitations
- Results and in-progress answers are saved only in the browser's local storage. No account login or cross-device sync.
- Question bank and answer keys are public in a static GitHub Pages site. This is not cheating-resistant.
- Users can print results or save as PDF from their browser.
- Telugu font rendering depends on fonts available on the user's device/browser.
- Uploaded JSON is temporary for that browser tab session; commit questions.json to distribute a new bank to everyone.
