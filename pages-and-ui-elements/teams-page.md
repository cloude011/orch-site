> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/teams-page.md).

# Teams Page

The **Teams page** is where you **manage members** of your workspace. From here, you can add or remove workspace members, assign roles, and create teams.

The Teams page consists of the following blocks:

* Left sidebar;
* Members block;
* [Chat Sidebar](/pages-and-ui-elements/chat-sidebar.md);
* [Info Sidebar](/pages-and-ui-elements/info-sidebar.md).

<figure><img src="/files/3j3JHIecd8NOzHZyFCke" alt=""><figcaption></figcaption></figure>

## Left sidebar

The **Left sidebar** contains the following blocks:

* Views block;
* Teams block.

Each block in the left sidebar can be collapsed by clicking on its header.

<figure><img src="/files/p91fX94ctPl1eZnMGdza" alt=""><figcaption></figcaption></figure>

### Views Block

The **Views Block** consists of several sections, each displaying different types of workspace members and their number:

* **All:** Displays all workspace users, regardless of their role or activity status.
* **Members:** Displays only active members of the workspace.
* **Guests:** Displays all guests in the workspace.
* **Bots:** Shows all bots added to a workspace.
* **Deactivated:** Shows all deactivated members of the workspace.

<figure><img src="/files/h6BQZXUdeil17sprOqRr" alt=""><figcaption></figcaption></figure>

### Teams Block

In the **Teams block**, you can **create and manage teams**. The main UI elements in this block are:

* `+` **icon:** Click this icon to create a new team.
* **Teams:** Click on a team to display the list of its members.
* **New messages:** A count of new messages count appears to the right of the team name, indicating how many new messages are in the team chat.

<figure><img src="/files/AR5zCfqgyPjf6yn3iEbL" alt=""><figcaption></figcaption></figure>

## Members Block

In the **Members block**, you can **manage workspace members and teams**. The main UI elements of this block are:

* Teams Header;
* Members section.

<figure><img src="/files/36F7slnHBfVqUp1M4w9T" alt=""><figcaption></figcaption></figure>

In the Members block, you can:

* View members;
* Invite, remove, and deactivate members in the workspace. Learn more about managing workspace members here: [Invite and Manage Members](/workspace/invite-and-manage-members.md);
* Search for members;
* View member info;
* Set member roles. Learn more about roles in Orchestra here: [User Roles](/workspace/user-roles.md)
* Open a chat with a member.

### Teams Header

The **Teams Header** has a similar structure to the Chat Header and Tasks Header[Chats Page](/pages-and-ui-elements/chats-page.md#chat-header), [Tasks Page](/pages-and-ui-elements/tasks-page.md#tasks-header). Regardless of which entity is selected (View or Team), the header will maintain almost similar structure:

* **Entity icon:** The team icon's color can be changed by clicking on it.
* **Entity name:** The name of the team or view.
* **Info icon:** This icon is only visible for teams and opens the Info side bar.
* **Search icon:** Clicking this icon expands the search input, allowing you to search for members.
* **Access link toggle:** This toggle enables or disables the access link to your workspace or team.
* **Access link:** Each entity has its own access link.
* **Renew link icon:** Click this icon will to renew the access link.
* **Copy link icon:** Click this icon to copy the access link.
* **Sorting button:** The sorting button allows you to sort members in the Members section.

<figure><img src="/files/Q4vjkFJR6rXZvHoGZxLD" alt=""><figcaption></figcaption></figure>

### Members Section

The **Members Section** displays all members of the selected view or team. It consists of the following elements:

* **Member name:** Click on the member's name to open their[Info Sidebar](/pages-and-ui-elements/info-sidebar.md).
* **Chat icon:** This icon appears when you hover over any member in the section.
* **Member role:** Indicates the member's role. Learn more about roles here: [User Roles](/workspace/user-roles.md).
* **Member status:** The member's status can be Active or Deactivated. Learn more about status here: [Invite and Manage Members](/workspace/invite-and-manage-members.md).
* **Member username:** A unique name for each member in Orchestra.
* **Member email:** The member's email address.
* **Member phone:** The member's phone number.

Right-click on a member's name to **open a context menu** with available actions for that member. You can click the `...`icon to the right of the Members section as well.

<figure><img src="/files/Cu52L31j2fCfkqGPwpWG" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/teams-page.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
