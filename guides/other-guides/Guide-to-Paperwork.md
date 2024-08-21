---
title: Guide to Paperwork
description: All the formats for the in-game paperwork.
published: true
date: 2024-08-21T11:06:14.367Z
tags: guide, other guide
editor: markdown
dateCreated: 2024-08-21T11:06:14.367Z
---

> This page is ported directly from [Sojourn's Wiki](https://sojourn13.space/wiki/Guide_to_Paperwork) with some modification.
{.is-info}


Writing is an integral part to paperwork and writing books! If you want to write an official department memo, or a good looking book, you're gonna have to know how to write it.


# Writing tools and Formatting key

Writing is performed on paper using any standard writing utensil.

* Pens come in a few different colors, black or blue by default, and some departments are provided with red pens. Pens have a variety of functions!
* Crayons work much like pens, except that they are always bold, and lack the list, horizontal rule, and small tags.

# Formatting Paper:
## Signature

To sign your name, use the `[sign]` tag. Remember that if you use the `[sign]` tag, your signature is unique and cannot be forged in most cases.

`Your signature: [sign]`

## Field

To insert a field from which you can start writing (instead of just using the bottom of the paper), use the `[field]` tag.

`Reason for Request: [field]`

## New Lines

New lines can be created by using the `[br]` tag. Without this, anything you write will continue on the same line until it reaches the end of the page.

`text above
[br]
text below`

## Text Stylizing

### Bold

To make text bold, enclose it within the `[b]` and `[/b]` tags.

`[b]This text is going to be bold.[/b] This text is not.`

### Italics

To italicize text, enclose it within the `[i]` and `[/i]` tags.

`[i]This text is italicized.[/i] This text is not.`

### Underlining

To underline text, enclose it within the `[u]` and `[/u]` tags.

`[u]This text is underlined.[/u] This text is not.`

### Large Text

Make text larger, enclose it within the `[large]` and `[/large]` tags. Large text like this can be used for emphasis or for titles.

`[large]This text is much larger[/large] than this text.`

### Small Text

To shrink text, enclose it with the `[small]` and `[/small]` tags. Shrunken text can be used to fit more information onto your paper.

`[small]This text is very small![/small] This text is normal-sized.`

## Centering

To center text, enclose it with the `[center]` and `[/center]` tags.

`[center]Type the center tags onto the paper like this![/center]`

## Lists

Create a list by using the `[list]` and `[/list]` tags. For every entry in your list, add a `[*]` in front of your entry. For example;

`[list][*]Bullet one.[*]Bullet two.[/list]`

## Horizontal rules

To add a horizontal rule which is a line separating the text, use the `[hr]` tag.

`text above
[hr]
text below`