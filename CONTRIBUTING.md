# Contributing

This repository holds the ACPE 2026 Track C course materials. Contributions
are credited through Git history, so please follow these steps to make sure
your work is attributed to you.

## Before you start

1. Use **your own GitHub account**, and make sure the email in your Git config
   is linked to it (GitHub → Settings → Emails):

   ```bash
   git config --global user.name  "Your Name"
   git config --global user.email "you@example.com"
   ```

2. Ask the repository owner to add you as a collaborator, then work on a
   branch and open a pull request.

## Where things go

- `pre-course/`: pre-course reading and the Google Colab setup guide
- `slides/`: lecture slides. Text-based slides (Quarto `.qmd` or Markdown)
  let Git attribute every line. If you use PowerPoint, also add a PDF export.
- `labs/`: Colab notebooks. Clear all outputs before committing
  (Edit → Clear all outputs) to keep changes readable.

## Data and privacy

Only commit **synthetic or publicly available, de-identified** example text and
data. Never commit real patient records, clinical notes, or safety reports,
and never commit API keys or tokens.

## Co-authored work

If you wrote something together with another person, credit both of you by
adding a trailer at the end of the commit message:

```
Add lab exercise

Co-authored-by: Name <their-github-email@example.com>
```

## Getting listed as a contributor

After your pull request is merged, a maintainer will comment:

```
@all-contributors please add @your-username for content, tutorial
```

Common types: `content` (slides/text), `tutorial` (labs), `doc` (guides),
`code`, `review`, `ideas`, `talk` (teaching a session).
Full list: https://allcontributors.org/docs/en/emoji-key
