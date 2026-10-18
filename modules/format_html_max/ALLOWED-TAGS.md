# Allowed tags


## HTML Tags

| Tag            | Attributes                 | Replacement      | Included | Query |
|----------------|----------------------------|------------------|----------|-------|
| \<a\>          | href, hreflang, aria-label |                  | ✅        |       |
| \<abbr\>       |                            | Core user module | ✅        |       |
| \<address\>    |                            |                  | ❌        |       |
| \<area\>       |                            |                  | ❌        |       |
| \<article\>    |                            |                  | ❌        |       |
| \<aside\>      |                            |                  | ❌        |       |
| \<audio\>      |                            | \<drupal-media\> | ❌        |       |
| \<b\>          |                            |                  | ✅        |       |
| \<base\>       |                            |                  | ❌        |       |
| \<bdi\>        |                            |                  | ❌        |       |
| \<bdo\>        |                            |                  | ❌        |       |
| \<blockquote\> | cite                       |                  | ✅        |       |
| \<body\>       |                            |                  | ❌        |       |
| \<br\>         |                            |                  | ✅        |       |
| \<button\>     |                            |                  | ❌        |       |
| \<canvas\>     |                            |                  | ❌        |       |
| \<caption\>    |                            |                  | ✅        |       |
| \<cite\>       |                            |                  | ✅        |       |
| \<code\>       |                            |                  | ✅        |       |
| \<col\>        |                            |                  | ✅        |       |
| \<colgroup\>   |                            |                  | ✅        |       |
| \<data\>       |                            |                  | ❌        |       |
| \<datalist\>   |                            |                  | ❌        |       |
| \<dd\>         |                            |                  | ✅        |       |
| \<del\>        |                            |                  | ✅        |       |
| \<details\>    |                            |                  | ❌        |       |
| \<dfn\>        |                            |                  | ✅        |       |
| \<dialogue\>   |                            |                  | ❌        |       |


## Drupal Specific Tags

| Tag              | Attributes                         | Included | Query |
|------------------|------------------------------------|----------|-------|
| \<drupal-media\> | data-entity-type, data-entity-uuid | ✅        |       |




[^2]: Tag is a form component:
- Unnecessary for content editors.
- Dangerous for use in site content.
- Forms should only be created and managed by those with high privilege.
- Drupal provides a safer, more manageable way to create and consume forms.

[^2]: Tag is a media component:
- Drupal provides a rounded way of handling of this type of content through the media module.
- Links and changes are managed through the media module.

[^2]: Other, provided via Drupal or module:
- Drupal core modules provide an improved way of managing this tag or type of content.
- Drupal contrib modules provide an improved way of managing this tag or type of content.

[^2]: Other, outside content editing scope:
