---
title: "Beginnings"
header:
  video:
    id: JSBr8Thk6fU
    provider: youtube
categories:
  - Layout
  - Uncategorized
tags:
  - video
  - layout
---

This post should display a **header with a responsive video**, if the theme supports it.

## Settings

| Parameter  | Required     | Description |
|----------  |---------     | ----------- |
| `id`       | **Required** | ID of the video |
| `provider` | **Required** | Hosting provider of the video, either `youtube` or `vimeo` |

### YouTube

To embed the following YouTube video at url `https://www.youtube.com/watch?v=XsxDH4HcOWA` (long version) or `https://youtu.be/XsxDH4HcOWA` (short version) into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="XsxDH4HcOWA" provider="youtube" %}{% endraw %}
```

{% include video id="XsxDH4HcOWA" provider="youtube" %}
