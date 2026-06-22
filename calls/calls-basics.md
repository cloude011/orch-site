> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/calls/calls-basics.md).

# Calls Basics

## Overview

In Orchestra, Calls provide an integrated space for seamless voice and video communication within your workspace. You can schedule and join meetings, initiate quick calls with teammates, and collaborate in real time without leaving the app. Whether discussing tasks, brainstorming ideas, or resolving issues, Calls ensure smooth and efficient communication.

Calls have the following UI blocks and elements:

* **Small Call Island:** Located in the bottom-right corner of the screen, it appears after you join a call. It contains the following icons for basic call features:
  * Mic icon: Turns your microphone on or off.
  * Additional features icon: Provides access to additional call features.
  * Expand icon: Opens the Call sidebar.
  * Leave call icon. Clicking this icon will leave or end the call.
* [Calls Sidebar](/pages-and-ui-elements/calls-sidebar.md): The main view for calls, where all call features are available.
* **In-App Call Floating:** This persistent block appears when you switch to another chat or page within Orchestra. It contains icons for all the basic call features. You can click the call floating block from the [Chats Page](/pages-and-ui-elements/chats-page.md#chats-list-sidebar) on the [Chats Page](/pages-and-ui-elements/chats-page.md) to get back to the chat where you have a call.
* **Global Call Floating:** This block appears when you switch to another app, containing icons for Mic, Video, and Leave.

## **Starting and Leaving a Call**

* You can **start a call** from any chat by clicking the Start Cal**l** icon, located to the right of the chat input field at the bottom of the screen.
* To **leave a call**, click the Leave Call icon, which appears in the Small Call Island when you're on a call.

## **Identifying Active Calls**

Chats with active calls are marked with a **special call indicator** on the chat icon, making it easy to spot where conversations are happening.

You can see the **avatars of call participants** above the **Small Call Island** in the chat or next to the chat icon in the **chat list** within the sidebar.

## **Call Recording**

You can record a call by clicking the Record button on the Call Island or by opening the context menu (clicking `...`on the Small Call Island).

Once a call ends, **recordings are automatically added** **to the chat** where the call took place, ensuring easy access to past discussions.

## **Adjusting the Call Screen**

To **resize the call screen** and see the content behind it, hold the drag icon on the separator of the call screen. **Drag left or right** to adjust the size according to your needs, allowing for a more flexible viewing experience.


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/calls/calls-basics.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
