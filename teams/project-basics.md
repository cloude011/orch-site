> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/teams/project-basics.md).

# Teams Basics

## Overview

The [Teams Page](/pages-and-ui-elements/teams-page.md) is where you manage your organization's collaboration. It allows you to create teams, add members, assign roles, and structure your workflow efficiently. With clear role-based permissions, you can ensure the right people have access to the right information. Teams help streamline task assignment, improve communication, and keep all relevant work centralized within a shared space.

## Team Chat

Each team has its own chat, which can be used for team communication related to the project or task. You can access a team chat in three main ways:

1. From the [Chats Page](/pages-and-ui-elements/chats-page.md): find a team in the chat list and click on it;
2. From the [Tasks Page](/pages-and-ui-elements/tasks-page.md):&#x20;
   1. Find a team in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#teams-block);
   2. Hover over the team;&#x20;
   3. Click on the chat icon that appears to the right of the team name.
3. From the [Teams Page](/pages-and-ui-elements/teams-page.md):&#x20;
   1. Select a team on the Tasks page;
   2. Click the info icon in the top left corner of the screen;
   3. Click the chat icon in the top left corner of the Info block.

### Chat with a Team Member

You can also open a private chat with a team member. To do it:

* Navigate to the [Teams Page](/pages-and-ui-elements/teams-page.md);
* Choose the team the member you want to communicate with belongs to;
* Open the team [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Go to the [Teams Page](/pages-and-ui-elements/teams-page.md#members-section);
* Find the member you need and hover over their name;
* Click on the chat icon that appears to the right of the member's name.

## Creating a Team

You can create a new team from the following pages:

1. [Chats Page](/pages-and-ui-elements/chats-page.md);
2. [Teams Page](/pages-and-ui-elements/teams-page.md).

### Creating a Team on the Chats Page

* Go to the Chats page;
* Click `Create New Chat` icon in the top right corner of the left sidebar;
* Choose `Team` in the dropdown menu;
* Enter a team name and press Enter.

### Creating a Team on the Teams Page

* Go to the Teams page;
* Find the Teams section in the left sidebar;
* Click `+` button;
* Enter team name and press Enter.

Once the team is created, you can add users and tasks to it.

## Deleting a Team

You can delete a project in three ways:

1. From the [Teams Page](/pages-and-ui-elements/teams-page.md);
2. From the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
3. From the team's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md).&#x20;

*Deleting a team permanently removes all associated data. This action **cannot** be undone.*

### Deleting a Team on the Teams Page

* Find a team you want to delete in the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block);&#x20;
* Right-click on the team;
* In the opened [Context Menu](/pages-and-ui-elements/context-menu.md) select `Delete` action;
* Click `Yes` in the confirmation window.

### Deleting a Team on the Tasks Page

* Find a team you want to delete in the left sidebar of the Tasks page;&#x20;
* Right-click on the team name;
* In the opened [Context Menu](/pages-and-ui-elements/context-menu.md) select `Delete` action;
* Click `Yes` in the confirmation window.&#x20;

### Deleting a Team in the Team Info Sidebar

* On the Teams or Tasks page, select a team you want to delete;
* Open team Info sidebar by clicking on the team's header;
* Click on the `...` icon in the top right corner of the screen;
* In the opened [Context Menu](/pages-and-ui-elements/context-menu.md) select `Delete` action;
* Click `Yes` in the confirmation window.

## Leaving a Team

You can **leave a team** in several ways:

* From the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block) on [Teams Page](/pages-and-ui-elements/teams-page.md)
  * Find the team you want to leave;
  * Right-click the team;
  * In the opened context menu, select `Leave` ;
* From the Team header
  * Open the team you want to leave;
  * Right-click the team's header;
  * In the opened context menu, select `Leave` ;
* From the Team [Info Sidebar](/pages-and-ui-elements/info-sidebar.md)
  * Left-click on the `...` icon in the top right corner of the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
  * In the opened context menu, select `Leave` .


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/teams/project-basics.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
