---
title: "Instructions"
date: 2020-11-07T21:29:16-07:00
draft: false
toc: true
tags:
  - Instructions
  - Learning
---

Welcome to your new _Hugo_ website!

Hugo parses **markdown** files like this one, and turns them into `html`.
Having an empty line-return between two sentences separates them into
paragraphs. Having no space between lines means content stays in the same
paragraph.

Use **stars** for bold and some _underlines_ for italics.

The rest you can Google. Lol.

# Creating Content

To make a new post type this:

```
hugo new posts/my-new-post.md
```

# Adding Images

So you want some pictures, eh?

![Junior Devs don't know what they're in for.](/images/code-complexity.jpg)

The picture above was added with this line of markdown:

```md
![Junior Devs don't know what they're in for.](/images/code-complexity.jpg)
```

The first bit is the _alt text_, what people will see if the image doesn't load.
It's important to include for handicapped people and such.
The second bit (in the round brackets) is the path to the image, which is stored in the
_static_ folder. You don't need to include the name _static_, but you do need to
have everything after it, so in this case, `images/code-complexity.jpg`.

# Modifying The Site Appearance
