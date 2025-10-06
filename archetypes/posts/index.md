---
### Required / basic
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'    # auto-generate title from folder name
date: '{{ .Date }}'                                             # sets the creation date

### Draft / publication control
draft: true                                          # mark new posts as drafts by default

### SEO / metadata
description: ""                                       # short description or excerpt for meta tags

### Feature image / hero
# featureimage: "images/cover.jpg"                      # path to a feature image (optional)
# featureimagecaption: "An illustrative cover"          # caption for the feature image
# showHero: true                                        # whether to show the hero image

### Content display controls
# showDate: true                                         # show the date in the article
showReadingTime: true                                  # show estimated reading time
# showTableOfContents: false                              # whether to show a TOC in the article

### Taxonomy fields
tags: []                                               # tags for this blog post
# series: []                                             # series name(s) if you group posts
# series_order: 1                                        # ordering in series, if used

### Comments / sharing
### Available values are: “bluesky”, “email”, “facebook”, “line”, “linkedin”, “mastodon”, “pinterest”, “reddit”, “telegram”, “twitter”, and “whatsapp”.
# showComments: false                                    # whether to include comments section
# sharingLinks: ["twitter", "linkedin", "facebook"]      # which social links to show. 

### Edit link (if your config enables showEdit)
# editURL: ""                                            # base URL for “edit this page”
# editAppendPath: true                                   # whether to append the page path to editURL
---

Start writing your blog post in Markdown here.

Use images placed in the `images/` folder next to this file, e.g.:

![Caption](images/photo1.jpg)
