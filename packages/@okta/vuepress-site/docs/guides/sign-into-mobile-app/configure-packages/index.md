---
title: Add and configure packages
---
Next you need to add Okta to your application by installing our SDK.

### Install the SDK

<StackSelector snippet="installsdk"/>

### Configure the SDK

You need the following values from the Okta Application and the Admin Console that you worked with in <GuideLink link="../create-okta-application">Create an Okta application</GuideLink>:

* **Client ID** &mdash; find it in the applications list or on the **General** tab of your app integration.
* **Okta Domain** &mdash; you can find the Okta Domain in the Admin Console's global header in the upper-right corner of the page. Click the section that displays your email and company name.  A drop-down box appears and displays general org information including the full Okta domain (for example, subdomain.okta.com).

> **Note:** Your Okta domain is different from your admin domain. Don't include `-admin` in your Okta domain.

You'll also need the full redirect URI that you defined in <GuideLink link="../define-callback">Define a callback route</GuideLink>.

<StackSelector snippet="configuremid"/>

<NextSectionLink/>
