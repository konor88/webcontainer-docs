unknown: Invalid left-hand side in prefix operation. (1:2)

> 1 | ---
    |   ^
  2 | title: &title builder.io playground
  3 | description: &description Explore builder.io's visual editor fully in the browser.
  4 | outline: [2, 3]

</script>
unknown: Unexpected token (1:42)

> 1 |  ['meta', {property: 'og:title', content: *title}]
    |                                           ^
  2 |   - ['meta', {property: 'og:image', content: 'https://webcontainers.io/img/og/guide-community_inspirations.png'}]
  3 |   - ['meta', {name: 'twitter:title', content: *title}]
  4 |   - ['meta', {name: 'twitter:description', content: *description}]

<PageHeading title="builder.io playground" category="ide" />

Explore builder.io's visual editor fully in the browser

<Screenshot src="/img/community/builder-io-playground.png" alt="builder.io playground" href="https://playground.builder.io/" />
---
title: &title builder.io playground
description: &description Explore builder.io's visual editor fully in the browser.
outline: [2, 3]
head:
  - ['meta', {property: 'og:title', content: *title}]
  - ['meta', {property: 'og:image', content: 'https://webcontainers.io/img/og/guide-community_inspirations.png'}]
  - ['meta', {name: 'twitter:title', content: *title}]
  - ['meta', {name: 'twitter:description', content: *description}]
---
