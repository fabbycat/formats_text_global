# Allowed tags

## HTML Tags

|   Tag              |   Attributes                   |   Replacement        |   ✅❌❔   |
|  ----------------  |  ----------------------------  |  ------------------  |  --------  |
|   \<a\>            |   aria-label, href, hreflang   |                      |   ✅       |
|   \<abbr\>         |   class                        |                      |   ✅       |
|   \<address\>      |   class                        |   Core user module   |   ❌       |
|   \<area\>         |                                |                      |   ❌       |
|   \<article\>      |   [^2]                         |   Twig               |   ❌       |
|   \<aside\>        |   class                        |                      |   ✅❔     |
|   \<audio\>        |   [^3]                         |   \<drupal-media\>   |   ❌       |
|   \<b\>            |                                |                      |   ✅       |
|   \<base\>         |                                |                      |   ❌       |
|   \<bdi\>          |                                |                      |   ❌       |
|   \<bdo\>          |                                |                      |   ❌       |
|   \<blockquote\>   |   cite, class                  |                      |   ✅       |
|   \<body\>         |                                |                      |   ❌       |
|   \<br\>           |                                |                      |   ✅       |
|   \<button\>       |   [^1]                         |                      |   ❌       |
|   \<canvas\>       |                                |                      |   ❌       |
|   \<caption\>      |   class                        |                      |   ✅       |
|   \<cite\>         |   class                        |                      |   ✅       |
|   \<code\>         |   class                        |                      |   ✅       |
|   \<col\>          |                                |                      |   ✅       |
|   \<colgroup\>     |                                |                      |   ✅       |
|   \<data\>         |                                |                      |   ❌       |
|   \<datalist\>     |                                |                      |   ❌       |
|   \<dd\>           |                                |                      |   ✅       |
|   \<del\>          |                                |                      |   ✅       |
|   \<details\>      |                                |                      |   ❌       |
|   \<dfn\>          |   class                        |                      |   ✅       |
|   \<dialogue\>     |                                |                      |   ❌       |
|   \<div\>          |   class                        |                      |   ✅❔     |
|   \<dl\>           |   class                        |                      |   ✅       |
|   \<dt\>           |   class                        |                      |   ✅       |
|   \<em\>           |                                |                      |   ✅       |
|   \<embed\>        |                                |                      |   ❌       |
|   \<fieldset\>     |                                |                      |   ❌       |
|   \<figcaption\>   |   class                        |                      |   ✅       |
|   \<figure\>       |   class                        |                      |   ✅       |
|   \<footer\>       |                                |                      |   ❌       |
|   \<form\>         |                                |                      |   ❌       |
|   \<head\>         |                                |                      |   ❌       |
|   \<header\>       |                                |                      |   ❌       |
|   \<hgroup\>       |   class                        |                      |   ✅❔     |
|   \<h1\>           |                                |                      |   ❌       |
|   \<h2\>           |   class, id                    |                      |   ✅       |
|   \<h3\>           |   class, id                    |                      |   ✅       |
|   \<h4\>           |   class, id                    |                      |   ✅       |
|   \<h5\>           |   class, id                    |                      |   ✅       |
|   \<h6\>           |   class, id                    |                      |   ✅       |
|   \<hr\>           |                                |                      |   ✅       |
|   \<html\>         |                                |                      |   ❌       |
|   \<i\>            |                                |                      |   ✅       |
|   \<iframe\>       |                                |                      |   ❌       |
|   \<img\>          |                                |   \<drupal-media\>   |   ❌       |
|   \<ins\>          |   class                        |                      |   ✅       |
|   \<kbd>           |                                |                      |   ❌       |
|   \<keygen\>       |                                |                      |   ❌       |
|   \<label\>        |                                |                      |   ❌       |
|   \<legend\>       |                                |                      |   ❌       |
|   \<li\>           |   class                        |                      |   ✅       |
|   \<link\>         |                                |                      |   ❌       |
|   \<main\>         |                                |                      |   ❌       |
|   \<map\>          |                                |                      |   ❌       |
|   \<mark\>         |   class                        |                      |   ✅       |
|   \<menu\>         |                                |                      |   ❌       |
|   \<menuitem\>     |                                |                      |   ❌       |
|   \<meta\>         |                                |                      |   ❌       |
|   \<meter\>        |   class                        |                      |   ✅       |
|   \<nav\>          |                                |                      |   ❌       |
|   \<noscript\>     |                                |                      |   ❌       |
|   \<object\>       |                                |                      |   ❌       |
|   \<ol\>           |   class, start, type           |                      |   ✅       |
|   \<optgroup\>     |                                |                      |   ❌       |
|   \<option\>       |                                |                      |   ❌       |
|   \<output\>       |                                |                      |   ❌       |
|   \<p\>            |   class                        |                      |   ✅       |
|   \<param\>        |                                |                      |   ❌       |
|   \<picture\>      |                                |                      |   ❌       |
|   \<pre\>          |   class                        |                      |   ✅       |
|   \<progress\>     |                                |                      |   ❌       |
|   \<q\>            |   class                        |                      |   ✅       |
|   \<rp\>           |                                |                      |   ❌       |
|   \<rt\>           |                                |                      |   ❌       |
|   \<ruby\>         |                                |                      |   ❌       |
|   \<s\>            |   class                        |                      |   ✅       |
|   \<samp\>         |   class                        |                      |   ✅       |
|   \<script\>       |                                |                      |   ❌       |
|   \<section\>      |   class                        |                      |   ✅❔     |
|   \<select\>       |                                |                      |   ❌       |
|   \<small\>        |   class                        |                      |   ✅       |
|   \<source\>       |                                |                      |   ❌       |
|   \<span\>         |   class                        |                      |   ✅       |
|   \<strong\>       |   class                        |                      |   ✅       |
|   \<style\>        |                                |                      |   ❌       |
|   \<sub\>          |   class                        |                      |   ✅       |
|   \<summary\>      |                                |                      |   ❌       |
|   \<sup\>          |   class                        |                      |   ✅       |
|   \<svg\>          |                                |                      |   ❌       |
|   \<table\>        |   class                        |                      |   ✅       |
|   \<tbody\>        |   class                        |                      |   ✅       |
|   \<td\>           |   class                        |                      |   ✅       |
|   \<template\>     |                                |                      |   ❌       |
|   \<textarea\>     |                                |                      |   ❌       |
|   \<tfoot\>        |   class                        |                      |   ✅       |
|   \<th\>           |   class                        |                      |   ✅       |
|   \<thead\>        |   class                        |                      |   ✅       |
|   \<time\>         |   class                        |                      |   ✅       |
|   \<title\>        |                                |                      |   ❌       |
|   \<tr\>           |   class                        |                      |   ✅       |
|   \<track\>        |                                |                      |   ❌       |
|   \<u\>            |   class                        |                      |   ✅       |
|   \<ul\>           |   class                        |                      |   ✅       |
|   \<var\>          |   class                        |                      |   ✅       |
|   \<video\>        |                                |                      |   ❌       |
|   \<wbr\>          |   class                        |                      |   ✅       |

## Drupal Specific Tags

|   Tag                |   Attributes                           |   Replaces   |   ✅❌❔   |
|  ------------------  |  ------------------------------------  |  ----------  |  --------  |
|   \<drupal-media\>   |   data-entity-type, data-entity-uuid   |              |   ✅       |

---

[^1]: Tag is a form component:  
  Unnecessary for content editors.
