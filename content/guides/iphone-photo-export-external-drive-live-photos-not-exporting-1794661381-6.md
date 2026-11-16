---
title: "Live Photos Not Exporting: Why the Paired Video Goes Missing and How to Restore It"
description: "Still images copy but Live Photo videos are missing after export. Learn how to diagnose and fix live photos not exporting to an external drive."
seo_title: "Live Photos Not Exporting: Fix Missing Paired Video on External Drive"
seo_description: "Still images copy but Live Photo videos are missing after export. Learn how to diagnose and fix live photos not exporting to an external drive."
keywords:
  - "live photos not exporting"
date: 2026-11-16T10:13:50+08:00
publishDate: 2026-11-16T10:13:50+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but while the still images appear, the paired Live Photo videos are missing—so you're stuck at the live photos are missing after export step without a clear diagnosis.

## Check the Export Format and Settings

First, confirm whether your export method preserves Live Photos. If you used Finder or iTunes to drag photos, those tools often export only the still image, not the .mov companion. Open the export folder and look for files with the same name but .mov extension. If none exist, the export process likely stripped them. Also, check the source: on your iPhone, go to Settings > Photos and ensure "Transfer to Mac or PC" is set to "Keep Originals" (not "Automatic"). Then re-export a small batch and verify if .mov files appear.

## Verify the External Drive's File System

A drive formatted as exFAT or FAT32 may not support the extended attributes or folder structures needed for Live Photos. Check the drive's format in Disk Utility (Mac) or File Explorer (Windows). If it's not APFS or Mac OS Extended, reformatting may be necessary—but back up existing data first. After reformatting, test with a single Live Photo export.

## Run a Verification Test

Select one Live Photo on your iPhone, export it to the drive, and immediately check for both .jpg and .mov files. If the .mov is present, the issue was likely a batch export glitch; if not, the problem is systemic. Repeat with a different export tool (e.g., Image Capture on Mac) to isolate the cause.

## Rollback and Recovery

If you've already deleted originals from your iPhone after a failed export, do not erase the drive. Use recovery software to scan for .mov files, or re-import from iCloud if synced. Always keep a backup until verification succeeds.

If these steps don't resolve your **live photos not exporting** issue,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) for a guided diagnosis.
