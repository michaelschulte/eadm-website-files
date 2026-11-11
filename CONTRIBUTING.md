# Adding files to the EADM website

This repository holds the PDFs served under `https://eadm.eu/files/`.
The folder path is the web address: `2026/11/report.pdf` is published at
`/files/2026/11/report.pdf`. Everything below is done in the browser on
github.com; you do not need to install anything.

Every push to this repository rebuilds the website, so an upload is
live a few minutes later.

## Adding a newsletter

### 1. Name the PDF

Name the file after the month of the issue:

```
EADM-Newsletter-YEAR-MONTH.pdf
```

for example `EADM-Newsletter-2026-11.pdf` for the November 2026 issue.
Use the two-digit month and no spaces.

### 2. Upload it

1. Go to <https://github.com/michaelschulte/eadm-website-files> and
   sign in.
2. Open the folder for the year and month (e.g. `2026/11/`).
   If that folder does not exist yet, upload the file from the top
   level and type the folder path in front of the file name.
3. Choose **Add file → Upload files** and drag in the PDF.
4. Describe the change in a sentence, e.g. *Add the November 2026
   newsletter*, and choose **Commit directly to the main branch**.

You do not need to edit the newsletter archive or write an announcement
for the News page: when the website picks up a correctly named
newsletter, it adds the archive entry, a cover image and a News post by
itself.

## Other files

Upload them the same way, into the `YEAR/MONTH/` folder of the upload
date. Avoid spaces in file names. Uploading a file only publishes it;
to link it from a page, tell Michael where it should appear.

Not sure about something? Ask Michael before uploading.
