---
layout: links                 # ← tells Jekyll to use your new layout
title: resources (Coming Soon)
description: A list of resources I come across that are useful to me and maybe others pertaining to research
permalink: /resources/            # nice, short URL (optional but common)

nav: true                     # show in the top-right navbar
nav_order: 7                  # smaller = farther left; adjust as you like

links:
  - category: "Research Tools"
    icon: "bi-journal-text"   # Bootstrap Icon (optional)
    items:
      - name: "Google Scholar"
        url: "https://scholar.google.com"
        description: "Search scholarly literature"
      - name: "arXiv"
        url: "https://arxiv.org"
        description: "Pre-print repository"

  - category: "Machine-Learning Libraries"
    icon: "bi-cpu"
    items:
      - name: "PyTorch"
        url: "https://pytorch.org"
        description: "Popular deep-learning framework"
      - name: "TensorFlow"
        url: "https://www.tensorflow.org"
        description: "Google’s end-to-end ML platform"

  - category: "Productivity"
    icon: "bi-lightning-charge"
    items:
      - name: "Overleaf"
        url: "https://www.overleaf.com"
        description: "Collaborative LaTeX editor"
      - name: "Notion"
        url: "https://www.notion.so"
        description: "All-in-one notes & project space"
---

You can write **regular Markdown** here if you want an intro paragraph.
Anything below the front-matter appears above the card grid on the page.
