---
title: "Reconciling an Interrupted iPhone Photo Export When Live Photos Are Missing"
description: "Still images copy but Live Photo videos are missing from your external drive? Follow these checks to reconcile an interrupted iPhone export and recover paired video files."
seo_title: "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
seo_description: "Still images copy but Live Photo videos are missing from your external drive? Follow these checks to reconcile an interrupted iPhone export and recover paired video files."
keywords:
  - "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
date: 2026-11-14T20:07:16+08:00
publishDate: 2026-11-14T20:07:16+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but the still images arrived while the paired Live Photo videos did not, and you want to reconcile that gap before deciding what to do next.

## Confirm what actually copied

Open the destination folder on the external drive and switch to list view. A complete Live Photo export normally produces a still image plus a short companion video file (often .mov) with a matching name. If you see only .heic or .jpg files, the video half never landed. Next, check the drive's free space and file system: a drive formatted as FAT32 cannot hold files over 4 GB, and a nearly full drive can silently drop items mid-copy. Interpret a full or FAT32 drive as a likely cause of the interruption, not as proof the originals are lost.

## Check the source before re-exporting

On the iPhone, open Photos, select one affected photo, and look for the LIVE badge. If the badge is absent, the item was never a Live Photo and nothing is missing. If the badge is present, the original pair still exists on the device, so the export can be repeated safely.

## Run a verification test

Create a small test folder on the drive. Export five known Live Photos using Files or Image Capture, then count the files. Ten files (five stills, five videos) means the pipeline works; fewer means the transfer is still being interrupted. This is the controlled diagnosis step for **iPhone Export Interrupted or Live Photos Missing: How to Reconcile**.

## Rollback and recovery

Do not delete anything from the iPhone until the test passes. If a partial export exists, move it to a folder named incomplete rather than overwriting it, then re-export the affected range. Keep the originals untouched until the file counts match.

If the counts still disagree,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
