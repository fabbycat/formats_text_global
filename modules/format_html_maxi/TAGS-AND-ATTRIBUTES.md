# HTML, Maxi Format

A text filter supporting a large number of tags and attributes. The filter may open the site to
security risks if misused. Only the most trusted users with a good knowledge of HTML, tag attributes
and CSS should be given permissions for it's usage.

## Tags

### HTML Tags

|   Tag              |   Attributes                   |   ✅❌❔   |
|  ----------------  |  ----------------------------  |  --------  |
|   \<a>            |   aria-label, href, hreflang   |   ✅       |
|   \<abbr>         |   class                        |   ✅       |
|   \<address>      |   class                        |      ❌       |
|   \<area>         |                                |   ❌       |
|   \<article><sup>[forms](#forms)</sup>      |                               ❌       |
|   \<aside>        |   class                        |   ✅❔     |
|   \<audio>        |                                |      ❌       |
|   \<b>            |                                |   ✅       |
|   \<base>         |                                |   ❌       |
|   \<bdi>          |                                |   ❌       |
|   \<bdo>          |                                |   ❌       |
|   \<blockquote>   |   cite, class                  |   ✅       |
|   \<body>         |                                |   ❌       |
|   \<br>           |                                |   ✅       |
|   \<button>       |                                |   ❌       |
|   \<canvas>       |                                |   ❌       |
|   \<caption>      |   class                        |   ✅       |
|   \<cite>         |   class                        |   ✅       |
|   \<code>         |   class                        |   ✅       |
|   \<col>          |                                |   ✅       |
|   \<colgroup>     |                                |   ✅       |
|   \<data>         |                                |   ❌       |
|   \<datalist>     |                                |   ❌       |
|   \<dd>           |                                |   ✅       |
|   \<del>          |                                |   ✅       |
|   \<details>      |                                |   ❌       |
|   \<dfn>          |   class                        |   ✅       |
|   \<dialogue>     |                                |   ❌       |
|   \<div>          |   class                        |   ✅❔     |
|   \<dl>           |   class                        |   ✅       |
|   \<dt>           |   class                        |   ✅       |
|   \<em>           |                                |   ✅       |
|   \<embed>        |                                |   ❌       |
|   \<fieldset>     |                                |   ❌       |
|   \<figcaption>   |   class                        |   ✅       |
|   \<figure>       |   class                        |   ✅       |
|   \<footer>       |                                |   ❌       |
|   \<form>         |                                |   ❌       |
|   \<head>         |                                |   ❌       |
|   \<header>       |                                |   ❌       |
|   \<hgroup>       |   class                        |   ✅❔     |
|   \<h1>           |                                |   ❌       |
|   \<h2>           |   class, id                    |   ✅       |
|   \<h3>           |   class, id                    |   ✅       |
|   \<h4>           |   class, id                    |   ✅       |
|   \<h5>           |   class, id                    |   ✅       |
|   \<h6>           |   class, id                    |   ✅       |
|   \<hr>           |                                |   ✅       |
|   \<html>         |                                |   ❌       |
|   \<i>            |                                |   ✅       |
|   \<iframe>       |                                |   ❌       |
|   \<img>          |                                |   ❌       |
|   \<ins>          |   class                        |   ✅       |
|   \<kbd>           |                                |   ❌       |
|   \<keygen>       |                                |   ❌       |
|   \<label>        |                                |   ❌       |
|   \<legend>       |                                |   ❌       |
|   \<li>           |   class                        |   ✅       |
|   \<link>         |                                |   ❌       |
|   \<main>         |                                |   ❌       |
|   \<map>          |                                |   ❌       |
|   \<mark>         |   class                        |   ✅       |
|   \<menu>         |                                |   ❌       |
|   \<menuitem>     |                                |   ❌       |
|   \<meta>         |                                |   ❌       |
|   \<meter>        |   class                        |   ✅       |
|   \<nav>          |                                |   ❌       |
|   \<noscript>     |                                |   ❌       |
|   \<object>       |                                |   ❌       |
|   \<ol>           |   class, start, type           |   ✅       |
|   \<optgroup>     |                                |   ❌       |
|   \<option>       |                                |   ❌       |
|   \<output>       |                                |   ❌       |
|   \<p>            |   class                        |   ✅       |
|   \<param>        |                                |   ❌       |
|   \<picture>      |                                |   ❌       |
|   \<pre>          |   class                        |   ✅       |
|   \<progress>     |                                |   ❌       |
|   \<q>            |   class                        |   ✅       |
|   \<rp>           |                                |   ❌       |
|   \<rt>           |                                |   ❌       |
|   \<ruby>         |                                |   ❌       |
|   \<s>            |   class                        |   ✅       |
|   \<samp>         |   class                        |   ✅       |
|   \<script>       |                                |   ❌       |
|   \<section>      |   class                        |   ✅❔     |
|   \<select>       |                                |   ❌       |
|   \<small>        |   class                        |   ✅       |
|   \<source>       |                                |   ❌       |
|   \<span>         |   class                        |   ✅       |
|   \<strong>       |   class                        |   ✅       |
|   \<style>        |                                |   ❌       |
|   \<sub>          |   class                        |   ✅       |
|   \<summary>      |                                |   ❌       |
|   \<sup>          |   class                        |   ✅       |
|   \<svg>          |                                |   ❌       |
|   \<table>        |   class                        |   ✅       |
|   \<tbody>        |   class                        |   ✅       |
|   \<td>           |   class                        |   ✅       |
|   \<template>     |                                |   ❌       |
|   \<textarea>     |                                |   ❌       |
|   \<tfoot>        |   class                        |   ✅       |
|   \<th>           |   class                        |   ✅       |
|   \<thead>        |   class                        |   ✅       |
|   \<time>         |   class                        |   ✅       |
|   \<title>        |                                |   ❌       |
|   \<tr>           |   class                        |   ✅       |
|   \<track>        |                                |   ❌       |
|   \<u>            |   class                        |   ✅       |
|   \<ul>           |   class                        |   ✅       |
|   \<var>          |   class                        |   ✅       |
|   \<video>        |                                |   ❌       |
|   \<wbr>          |   class                        |   ✅       |

### Drupal Specific Tags

|   Tag                |   Attributes                           |    ✅❌❔   |
|  ------------------  |  ------------------------------------  |   --------  |
|   \<drupal-media>   |   data-entity-type, data-entity-uuid   |    ✅       |

***

## Thoughts and Reasoning

### Forms

- Unnecessary for content editors.
- Dangerous for use in site content.
- Forms should only be created and managed by those with higher privileges such as site
  administrators.
- Drupal provides a safer, more manageable way to create and consume forms.

### Structural

- Drupal core handles structural tags through the Twig template engine.
- Drupal modules add additional handling of structural tags through the Twig template engine.
- Use of structural tags may confuse semantic markup and therefore result in failures to achieve a
  good standard of accessibility.

### Media

- Drupal provides a more rounded way of handling of this type of content through the core media
  module.
- Links and changes are managed through the media module.
