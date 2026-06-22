> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/context-menu.md).

# Context Menu

The Context menu in Orchestra provides quick access to **key actions for various entities and elements**. Different entities and elements have different options in their context menus, which you can open by right-clicking on various interface elements or by clicking on the `···` icon.

Below is the list of entities and elements where the **Context menu** is available:

* [Chats Page](/pages-and-ui-elements/chats-page.md)
  * Workspace name;
  * Chats in the chat list;
  * Header section in the Unread tab of the chat list;
  * Chat header;
  * Message in chat;
  * Breadcrumbs in chat header;
  * User avatar and name in chat;

<figure><img src="/files/W9cKRrAIwuHFNZwm19S5" alt=""><figcaption></figcaption></figure>

* [Tasks Page](/pages-and-ui-elements/tasks-page.md)
  * Workspace name;
  * Custom Views;
  * Project block header;
  * Projects in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block);
  * Teams in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#teams-block);
  * Project, view, or team header;
  * Layout tabs in project, view and team;
  * Tasks in list and kanban views;
  * Fields values in list and kanban views;

<figure><img src="/files/ZGR80pex6dg4vo303KBp" alt=""><figcaption></figcaption></figure>

* [Teams Page](/pages-and-ui-elements/teams-page.md)
  * Workspace name;
  * Teams in the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block)
  * Members in the [Teams Page](/pages-and-ui-elements/teams-page.md#members-section)

<figure><img src="/files/tcsXxmbGsM1nRAFJ6QfA" alt=""><figcaption></figcaption></figure>

* [Info Sidebar](/pages-and-ui-elements/info-sidebar.md)
  * `···` icon in the top right corner of the block;
  * Field values in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#info-tab);
  * Subtasks and Related tasks in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#info-tab);
  * Attached files in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#info-tab);
  * Member section in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab);
  * Invite link in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab);
  * Attachments in the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#attachments-tab)

<figure><img src="/files/fYFrlP6WZKAZAZP7gaXn" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/context-menu.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
