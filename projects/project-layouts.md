> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/projects/project-layouts.md).

# Project Layouts

In Orchestra, each project has two **default layouts**: List and Kanban. You can choose one of these as the default layout to be displayed when you open a project.&#x20;

To **set a default layout**, right-click on the layout name and select `Set as default` from the context menu.

Additionally, you can **create custom layouts** tailored to your specific workflows.

## Default Layouts

There are two main layouts in Orchestra:

* **List layout:** The List layout displays all tasks, including nested tasks and fields. You can edit field values directly in the list by clicking on the field. Tasks can be reordered or nested by dragging them;
* **Kanban layout:** The Kanban layout shows tasks organized by their status. This layout provides a clear visual representation of task progress.

<figure><img src="/files/ybT1yD43Mj5KnLJKA5Nt" alt=""><figcaption></figcaption></figure>

## Custom Layouts

You can **create custom layouts** in projects with different filters, grouping, and sorting applied to tasks. These layouts allow you to **personalize how tasks are displayed** based on your needs.

### Create a Custom Layout

* Click the `+` button to the right from the default layout;
* Enter a name for your custom layout;
* Apply the desired filters, sorting, and grouping options;
* Click `Save` to save your custom layout.

<figure><img src="/files/vmb8KnoOzaK1nCc9s1Rk" alt=""><figcaption></figcaption></figure>

### Edit a Custom Layout

* Right-click on the tab of the custom layout you wish to edit;
* Select `Edit` from the dropdown menu;
* Update the layout name;
* Edit filters, sorting, and grouping as needed;
* Click `Save` to save the changes.

### Delete a Custom Layout

* Right-click on the tab of the custom layout you want to delete;
* Select `Delete` from the dropdown menu.

*Deleting a custom layout is permanent and cannot be undone. There will be no confirmation prompt, and all data associated with the layout will be lost.*

<figure><img src="/files/WWc8t4qj5cTo8AqVYupW" alt=""><figcaption></figcaption></figure>


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/projects/project-layouts.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
