> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/teams/add-and-manage-team-members.md).

# Add and Manage Team Members

To **manage members in a team**, you must have the Owner or Editor role in it, or be an Owner or Editor of your workspace. To manage team members, navigate to the team [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking on the `Info` icon in the top-right corner of the [Teams Page](/pages-and-ui-elements/teams-page.md) and then on the members tab.&#x20;

From there, you can:

* Add members to the team;
* Remove members from the team;
* Invite new members;
* Set roles for members.

## Adding Members to a Team

* Go to the [Teams Page](/pages-and-ui-elements/teams-page.md);
* In the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block), click on the team to which you want to add members;
* Open the team's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Info` icon in the top-right corner of the screen;
* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking on it;
* Click the `+` button to the right of the Members section;
* In the popup, select the members you want to add to the team, and click the `Add member` button.

## Removing Members from a Team

* Navigate to the [Teams Page](/pages-and-ui-elements/teams-page.md);
* In the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block), click on the team from which you want to remove a member;
* Open the team's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Info` icon in the top-right corner of the screen;
* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking on it;
* Right-click on the member you want to remove;
* Click `Remove member` from the context menu that appears.

## Inviting Members

You can **invite new users directly to a team** using the **team invite link**. Invited users will also join the workspace as members.

* Go to the [Teams Page](/pages-and-ui-elements/teams-page.md);
* In the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block), click on the team to which you want to invite a member;
* Open the team's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Info` icon in the top-right corner of the screen;
* Click the `Copy link` button in the the Invite Link section;
* Send the copied link to the user you want to invite.

## Set Roles for Team Members

* Go to the [Teams Page](/pages-and-ui-elements/teams-page.md);
* In the [Teams Page](/pages-and-ui-elements/teams-page.md#teams-block), click on the team in which you want to set member roles;
* Open the team's [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking the `Info` icon in the top-right corner of the screen;
* Right-click on the member or click on their current role name;
* Select the role you want to assign to the member.

For **more information about roles** in Orchestra, read here: [User Roles](/workspace/user-roles.md)


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/teams/add-and-manage-team-members.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
