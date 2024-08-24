---
title: Untitled Page
description: 
published: true
date: 2024-08-24T15:43:33.545Z
tags: 
editor: markdown
dateCreated: 2024-08-12T11:52:42.843Z
---

# Editing Tips!

You can mix HTML and markdown!

> Note that html will work at any point inside markdown, however, if you wish to use markdown inside HTML, you need to include an empty line between the HTML tag above the markdown, otherwise the renderer will ignore the markdown definition. See the dropdown example below for what is meant.
>
> Due to some issues with how markdown-it handles HTML, some elements may not render as expected and require some extra "help" to work. Please let WolfSkin know if that happens.
{.is-warning}

For example, to render a dropdown:
## Dropdown {.tabset}

### Code
```html
<details>
  <summary>
    
What you want showing when the dropdown is closed. (***It even supports markdown!***)
  </summary>
  
  The contents of the dropdown. Yup, this bit _supports markdown too_!
</details>
```
### Example
<details>
  <summary>

What you want showing when the dropdown is closed. (***It even supports markdown!***)
  </summary>
  
  The contents of the dropdown. Yup, this bit _supports markdown too_!
</details>