# Eqvaldi Linux — How to update the site

There are only **2 files** you need to edit to push updates to users.

---

## To post new news → edit `NEWS.txt`

Open `NEWS.txt` in the root of the repo and write whatever you want.
It shows up on the **News** page of the website automatically.

## To post a new release → edit `Changelog.txt`

Open `Changelog.txt` in the root of the repo and add the new release at the top.
It shows up on the **Changelog** page of the website automatically.

---

## To publish your changes

After saving your edits, push to GitHub:

```bash
git add .
git commit -m "update"
git push
```

The site rebuilds and goes live automatically. That's it.

---

## Anything else you might want to change

| What | File |
|---|---|
| Site colors | `docs/stylesheets/colors.css` — change the hex values at the top |
| Home page text | `docs/index.md` |
| Download links | `docs/downloads.md` |
| Site name / author | `mkdocs.yml` — first 4 lines |
