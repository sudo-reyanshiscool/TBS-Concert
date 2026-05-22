# TBS End of Year Concert Programme

Static host for the TBS End of Year Concert programme (14 May 2026), designed for QR code access. Hitting the root URL redirects straight to the PDF.

## Updating the PDF

1. Replace `programme.pdf` in the repo root with the new file (keep the same filename).
2. Commit and push to `main`:
   ```sh
   git add programme.pdf
   git commit -m "update: programme pdf"
   git push
   ```
3. Vercel auto-deploys on push.

## Live URLs

- Site: https://tbs-concert.vercel.app/
- Direct PDF: https://tbs-concert.vercel.app/programme.pdf

(URLs will be updated after the first deploy if the project name differs.)
