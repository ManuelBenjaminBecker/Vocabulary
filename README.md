# Australia Vocab Sprint

A responsive, browser-only German-to-English vocabulary quiz for students, ready for GitHub Pages.

## Features

- Student name entry screen
- 50 German prompts with free-text English answers
- 30-minute countdown timer
- One canonical answer per prompt: capitalization and extra whitespace are ignored, while alternate spellings and synonyms are marked wrong
- Incorrect words are repeated automatically until answered correctly
- Final first-attempt accuracy, elapsed time, total answer count, and corrections
- Responsive, accessible layout
- No build step or external dependencies; student name and quiz state are not sent or saved

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Open the Pages URL shown on the settings page after deployment finishes.

The site entry point is `index.html`.

## Vocabulary source note

The 50 prompts are based on the Australia-topic word list discussed in the conversation. The linked textbook pages were not directly verified, so check the words and exact forms against the textbook's official vocabulary section before using the quiz as a formal assessment.
