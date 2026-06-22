> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/projects/project-settings.md).

# Project Settings

Each project in Orchestra has its own settings. To **access project settings**:

* Go to the [Chats Page](/pages-and-ui-elements/chats-page.md) or [Tasks Page](/pages-and-ui-elements/tasks-page.md) and select the project you need;
* Click the `Info` icon in the top-right corner of the screen;
* In the Info block that appears, click the Settings tab.

In the project settings, **you can**:

* Manage [Fields](/projects/fields.md);
* Set [Key Project Features](/projects/key-project-features.md#project-privacy);
* Set time for [Key Project Features](/projects/key-project-features.md#task-automatic-archiving);
* Enable or disable [Key Project Features](/projects/key-project-features.md#chats-automatic-following).


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/projects/project-settings.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
