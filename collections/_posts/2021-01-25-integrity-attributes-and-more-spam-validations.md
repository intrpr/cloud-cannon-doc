---
title: Integrity attributes and more spam validations
type: minor
---

This release adds integrity attribute support to the compressor, extra spam validation for forms and easier access to test domains. It also fixes a variety of issues reported through support.

**Features:**

* Compressor now properly handles integrity attributes
* Added secondary spam validation on forms submissions with reCAPTCHA enabled&nbsp;
* Added test domain details to domain settings page

**Fixes:**

* Fixed issue allowing a user to change their own permission within a team
* Fixed issues with adding/cloning array structures using modals
* Fixed issue creating a site from forked templates
* Re-added missing option to copy output URL from images
* Fixed upload of files with special characters
* Fixed issue incorrectly adding front matter delimiters to .yml files on the source editor
* Fixed missing access to Inbox forms
