> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/tasks/filters-sort-group-and-fields.md).

# Filters, Sort, Group, and Fields

Orchestra provides multiple ways to structure your projects and views efficiently. With filtering, sorting, and grouping options which you can find on the [Tasks Page](/pages-and-ui-elements/tasks-page.md), it's possible to quickly reorganize information and extract valuable insights.&#x20;

## Filters

To focus on specific projects or views, you can filter both List and Kanban layouts by any [Fields](/projects/fields.md#default-fields) and [Fields](/projects/fields.md#custom-fields) you have in a view or project. Also, you can apply single or multiple filters at the same time.

*To **restore default filter settings**, click the* `Reset` *button located:*

* *To the left of Filters, Sort, Group, and Fields panel , or*
* *In the Filters context menu.*

## Sorting

ou can apply sorting to each filter by clicking`Sort`  in the toolbar. Sorting allows you to arrange entities based on [Fields](/projects/fields.md#default-fields) and [Fields](/projects/fields.md#custom-fields) in both List and Kanban layouts.

You can sort data in two ways:

* By clicking a field name:&#x20;
  * One click sorts in ascending (A-Z) order;
  * Two clicks sort in descending (Z-A) order;
  * A third click removes sorting.
* From the toolbar: just click `Sort` in the toolbar and choose the relevant fields in the context menu.

When sorting by multiple fields, **priority in the sorting order  is given to the first selected field.**

## Grouping

Group entities within your workspace using the [Fields](/projects/fields.md#default-fields) and [Fields](/projects/fields.md#custom-fields):

**There are two grouping levels** that can be selected for grouping in List and Kanban layouts.&#x20;

For instance, to group data by Status and Assignee:

* Click `Group` in the layout toolbar;
* Select `Status` from the context menu;
* Choose the relevant status options in the panel on the right;
* Seect `Assignee` from the context menu;
* Pick the required team members from the panel on the right.

To undo changes, click the `Reset`button.

## Fields

Each project or view contains multiple fields that can be used for filtering, sorting, and grouping. To display only relevant information, use the `Fields` option in both List and Kanban layouts to show or hide specific fields:

* Click the checkbox next to a field name in the `Fields` context menu to toggle visibility;
* Reorder fields in both List and Kanban views by dragging them. Click and hold the **drag icon** next to the field name in the layout toolbar or `Fields` menu, then move it to the desired position.

To undo any changes, click the `Reset`button.

*Note: Applying different filtering, sorting, or grouping options **removes all existing nesting structures**.*


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/tasks/filters-sort-group-and-fields.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
