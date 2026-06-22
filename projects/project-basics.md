> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/projects/project-basics.md).

# Project Basics

## Overview

A **Project** is the next level in the hierarchy after a workspace and serves as the primary organization unit for all your tasks.&#x20;

With projects, you can **structure your workspace in any way to fit your needs**. For instance, you can create projects for each of your clients or departments, populate them with tasks, add members, assign roles, and get to work.

[Tasks Page](/pages-and-ui-elements/tasks-page.md) is where you'll primarily work with your projects. In the left sidebar, you'll see a list of all your projects. To **view the tasks** within a specific project, simply select it from the list.

<figure><img src="/files/SRP5IfLnuNMlKnpEVSX6" alt=""><figcaption></figcaption></figure>

## Project Chat

Each project has its own dedicated **chat,** where you can communicate with your team regarding project-related matters. You can **access a project chat** in three main ways:

1. From [Chats Page](/pages-and-ui-elements/chats-page.md): Find the project in the chat list and click on it;
2. From [Tasks Page](/pages-and-ui-elements/tasks-page.md):
   1. Find the project in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#tasks-block);
   2. Hover over the project name;
   3. Click the chat icon that appears to the right of the project name.
3. From Project Info:
   1. Click on the project on Tasks page;
   2. Click the `Info`icon in the top-left corner of the screen;
   3. Click the chat icon in the top-left corner of the Info block.

## Project Nesting

Orchestra supports **two levels of project nesting**, allowing you to organize your projects into a clear hierarchy, like:

* Product development
  * Product design
  * Frontend
  * Backend
* Marketing
  * Landing page
  * FB campaigns

You can nest projects in three ways:

* By dragging the project to the second level of nesting. Here's how you can do it:
  * Open [Tasks Page](/pages-and-ui-elements/tasks-page.md);
  * Hover over the project you want to nest in the[Tasks Page](/pages-and-ui-elements/tasks-page.md#tasks-block);
  * Click and hold the `Drag` icon;
  * Move the subproject to the right and below the parent project you want to nest it under;
  * You can also drag the subproject to the first nesting level (above the parent).
* &#x20;By setting a parent project in the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md):
  * Open [Tasks Page](/pages-and-ui-elements/tasks-page.md);
  * In the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block), click on the project you want to nest under another project;
  * Open the project's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Info` icon in the top-right corner of the screen;
  * Click on the Parent selector;&#x20;
  * Choose the project you want to nest your current project under;
  * To remove the nesting, select `Set no parent` in the Parent field selector.
* By creating a subroject. Here you can read more about it: [#create-a-subproject](#create-a-subproject "mention").

## Create a Project

You can **create a new project** from the following pages:

1. Chats page;
2. Tasks page.

### Create a Project on the Chats Page

<figure><img src="/files/WEYAi4KdcsMiw4OmDzh0" alt=""><figcaption></figcaption></figure>

* Go to the Chats page;
* Click the `Create New Chat` icon in the top-right corner of the left sidebar;
* Select `Project` from the dropdown menu;
* Enter the project name and press Enter.

This method is convenient if you don't need to set up a project structure right away or if you want to start a conversation about the project immediately.

### Create a Project on the Tasks Page

* Navigate to the Tasks page;
* Find the Projects section in the left sidebar;
* Click the `+` button;
* Enter the project name and press Enter.

Once the project is created, you can add users and start creating tasks.

<figure><img src="/files/oDzhXecoFCFAw3z5ux9d" alt=""><figcaption></figcaption></figure>

### Create a Subproject

To **create a subproject**, you can either drag one project into another in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block), or right-click on a project in the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block) and select `+ Add subproject` from the [Context Menu](/pages-and-ui-elements/context-menu.md).

<figure><img src="/files/LrXl0gKsBjUBRngQd666" alt=""><figcaption></figcaption></figure>

## Delete a Project

You can **delete a project** in three ways:

1. On the Chats page;
2. On the Tasks page;
3. In the Project Info.

*Deleting a project will also delete all data inside the project. This action cannot be undone.*

### Delete a Project on the Chats Page

* Find the project you want to delete in the chat list;
* Right-click on the project;
* In the [Context Menu](/pages-and-ui-elements/context-menu.md), select `Delete`;
* Click `Yes` in the confirmation window.

### Delete a Project on the Tasks Page

* Find the project you want to delete in the left sidebar;
* Right-click on the project name;
* In the [Context Menu](/pages-and-ui-elements/context-menu.md), select `Delete`;
* Click `Yes` in the confirmation window.

### Delete a Project in the Project Info

* On the Chats or Tasks page, select the project you want to delete;
* Open the Project Info by clicking the Info icon in the top-right corner of the screen;
* Click the `...` icon in the top-right corner of the screen;
* In the [Context Menu](/pages-and-ui-elements/context-menu.md), select `Delete`;
* Click `Yes` in the confirmation window.

<figure><img src="/files/xKYuQRUD0RLME36DFXEP" alt=""><figcaption></figcaption></figure>

## Leaving a Project

You can **leave a project** in several ways:

* From the [Tasks Page](/pages-and-ui-elements/tasks-page.md#projects-block) on [Tasks Page](/pages-and-ui-elements/tasks-page.md)
  * Find the project you want to leave;
  * Right-click on the project;
  * In the opened context menu choose `Leave` ;
* From the Project header
  * Open the project you want to leave;
  * Right-click on the Project header;
  * In the opened context menu choose `Leave` ;
* From the Project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md)
  * Left-click on the `...` icon in the top right corner of the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
  * In the opened context menu choose `Leave` .


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/projects/project-basics.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
