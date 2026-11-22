# Post template

Not part of the site build. To write a new post:

1. Copy `post.md` to `src/content/posts/<slug>.md` (the filename becomes the URL: `/posts/<slug>`).
2. Fill in `title`, `description`, `pubDatetime` and `tags`.
3. Write the post. Keep `draft: true` until it is ready, then set it to `false`.
4. Commit and push to `main`. GitHub Actions deploys the site.

Preview locally with `npx pnpm@11.3.0 run dev`.
