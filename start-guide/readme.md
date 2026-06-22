> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/start-guide/readme.md).

# Download Orchestra

## Desktop Clients

Orchestra is available as a desktop app for macOS (Apple Silicon and Intel) and Windows. **Download the desktop app** from: [orch.so/download](https://orch.so/download)

### App updates

All Orchestra apps require **manual updates**. When a new update is available, a prompt will appear. Simply click the **Update** button to install the latest version.

{% embed url="<https://ik.imagekit.io/86fakvf50/Orchestra-ProductDoc-Update-Desktop.webm?updatedAt=1719508061511>" fullWidth="false" %}

## Browsers

You can access the Orchestra **web app** by logging in at [orch.so](https://orch.so). The app will open directly in your browser.

Most features available in the desktop app are also accessible in the web version. Orchestra is compatible with most modern browsers. While we recommend using Chrome or Safari, we also strive to support other popular browsers such as Arc, Firefox, and Brave.

## Mobile apps

Orchestra **mobile apps** are available for both **iOS** and **Android**. You can **download** them from:

* **App Store** (iOS)
* **Google Play** (Android)

## Progressive Web App (PWA)

Orchestra is built as a **Progressive Web App** (PWA), allowing you to install it on your desktop using Chrome or Safari.

{% tabs %}
{% tab title="Safari" %}
Open [app.orch.so](https://app.orch.so) in Safari (Sonoma and later versions), click the Share icon, then select *Add to Dock*.

<figure><img src="/files/hB9BGwYgPKffzjo2vML9" alt="" width="375"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/start-guide/readme.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
