> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/projects/add-and-manage-project-members.md).

# Add and Manage Project Members

To manage members in a project, you must have one of the following roles: Workspace Owner/Editor, Project Owner/Editor.&#x20;

To **access the member management options**, navigate to the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking the `Members` icon in the top-right corner of the screen.

From there, you can:

* Add members to the project;
* Remove members from the project;
* Invite members;
* Set roles for members.

## Add members to a project

* Open [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Members` icon in the top-right corner of the screen;
* Click the `+` button to the right of the Members section;
* In the popup, select the members you wish to add and click `Add member` .

## Remove members from a project

* Open [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Members` icon in the top-right corner of the screen;
* Right-click on the member you wish to remove;
* Click `Remove member` in the context menu.

## Invite members

With a **project invite link** you can invite new users directly to project. Users who are invited to the project will also join your workspace as members.

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Members` icon in the top-right corner of the screen;
* Click the `Copy link` button in the the Invite link section;
* Send the link with the user you want to invite.

## Set roles for members

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the project [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Members` icon in the top-right corner of the screen;
* Right-click on a member or click on the current next to their name;
* Select the role you want assign to the member.

For **more information about roles** in Orchestra - see [User Roles](/workspace/user-roles.md)


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/projects/add-and-manage-project-members.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
