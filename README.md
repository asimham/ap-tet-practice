# Teacher Prep Hub — GitHub Pages

Bilingual topic-based practice and 150-question exam simulation using a static website.

## Deploy

Upload **the contents** of this folder to the root of your GitHub repository; enable Settings → Pages → Deploy from branch → main → /(root).

Keep the `data/questions.json` path. No build commands required. Open the site via GitHub Pages, not by double-clicking `index.html` (the fetch requires HTTP).

## Existing question data

This release contains 3,000 **draft** records; these have NOT undergone individual SCERT text edition verification or expert answer checking. Do not describe them as 3,000 verified questions. It does not add copied previous papers. The default filter includes draft items to support personal practice. The **Reviewed only** filter intentionally returns zero until externally checked records have `review_status: "reviewed"`.

## How to approve questions

For each question, review the answer and explanation, check for near duplicates, verify the 2025–26 state textbook class/chapter and linguistic accuracy, record the concrete chapter reference, and only then set `review_status` to `reviewed`. Never mark an entire generated batch reviewed without actual checking. Use the official documents below as reference material.

- https://tet2dsc.apcfss.in/TET-PDF/APTET%20Information%20Bulliten.pdf
- https://tet2dsc.apcfss.in/TET-PDF/PressNote/TET%20%20OCTOBER%202025%20SYLLABUS%20BOOK%20FINAL.pdf
- https://cse.ap.gov.in/textBooksDownloadingPagetitleWise

## Exam structure

150 MCQs: Psychology 30; Language I Telugu 30; Language II English 30; Math 20; Physical Science 20; Biological Science 20. Topic practice supports 10–500 questions where the selected pool is large enough.

The website saves responses and incorrect question IDs locally, without server accounts or analytics. Browser storage may be cleared by the user or device. This is an independent, unofficial study tool.
