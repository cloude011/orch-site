> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/start-guide/orchestra-flow.md).

# Orchestra Flow

We believe that **Collaboration and Productivity** are not separate processes, but two sides of the same coin. That's why we've created a unified entity — a **Work building block** — in Orchestra. This block brings together all the info about the work you are doing, whether it's a task, idea, or issue you are working on. It includes all useful information about the project: messages, calls, descriptions, fields, deadlines, and more.

This approach bridges the gap between collaboration and productivity tools, helping teams save time, work faster, and become more efficient than ever before.


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/start-guide/orchestra-flow.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
