# GPTrive Demo

If this file exists, GPTrive Phase 1.1 upload/apply loop worked.

Expected flow:

1. Upload `gptrive.zip` from GPTrive popup.
2. GitHub Actions picks `.ready.json`.
3. Workflow applies `files/`.
4. Workflow commits result.
5. Workflow removes patch files from `.gptrive/patches/` on success.
