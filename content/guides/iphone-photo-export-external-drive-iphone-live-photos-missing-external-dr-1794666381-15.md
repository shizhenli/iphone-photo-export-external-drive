---
title: "Live Photo Videos Missing After iPhone Export to External Drive"
description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose and restore the paired video files."
seo_title: "iPhone Live Photos Missing on External Drive: Fix the Paired Video"
seo_description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose and restore the paired video files."
keywords:
  - "iphone live photos missing external drive"
date: 2026-11-21T17:21:38+08:00
publishDate: 2026-11-21T17:21:38+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but the still images are there while the paired Live Photo videos are missing. This is a common export issue, and we can diagnose it step by step.

## Check the export method and file types

First, confirm how you exported. If you used Finder or iTunes to drag photos, Live Photos may be exported as separate .HEIC and .MOV files. Look for .MOV files with the same name as your .HEIC images. If you used a third-party app, check its settings for a "Include Live Photos" or "Export paired video" option. If the option is off, enable it and re-export a small test batch.

## Verify the external drive format

Connect the drive to your computer and check its format. If it is formatted as exFAT or FAT32, it should support the .MOV files. If it is NTFS, macOS may not write to it without additional software, causing silent failures. Reformat to exFAT if needed, but back up existing data first.

## Inspect the export folder structure

Open the export folder on the external drive. Live Photos are often stored in a subfolder named "DCIM" or alongside the images. Use your computer's search to look for .MOV files. If none exist, the export process likely skipped them. This is a known symptom of **iphone live photos missing external drive** scenarios, often due to interrupted transfers or incorrect settings.

## Verification test

Export a single Live Photo from your iPhone to the external drive using the same method. Then check if both the .HEIC and .MOV files appear. If the .MOV is missing, the issue is with the export tool or settings, not the drive.

## Rollback and recovery

If you reformatted the drive, restore from a backup. If the export was interrupted, delete the partial export and start over with a stable connection. For personalized help,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
