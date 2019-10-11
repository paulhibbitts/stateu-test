---
title: 'Body & Hero Classes'
date: '14:55 08/11/2017'
taxonomy:
    category:
        - blog
    tag:
        - photography
        - journal
hide_git_sync_repo_link: false
hero_classes: 'text-light title-h1h2 overlay-dark-gradient hero-large parallax'
hero_image: unsplash-overcast-mountains.jpg
header_image_alt_text: Mountains
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
hide_from_post_list: false
feed:
    limit: 10
author: 'Tasha Maxwell'
continue_link: true
---

<p>The <a href="https://getgrav.org/downloads/themes">Quark theme</a>
 has the ability to allow pages to override some of the default options by letting the user set <code>body_classes</code>
 for any page.  The theme will merge the combination of the defaults with any <code>body_classes</code>
 set. This allows you to easily add hero classes to give your blog post some <strong>bling</strong>
. NEW.</p>
<h2>Body Classes</h2>
<pre><code class="language-yaml">body_classes: "header-dark header-transparent"</code>
</pre>
<p>On a particular page will ensure that page has those options enabled (assuming they are false by default).</p>
<h2>Hero Options</h2>
<p>The hero template allows some options to be set in the page frontmatter. This is used by the modular <code>hero</code>
 as well as the blog and item templates to provide a more dynamic header.</p>
<pre><code class="language-yaml">hero_classes: text-light title-h1h2 parallax overlay-dark-gradient hero-large
hero_image: road.jpg
hero_align: center</code>
</pre>
<p>The <code>hero_classes</code>
 option allows a variety of hero classes to be set dynamically these include:</p>
<ul>
<li><code>text-light</code>
 | <code>text-dark</code>
 - Controls if the text should be light or dark depending on the content</li>
<li><code>title-h1h2</code>
 - Enforced a close matched h1/h2 title pairing</li>
<li><code>parallax</code>
 - Enables a CSS-powered parallax effect</li>
<li><code>overlay-dark-gradient</code>
 - Displays a transparent gradient which further darkens the underlying image</li>
<li><code>overlay-light-gradient</code>
 - Displays a transparent gradient which further lightens the underlying image</li>
<li><code>overlay-dark</code>
 - Displays a solid transparent overlay which further darkens the underlying image</li>
<li><code>overlay-light</code>
 - Displays a solid transparent overlay which further darkens the underlying image</li>
<li><code>hero-fullscreen</code>
 | <code>hero-large</code>
 | <code>hero-medium</code>
 | <code>hero-small</code>
 | <code>hero-tiny</code>
 - Size of the hero block</li>
</ul>
<p>The <code>hero_image</code>
 should point to an image file in the current page folder.</p>
