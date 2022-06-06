---
title: "Welcome"
date: 2022-06-06T10:49:17-05:00
draft: true
# weight: 1
# aliases: ["/first"]
tags: ["welcome"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
hidemeta: false
comments: true
description: "First blog post acting as a playground to demo the features of Hugo."
disableShare: true
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
  image: "images/cover.jpg" # image path/url
  alt: "Cover Image" # alt text
  caption: "Cover Caption Text" # display caption under cover
  relative: true # when using page bundles set this to true
  hidden: false # only hide on current single page
editPost:
  URL: "https://github.com/zibbp/blog/content"
  Text: "Suggest Changes" # edit text
  appendFilePath: true # to append file path to Edit link
---

# Welcome

This post is a playground to demo the features of Hugo.

---

## Images

The below image is a raw 14mb image with a resolution of 9335x2400px. It is being downscaled and minimized to webp format for faster loading via a Hugo shortcode.

{{< img src="images/raw.jpg" alt="Screenshot of my terminal" >}}

## Code

Code highlighting using the built-in syntax highlighter.

{{< highlight html >}}

<!doctype html>
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}
