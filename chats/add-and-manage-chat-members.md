> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/chats/add-and-manage-chat-members.md).

# Add and Manage Chat Members

To **manage members in a cha**t, you should have the Owner/Editor role in that chat, or be an Owner/Editor of the superior entity. To manage members, go to the chat [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) by clicking on the `Members` icon in the top-right corner of the screen. There you can:

* Add members to a chat;
* Remove members from a chat;
* Invite members;
* Set roles for members.

## Add Members to Chat

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the chat [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking on the `Members` icon in the top-right corner of the screen;
* Click the `+` button to the right of the Members section;
* In the popup, select the members you want to add to chat, and click the `Add member` button.

<figure><img src="/files/Qr3nEneLeepM5W6it7zw" alt=""><figcaption></figcaption></figure>

## Remove Members from Chat

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the chat [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking on the `Members` icon in the top-right corner of the screen;
* Right-click on the member you want to remove;
* Click the `Remove member` action in the context menu that appears.

<figure><img src="/files/bgZlBAigoTYDrQGeeWqD" alt=""><figcaption></figcaption></figure>

## Invite Members

You can **invite new users directly to a chat** using the **chat invite link**. Users invited to a chat will also join the workspace as members, and to a project if you invited them to a task chat.

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the chat [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking on the `Members` icon in the top right corner of the screen;
* Click the `Copy link` button in the the Invite link section;
* Send the link to the user you want to add.

<figure><img src="/files/PwhPuGo1k1dhhJtFz4bF" alt=""><figcaption></figcaption></figure>

## Set Roles for Members

* Open the [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab) in the chat [Info Sidebar](/pages-and-ui-elements/info-sidebar.md) by clicking on the `Members` icon in the top right corner of the screen;
* Right-click on a member or click on the role name;
* Click on the role you want to assign to the member.

Here you can **read more about roles** in Orchestra: [User Roles](/workspace/user-roles.md)

<figure><img src="/files/9d1TxwXP4tqVExHR7Whl" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/chats/add-and-manage-chat-members.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
