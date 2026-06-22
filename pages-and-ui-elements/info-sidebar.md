> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/info-sidebar.md).

# Info Sidebar

The **Info Sidebar** is one of the main blocks in Orchestra. All major entities have an associated Info Sidebar, where you can **manage and configure the settings** for each entity.

Here is the list of entities that have an Info Sidebar:

* Workspace;
* Task;
* Project;
* Team;
* Member;
* Channel;
* Group;
* View.

The Info Sidebar follows the same general structure and interface logic across all entities, but the specific features will vary depending on the entity type. Here are the main UI elements of Info Sidebar:

* **Entity icon:** The icon representing the entity. You can change it to an emoji for task chats or modify the icon color for all other chat types. To do this, click on the chat icon and select an emoji or color.
* **Entity name:** The name of the entity. You can edit the name by double-clicking on it.
* **Entity menu button:** Click this button to open the context menu, where you'll find all the actions you can perform on the selected entity. Learn more about context menus here: [Context Menu](/pages-and-ui-elements/context-menu.md)
* **Tabs block:**
  * Info tab;
  * Members tab;
  * Attachments tab;
  * Settings tab.

<figure><img src="/files/c3zNAVI3QHPEcOdhjmUA" alt=""><figcaption></figcaption></figure>

Depending on the entity, the Tabs block will contain a different **set of tabs** tailred to the entity's features and functionality:

<table><thead><tr><th width="187">Entity type</th><th width="114" data-type="checkbox">Info</th><th width="137" data-type="checkbox">Members</th><th width="160" data-type="checkbox">Attachments</th><th data-type="checkbox">Settings</th></tr></thead><tbody><tr><td>Workspace</td><td>true</td><td>true</td><td>true</td><td>true</td></tr><tr><td>Task</td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td>Project</td><td>true</td><td>true</td><td>true</td><td>true</td></tr><tr><td>Team</td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td>Member</td><td>true</td><td>false</td><td>true</td><td>false</td></tr><tr><td>Channel</td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td>Group</td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td>View</td><td>true</td><td>true</td><td>false</td><td>false</td></tr></tbody></table>

To **open the Info Sidebar**, click on the header of an entity or on the Info icon in the top-right corner of the screen.

## Info Tab

The Info tab is the main section of the Info sidebar for any entity. It displays **all the basic info** about the selected entity. Depending on the entity type, the Info tab may include different content.

### Workspace

Here are the main elements in the **Workspace Info Tab**:

* **Description:** Add some text about your company, useful links, and more.
* **Project list:** View all projects you have access to within the workspace.

<figure><img src="/files/nGofyxYSQtAC4jPJSaDG" alt=""><figcaption></figcaption></figure>

### Task

The main elements of the Task Info Tab are:

* **Fields list:** View and modify the fields associated with the task;
* **Description:** Add text about the task, such as details, useful links, etc.;
* **Files:** Attach files by browsing from your device or using drag-and-drop;
* **Subtasks:** Shows all subtasks related to the specific task. You can also create, edit, and delete subtasks if you have the necessary permissions. Here you can read more about permissions and roles: [User Roles](/workspace/user-roles.md);
* **Related tasks:** See all the tasks that are related to a certain one. You can also add or remove tasks there if you have the necessary permissions. Here you can read more about permissions and roles: [User Roles](/workspace/user-roles.md)

<figure><img src="/files/JfAtY40701DSITmXxM3k" alt=""><figcaption></figcaption></figure>

### Project

Here are the main elements in **Project Info Tab:**

* **Fields list:** Here you can see all fields that a project has.
* **Description:** Here you can add info about a project, useful links, and so on.
* **Files:** Here you can attach files by browsing them from your device or using drag-and-drop feature.
* **Tasks list:** Here you can see all tasks you have access to within a project. Also you can create, edit, and delete tasks there if you have necessary permissions. Here you can read more about permissions and roles: [User Roles](/workspace/user-roles.md)

<figure><img src="/files/F2dRHzbg1jNYEHJfZo5A" alt=""><figcaption></figcaption></figure>

### Team

Here are the main elements of the Team Info Ta&#x62;**:**

* **Fields list:** Here you can see all fields that a team has;
* **Description:** Here you can add some text about a team, useful links, and so on.

<figure><img src="/files/OuJ2wOe3SLq1EIkFtCfu" alt=""><figcaption></figcaption></figure>

### Member

Here are the main elements of the Member Info Tab:

* **Member avatar;**
* **Member name**;
* **Fields list:** View all fields that a member possesses;
* **Assigned tasks:** Displays all tasks assigned to a member;
* **Common chats:** See all chats you both participate in;
* **Common workspaces:** See all workspaces you both participate in.

<figure><img src="/files/wsFwJ6KjhPqZtCRH5JB5" alt=""><figcaption></figcaption></figure>

### Channel

The main elements of the Channel Info Tab are:

* **Channel type**;
* **Channel Owner**;
* **Description:** Add some info about the channel.

<figure><img src="/files/hsxIFElGWnEO8OlBkO6o" alt=""><figcaption></figcaption></figure>

### Group

The main elements of the Group Info Tab are:

