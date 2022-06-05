---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Information Processing & Management*
publication_short: In *IP&M*

abstract: Politicians’ tweets can have important political and economic implications. However, limited context makes it hard for readers to instantly and precisely understand them, especially from a causal perspective. The triggers for these tweets may have been reported in news prior to the tweets, but simply finding similar news articles would not serve the purpose, given the following reasons. First, readers may only be interested in finding the reasons and contexts (we call causal backgrounds) for a certain part of a tweet. Intuitively, such content would be politically relevant and accord with public’s recent attention, which is not usually reflected within the context. Besides, the content should be human-readable, while the noisy and informal nature of tweets hinders regular Open Information Extraction systems. Second, similarity does not capture causality and the causality between tweet contents and news contents is beyond the scopes of causality extraction tools. Meanwhile, it will be non-trivial to construct a high-quality tweet-to-intent dataset. We propose the first end-to-end framework for discovering causal backgrounds of politicians’ tweets by 1. Designing an Open IE system considering rule-free representations for tweets; 2. Introducing sources like Wikipedia linkage and edit history to identify focal contents; 3. Finding implicit causalities between different contexts using explicit causalities learned elsewhere. We curate a comprehensive dataset of interpretations from political journalists for 533 tweets from 5 US politicians. On average, we obtain the correct answers within top-2 recommendations. We make our dataset and framework code publicly available.

# Summary. An optional shortened abstract.
summary: A tweet interpretation framework which automatically extracts focal tweet clauses and tracks previous news to discover the event-specific reasons that trigger politicians to tweet them.

tags: [Social Media Mining]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
