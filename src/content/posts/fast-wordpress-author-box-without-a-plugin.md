---
title: Fast WordPress Author Box Without A Plugin
pubDate: 2022-04-23
categories:
  - website-publishing
  - how to
slug: fast-wordpress-author-box-plugin
description: |
  With WordPress v6, sites can begin trimming down all that bulk; as the latest version of WordPress sets the foundation.
  author: Tyler Bishop
image:
  url: /images/herobox.png
  alt: wordpress authorbox
preview: /images/herobox.png
tags:
  - wordpress
wordcount: 1000
author: Tyler Bishop
type: article
---

Plugins and themes tend to be the culprits of most site speed issues that publishers have using WordPress.

In most cases, sites have no idea what a plugin actually does or adds to their WordPress site or what files it may burden your visitors with loading.

With WordPress v6, sites can begin trimming down all that bulk; as the latest version of WordPress sets the foundation for eliminating even themes themselves ... seriously.

Caveat: You need V6.0+ to do this and a block theme (Twenty-Twenty-Three will work). It will only really benefit if you aren't using a page builder (i.e. Elementor) and aren't disabling the block editor or Full-Site Editing (FSE).

## Author Box in WordPress V6 No Plugins

**Step 1:**

**Admin > theme/ site editor > template (or template part\*)** \> then inside the editor, make a group (you can design differently if you prefer and know the block editor well)

![](/images/1669166463.png)

_\*Note: Template is if you want to create a whole page that includes an author box at the bottom that will become the default for posts that you wish to have your author box on. If you simple want to add the author box to an existing post template (ex. the one your using on your posts now, just use template part)_ — I'm doing "part" here.

**Step 2:**

Next, set the width of the group container that you want. Usually, your page already has a general width and alignment you can use as guidance - for my example, I'm using _Wide width_).

Now create a column block of "33/66" inside your group block.

![column blocks](/images/1669166776-1024x507.png)

Next, add an "avatar" block to the left column (don't worry we'll style in a sec), then add two blocks to the right column "post author" and "author biography".

![](/images/1669167030-1024x576.png)

  
Now set the background color of the block to linear-gradient (to be fancy) or whatever your preference might be. Then, add a border width and radius to give it an outline that meets your style preferences.

Radius rounds the corners, and if after it's done you want to adjust the text colors and font sizes, it should be pretty straightforward.

Once you're done making it look nice, save the template part or template.

![](/images/1669167760.png)

**Step 3:**

The box is done. Now, you just have to add the part to your template, and then ensure that the template is the one selected in the posts you want the box to appear on.

This can be done in Bulk by going to Admin>Posts> Select All (top) and editing the default template.

![author box template](/images/1669167942-1024x479.png)

To add the part to a template, go to the site-editing admin area to the left of where you were editing the author box, select templates, and then you'll find the template part as a block you can add to the bottom above the footer (or wherever you want it on the posts).

Done. Goodbye plugins.
