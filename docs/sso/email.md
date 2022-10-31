---
sidebar_position: 5
---

# Email

You can send emails to the users with Keycloak by just making a simple configuration, 
in this case the sent emails are use for forgot password protocol only. 
Here is the explanation of the requirements needed for doing that and also how to enable 
the forgot password protocol for users in the Evoke realm.




## Configuration

In order to configure the email attributes for Keycloak **first sign in to the administration console**,
then select the realm of Evoke, then browse in the left side bar the section called **Realm Settings**, once there it should appear multiple tabs for the configuration of the realm, 
the one we are interested in is the **Email** tab, click and it should appear the following form.

![img](./resources/email/email-configuration.PNG)

The required fields are:
- **Host**: The Simple Mail Transfer Protocol provided by AWS in the case for Evoke.
- **Port**: Mail submission port.
- **From Display Name**: Nambe of the mail sender (Evokenet).
- **From**: Name of the email address.
- **Enable TLS**: Transport Layer Security must be on.
- **Enable Authentication**: Must be on.
- **Username**: Unique Username from the SMTP Provider.
- **Password**: Unique Password from the SMTP Provider.

**Important!** Test the connection in order to check that the configuration
is working by clicking at the blue button **Test connection**. 




## Enable forgot password

In the same page of the realm settings, click on the tab **Login**, enable the slide that says
**Forgot Password** so it can show a link on login page for users to click on when they have
forgotten their credentials.

![img](./resources/email/forgot-password.PNG)





