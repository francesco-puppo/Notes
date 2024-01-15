---
layout: default
title: Moo.com rules 
parent: UX Principles
grand_parent: User Experience
---

# {{ page.title }} (circa 2008)
{: .no_toc }

<details markdown="block">
  
  <summary>
## Table of contents
{: .no_toc .text-delta }
  </summary>
  
- TOC
{:toc}

</details>

## Optimise for the common case
Adding something to satisfy the needs of a small number of users confuses the rest. The tools we build should satisfy the needs of the majority of users.

## Build tools that focus on meeting one simple need
Tools should focus on solving one problem e.g. “Signing up for a newsletter”, “Previewing a pack”. If a problem can’t be articulated in a single sentence, rethink the problem, there’s probably more than one thing that needs building.

## Build tools for users without experience
Tools should be easy to use for users those without experience of our websites, and meets users initial needs.

## Users needs are not always the same as the features they ask for

## One action per page
Stick to 1 action per page (search, crop, signup), with clear escape routes / next steps.

## Context is more important than consistency
Giving users the most useful information, at a given point, is more important than consistency across pages e.g. changing a sidebar based on where you are in the site is good if it bubbles up useful content to the user (see Ready Made).

## Optimise for average user’s return rate
Tools that people use on a daily basis need to be designed differently from ones that people use only occasionally.
People using tools regularly have more time to learn, and need shortcuts for repetitive tasks. Iconography and more complex user paths are fine for them because they have time to learn how they work.
Occasional tools need to be straightforward at first glance, their use transparent on first glance, with a small number of simple text hints.
Too many features can make things harder to understand at first glance. As can iconography or shortcuts that they have to learn the meaning of first before they can use them.

## Make a page functionality readable
You should be able to give a page a single scan and work out what it does. The most important thing here is the order and prominence of elements. e.g. closing your eyes, them opening them and see whether they jump to the page elements in the order they should be used.

## Only tell people things once per page
Do not repeat instructions to people. For example, if you have an area
of a page where you can drag items to, do not have text at the top of the page AND within the drag area explaining what a user needs to do.

## Contextual help is best
Help text and hints should be placed as close to the relevant page element as possible. e.g. If a page element needs some explanation
that it should be dragged, then place the text “Drag to crop”. Hiding help text in popups is bad.

## Let people teach themselves
Let people figure things out for themselves by making sure the most
obvious action is something you want them to do. This is better than longwinded explanations. E.g. the photo picker page has little text, but almost the only thing you can do initially is drag something.

## Keep the user path as short as possible
The user should be presented with the shortest path to their goal. the exception to this is where a valid business case can be made for extending it.

## Make decisions for people
Giving people endless choice confuses. Make some choices for people and let them focus on the things that are really important to them. e.g. don’t give people a choice between 10 fonts that all look the same.

## Make people confident in their actions
Explain to people what is about to happen to them e.g. “Want to add more images? your crop positions will be saved”. Explain how many steps something is going to take and where they are in a process / navigation system.

## Pages make sense before and after action
Or “Designing for empty”. If an area of a page is going to change after a user’s action, explain what is likely to happen and use it as space for a hint. e.g. a floating button that says upload, with no context of what it is uploading is bad. A simple box with “uploaded files will appear here” does the job (hide the message after first upload).

## State should always be maintained between pages
The state of a page (i.e. any actions made by a user) should be
maintained between postbacks and when returning to a page.

## Make sure pages content can be linked to forever
If pages have to be removed, then redirect to somewhere useful.

## Specific ones

### Warning and errors
Error messages and warnings should be straight to the point, polite and written in plain english. People are not computers (i.e. “Unhanded exception” is not a good error message), and should never be made to feel stupid.

All error messages should be displayed using the red box at the top of the page. The only exception is if the user has failed to make as single action on the page and it would be impossible for them to proceed. e.g. they need to uploaded some images but have clicked the “next step” button without trying to do so. In this situation the user should be shown a javascript alert() box.

### Hints and text
All headers, hints and control labels should be written in sentence case. Hints and help text should be short and straightforward to understand and should never been hidden from a user (e.g. under rollovers or popups).

### Links
Links should always be underlined, unless they are part of a top-level menu system.

---

Source: [Richard Pope’s Blog](https://richardpope.org/blog/2014/08/02/moo-ux-rules-circa-2008/)