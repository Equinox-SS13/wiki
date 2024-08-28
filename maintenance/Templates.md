---
title: Wiki Templates
description: 
published: true
date: 2024-08-28T12:30:20.098Z
tags: wiki contribution
editor: markdown
dateCreated: 2024-08-28T12:20:52.627Z
---

## Overview and Usage

The following Templates are standardization informationlet formatting in the form of "info box" that is used to note the completeness or integrity of articles for the end-user. 
> This is not an enforcement of use but a suggested quick copy-paste templates for the contributors to use.
{.is-info}

### Using Templates
Templates accompany lore and maintenance category, this is to make note of pages that require work and contribution towards. When using the template, the relevant category should always be used for easy searching for contributors.
* If the entire article is relevant, the template info box should be put at the top of the article, above the first header and alongside foreword (if any)
* If only a specific section is relevant, the template info box should be put underneath the section header and above any other paragraphs.

---

# Lore Template
Lore templates are used to mark and organize lore articles for their relevancy to the server.

## Canonical
The category `lore: canon` is used to mark lore pages that are **canon**, **current**, **complete**, and considered **in use** for the game server.

An information box is not required for pages marked as canonical. If for any reason a page is mostly considered otherwise with a section that is canonical, the following is to be used:

---

> [**Canonical**](/maintenance/Templates#canonical): This section is considered **canonical**, **current**, and **in-use**.
> {.is-success}

```
> [**Canonical**](/maintenance/Templates#canonical): This section is considered **canonical**, **current**, and **in-use**.
> {.is-success}
```

## Planned
The category `lore: planned content` is used to mark lore article or sections that are **planned**, **unfinished**, and/or **not yet released** for the game server.

The following information box is to be used;

---

> [**Planned Content**](/maintenance/Templates#planned): This article or section is considered **planned**, **unfinished**, and/or **not yet released** for use.
{.is-info}

```
> [**Planned Content**](/maintenance/Templates#planned): This article or section is considered **planned**, **unfinished**, and/or **not yet released** for use.
{.is-info}
```

## Unused
The category `lore: Unused` is used to mark lore article or sections that are **not canonical**, **unused**, or completely **irrelevent** to the game server.

This is not to be used with pages outlining mechanics, the category [`wiki: outdated`](/maintenance/Templates#outdated) alongside the reasoning should be applied instead.


> [**Unused Content**](/maintenance/Templates#unused): This article or section is considered **non-canonical** and **unused**.
{.is-danger}

```
> [**Unused Content**](/maintenance/Templates#unused): This article or section is considered **non-canonical** and **unused**.
{.is-danger}
```

---

# Maintenance Template
Maintenance templates are used to mark and organize pages that are incorrect, out-of-date, or has broken format/link/image in some way or another.


## Needs Revision
The category `wiki: needs revision` is used to mark an article or section that may be incomplete, incorrect, or potentially out-of-date information for review. 

For game mechanic articles this means accuracy to the code. For lore articles this means relevancy determined by the lore team.
* If verified **up to date and relevant**, the category and info box should be removed.
* If verified **out of date or incorrect**, the category [`wiki: outdated`](/maintenance/Templates#outdated) and info box alongside reasoning should be assigned.
* If verified **irrelevant or not current** for lore articles, the following relevant [lore category](/maintenance/Templates#lore-template) and info box should be assigned.

---

> [**Needs Revision**](/maintenance/Templates#needs-revision): This article or section may be **outdated or incorrect**, once verified this tag should be removed or replaced with relevant [tags](/maintenance/Templates#maintenance-template).
{.is-info}

```
> [**Needs Revision**](/maintenance/Templates#needs-revision): This article or section may be **outdated or incorrect**, once verified this tag should be removed or replaced with relevant [tags](/maintenance/Templates#maintenance-template).
{.is-info}
```

## Work in Progress
The category `wiki: work in progress` is used to mark an article as unfinished or incomplete but is **being worked on actively** by a user which should be specified.
* If for some reason, the user is no longer working on the article and the article is still incomplete, the category [`wiki: outdated`](/maintenance/Templates#outdated) or [`wiki: stub`](/maintenance/Templates#stub) should be used instead.

---

> [**Work in Progress**](/maintenance/Templates#work-in-progress): This article is **incomplete** and is being **actively worked on** by user: `@usernamehere`
{.is-warning}

```
> [**Work in Progress**](/maintenance/Templates#work-in-progress): This article is **incomplete** and is being **actively worked on** by user: `@usernamehere`
{.is-warning}
```

## Outdated
The category `wiki: outdated` is used to mark an article as **out-of-dated**, **incomplete**, or **not in game**. Alongside the info box and category tag, a reason should be provided on how it is outdated, incomplete, or not currently in the game.

---

> [**Outdated Article**](/maintenance/Templates#outdated): This article is **out-of-date**, **incomplete**, or **not currently in the game**. **Reason**: `reasonhere`
{.is-warning}

```
> [**Outdated Article**](/maintenance/Templates#outdated): This article is **out-of-date**, **incomplete**, or **not currently in the game**. **Reason**: `reasonhere`
{.is-warning}
```

## Stub
The category `wiki: stub` is used to mark an article that has lacks a majority of the content (including those that has been created and/or linked, but no content has been written). A reason may be provided.
* This may be an informal request for an article or section on an information to be created. 
  * Some examples may include writing a section of a mechanic that is linked to another page, but the full section of the mechanic has not been written up yet, or the aformentioned pages that are not currently worked on.
* If someone has explicitly stated that they're taking on the creation, the category [`wiki: work in progress`](/maintenance/Templates#work-in-progress) should be used instead (self assignee welcome!).

---

> [**Stub**](/maintenance/Templates#stub): This article or section is **incomplete** and require more write up or expansion on the content. **Reason**: `reasonhere`
{.is-danger}

```
> [**Stub**](/maintenance/Templates#stub): This article or section is **incomplete** and require more write up or expansion on the content. **Reason**: `reasonhere`
{.is-danger}
```

## Broken Page/File
This category `wiki: broken page/file` is used to mark a page that may have broken page formatting, broken images, or broken links. No info box is necesssary.

---

# Article Ports
These template info box are not used alongside category, but used to signify pages that are ported directly from the respective wiki without enough modification or rewrite.

### [Sojourn Wiki](https://sojourn13.space/wiki/)
> This article is ported directly from [Sojourn Wiki](https://sojourn13.space/wiki/).
{.is-info}

### [Eris Wiki](https://wiki.cev-eris.com/)
> This article is ported directly from [Eris Wiki](https://wiki.cev-eris.com/).
{.is-info}


