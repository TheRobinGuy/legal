# legal

Privacy policies (and later any terms) for every app published by Seanchas, in one place.

The Play Console and the App Store both need a public privacy policy URL for each app. Rather than a website per app,
this one public repo is served by GitHub Pages, with a folder per app:

| App | Folder | Policy URL | Status |
| --- | --- | --- | --- |
| Camino Diary | [`camino-diary/`](camino-diary/) | `/camino-diary/privacy/` | Draft |
| Wild Swim Log | | | Not started |
| Line of Fire | | | Not started |

## Rules

- **One policy per app.** Each must match that app's Play Data safety form and App Store privacy labels, and the apps
  collect different things. Shared wording is fine; a shared policy is not.
- **Write what the app does today**, not what it might do. When an app starts sending data somewhere new (crash
  reports, purchases, sync), the policy changes in the same release. Each policy marks the sections that must change
  with HTML comments (`<!-- WHEN ... -->`), which don't show on the page.
- **Stable URLs.** Each page sets its `permalink` in front matter, so the URL never depends on the file name. The URL
  is baked into the app and its store listing; don't change it.
- **Plain language**, short sentences, no legal boilerplate the app doesn't need.
- **Every change is a commit**, and each policy's "Last updated" date changes with it. The git history is the record of
  what each version said.

## Publishing

GitHub Pages builds the Markdown with Jekyll (Settings → Pages → Deploy from branch `main`, folder `/`). Pages from a
public repo is free.

Before an app's URL goes into the app or a store listing:

1. Fill every `TODO` in its policy and remove the draft notice.
2. Set the "Last updated" date.
3. Ideally put a custom domain in front of the site first (Settings → Pages → Custom domain, plus a `CNAME` file),
   so the hosting can move later without changing a URL inside a shipped app.
