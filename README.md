# Leadership as a Second Language

Everything here can be done on github.com in your browser. No installs needed.
Cloudflare rebuilds the site automatically about a minute after every change you save ("commit").

## Publish a new post
1. On GitHub, open `drafts/_template.md` and copy all of its text.
2. Go to the `src/writing` folder, click **Add file > Create new file**.
3. Name it with dashes and `.md`, e.g. `the-accent-phase.md` (this becomes saeedsabeti.com/the-accent-phase/).
4. Paste the template, fill in the top section (title, kind, number, date, summary), write the post.
5. Click **Commit changes**. The site updates in about a minute.

`## ` makes a subheading. A line starting with `> **Try this week:**` becomes the exercise box.
`kind` can be Field Note, Essay, or Conversation (only Field Notes need a number).

## Publish a draft
Open the file in `drafts/`, copy its text, create a new file in `src/writing/` with the same name, paste, set the date, and commit. Then delete the draft copy.
`principles-create-gravity.md` is ready as Field Note 2.

## Change site-wide settings (click the file, then the pencil icon)
- `src/_data/site.json`: title, description, domain, Buttondown username (turns on the subscribe form).
- `src/_data/phrases.json`: the translated phrases on the home page.
- `src/about.md`: the About page.
