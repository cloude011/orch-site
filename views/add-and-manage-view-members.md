> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/views/add-and-manage-view-members.md).

# Add and Manage View Members

To **manage members in a view**, you must have the Owner or Editor role in it, or be an Owner or Editor of your workspace. To manage members, go to the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking on the view on the [Tasks Page](/pages-and-ui-elements/tasks-page.md) and then on the Members tab in the view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md).&#x20;

From there, you can:

* Add members to the view;
* Remove members from the view;
* Invite new members;
* Assign roles.

## Adding Members to a View

* Navigate to the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
* Find the view you want to add members to;
* Open the view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by left-clicking the view;
* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Click the `+` button to the right of the Members section;
* In the popup, select the members you want to add to the view, and then click the `Add member` button.

## Removing Members from a View

* Go to the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
* Find the view you want to remove members from;
* Open task's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by left-clicking the view;
* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Right-click on the member you want to remove;
* Select `Remove member` from the context menu that appears.

## Setting Roles for Members

* Go to the [Tasks Page](/pages-and-ui-elements/tasks-page.md);
* Find the view where you want to assign roles;
* Open view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by left-clicking the view;
* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the view's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md);
* Right-click on the member, or click on their current role name;
* Select the role you want to assign to the member.

Here you can **read more about roles** in Orchestra: [User Roles](/workspace/user-roles.md)


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/views/add-and-manage-view-members.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
