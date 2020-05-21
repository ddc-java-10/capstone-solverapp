---
title: My project
description: "Trust me, it'll be cool"
layout: default
---

## Summary

Replace this paragraph with one or more paragraphs summarizing the purpose and operation of the software you propose to develop in this project.

## Intended users

Write a bullet list here, consisting of at least 2 different types of intended users. Make it reasonably specific; simply saying "Anyone who likes games" (for example) is not sufficiently specific.

For each type of intended user, include at least 1 _user story_. A user story is usually just 1 simple sentence (no more than 2 sentences), in the voice of the intended user, stating a specific task that the user needs to perform, and the benefit that will be obtained. The simplest user stories take the form 

> As a <type of intended user (_who_)> I want to <goal (_what_)> so that <benefit (_why_).

Please avoid writing too much for the user story. In particular, if the way the user story is written makes it difficult to see the _who_, _what_, and _why_, then you probably need to re-write it more directly. 

Here is one (silly) example of an intended user, along with a user story. Please note not only the conceptual structure, but the Markdown syntax used.

* People who like to use randomness in their decision making.

    > As someone who enjoys randomness in my life, I need an app that lets me flip a virtual coin or roll one or more virtual dice, so that I can base my decisions on randomness, without having to carry coins or dice in my pockets.

## Client component

* **Functionality**

    If your software is a full-stack/multi-tier system, with a user interface, as well as a component on a server/in the cloud, list (using a bullet list) the key functional aspects that will be provided by the user interface&mdash;i.e. tell us what the user will be able to do in the GUI.

* **Device/external services**

    If the client component will need to access special services of the device (e.g. sensors, contacts, messaging), list them here. Also, if the client component will need to access already-existing external services (e.g. real-time weather data, Open Movie Database, Open Trivia Database), those should also be listed here; any such references to external services should include links to the main page or API description page for the service.
    
    Please remember to use bullet lists (or ordered lists, if order is relevant), not just separate lines or paragraphs of text.
    
If there is only a user application, without a server/cloud component, then feel free to rename/reorganize this section&mdash;for example, you might create replace it with 2 separate sections with the headings, `## Functionality` and `## Device/external services`.

## Server component

* **Functionality**

    If your software is a full-stack/multi-tier system, with a user interface, as well as a component on a server/in the cloud, list (using a bullet list) the key functional aspects that will be provided by the server component&mdash;i.e. tell us what parts of the system functionality will be performed by the server.

* **External services**

    If the server component will need to access already-existing external services (e.g. real-time weather data, Open Movie Database, Open Trivia Database), those should also be listed here. Any such references to external services should include links to the main page or API description page for the service.
    
    Please remember to use bullet lists (or ordered lists, if order is relevant), not just separate lines or paragraphs of text.
    
If there is only a user application, without a server/cloud component, then omit this section.

## Stretch goals/possible enhancements 

If you can identify functional elements of the software that you think might not be achievable in the scope of the project, but which would nonetheless add significant value if you were able to include them, list them here. For now, we recommend listing them in order of complexity/amount of work, from the least to the most.
