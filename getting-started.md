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
protected function blockCodeContinue($Line, $Block)
{
  if ($Line['indent'] >= 4) {
    if (isset($Block['interrupted'])) {
      $Block['element']['text']['text'] .= "\n";

      unset($Block['interrupted']);
    }

    $Block['element']['text']['text'] .= "\n";

    $text = substr($Line['body'], 4);

    $Block['element']['text']['text'] .= $text;

    return $Block;
  }
}
```
