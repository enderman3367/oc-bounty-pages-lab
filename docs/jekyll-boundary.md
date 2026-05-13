---
layout: null
---
Jekyll boundary probe start.

Direct include_relative outside attempt follows:
{% include_relative ../outside/should-not-render-jekyll.txt %}

Encoded-ish literal include_relative attempt follows:
{% include_relative ..%2foutside%2fshould-not-render-jekyll.txt %}

Jekyll boundary probe end.
