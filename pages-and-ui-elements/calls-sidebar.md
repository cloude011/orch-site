> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/calls-sidebar.md).

# Calls Sidebar

The Calls Sidebar is where you can **manage and control calls** with your teammates and colleagues. It opens by clicking the`Expand`icon during a call. The Calls Sidebar is a persistent block that can be displayed on any page of Orchestra while the call is active. You can **adjust the width** of the Call sidebar by dragging its left border.

<figure><img src="/files/DMNAkxQHPn2Y4SHExmVi" alt=""><figcaption></figcaption></figure>

The Calls Sidebar consists of the following UI elements:

* **Chat name:** The name of the chat where the call is taking place;
* **Number of participants:** Displays the number of participants in the call;
* **Call duration**;
* **Call sidebar island:** Located at the bottom of the Calls Sidebar, the Call sidebar island contains from 4 to 9 call icons, depending on the sidebar's width. These icons represent the core features of the call:
  * **Mic icon:** Turns your microphone on/off. Right-click s to choose which microphone to use during the call.
  * **Video icon:** Turns your video on/off. Right-click to choose which camera to use.
  * **Share screen icon:** Starts or stops screen sharing.
  * **Call recording:** Starts or stops the call recording.
  * **Additional features icon:** Provides access to additional call features:
    * **Camera:** Choose which camera to use for the call.
    * **Microphone:** Choose which microphone to used during the call.
    * **Audio output:** Choose the audio output device for the call.
    * **Copy Meeting Link:** Click to copy the invite link for the call.
    * **Choose a view:**
      * **Tile view:** Enables or disables tile view for the call.
      * **Full-screen icon:** Expands or collapses the Calls Sidebar.
      * **Shrink icon:** Closes the Calls sidebar.
      * **Leave a call icon:** Click to leave or end the call.

<figure><img src="/files/rfmVVveIu8WXZfP7wvO9" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/calls-sidebar.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
