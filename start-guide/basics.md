> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/start-guide/basics.md).

# Basics

<figure><img src="/files/ur9LMzj01qEmKxqlFpMm" alt=""><figcaption></figcaption></figure>

## Workspace

Orchestra workspace serves as the central hub for all chats, tasks, teams, and other elements related to a company. The most common approach is to have a single workspace for the entire organization.

As a user, you can be a member of multiple workspaces and easily switch between them using the dropdown menu on the workspace icon in the top-left corner of the app. Each workspace has a unique URL, formatted as  orch.so/example. When you log in to Orchestra, you are accessing a specific workspace.

## Chat

Chats are the core collaboration feature in Orchestra, serving as hubs for various work processes. They enable messaging, calls, task management, and documentation.

There are seven types of chats in Orchestra, each designed for a specific purpose. Depending on your company's workflow, a chat can represent a project, task, CRM card, event, info channel, and more.

Chats are always accessible from the [Chats Page](/pages-and-ui-elements/chats-page.md).

## Task

A **task** is a fundamental concept in Orchestra, similar to task management software you may already be familiar with. Every task has its own dedicated chat.

There are only two properties required to create a task - name and status - for quick task setup.

Tasks support four levels of nesting,  customizable fields, and relations. Basic task fields include project, status, priority, assignee, and due date. Relations connect tasks with for better workflow management.&#x20;

## Project

A project forms the foundation of task management in Orchestra. Each project has a dedicated page containing all associated tasks.

Projects have all essential features to organize team work: a dedicated chat, custom views and fields, two-level nesting structure, sorting, grouping, and filtering. Projects can also be shared across teams and departments.

## Team

A team helps organize people into groups based on company structure or workflow needs. Teams can be assigned to projects and tasks and have a dedicated team chat. Also, teams have their own task page to provide an overview of all assigned tasks.

## Pages

In Orchestra, there are three main pages: Chats, Tasks, and Teams, each representing the basic concepts described above.&#x20;

### Chats page

Chats page contains all chats you have an access to in your workspace. This is where all team communication and collaboration take place.

### Tasks Page

Contains all **projects and tasks** accessible to you. This page provides essential task management features for structuring workflows, creating views, and tracking project progress.

### Teams Page

Designed for managing team members. From here, you can invite or remove teammates, assign roles, create teams, and oversee team activities.

## Additional features

We strive to make Orchestra as simple and intuitive as possible. To achieve this, we minimize unnecessary UI elements and focus on reusing existing components effectively. Two essential elements you will frequently use in Orchestra are the **Info sidebar** and the **Context menu**.

### Info sidebar

All key concepts in Orchestra have their own **info section** located in the Info sidebar. The content of the Info sidebar varies depending on the concept and may include **general information, member lists, attachments, settings,** and more.

We consider the Info sidebar the primary place for managing and configuring different elements within Orchestra. It will continue to be enhanced with new features as Orchestra evolves.

### Context menu&#x20;

In Orchestra, we widely use context menus to simplify and speed up various in-app actions. For example, you can **create or delete tasks, add members, open info panels,** and more with just a few clicks.

Context menus are available for all key concepts and elements in Orchestra. They appear on **right-click** and provide different options depending on the selected entity.


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/start-guide/basics.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
