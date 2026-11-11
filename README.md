# meets-this-weekend-images

Public image host for the carousel slides posted by the Instagram account @meetsthisweekendsa (Meets This Weekend SA).

Buffer schedules the posts and fetches each slide from its public `raw.githubusercontent.com` URL. Everything in this repo is public on purpose.

## Layout

One folder per weekend, named by the date of that weekend's post. Slides are numbered in carousel order:

```
<YYYY-MM-DD>/01.png
<YYYY-MM-DD>/02.png
<YYYY-MM-DD>/03.png
...
```

Example URL:

```
https://raw.githubusercontent.com/Ajohnson123/meets-this-weekend-images/main/2026-11-12/01.png
```

## Rule: never delete files

Do not delete, rename, or move any file once it is pushed. Instagram fetches the image from its URL when a post publishes, so a missing file breaks a scheduled post. Add new folders only.
