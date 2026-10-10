---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy

**Effective date:** October 10, 2026

## Overview

This privacy policy applies to the Google Cloud project 'rclone' (the "Project"), which I created and use only for my own personal file management. The Project provides the OAuth credentials that allow [rclone](https://rclone.org/), an open-source command-line tool running on my own computer, to access my own Google Drive through the Google Drive API.

The Project is not a public app or service. It is not offered to anyone else, and it has no website, server, or database.

## Who this applies to

The Project is operated by frowzencamper and is used by me alone. If you are not me, you are not expected to use it, and I do not collect any information from you.

## What data is accessed

When I authorize rclone, it can access files and metadata in my own Google Drive account. This access is used only to list, upload, download, sync, and manage my own files.

## How data is used and stored

- All data moves directly between my device and Google's servers. It does not pass through any server operated by me or anyone else.
- OAuth tokens issued by Google are stored locally on my device in the rclone configuration file (`rclone.conf`).
- I do not collect, copy, store, or process Google user data anywhere other than on my own devices and in my own Google Drive.

## Data sharing

I do not sell, share, transfer, or disclose Google user data to any third party. I do not use Google user data for advertising, analytics, profiling, or training any machine learning or AI model.

## Google API Services User Data Policy

The Project's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Data retention and deletion

The only data retained is my own files in my own Google Drive and the token stored in my local rclone configuration. I can delete the token at any time by removing the remote from rclone (`rclone config delete <remote-name>`) or deleting the configuration file.

## Revoking access

Access can be revoked at any time at [myaccount.google.com/permissions](https://myaccount.google.com/permissions) by removing the app named 'rclone'. Once revoked, rclone can no longer access the Drive account.

## Children's privacy

The Project is not directed at children and does not knowingly collect information from anyone.

## Changes to this policy

If this policy changes, I will update the effective date at the top of this page.

## Contact

Questions about this policy can be raised by [opening an issue](https://github.com/frowzencamper/frowzencamper.github.io/issues) on this site's GitHub repository.
