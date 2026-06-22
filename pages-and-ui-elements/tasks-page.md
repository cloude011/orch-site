> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/tasks-page.md).

# Tasks Page

**Tasks page** is where you can manage and organize projects, tasks, and workflows.

Tasks page consists of the following sections:

* Left sidebar;
* Tasks block;
* Chat sidebar;
* [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* [Calls Sidebar](/pages-and-ui-elements/calls-sidebar.md).

<figure><img src="/files/HejvNcartlfi9CmCGmkM" alt=""><figcaption></figcaption></figure>

## Left Sidebar

Left sidebar contains the following blocks and UI elements:

* Overview / My tasks icon;
* Views block;
* Projects block;
* Teams block.

<figure><img src="/files/KrJbRdM5oPqRqqy78sFe" alt=""><figcaption></figcaption></figure>

Each block in the left sidebar **can be collapsed** by clicking on its header. Right-clicking on a block header opens a context menu with available actions for the selected block.

### Overview / My tasks Icon

This icon toggles between two **task display modes**:

* **Overview mode:** In this mode, you can view all tasks you have access to. This mode is ideal for managers who need to see the big picture of how their teams or the entire company are performing.
* **My tasks mode:** This mode allows you to focus on your tasks. There you only see the tasks where you are listed as the Owner or Assignee.

To **switch between** these two modes, simply click the Overview / My tasks icon and select the desired mode.

<figure><img src="/files/qqYCy0xqNKfKPi6Xg4e5" alt=""><figcaption></figcaption></figure>

### Views Block

In the **Views block**, you can either **use the default views** or **create custom views**. Views allow you to quickly organize and manage your workflows in Orchestra, saving you time by reducing the need for constant searching and filtering of data.

On the right side of each view, you will see a number indicating how many tasks are currently in that particular view.

#### Default views

The following **default views** are available in Orchestra:

* **All:** Displays all tasks from all projects you have access to.
* **Assigned to me:** Shows all tasks assigned to you.
* **Today:** Displays all tasks that are due today.
* **Recently completed:** Shows all tasks completed in the last 24 hours.
* **Expired:** In this view, you will find all tasks that have expired.
* **Archived:** Displays all archived tasks.

<figure><img src="/files/0NXIkZQrVrclTsiBLNWr" alt=""><figcaption></figcaption></figure>

#### Custom views

You can create **custom views** with custom grouping and filtering. Also, you can **share the views** with other workspace members and **assign roles** to them.

How to **create a custom view**:

* Click on `+` to the right of the Views header;
* Enter a name for the new view and press `Enter`;
* Click the view icon in the header to select a color;
* Use filters, sorting, and grouping options to configure the view, then click `Save`;

<figure><img src="/files/JKxHzQnoYccSJ39DfJDy" alt=""><figcaption></figcaption></figure>

**Share a custom** **view** with other members:

* Open the Members tab in the view's Info sidebar by clicking the `Members` icon in the top-right corner of the screen;
* Click `+`  to the right of the Members section;
* In the popup, select the members you want to add and click `Add member` .

<figure><img src="/files/kHoTGhHE9Qs84L8bGP3D" alt=""><figcaption></figcaption></figure>

**Remove members** from a view:

* Open the Members tab in the view's Info sidebar by clicking the `Members` icon in the top-right corner of the screen;
* Right-click on the member you wish to remove;
* Select `Remove member` from the context menu.

**Assign roles** to members:

* Open the Members tab in the view's Info sidebar by clicking the `Members` icon in the top-right corner of the screen;
* Right-click on the member or click the member role selector next to their name;
* Choose the role you want to assign to the member.

Views have their own **role model**. You can learn more about this here: [User Roles](/workspace/user-roles.md#views-role-model)

<figure><img src="/files/HRCcC5DgrbrqFSTOGPB3" alt=""><figcaption></figcaption></figure>

### Projects Block

In the **Projects Block**, you can view and manage all the projects you have access to. Here are the main elements of this block:

* `+` **icon:** Click this icon to create a new project;
* **Search Icon:** This icon appears when you hover over the Projects Block header. Click it to open a search input and search for a project by name;
* **Project List:** Contains all projects and subprojects you have access to;
* **Chat Icon:** This icon appears when you hover over a project and opens the project chat in the[Chat Sidebar](/pages-and-ui-elements/chat-sidebar.md);
* **New Messages:** A count of new messages is displayed to the right of the project name, indicating how many new messages are in the project chat.

You can find **more info about projects and their features** here: [Project Basics](/projects/project-basics.md)

<figure><img src="/files/zfHdnHEHB6EBXaxgMH2u" alt=""><figcaption></figcaption></figure>

### Teams Block

In the **Teams Block**, you will see all the teams you are a part of or have access to based on your role as the Workspace Owner or Editor.

Each team contains all tasks related to its members.

Here are the main elements of this block:

* **Teams List:** Displays all teams you have access to;
* **Chat Icon:** This icon appears when you hover over a team and opens the team chat in the [Chat Sidebar](/pages-and-ui-elements/chat-sidebar.md);
* **New Messages:** A count of new messages is displayed to the right of the team name, indicating how many new messages are in the team chat.

Currently, the Teams Block cannot be modified, but it will be improved with additional features in future updates.

<figure><img src="/files/iz7qkYaPWysLRnMMpPHg" alt=""><figcaption></figcaption></figure>

## Tasks Block

The **Tasks block** is designed to display and manage all your tasks. It consists of the following main elements:

1. Tasks Header;
2. Layout Selector;
3. Filters, Sort, Group, and Fields;
4. Tasks section;
5. Tasks Footer.

<figure><img src="/files/oBl4NEfNfqrxIh1ubtXx" alt=""><figcaption></figcaption></figure>

### Tasks Header

The **Tasks Header** follows the same structure as the Chat Header [Chats Page](/pages-and-ui-elements/chats-page.md#chat-header). Regardless of which entity (View, Project, or Team) is selected, the header structure remains consistent:

* **Entity icon:** The icon representing the current entity. The color can be changed by clicking on it.
* **Entity name**.
* **Members icon:** Displays the members of the current entity. Click to open the Members tab in the Info sidebar.
* **Chat icon:** Opens the project chat in the [Chat Sidebar](/pages-and-ui-elements/chat-sidebar.md).
* **Info icon:** Opens the Info sidebar.
* **Search icon:** Expands a search input where you can search for tasks.

<figure><img src="/files/q98YNg7JLvTJuYcE6Yhx" alt=""><figcaption></figcaption></figure>

### Layout Selector

Here are the basic actions you can perform with layouts:

* **Choose a layout** to display tasks. To do it, click on the layout name.
* **Create a custom layout** for a project. Learn more about creating and managing custom project layouts - [Project Layouts](/projects/project-layouts.md).
* **Set a default view**. Right-click on a view name → `Set as default`.
* **Change the order of layout**s. Click and hold the layout you want to move → drag it to a new position.

<figure><img src="/files/BdKmKdTZsLYVuocMGhxF" alt=""><figcaption></figcaption></figure>

### Filters, Sort, Group and Fields

This section allows you to **filter, sort, group, and configure the fields** in the Tasks Block.&#x20;

You can **read more** about how these features work: [Filters, Sort, Group, and Fields](/tasks/filters-sort-group-and-fields.md)

### Tasks Section

The **Tasks section** displays all the tasks you have access to. In this section, you can:

* Create, edit, and delete tasks;
* Change the order of tasks;
* Nest tasks;
* Open task chats;
* Change the order of fields;
* Set field values;

You can **learn more** about managing tasks and their features here: [#tasks](#tasks "mention")

### Tasks Footer

The **Tasks Footer** currently has two functions:

* Displaying the statuses and quantity of all tasks;
* `Show archived` button, which reveals archived tasks for a project, view, or team.

<figure><img src="/files/VUA0AHH7ri4J2YrGbKxh" alt=""><figcaption></figcaption></figure>

*The Tasks Footer will be enhanced with additional features in future updates.*


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/tasks-page.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
