---
# Copy this file to src/content/posts/<your-post-slug>.md and fill it in.
# Required: pubDatetime, title, description. Everything else is optional.

title: Your post title
description: One or two sentences shown in post lists, search results and link previews.
pubDatetime: 2026-01-01T12:00:00Z # publish date (UTC). Future dates are hidden until then.
# modDatetime: 2026-01-02T12:00:00Z # set when you update the post
author: turtleduckiee # defaults to the site author if omitted
tags:
  - others # lowercase, one or more
featured: false # true = shown in the Featured section on the home page
draft: true # true = not published; set to false when ready
# ogImage: ../../assets/images/my-image.png # social preview image (otherwise auto-generated)
# canonicalURL: https://example.com/original-post # only if cross-posting
# hideToc: false # true = hide table of contents
# hideEditPost: false # true = hide the "Edit page" link
---

Intro paragraph. Say what the post is about in a sentence or two.

## Headings

Headings (`##` and below) automatically build the table of contents. The post title is already an `h1`, so start at `##`. Don't add your own "Table of contents" heading.

## Text formatting

Regular text with **bold**, _italic_, ~~strikethrough~~, `inline code` and a [link](https://example.com).

> A blockquote.

- Bullet one
- Bullet two

1. Numbered one
2. Numbered two

## Code

```ts
const greeting: string = "hello";
console.log(greeting);
```

## Images

Put images in `src/assets/images/` and reference them relatively:

```md
![Alt text](../../assets/images/my-image.png)
```

## Conclusion

Wrap up, link related posts, say what's next.
