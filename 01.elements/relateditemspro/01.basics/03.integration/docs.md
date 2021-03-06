---
title: Integration
taxonomy:
    category: docs
---

RelatedItemsPro is a standard ZOO element, you can follow the [extending type](http://yootheme.com/zoo/documentation/advanced/extend-pre-build-types) guide to integrate the element into your existent Apps. Once the element is set in the Type there are several configuration params that do differ from the ZOO ones, lets see what is all that about.

The Basic set are ZOOlanders common [Configuration fields](/extensions/zoolanders/elements/fields#configuration). The Specific and Item sets are RelatedItemsPro related fields.

| Field       | Description |
| :---------- | :---------- |
| **Editable** | Determines if the element should allow make relations or only show them. Usually combined with Bi-relation feature. |
| **Authored by User** | Limit the relations list to items authored by current User. |
| **Hide Unpublished** | Limit the relations list to published items. |
| **Apps** | Limit the relations list to items belonging to selected Apps. |
| **Types** | Limit the relations list to items being of selected Type. |
| **Bi-Related Elements** | Choose the elements from other Types that will be used for the bi-directional relation. |

## Bi-related items

Two ZOO items can be related to each other (bi-related). This way two items like Event and Venue can be related to each other by saving only one item, the second item will be related to the first one automatically. The relation will be saved in the element specified in the "Bi-Related Elements" section:

![Bi-related configuration](bi-relation.png)

## Assignment

The Element is set now but is not rendering at all, let's fix that. Assign the element to the position of your choice following the [assign elements](http://yootheme.com/zoo/documentation/advanced/assign-elements-to-layout-positions) guide. Once assigned there will be another set of fields requiring attention.

The Basic, Filter and Separator sets are ZOOlanders common [Assignment fields](/extensions/zoolanders/elements/fields#assignment).The Layout set displays the fields related to RelatedItemsPro layouts, which is the topic of the next page.
