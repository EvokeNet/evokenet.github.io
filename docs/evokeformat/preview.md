---
sidebar_position: 3
---

# Preview mode

Moodle was not thought to sell courses, so by default, it doesn't have a feature for users to preview courses, and see important data like syllabus, course price, teachers, and more.

With that in mind, we extended Moodle using the course format to allow students to preview courses without having an account, and after login, they can purchase the course, or just enroll in it, if it is a free course.

![Evoke format course view](/img/format_evoke/format5.png)

Now, when guest users access the course link, they will see a course preview, with some configurable data, like the course image and syllabus.

### Allow guests to visit Moodle internal pages

To enable course preview visualization for guest users, you need to configure Moodle to allow guests to access the site.

In order to do it you need to set up two settings in two different places.

1. Go to `Site administration > Plugins > Authentication > Manage authentication` and select the option **Show** on the setting Guest login button.

2. Go to `Site administration > Users > Permissions > User policies` and mark the box of the setting **Auto-login guests**.

This is a Moodle global setting and only needs to be setup once.

### Course setup

All course data related to the course is configured on the course settings.

Course summary and course image are default Moodle fields and are available to be editable on this page.

Courses can also have extra fields and these fields are displayed on the right side of the preview page, just below the course image.

To add/edit course extra fields you first need to go to `Site administration > Courses > Course custom fields` and create your desired fields.

Once created, custom fields will be available to be filled on every course settings page.

### Course enrolments

Students can enter a course in various ways. A teacher can add them manually to the course, they can enroll themselves in the course, they can pay for a course and others. Moodle has a lot of enrolment methods available.

To configure enrolment methods you need to go to the course **Participants** page and at the top left side, on the select field, select the option **Enrolment methods**.

![Course enrolment methods settings](/img/format_evoke/format6.png)

To allow guest users to visit the course and view the preview page, it is necessary to allow guest enrolment method.

If you want to allow students to enroll themselves in the course, you can set up a self enrolment method.

#### Self enrolment with password

It is possible to configure a password to the self enrolment method. Only users who type the right password will be enrolled in the course.

#### Use group enrolment keys

In addition to restricting access to the course to only those who know the key, use of group enrolment keys means users are automatically added to groups when they enrol in the course.

**Note: An enrolment key for the course must be specified in the self enrolment settings as well as group enrolment keys in the group settings.**

In the case you have the following scenario:

- Self enrolment method with password: 123
- Course with Group A and password: 1234
- Course with Group B and password: 12345

If the user type password **123**, the user will be enrolled in the course but without a group.

If the user type password **1234**, the user will be enrolled in the course and automatically added to group A.

If the user type password **12345**, the user will be enrolled in the course and automatically added to group B.