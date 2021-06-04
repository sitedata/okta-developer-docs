---
title: Add and configure packages
---
Next you need to add an Okta SDK to your application.

<StackSelector snippet="addconfigpkg"/>

### Configure the package

You need the following values from the Okta Application and the Admin Console that you worked with in <GuideLink link="../create-okta-application">Create an Okta application</GuideLink>:

* **Client ID** &mdash; find it in the applications list or on the application's **General** tab.
* **Client Secret** &mdash; find it on the application's **General** tab.
* **Issuer** &mdash; if you're using your Okta Org authorization server, this is found in the Admin's Console global header in the upper-right corner of the page. If you're using a custom authorization server, you can find the URL in the Admin Console dashboard under **Security** > **API** > **Authorization Servers**.

You can configure the properties of your application with configuration files, environment variables, or other framework specific techniques.

<StackSelector snippet="configmid"/>

<NextSectionLink/>
