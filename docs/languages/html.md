---
subtitle: HTML
layout: layouts/langs.njk
---
| Eleventy Short Name | File Extension | NPM Package |
| ------------------- | -------------- | ----------- |
| `html`              | `.html`        | N/A         |

HTML files can be optionally pre-processed with an additional template engine. This can be configured on a per-template basis or globally. Read more at [Changing a Template’s Rendering Engine](/docs/languages/).

{% callout "warn" %}
Careful with this template type when using the same <code>--input</code> and <code>--output</code> directory (this is not the default). Read more at <a href="/docs/pitfalls/">Common Pitfalls</a>.
{% endcallout %}

## Related Configuration

* [Default Template Engine for HTML Files](/docs/config/#default-template-engine-for-html-files)
