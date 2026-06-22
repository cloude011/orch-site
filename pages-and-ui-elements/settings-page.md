> For the complete documentation index, see [llms.txt](https://docs.orch.so/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.orch.so/pages-and-ui-elements/settings-page.md).

# Settings Page

This page contains all your personal and workspace settings. You can access the Settings page in two ways:

* Click on your avatar in the bottom-left corner of the screen;
* Click on the workspace icon in the top-left corner of the screen, and in the opened context menu, click on `Workspace settings`.

The Settings page consists of two main blocks:

* Left sidebar (Settings menu): Here you can find all sections of the Settings page.
* Central block: This block displays all the info for the selected Settings section.

<figure><img src="/files/zrT8bKRWjI9rIyHnOpnO" alt=""><figcaption></figcaption></figure>

## Left Sidebar (Settings Menu)

As mentioned, the left sidebar displays all the sections of the Settings page:

* My account
  * My account;
  * Preferences;
* Settings
  * Space settings;
  * Notifications;
  * App config.

<figure><img src="/files/APLaRWyY9oAsBZc00OyW" alt=""><figcaption></figcaption></figure>

### My account

In this section, you can manage your personal account details:

* Edit name: Click on the `Edit` button next to the Name field.
* Edit avatar: Click on the `Edit user avatar` button next to your avatar.
* Edit username: Click on the `Edit` button next to the Username field.
* Edit email: Click on the `Edit` button next to the Email field.
* Edit password: Click on the `Change password` button.
* Sign out from your account: Click on the `Sign Out` button to log out of your account.
* Remove your account: Click on the `Remove account` button and enter your email to delete your account.

<figure><img src="/files/jnfaxpgIgYcRTV5UTMT5" alt=""><figcaption></figcaption></figure>

### Subscription

In this section, you can manage your subscription. Click on the `Manage subscription` button and follow the instructions to make changes.

### Space settings

This section allows you to set up basic workspace settings:

* Set workspace icon: Click the pencil icon next to your current workspace icon to upload a new picture from your device.
* Chats automatic following. Read more about this feature here: [Key Project Features](/projects/key-project-features.md#chats-automatic-following)
* Delete your workspace. You can read about deleting a workspace below: [Settings Page](/pages-and-ui-elements/settings-page.md#deleting-a-workspace)

### Deleting a workspace

To delete your workspace, click on `Delete space` button at the bottom of the Space settings section, then type your workspace name in the opened input and click `Yes, delete space` button. This action can be performed only by the workspace Owner and cannot be undone.

**After deleting a workspace, all data within the workspace will be permanently deleted and cannot be recovered.**

*The Settings page is currently under development and will be significantly improved soon.*


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the `ask` query parameter:

```
GET https://docs.orch.so/pages-and-ui-elements/settings-page.md?ask=<question>
```

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
