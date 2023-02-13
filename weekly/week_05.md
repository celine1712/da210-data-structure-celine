# Planning for Week 5

## High Level Topic Summary

  - Advanced Operations in the Tabular Model
      - Aggregating Data
      - Grouping Data
      - Mutations
      - Combining Tables
      - Missing Data
  - Transformations and Tidy Data Normalization
      - Constraints Review
      - Melt

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Section 8.1  | none
Tuesday    | Section 8.2  | none
Wednesday  | Section 8.3  | none
Friday     | Sections 8.4, 9.1-9.2.2, 9.3.1 | 9.16, 9.18, 9.20

## Progression

This week we will explore advanced tabular operations of aggregation, mutation, and combining tables.  We will then begin to learn about operations that *transform* row-column data into altered structures.

Monday: Explore aggregation, starting with simple aggregation of column vectors, and proceeding to variations (uniform and non-uniform) aggregating on subsets of columns in a dataframe.  Finally, we'll extend this to group partitioning and GroupBy.

Tuesday: Complete software lab focusing on mutations to change values, delete rows or columns, add rows and columns, and even conditionally update values for only some rows.

Wednesday: Discuss combining tables, extending to integrating combining tables with join and merge operations.

Friday: Discuss handling of mising data, then introduce tabular transformation operations of transpose and melt.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_2.c](../hw/HW_2.c/README.md) | Friday (2/10) | Monday (2/13) | Row selection, complex access combinations
[HW_2.d](../hw/HW_2.d/README.md) | Monday (2/13) | Wednesday (2/15) | Aggregation and GroupBy
HW_2.e | Wednesday (2/15) | Friday (2/17)    | Table combining
HW_2.f | Friday (2/17) | Monday (2/20) | Transpose, melt, normalization I

## Tuesday Software Lab

In the fifth software lab, we'll explore our second advanced tabular operation: mutation.  We'll look at deleting one or more columns or rows, adding a column to an existing `DataFrame`, and updating all or some values within an existng column.