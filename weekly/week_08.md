# Planning for Week 8

## High Level Topic Summary

  - Hierarchical Data Model
      - Declarative traversals of trees using XPath (XML)
      - Constraints and enforcement
      - HTML table structuring tags
        - `table`
        - `ol` and `ul`

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Sections 16.4.1-16.4.3, 16.4.7 | none
Tuesday    | Sections 16.4.4-16.4.6         | none
Wednesday  | Sections 17.1-17.3             | 17.4, 17.5, 17.6, 17.7
Friday     | Section 22.1                   | 22.6, 22.10, 22.11

## Progression

This week, we will extend our study of XML operations to include `XPath` as a declarative alternative to the procedural traversal and access operations we've seen using `lxml`'s `etree` module.  Then, we address the constraints of the hierarchical model, more formally defining the syntactic rules and then layering constraints that specify value and tree-relationship limitations on an XML structure.  Finally, we introduce HTML as a subset of XML, preparing us try some web scraping after spring break.

Monday: Introduce XPath for declarative XML operations.

Tuesday: Complete software lab on using XPath.

Wednesday: Discuss hierarchical model constraints.

Friday: Introduce HTML and its structure.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_3.d](../hw/HW_3.d/README.md) | Friday (3/3) | Wednesday (3/8) | Regular expressions
[HW_3.e](../hw/HW_3.e/README.md) | Monday (3/6) | Wednesday (3/8) | XPath

__Note__: There will be no homework due Friday 3/10 or Monday 3/20.  Have a great break!

## Tuesday Software Lab

In the [eighth software lab](../sw_lab/lab_08/README.md), we'll continue practicing working with XPath to process XML data.