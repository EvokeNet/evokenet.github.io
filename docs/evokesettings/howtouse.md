---
sidebar_position: 2
---

# How to use

To accomplish the challenge of flow and User Experience of Evoke, it was necessary to create a plugin to store global specific settings and course level settings for Evoke project.

### Evoke Course Settings

Evoke courses can have extra settings, here we detail all of them.

To access Evoke course settings, you need to navigate through the secondary menu and click on More, and then in Evoke course settings.

![Evoke course settings](/img/local_evokesettings/settings1.png)

#### Course menu items

Some courses can have extra or exclusive navigation menu items. You can setup these links and it will be presented on the secondary top menu bar.

You can use this field to add these extra menu items. Enter each menu item on a new line with format: menu text and a link URL. eg:

```
Announcements|/course/
Team chat|/mod/chat/view.php?id=2
Course forum|/mod/forum/view.php?id=3
```

### Secondary top menu bar

The secondary top menu bar is presented according to the user's permissions.

#### Students view

When a student is inside a course, they can see only these static menu items:

- HQ: when the block HQ is present on the course
- Map: when the block Map is present on the course
- My progress: when the game is enabled in the course
- Marketplace: when the game is enabled in the course

If it was configured extra menu items, then they will be printed in the navigation, like the image below:

![Extra menu items](/img/local_evokesettings/settings4.png)

#### Teachers and site administrators view

People who have permission to configure and edit the course will see different menu items, depending on their role and permissions.

![Administrator secondary menu items](/img/local_evokesettings/settings5.png)

### Redirect users to enroled course

Users who are enroled in only one course are redirected direct to the course after login.

Default Moodle behavior is to redirect these users to frontpage or my page. We removed this step and redirect the users direct to their course, saving up clicks and time, and making the platform more objective for the context of one course in use.
