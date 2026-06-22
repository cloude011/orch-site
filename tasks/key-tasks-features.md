> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/tasks/key-tasks-features.md).

# Key Tasks Features

Orchestra provides a comprehensive task management system that helps streamline workflows and improve productivity. Key task features include:

* Task duplication;
* Archiving;
* Unarchiving;
* Opening archived tasks;
* Drag-and-drop task management;
* Related tasks.

## Duplicating a Task

The Task Duplication feature allows users to quickly create copies of existing tasks, saving time and effort when managing similar work items. It can prove itself useful for recurring tasks, template-based workflows, consistent task assignments, and project scaling.&#x20;

To duplicate a task, do the following steps:

* Navigate to the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
* Find the relevant project and the task you need in it;
* Right-click the task;
* In the appeared context menu, select `Duplicate`.

## Archiving Tasks

Each task in Orchestra can be archived. There are several ways to do it:

* In List layout;
* In Kanban layout;
* In [Info Sidebar](/pages-and-ui-elements/info-sidebar.md).

### Archive Task in List Layout

* Right-click on the task in the tasks list;
* Select `Archive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Archiving a Task in Kanban Layout

* Right-click on the task in Kanban;
* Select `Archive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Archiving Task in Info Sidebar

* Click `...`icon in the top right corner of [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Select `Archive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

## Archived Tasks Block

You can find archived tasks in the Archived Tasks Block on the [Tasks Page](/pages-and-ui-elements/tasks-page.md). To open it, click `Show Archived` in the bottom right corner of the screen. Archived tasks can be viewed within any project or view. If you want to see all archived tasks at once, go to the `All` view and click `Show Archived`.

## Unarchiving Tasks

* From the [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list) on Chats page;
* From the task header;
* From the task [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* From the [#archived-tasks-block](#archived-tasks-block "mention").

#### Unarchiving a Task from Chat List

All archived tasks you have access to are available in [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list). You can use chat list search input to find them. After finding it, follow the next steps to unarchive:

* Right-click on the task chat in the chat list;
* Select `Unarchive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

#### Unarchiving a Task from Task Header

* On the Chats and Tasks pages, right-click on the task header;
* Select `Unarchive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

#### Unarchiving a Task from Task Info Sidebar

* In the top right corner of the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) click on `...` icon;&#x20;
* Select `Unarchive` in the context menu.

#### Unarchiving a Task from Archived Tasks Block

* Open [#archived-tasks-block](#archived-tasks-block "mention");
* Right-click on the task in List or Kanban view;
* Select `Unarchive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Opening Archived Tasks&#x20;

You can open archived tasks in the following ways:

* From [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list) on the Chats page;
* From [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block);
* From [#archived-tasks-block](#archived-tasks-block "mention").

### Opening Archived Tasks from Chat List

All archived tasks you have access to are available in [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list). You can use chat list search input to find them. After that, follow the next steps to unarchive:

* Right-click the task you want to unarchive;
* In the opened context menu, select `Unarchive .`

### Open Archived Tasks from Project Block

**After project archivation, all tasks within the project will also be archived**. To view archived tasks, follow these steps:

* In the Project block, find the Project block header and right-click it;
* In the opened context menu, select `Show archived`;
* All archived tasks will be displayed and colored in gray.

### Opening Archived Tasks from Archived Tasks Block

On the [Tasks Page](/pages-and-ui-elements/tasks-page.md) of your workspace, you can find archived tasks related to a view or a project. To view them, do the following actions:

* Choose the view in the Views block or the project in the Project block;
* In the bottom right corner of the screen, left-click `Show archived`;
* Choose the archived task you would like to interact with.

To get back to current tasks, left-click `Show current tasks`in the bottom right corner of the screen.

## Drag-and-Drop Task Management

Orchestra allows for seamless task organization with drag-and-drop functionality:

* **Rearrange Tasks** – Move tasks within a project by dragging them to a new position in the List or Kanban layout.
* **Move Between Projects** – Drag a task directly into another project using the left sideba**r** on the [Tasks Page](/pages-and-ui-elements/tasks-page.md).
* **Create Nested Tasks** – Drag a task onto another task to establish a hierarchical structure within a project.

This intuitive feature helps streamline task management, making it easy to adjust workflows on the fly.

## Related tasks

The Related Tasks feature in Orchestra enables users to link tasks that are connected, dependent on each other, or share common elements. This provides a clear, contextual view of how different tasks interact, ensuring better workflow coordination and visibility.&#x20;

Here's how it works:

1. **Feature Concept** – A new feature is first discussed and documented in a dedicated task, outlining goals, requirements, and initial ideas.
2. **Design Task** – Once the concept is approved, a separate design task is created to develop wireframes, UI/UX elements, and user flows.
3. **Development Task** – After the design is finalized, developers create their own task to implement the feature, referencing both the concept and design tasks.
4. **QA Task** – Once development is complete, the QA team sets up a testing task to validate functionality, ensure quality, and report any issues.

By linking these tasks, teams gain a **structured workflow**, ensuring transparency, smooth handoffs, and efficient progress tracking across departments.

To **add a related task**:

* Click the task you would like to add a related task to in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#tasks-block) on the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
* Scroll down to the bottom of the task [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Press `+`to the right of the `Related tasks`section;
* Choose the task you need from the list or type its name in the input field.

*You can add single or multiple tasks as related at once.*


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/tasks/key-tasks-features.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
