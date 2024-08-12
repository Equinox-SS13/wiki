---
title: Guide to Contributing
description: How to contribute to this wiki.
published: true
date: 2024-08-12T07:06:53.653Z
tags: 
editor: markdown
dateCreated: 2024-08-10T19:34:56.088Z
---

# Contributing
If you're reading this, you're likely looking to contribute to this wiki. If so, this page will walk you through the basics, and hopefully act as a somewhat decent starting place.

## Working with Pages

### How pages work
Wiki.js handles pages and categories by treating them similarly to a filesystem. You have "folders" which represent categories and sub-categories (etc.), and pages.
This allows us to differentiate between the name of a page, and its path in the URL as well, for example:
- A page at `/objects/clothing/torso/sweater` means that there is a page whose "file" is called `sweater`, living inside the category `objects`, subcategory `clothing`, sub-subcategory `torso`.
- This file itself can then have a different title like `Sweater` (note the capitalisation) or `Jumper` (if we wanted the British English word). The title of that page, as well as its content is then free to change as much or as little as pleased without causing any links that point to it to fail.
  
The content of pages in Wiki.js can take a variety of formats, with Markdown, ASCIIDoc and Raw HTML natively supported (though we ***strongly*** recommend the use of Markdown for consistency and maintainability). Additionally, features like PlantUML diagrams and Katex (LaTeX-like math and chemistry typesetting) are supported through plugins.

### Creating New Pages
Creating new pages in Wiki.js is easy. Merely follow the following steps to do it:

1) Identify the "New Page" button in the top right of the page (it should look like a rectangle, containing a few horizontal lines, and a plus icon). If you do not see this button, consult with an administrator about your level of permissions.
2) Press the button to open the new page modal.
3) In this modal you can enter the path at which this page will sit. Imagine it like the aforementioned file system. (Unlike a traditional filesystem though, you do not need to create the folders to put the file into them though, just make sure they are in the path that you enter and they will be created as needed).
4) Next you should be greeted by a selector to choose which editor your wish to use. If you want to base your page off of another existing page, select "From Template", and then navigate to and select the page you want to build from. Else, select "Markdown" (preferred), or the specific supported format you wish to write your page in.
5) You should now be greeted by the editor screen as well as a "Page Properties" modal. In this modal, make sure you set a page title (this is displayed at the top of the page when reading) and optionally a short description for when linking to the page. Tags can also be set to allow for grouping and easier searching. "Scheduling" allows you to keep the page unpublished and to publish it at a different time, and the "scripts" and "styles" tabs allow you to set custom javascript and css respectively.
6) When you are done filling in the properties, you can click "Ok" and begin editing. The page properties modal can be reopened at any point by clicking on "Page" in the top right.

### Editing Existing Pages
Editing pages is also easy and can be done in 2 ways.
1) If you have permission to edit a page you should see a button just under the title and to the very right of the page labelled "Edit"
2) You can click on the "Page Actions" button, which sits in the top right and looks like a rectangle filled with horizontal lines and a pencil, and then "Edit".

### Moving Pages
Should you at any point wish to move a page to a different path, it is possible to do so either by clicking "Move/Rename" under the page actions menu, or by editing the path field in the page properties modal while in the editor.


### Deleting Pages
Deleting pages can be done with the page actions modal.

---

## Wiki Etiquette and Guidelines
The following are general etiquettes and guidelines that editors should follow to keep the content consistent and easy to read. This is not an enforced rule, but should be considered as much as possible.

### General Etiquette
- This wiki uses proper American English spelling. Although using British English spelling is fine, do not make edits to correct American English spelling to British English spelling.
- After performing a major edit, a comment should be stated on discord as to what you did. This allows better communication between the maintainers and contributors.
- Any edits to lore should be notified to the lore team on discord first. SoP and Law pages are not to be touched without permission.
- Minor edits refer to spelling check, grammar fixes, missing punctuations. Anything larger is a major edit.

### General Guidelines
- It is very important to stay on topic, do not divert from the title. If explanation for something is needed, link to a new article/page.
- Capitalize special names, proper nounds, or unique places.
- If a page within the same category
- Refrain from using existing character's names, real life references, or making random jokes.
- Refrain from using strikethrough, random bolding, scaled up text, or otherwise random formatting.
