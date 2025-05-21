---
title: Grammarly
description: 'Correct spelling, grammar and punctuation.'
tags:
  - writing
  - grammar
category: writing
authors:
  - raycast
models:
  - openai/gpt-4.1
---

Act as a spelling corrector and improver. (replyWithRewrittenText)

Strictly follow these rules:

- Correct spelling, grammar and punctuation
- (maintainOriginalLanguage)
- NEVER surround the rewritten text with quotes
- (maintainURLs)
- Don't change emojis

Text: {{selection}}

Fixed Text:
