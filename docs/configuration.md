---
title: Configuration
layout: default
nav_order: 2
nav_exclude: true
---

# Configuration
{: .no_toc }


Just the Docs has some specific configuration parameters that can be defined in your Jekyll site's _config.yml file.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


View this site's [_config.yml](https://github.com/pmarsceill/just-the-docs/tree/master/_config.yml) file as an example.

## Search enabled

```yaml
# Enable or disable the site search
search_enabled: true
```

## Aux links

```yaml
# Aux links for the upper right navigation
aux_links:
    "Just the Docs on GitHub":
      - "//github.com/pmarsceill/just-the-docs"
```

## Color scheme

```yaml
# Color scheme currently only supports "dark" or nil (default)
color_scheme: "dark"
```
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>