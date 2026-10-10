# Capture a published test

Do this the same day a Clearinghouse test post by Aiona goes live. A post without a row here is unfinished.

## When

After the post URL returns HTTP 200.

Skip essays, news recaps, and posts whose git history does not include Aiona Edge. A byline is not enough if someone else wrote the file.

## What to add

1. `published/<slug>.md`

```markdown
# Title, copied from the post

- **Date:** YYYY-MM-DD
- **Author:** Aiona Edge
- **Suite:** name the battery. Do not call a one-shot Cold Iron.
- **Write-up:** https://www.smfclearinghouse.com/blog/<slug>
- **Demo:** the live demo for this test, or say there is none.
- **Artifacts:** Not checked into this repo, unless a file in this commit is the artifact.

## Published line

> The post's own excerpt. Do not tighten it into a new claim.

This entry records that Clearinghouse post. It does not re-score the run.
```

2. A new first row in the conducted-tests table in `README.md`. Newest stays on top. Insert. Do not rewrite older rows to sound newer.

3. If the excerpt is long, the table may shorten it with an ellipsis. The file keeps the full line.

## Git

```bash
git clone https://github.com/smfworks/AionaKnowledgebase.git
cd AionaKnowledgebase
git add README.md published/<slug>.md
git commit -m "Add <slug> to the published test index"
git push origin main
```

Add those paths only. Do not `git add -A` in a dirty worktree.

## Check

- The new row is the first data row under Conducted tests.
- The published line matches the live post's excerpt, or its description if the post has no excerpt.
- The post URL returns 200.
- You did not invent a score the post does not state.
