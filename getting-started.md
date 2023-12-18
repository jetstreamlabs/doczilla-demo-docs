---
title: Getting Started
description: Welcome to Doczilla
tags:
  - Doczilla
  - welcome
---

[[toc]]

## Welcome to Doczilla {.doc-heading}

```php
/**
 * Check if the given version is in the published versions.
 */
public function isPublishedVersion(string $version): bool
{
  return in_array($version, $this->publishedVersions);
}
```
