---
title: Perch Activity Log
summary: An event based activity log for the Perch CMS. Useful for keeping track which content editors have published changes and viewing the historical differences.
collection: portfolio
tags: 
    - PHP
    - Perch
accent: "#563DA3"
---

The Perch Activity Log app is a bespoke Perch App for monitoring user activity through the CMS. It makes use of the existing Perch API, including the v2.6 update's introduction of events.

![log-index.png]({{site.baseurl}}/_portfolio/log-index.png)

The listing view was designed to be informative without overloading the user with information as although the app was developed with system administrators in mind, content editors can be granted accessing using the Perch Roles and Priveleges API. The log can be filtered by event type or user account, using the controls at the top, giving those with access a simple but powerful way of identifying which content editor has accessed the CMS. These logs are automatically pruned at user configured intervals.

![detail-view.png]({{site.baseurl}}/_portfolio/detail-view.png)

Accessing the detail view gives a complete history of changes to the content for a region showing replacements, additions and deletions.

Future updates to the app will include greater detail about the user accessing the CMS to alert system administrators of potential account breaches allowing for more proactive management.

### Further Reading

The app is available free and opensource on GitHub

* [Project Page](http://perch-log.jameswigger.co.uk)
* [Repository](https://github.com/Jamesyps/Perch-Activity-Log)
