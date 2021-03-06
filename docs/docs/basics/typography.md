---
layout: doc
title: Typography
categories: basics
permalink: /docs/basics/typography/

table-of-content:
- Typography base
- Headings
---

<p>Type is all set with the <code>rems</code>, so font-sizes and spacial relationships can be responsively sized based on a single <code>&lt;html&gt;</code> font-size property. Out of the box, Kissui never changes the <code>&lt;html&gt;</code> font-size, but it's there in case you need it for your project. All measurements are still base 10 though so, an <code>&lt;h1&gt;</code> with <code>5.0rem</code>font-size just means <code>50px</code>.</p>

<h4 id="Typography base">Typography base</h4>
<p><strong>The typography base</strong> is <a href="https://www.google.com/fonts/specimen/Open+Sans">Open Sans</a> served by Google, set at 15rem (15px) over a 1.6 line height (24px). Other type basics like <a href="#">anchors</a>, <strong>strong</strong>, <em>emphasis</em>, and <u>underline</u> are all obviously included.</p>

<h4>Headings</h4>
<p><strong>Headings</strong> create a family of distinct sizes each with specific <code>letter-spacing</code>, <code>line-height</code>, and <code>margins</code>.</p>

<h1>Heading<span class="heading-font-size"> <code>&lt;h1&gt;</code> 50rem</span></h1>
<h2>Heading<span class="heading-font-size"> <code>&lt;h2&gt;</code> 42rem</span></h2>
<h3>Heading<span class="heading-font-size"> <code>&lt;h3&gt;</code> 36rem</span></h3>
<h4>Heading<span class="heading-font-size"> <code>&lt;h4&gt;</code> 30rem</span></h4>
<h5>Heading<span class="heading-font-size"> <code>&lt;h5&gt;</code> 24rem</span></h5>
<h6>Heading<span class="heading-font-size"> <code>&lt;h6&gt;</code> 15rem</span></h6>

<pre class="code-example">
<code class="language-html">&lt;!-- Standard Headings --&gt;
&lt;h1&gt;Heading&lt;/h1&gt;
&lt;h2&gt;Heading&lt;/h2&gt;
&lt;h3&gt;Heading&lt;/h3&gt;
&lt;h4&gt;Heading&lt;/h4&gt;
&lt;h5&gt;Heading&lt;/h5&gt;
&lt;h6&gt;Heading&lt;/h6&gt;

&lt;!-- Base type size --&gt;
&lt;p&gt;The base type is 15px over 1.6 line height (24px)&lt;/p&gt;

&lt;!-- Other styled text tags --&gt;
&lt;strong&gt;Bolded&lt;/strong&gt;
&lt;em&gt;Italicized&lt;/em&gt;
&lt;a&gt;Colored&lt;/a&gt;
&lt;u&gt;Underlined&lt;/u&gt;
</code>
</pre>
