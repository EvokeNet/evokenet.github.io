---
sidebar_position: 2
---

# How to use

To accomplish the challenge of flow and User Experience of Evoke, it was necessary to create a plugin to store global specific settings and course level settings for Evoke project.

### Evoke Course Settings

Evoke courses can have extra settings, here we detail all of them.

To access Evoke course settings, you need to navigate through the secondary menu and click on the More, and then in Evoke course settings.

![Evoke course settings](/img/local_evokesettings/settings1.png)

#### Course menu items

Some courses can have extra or exclusive navigation menu items. You can setup these links and it will be presented on the secondary top menu bar.

You can use this field to add these extra menu items. Enter each menu item on a new line with format: menu text and a link URL. eg:

```
Announcements|/course/
Team chat|/mod/chat/view.php?id=2
Course forum|/mod/forum/view.php?id=3
```

### Evoke pages

When we use an CMS like Wordpress it is very simple to create pages for our users, unfortunately Moodle doesn't have this feature easy and clearly. To handle that we create a feature called Evoke Pages.

To manage evoke pages you need to go to:

`Site administration > General > Evoke > Evoke pages`

![Evoke settings pages management](/img/local_evokesettings/settings2.png)

Note you can create new pages, as you can view, edit or delete an existing one.

When you click to create a new page, the following form is presented:

![Evoke settings page creation](/img/local_evokesettings/settings3.png)

Here are all form fields explained:

- **Page title:** The title of your page;
- **Page slug:** The url of your page is composite by the page slug;
- **Show on menu?:** If you choose YES, a link to the page will be created in the primary top navbar;
- **Page content:** The HTML content of your page.

### Redirect users to enroled course

Users who are enroled in only one course are redirected direct to the course after login.

Default Moodle behavior is to redirect these users to frontpage or my page. We removed this step and redirect the users direct to their course, saving up clicks and time, and making the platform more objective for the context of one course in use.
