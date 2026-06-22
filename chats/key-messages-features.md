> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/chats/key-messages-features.md).

# Key Messages Features

Here are the **main actions you can perform on chat messages** in Orchestra:

1. Send messages;
2. Edit messages;
3. Delete message;
4. Mention users or entities;
5. Media lightbox;
6. Message context menu
   1. React to a message;
   2. Reply to a message;
   3. Forward a message;
   4. Mark a message as starred;
   5. Copy a message;
   6. Select messages;
   7. View "Seen by" info;
   8. Create a task or subtask;
   9. Add a message to the description;
   10. Add a message to the checklist.

## Send messages

To **send messages** in a chat, use the text input field at the bottom of the [Chats Page](/pages-and-ui-elements/chats-page.md#chat-block). You can send text, emojis, and files of any type in a chat.

<figure><img src="/files/5aHjnVCgg3qqoPT10YEi" alt=""><figcaption></figcaption></figure>

### Send message

To **send a text message**, just type it in the input field and press Enter or click the `Send message` icon on the right side of the text input;

### Upload files

You can **add a file to your message** in several ways:

* Click the `Upload file` icon on the left side of the text input field and select the file you want to upload;
* Drag and drop the files directly into the chat;
* Use the hotkeys `cmd+V` (Mac) or `ctrl+V` (Windows) to paste a file from your clipboard.

You can **add multiple files** at once.

After adding a file, a file upload block will appear, where you can **remove files, change their order, or preview** them.

### Add emoji

To **add an emoji** to the message, click the `Emoji` icon to the right of the text input, then select the emoji you want to add from the popup.

## Edit a message

You can **edit a message** in two ways:

* Right-click on the message you want to edit and select `Edit`;
* Press the Up Arrow key on your keyboard to edit the last sent message.

You can edit messages **within 30 minutes** after sending them.

## Delete a message

Right-click on the message and select `Delete`.

## Mentions

In Orchestra, you can **mention various entities and send them as actionable links** in the chat. The following entities can be mentioned:

* Members;
* Projects;
* Tasks;
* Teams;
* Group chats;
* Channels.

To **mention an entity**:

* Type `@` in the text input field;
* A [Broken mention](broken://pages/zyfejAqwD93FxwTvxcHn#mention-selector) will appear. Choose the entity you want to mention;
* Send a message with the mention.

There is **no limitation of the mentions** quantity in a message.

Sent mentions are **highlighted** in chats. You can left-click or right-click on them to **open the mention sidebar or the context menu**.

<figure><img src="/files/lhGWjRSxNi6mGZyiKnFe" alt=""><figcaption></figcaption></figure>

## Media Lightbox

In the **media lightbox**, you can **preview any media files uploaded to a chat**. To open it, click on a media file in the chat.&#x20;

Here are the **actions you can perform with the lightbox**:

* **Slide media files.** Click on the arrows on the left and right sides of the screen or use the arrow keys on your keyboard.
* **Collapse the lightbox.** This allows you to navigate through the app without losing the opened file. To do this, click on the `Collapse` icon in the top-right corner of the lightbox. Collapsed window will appear in the bottom-left corner of the screen. To expand it, click `Expand` in the top-right corner of the window.
* **Zoom.** To zoom an image in or out, use `Zoom in` and `Zoom out` icons in the bottom-right corner of the lightbox.
* **Download files.** Click `Download`  in the bottom-right corner of the screen to save a file directly on your device.
* **Context menu.** Click the `...` icon in the bottom-right corner of the screen to open the[Context Menu](/pages-and-ui-elements/context-menu.md)with the following actions:
  * **Forward:** Forward a file to another chat;
  * **Save as:** Save a file locally on your desktop;
  * **Copy:** Copy a file to your clipboard;
  * **Show message:** Navigate to the original message in the chat which contains the file you’re viewing.

<figure><img src="/files/GCU2oZzzxzZkzwYrOmtA" alt=""><figcaption></figcaption></figure>

## Message context menu

The **Message context menu** contains all the main actions you can perform on a message. To open it, right-click on a message. Here you can read more about [Context Menu](/pages-and-ui-elements/context-menu.md)

### React to a Message

You can **place a reaction** to any message in a chat. To do so, click on the reaction icon to the left of the message context menu. Here, you can select from a set of basic reactions, or click the `+` icon to open a popup with additional reactions available in Orchestra.

All reactions for a message are displayed underneath it in the Reactions block. Reactions with a blue border are the ones you've made.

You can also set a reaction by clicking the `+` icon in the Reactions block.

### Reply to a Message

Use this action to **directly respond to specific messages** in a chat, providing context and keeping conversations organized. Your reply will include a **preview** of the original message for easy reference. Clicking the preview will scroll the chat to the original message that the reply references.

If someone replies to your message,  a `Mention` icon will appear in the chat in the [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list).

### Forward a Message

This action allows you to **share messages with others** by sending them to different chats. This way, you can quickly relay information without retyping or copying the original message. A forwarded message includes a preview of the original message and its source for easy reference.

<figure><img src="/files/md7kW4u0OzA4HGGDHs1W" alt=""><figcaption></figcaption></figure>

### Mark a Message as Starred

You can **mark important messages as starred** for easy access. Three UI elements indicate marked messages:

* `Star` **icon in a chat** **in** [Chats Page](/pages-and-ui-elements/chats-page.md#chat-list): This icon indicates that there is at least one starred message in a chat.
* **Starred folder:** This folder contains all chats with starred messages. Each starred message in the folder is displayed with its own section. If there are multiple starred messages in a single chat, each one will be listed separately in the Starred folder. Messages in the Starred folder are sorted by date, from the latest to the earliest.
* **Starred block in a chat:** The `Star` icon in the top-right corner of the screen indicates that there is at least one starred message in the chat. Clicking this icon scrolls the chat to the starred message and opens the Starred block. In this block, you can navigate through all starred messages using the`Up arrow` and `Down arrow` icons.

All starred messages are **highlighted** in a chat.

<figure><img src="/files/jjHtHi4Zl3xuieXo3KAu" alt=""><figcaption></figcaption></figure>

### Copy a Message

This action **copies the entire message** to the clipboard.

### Select Message

Message selection allows you to perform actions on a group of messages, such as forwarding or deleting multiple messages. To **select a message**, click on the `Select` action icon in the [#message-context-menu](#message-context-menu "mention") or by clicking on the message's timestamp. You can select multiple messages at once.

### Seen By

This feature shows who has seen the message you've selected. Hover over the `Seen by` item in the [#message-context-menu](#message-context-menu "mention") to display all members who have seen the message.

You can also see who has read a message in another way: the last read message by a member is marked with their avatar near the message timestamp. If a message has been read by multiple members, their avatars will be shown. Hovering over the avatars will display a popup with a list of all members who have read the message.

### Create a task and subtasks

You can **create a task** or subtask directly from a message. To do this, click on the `Create task` or `Create subtask` action in the [#message-context-menu](#message-context-menu "mention"). Here’s how this action works:

* A new task or subtask is created. A subtask is created for the original task where the `Create subtask` action was performed.
* The message from which the task was created is linked to the newly created task.
* All messages from which a task was created are sent to the new task.

If the message you want to create a task from includes [Key Messages Features](/chats/key-messages-features.md#mentions) of a member, you can assign the new task to that member by selecting them in the submenu.

<figure><img src="/files/Uhe8eLnwuzSJ9n5nyZ3z" alt=""><figcaption></figcaption></figure>

### Add a message to the description

You can add any message to the chat description in just two clicks. To do this, click on `Add to description`. You can add several messages at once by using [Key Messages Features](/chats/key-messages-features.md#select-message) feature.

### Add a message to the checklist

You can add any message to the chat checklist in two clicks. To do this, hover over the `Add to checklist` in [#message-context-menu](#message-context-menu "mention")and click on `Create new checklist` or select any existing checklist.

<figure><img src="/files/2ECuPA4TV1buSy5N0PHJ" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/chats/key-messages-features.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