* **Group Owner**;
* **Description:** Add some info about the group.

### View

The main elements of the View Info Tab are:

* **View Owner**;
* **Description:** Add some info about the view.

## Members Tab

The Members Tab allows you to manage the members of an entity.

<figure><img src="/files/66k6FfJ1eZcgjQxF6ReZ" alt=""><figcaption></figcaption></figure>

Here are the main blocks and UI elements of the Members Tab:

* **Members list:** This list may consist of several blocks depending on the entity you are viewing
  * **Members:** The list of members who are part of the entity;
  * **Who Can View:** This list includes members who aren't directly added to the entity but have access to it due to their Owner or Editor role. Learn more about roles in Orchestra:[User Roles](/workspace/user-roles.md)
  * **Deactivated:** The list of members who were previously part of the entity, but have been deactivated. Learn more about deactivation [Invite and Manage Members](/workspace/invite-and-manage-members.md#deactivate-members)
  * **Publishers (only in channels):** The list of members who have the ability to publish content in a channel.
  * **Subscribers (only in channels):** The list of members who are subscribed to the channel.
* `+` **icon:** Clicking this icon opens a popup where you can add new members to the entity. Here you can read more about adding member to any entity in Orchestra:
  * to Workspace [Invite and Manage Members](/workspace/invite-and-manage-members.md);
  * to Chat [Add and Manage Chat Members](/chats/add-and-manage-chat-members.md);
  * to Project [Add and Manage Project Members](/projects/add-and-manage-project-members.md);
  * to Task [Add and Manage Task Members](/tasks/add-and-manage-task-members.md);
  * to Team [Add and Manage Team Members](/teams/add-and-manage-team-members.md).
* **Members section:** Each block in the Members list contains a Members section. In the Members section, you can view basic info about each member:

  * **Member name**;
  * **Online/Last seen**;
  * **Member role selector:** Click on the role to assign it to the member. Learn more about roles here:[User Roles](/workspace/user-roles.md)

  You can also right-click on a member's name to **open a context menu**. Here you can learn more about it: [Context Menu](/pages-and-ui-elements/context-menu.md)
* **Invite Link:** In this block, you can create an Invite link for the entity. Here you can learn more about invite links: [Invite and Manage Members](/workspace/invite-and-manage-members.md#create-an-invitation-link-in-a-chat)

<figure><img src="/files/mpsVi0qGFuxyuGEh3EPs" alt=""><figcaption></figcaption></figure>

Depending on the entity, the Members tab may include a different set of blocks:

<table><thead><tr><th width="140">Entity type</th><th width="114" data-type="checkbox">Members</th><th width="142" data-type="checkbox">Who Can View</th><th width="129" data-type="checkbox">Deactivated</th><th width="103" data-type="checkbox">Publishers</th><th width="121" data-type="checkbox">Subscribers</th><th width="114" data-type="checkbox">Invite Link</th></tr></thead><tbody><tr><td>Workspace</td><td>true</td><td>false</td><td>true</td><td>false</td><td>false</td><td>true</td></tr><tr><td>Task</td><td>true</td><td>true</td><td>true</td><td>false</td><td>false</td><td>true</td></tr><tr><td>Project</td><td>true</td><td>true</td><td>true</td><td>false</td><td>false</td><td>true</td></tr><tr><td>Team</td><td>true</td><td>true</td><td>true</td><td>false</td><td>false</td><td>true</td></tr><tr><td>Channel</td><td>false</td><td>false</td><td>false</td><td>true</td><td>true</td><td>true</td></tr><tr><td>Group</td><td>true</td><td>true</td><td>true</td><td>false</td><td>false</td><td>true</td></tr><tr><td>View</td><td>true</td><td>false</td><td>true</td><td>false</td><td>false</td><td>false</td></tr></tbody></table>

## Attachments Tab

The Attachments tab collects all pictures, media, documents, and links that were sent in a chat. The tab consists of:

* **List of attachments:** Here you can find all attachments grouped by month.
* **Attachment type selector:** Clicking on the selector displays a dropdown with attachment types: All, Media, Files, Links. Clicking on a type displays only attachments of selected type.

<figure><img src="/files/9Xp0a5w9eda470WAsGwf" alt=""><figcaption></figcaption></figure>

## Settings Tab

The Settings tab is currently available for both workspaces and projects. Both entities have the same settings features related to configuring fields and managing task display and logic.

The main difference between the workspace and project Settings tabs is that the Workspace Settings tab applies to the entire workspace, while the Project Settings tab applies to a specific project.

Settings tab consists of the following blocks:

* **Fields**. In this block, you can manage fields of your workspace or project. Here you can read more about fields and how they work - [Fields](/projects/fields.md)
* **Adjustments**. In this block, you can set up how a task will be displayed on the Tasks and Chats pages.
* **Preferences**. In this block, you can set up chat auto-following. Here you can read more about this feature: [Key Project Features](/projects/key-project-features.md#chats-automatic-following)

To better understand how Settings tab works, please read this document: [Project Settings](/projects/project-settings.md).

<figure><img src="/files/jngxD8IbRlvdH0jyPPzQ" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/info-sidebar.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
