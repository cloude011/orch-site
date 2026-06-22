> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/projects/key-project-features.md).

# Key Project Features

All projects in Orchestra come with a variety of features to help you manage your team and workflows efficiently. These features allow you to customize fields, create different layouts, and much more.

Here are the **key project features**:

1. Creating and managing [Fields](/projects/fields.md);
2. Creating and managing [Project Layouts](/projects/project-layouts.md);
3. Project Privacy;
4. Archiving;
5. Opening an archived project;
6. Unarchiving;
7. Task automatic archiving;
8. Chats automatic following.

## Project Privacy

Orchestra offers two **types of projects**:

1. **Regular.**  Projects of this type are visible to all project members, as well as to all Workspace Owners and Editors.
2. **Private.** Projects of this type are only visible to the members specifically added to them. Even Workspace Owners and Editors will not have access unless they are added as members of a private project.

## Archive a Project

Once a project is complete, you can **move it to the archive**. This can be done in the following ways:

* From the [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list) on the Chats page;
* From the Project Header;
* From the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* From the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block) on the Tasks page.

*All tasks within the archived project will also be archived.*

### Archive a Project from the Chat list

* Right-click on the project chat in the chat list;
* Select `Archive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Archive a Project from the Project header

* On the Chats or Tasks page, right-click on the project header;
* Select `Archive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Archive a Project from the Project info sidebar

* Open the Project Info Sidebar;
* In the top-right corner of the sidebar, click the `...` icon;
* Select `Archive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Archive a Project from the Projects section in Tasks

* Right-click on the project name in the Projects section;
* Select `Archive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

### Open an Archived Project

* Right-click on the Projects section header;
* Select `Show archived` from the context menu;
* Click on the project you need.

<figure><img src="/files/zFX1tWH5j5Wbz7JLFPsZ" alt=""><figcaption></figcaption></figure>

### Unarchive a Project

You can **unarchive a project** in the following ways:

* From the Chat List;
* From the Project Header;
* From the Project Info Sidebar;
* From the Projects section in Tasks.

#### Unarchive a project from the Chat list

* Right-click on the project chat in the chat list;
* Select `Unarchive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

#### Unarchive a project from the Project header

* On the Chats and Tasks pages, right-click on the project header;
* Select `Unarchive` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

#### Unarchive a project from the Project Info sidebar

* Open the Project Info Sidebar;
* In the top-right corner of the info sidebar, click the `...` icon;
* Click `Unarchive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

#### Unarchive a project from the Projects section in Tasks

* Right-click on the project name;
* Click `Unarchive` in the [Context Menu](/pages-and-ui-elements/context-menu.md).

<figure><img src="/files/LuJcNdbYFyEJmb3WaMNE" alt=""><figcaption></figcaption></figure>

## Task automatic archiving

For each project in Orchestra, you can set a period after which completed tasks will be automatically archived. To enable this feature, follow these steps:

* Go to the [Chats Page](/pages-and-ui-elements/chats-page.md) or [Tasks Page](/pages-and-ui-elements/tasks-page.md) and select the project you need;
* Click the `Info` icon in the top-right corner of the screen;
* In the Info block that appears, click the Settings tab;
* Toggle the `Automatically archive tasks` option to enable or disable it.

## Chats Automatic Following

As an Owner or Editor of a workspace or project, you can auto-follow for all task chats within the project. This means you will receive notifications from all auto-followed task chats, even if you're not a member of them.

You can enable or disable the auto-follow feature in the following way:

* Go to the [Chats Page](/pages-and-ui-elements/chats-page.md) or [Tasks Page](/pages-and-ui-elements/tasks-page.md) and select the project you need;
* Click the `Info` icon in the top-right corner of the screen;
* In the Info block that appears, click the Settings tab;
* Toggle the `Automatically follow chats` option.


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/projects/key-project-features.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
