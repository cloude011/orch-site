> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/workspace/invite-and-manage-members.md).

# Invite and Manage Members

## Overview

As a workspace owner or editor, you can **manage members of your workspace** in the following ways:

* Invite members
* Delete members
* Deactivate members

## Invite members

Currently, members can only be invited to your company workspace via **invitation links**. In the future, we'll add additional ways to add members: by email, username, etc.

There are **two ways you can add a new member to your workspace** using invitation links:

* Create an invitation link on the Teams page
* Create an invitation link in a chat

<figure><img src="/files/l6geYPIngEiK2X3o9Gza" alt=""><figcaption></figcaption></figure>

### Create an invitation link on the Teams page

* Go to the Teams page
* In the header, turn on the `Access by link` toggle
* Copy the generated link
* Send the link to the member you want to invite to your workspace

With this method, a new member will be added to your workspace. When this happens, a system message will appear in your workspace chat, notifying everyone that a new member has joined.

### Create an invitation link in a chat

As a workspace owner or editor, you can i**nvite a member directly to any chat** in your workspace. To do so, follow these steps:

* Open the chat you want to invite a member to
* Open the Member section by clicking on the member icon in the top-right corner of the screen
* In the Invite link section, select `as Member`
* Copy the generated link
* Send the link to the user you want to invite to the chat

In this case, the member will join both your workspace and the specific chat where you created the invite link. When a new member joins a chat, a system message will appear both in your workspace chat and in the chat where you created the invite link.

All members you've added to the workspace will be listed on the **Teams page**, in the All and Members sections.

<figure><img src="/files/mdndP1oGyNah3XpAhZeM" alt=""><figcaption></figcaption></figure>

## Delete members

As a workspace owner, you can **remove members from your workspace**. To delete a member, follow these steps:

* Open the Teams page
* Find the member you want to delete
* Right-click on the member's name or left-click on the menu icon in the right side of the member row
* Select `Remove member`

**A member can only be removed if they are not an owner or assignee in any workspace chats.** Otherwise, a modal window will appear, prompting you to reassign their ownership or assignee roles.

Deleting a member from a workspace will completely revoke their access, but will not affect any data they created while working in the workspace.

<figure><img src="/files/xyZ6kauUCSHsoHpkrsGn" alt=""><figcaption></figcaption></figure>

## Deactivate members

In some cases, you may need to **temporarily remove a member from your workspace**. For example, if a member will be absent for a few months and you don't want to continue paying for their account, you can deactivate them.

To **deactivate a member**, follow these steps:

* Open the Teams page
* Find the member you want to deactivate
* Right-click on the member's name or left-click the menu icon on the right side of the member row
* Select `Deactivate member`

The deactivated member will lose access to the workspace. However, all their data, chats, and roles will be saved until you reactivate the member.

Deactivated users who have participated in any chats, task, projects, etc., will be listed in the Deactivated block in the **Members Tab** of the Info Sidebar - [Info Sidebar](/pages-and-ui-elements/info-sidebar.md#members-tab)

<figure><img src="/files/N34F21Nu9XdxPZkxaEgZ" alt=""><figcaption></figcaption></figure>

To **reactivate a member**:

* Open the Teams page
* Find the member you want to reactivate
* Right-click on the member's name or left-click on the menu icon on the right side of the member row
* Select `Reactivate member`

The member will regain access to the workspace, and all their data will be restored.

You can find the list of **all deactivated members** in the Deactivated section of the Teams page [Teams Page](/pages-and-ui-elements/teams-page.md). All deactivated members have the `Deactivated` status in the Members section [Teams Page](/pages-and-ui-elements/teams-page.md#members-section).

<figure><img src="/files/rPuvwHJjrNKJgqyiwXly" alt=""><figcaption></figcaption></figure>

## Invite guests

A Guest is a special role that allows you to **add a user to one or more chats** in your workspace. Guests can only be added to task chats. There is **no limit to the number of guests**, and there is **no charge for their participation**.

The guest role is commonly used to add customers, freelancers, or contractors to specific chats where they are working.

Here is how you can **add a guest** to your workspace:

* Open the chat you want to invite a guest to
* Open the Member section by clicking the member icon in the top-right corner of the screen
* In the Invite link section, select `as Guest`
* Copy the generated link
* Send the link to the user you want invite to the chat

<figure><img src="/files/zZTpkyAVL8Oumuk4kDrb" alt=""><figcaption></figcaption></figure>

## Leave a workspace

To **leave a workspace**, right-click on the workspace name in the top-left corner, then select the Leave action.

<figure><img src="/files/lYOvwNeEHc2NlG50Vhm7" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/workspace/invite-and-manage-members.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
