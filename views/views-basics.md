> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/views/views-basics.md).

# Views Basics

## Overview

Views let you **organize and customize how you interact with tasks across projects**. You can filter, sort, and group tasks based on various criteria, making it easy to focus on what’s most important. Choose from default layouts like Lis**t** and Kanban, or create custom views tailored to your workflow. With flexible customization options, the Views page helps you stay in control of your projects and manage tasks efficiently.

## Views Privacy

In Orchestra, views are private. Ir means that **they are only visible to the members specifically added to them**. Even Workspace Owners and Editors will not have access unless they are added as members of a private project.

## Creating a View

You can **create a new view** from the [Tasks Page](/pages-and-ui-elements/tasks-page.md). To do this, take the following steps:

* Navigate to the [Tasks Page](/pages-and-ui-elements/tasks-page.md)
* In the Views block, click the `+ icon`;
* In the opened context menu, select `Create new view`;
* Enter the view name in the text input field and press `Enter`.

Once the view is created, you can add members to it.

## Filters, Sort, Group, and Fields

To customise the views you create and make them work efficiently, use powerful yet easy tools - Filters, Sorting, Grouping, and Fields.&#x20;

You can learn more about fields, filtering, sorting, and grouping options here: [Filters, Sort, Group, and Fields](/tasks/filters-sort-group-and-fields.md)

## Leaving a View

You can **leave a view** in two ways:

* From the [Tasks Page](/pages-and-ui-elements/tasks-page.md#views-block) on [Tasks Page](/pages-and-ui-elements/tasks-page.md)
  * Find the view you want to leave;
  * Right-click on the view;
  * In the opened [Context Menu](/pages-and-ui-elements/context-menu.md), select `Leave` ;
  * Follow the instructions in the confirmation window.
* From the View [Info Sidebar](/pages-and-ui-elements/info-sidebar.md)
  * Open the view you want to leave;
  * Left-click on the `...` icon in the top right corner of the View[Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
  * In the opened [Context Menu](/pages-and-ui-elements/context-menu.md), select `Leave` ;
  * Follow the instructions in the confirmation window.

## Deleting a View

You can **delete a view** in two ways:

1. From the [Tasks Page](/pages-and-ui-elements/tasks-page.md#views-block) on the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
2. From the View Info sidebar.

***Deleting a view will also delete all data inside the view. This action cannot be undone.***

### Deleting a View on the Tasks Page

* Find the view you want to delete in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#views-block);
* Right-click on the view;
* In the [Context Menu](/pages-and-ui-elements/context-menu.md), select `Delete`;
* Click `Yes` in the confirmation window.

### Deleting a View from the View Info Sidebar

* Open the view you want to delete;
* Open the view's Info sidebar;
* Click the `...`button in the top-right corner of the screen;
* In the opened [Context Menu](/pages-and-ui-elements/context-menu.md), select `Delete`;
* Click `Yes` in the confirmation window.


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/views/views-basics.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
