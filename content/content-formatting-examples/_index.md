---
title: Content Formatting Examples
weight: 5
description: A collection of shortcode examples for formatting content, from basic Markdown text to advanced custom components.
draft: true
---

{{< alert type="danger" title="Example Page: Not for Production" >}}
This page will not be published in the [production version](https://cloud.layer5.io/academy/) of your Academy site. It is only visible for local preview (`draft: true`) and serves as a reference. You can safely delete this page from your repository at any time.
{{< /alert >}}

The Layer5 Academy platform supports a wide range of shortcodes for enriching your learning content. Shortcodes are reusable template snippets you invoke in Markdown files to generate HTML output.

Using a shortcode looks like this:

```code
  { {% shortcode-name %}}
```

Shortcodes come from three sources:

1. **Academy Theme** — shortcodes built specifically for the Layer5 Academy ([academy-theme repo](https://github.com/layer5io/academy-theme)).
2. **Docsy Theme** — shortcodes inherited from the [Google Docsy](https://www.docsy.dev/) documentation theme.
3. **Hugo Built-in** — shortcodes included with the [Hugo](https://gohugo.io/) static site generator.

For guidance on creating your own custom shortcodes, see [Extending the Academy](/cloud/academy/creating-content/extending-the-academy/).

The shortcode name is the file name (minus the `.html`) in `layouts/shortcodes/your-org-uuid`.

## Browse examples

Each example now lives in its own content file so you can inspect and reuse it independently.

The academy theme overrides the Docsy `alert` and `pageinfo` shortcodes, and it also overrides Hugo's built-in `details` shortcode. The dedicated example pages for those overridden implementations use local demo aliases: `docsy-alert`, `docsy-pageinfo`, and `hugo-details`.

The `lab-intro` shortcode stores content for lab layouts instead of writing output directly, so its dedicated example page uses a small local helper to preview the stored value.

### Hugo built-in shortcodes

* [Hugo Details](./hugo-details/)
* [Figure](./figure/)
* [Highlight](./highlight/)
* [Instagram](./instagram/)
* [Param](./param/)
* [QR](./qr/)
* [Ref](./ref/)
* [Relref](./relref/)
* [Vimeo](./vimeo/)
* [X](./x/)
* [YouTube](./youtube/)

### Docsy shortcodes

* [Docsy Alert](./docsy-alert/)
* [Blocks Cover and Link Down](./blocks-cover-link-down/)
* [Blocks Lead](./blocks-lead/)
* [Blocks Section and Feature](./blocks-section-feature/)
* [Card](./card/)
* [Cardpane](./cardpane/)
* [Comment](./comment/)
* [Conditional Text](./conditional-text/)
* [Iframe](./iframe/)
* [Imgproc](./imgproc/)
* [Docsy Pageinfo](./docsy-pageinfo/)
* [Readfile](./readfile/)
* [Redoc](./redoc/)
* [SwaggerUI](./swaggerui/)
* [Tabpane and Tab](./tabpane-tab/)

### Layer5 Academy theme shortcodes

* [Theme Alert](./theme-alert/)
* [Chapterstyle](./chapterstyle/)
* [CSV Table](./csvtable/)
* [CSV Table Roles](./csvtable-roles/)
* [Theme Details](./theme-details/)
* [Image](./image/)
* [Lab Intro](./lab-intro/)
* [Local Video](./local-video/)
* [Meshery Design Embed](./meshery-design-embed/)
* [Theme Pageinfo](./theme-pageinfo/)
* [SVG](./svg/)
* [Usestatic](./usestatic/)
* [Version](./version/)

### Repository-local organization shortcode

* [Custom Organization Shortcode](./custom-org-shortcode/)

## Markdown

* [Markdown Basics](./markdown-basics/)
* [Image Styling](./image-styling/)
* [Code](./code/)
* [Lists](./lists/)
* [Tables](./tables/)
* [Responsive Images](./responsive-images/)

## Components

* [Embedded Design](./embedded-design/)
* [Alerts](./alerts/)
* [TabPanel](./tabpanel/)
* [Collapsible](./collapsible/)
* [Footnotes](./footnotes/)
