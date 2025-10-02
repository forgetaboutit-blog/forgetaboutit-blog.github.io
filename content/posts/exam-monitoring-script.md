---
title: "Exam Monitoring Script"
date: 2025-10-02T12:56:06Z
draft: false
toc: false
images:
tags:
  - untagged
---

On Friday 25 September I completed the exam and submitted the report! Managed to get 9 flags. Must admit the report writing is the hard part and don't wait until last minute to start working on the report. Try and capture the steps and screenshots throughout the engagement.
After anxiously waiting for the results I decided to modify an existing python script to monitor the exam result.
As to give something back to the community I adjusted it to make use of Mailgun - to send the email.
It's deployed using GitHub Actions with a cron schedule and can also then be run manually.

https://github.com/livewireza/cbbh-exam-check/blob/main/check_htb_exam.py


