> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/chats-page.md).

# Chats Page

The **Chats page** is where all team communication takes place. You can **manage all your team communications** here: chat with your teammates, conduct meetings, record asynchronous videos, and more.

The Chats page consists of the following blocks:

* Chat list sidebar;
* Chat block;
* [Calls Sidebar](/pages-and-ui-elements/calls-sidebar.md)
* [Info Sidebar](/pages-and-ui-elements/info-sidebar.md)

## Chats list sidebar

The **Chats list sidebar** collects all your chats. It consists of the following elements:

<figure><img src="/files/ugZhT6iNVDVtjtbrd4Ea" alt=""><figcaption></figcaption></figure>

* Create chat icon;
* Search bar;
* Folders;
* Chat list;
* Call island.

### Create chat icon

As the name suggests, you can **create a new chat** by clicking on it. Learn more about creating a chat here: [Chats Basics](/chats/chats-basics.md#creating-a-chat)

<figure><img src="/files/zXHEq5qNxWhSaH1odIdh" alt=""><figcaption></figcaption></figure>

### Search bar

Allows you to **search for specific chats**. When searching, you will see two blocks in the chat list:

<figure><img src="/files/x0Pfa0Q2ITJjemVU9veg" alt=""><figcaption></figcaption></figure>

* **Chats:** This block displays all chats found by their name;
* **Messages:** Displays all chats that contain messages with the text you entered in the search input.

### Folders

**Organize your chats** into different folders for easier access. The following folders are available:

<figure><img src="/files/AWpeSpdfvQRu6Kj4jYWq" alt=""><figcaption></figcaption></figure>

* **All:** Displays all chats you are involved in.
* **Unread:** Displays all chats with new, unread messages.
* **Recent:** Displays chats you have accessed recently, in descending order.
* **Starred:** Lists all chats where you've starred any messages. Here you can read more about Starred messages:  [Key Messages Features](/chats/key-messages-features.md#mark-a-message-as-starred)
* **Favorite:** Shows all chats marked as favorites. You can learn more about Favorite chats here: [Key Chat Features](/chats/key-chat-features.md#make-chat-favorite).
* **Personal:** Displays all personal chats.
* **Assigned to me:** Shows all chats related to tasks assigned to you.
* **Projects:** Contains only project-related chats.
* **Tasks:** Contains only task-related chats.
* **Teams:** Contains only team chats.
* **Groups:** Shows all group chats.
* **Channels:** Displays all channels.

### Unread folder

<figure><img src="/files/vDuiP6wlMyvYx2lMnrin" alt=""><figcaption></figcaption></figure>

The **Unread folder** is divided into several blocks:

* **Mentioned:** Includes all personal chats and chats where you were mentioned.
* **Tasks:** Displays task and project chats with new messages.
* **Channels:** Shows channels with new posts.
* **Updates:** Displays chats that contain only unread system messages.

You can **mark all chats in a specific unread block** as read by following these steps:

<figure><img src="/files/YLJvLv5Esg1aRxUAdbUQ" alt=""><figcaption></figcaption></figure>

* Right-click on the block name of the unread folder;
* Select `Mark as unread` from the context menu.&#x20;

### Chat list

The **Chat list** contains all the chats you have access to. Chats are sorted from the most recent to the oldest based on message timestamps.

Each chat in the list has the following structure:

<figure><img src="/files/KJDu0ZpwEwBrxvcgR4jx" alt=""><figcaption></figcaption></figure>

<figure><img src="/files/F4YqnMM6yL6XMhAeMuHd" alt=""><figcaption></figcaption></figure>

* Chat type or project name for Project chats;
* Chat icon. There are three types of chat icons:
  * A unique icon for each chat type;
  * A custom emoji for Task chats;
  * An avatar for Personal chats.
* Status icon for Tasks chats;
* Chat name or member name for personal chats;
* Last message and its timestamp;
* Counter and mention icon;
* Starred icon;
* Muted chat icon.

To **open a chat**, left-click on it. To **access the context menu**, right-click on a chat.&#x20;

Here you can learn more about [Context Menu](/pages-and-ui-elements/context-menu.md).

You can also **open any chat over opened** by using `Cmd\Ctrl + Left click`. This allows you to quickly switch between chats. Clicking the `Close icon` of the opened chat will bring you back to the previous one.

## Chat block

The **Chat block** consists of four main sections:

* Chat Header;
* Message block;
* Chat Input;
* Calls icon.

### Chat Header

The **Chat header** includes the following elements:

* **Chat icon:** You can switch this to an emoji for task chats or change the icon color for all other chat types. To do this, click on the chat icon and choose an emoji or color.
* **Chat name:** You can edit the chat name by double-clicking it.
* **Task status:** This appears only in task chats.
* **Breadcrumbs:** For task chats, this shows the nesting structure (projects and parent tasks) of the opened chat. Left-click and right-click on the breadcrumbs for the following actions:
  * Left-click: opens the info of the clicked entity;
  * Right-click: opens a context menu.
* **Chat type:** Appears for all chats except task chats.
* **Members icon:** Displays the members of the chat. Clicking this icon opens the Members tab in the Info sidebar.
* **Info icon:** Opens the Info sidebar.
* **Search icon:** Opens a sidebar where you can search through messages.
* **Close icon:** Closes the opened chat.

Right-click on the Chat header to **open the chat context menu**.

### Message block

The **Message block** contains the following elements:

<figure><img src="/files/N8o7CUNjNHGdPc6KOsnS" alt=""><figcaption></figcaption></figure>

<figure><img src="/files/uGqCDz8J3O8iK6vptRpj" alt=""><figcaption></figcaption></figure>

* **Date:** A floating block in the center of the Message block that separates messages by date.
* **Member name and avatar:** Shows the name and avatar of the member who sent the message. Right-click on a member's name or avatar to open a context menu.
* **Messages:** Right-click on a message to open a context menu with actions.
* **Reactions:** If someone reacted to a message, the reaction along with their avatar will appear under the message. Your own reactions are highlighted with a blue border. A `+` icon next to the reactions opens the emoji selector.
* **Message time:** Indicates the time the message was sent.
* **Message status icon:**
  * Grey icon: message was sent to the server;
  * Blue icon: message was delivered;
* **Edited icon:** A pencil icon appears next to the message time if the message was edited.
* **Who read avatars:** Displays the avatars of users who have read the message. These will appear next to the message time.

#### Select messages

You can **select messages** in the Message block by clicking on the message time. Once selected, you can open the context menu and use actions like forwarding messages to another chat. To **unselect messages**, click the **Cancel** button.

### Chat input

The **Chat input** section allows you to:

* Create a message;&#x20;
* Create code block;
* Create mentions;
* Attach files;
* Add emoji.

### Calls icon

The **Calls icon** lets you **start or join a call**. You can learn more useful info about calls here: [Calls Basics](/calls/calls-basics.md).


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/chats-page.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
