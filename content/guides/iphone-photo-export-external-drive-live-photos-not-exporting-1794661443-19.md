---
title: "Live Photos Not Exporting: Restore the Paired Video After Copying to an External Drive"
description: "Still images copy but the Live Photo video is missing after export to an external drive. Follow these checks to diagnose and restore the paired video."
seo_title: "Live Photos Not Exporting: Fix Missing Paired Video on External Drive"
seo_description: "Still images copy but the Live Photo video is missing after export to an external drive. Follow these checks to diagnose and restore the paired video."
keywords:
  - "live photos not exporting"
date: 2026-11-18T12:18:04+08:00
publishDate: 2026-11-18T12:18:04+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but the still images are there while the paired Live Photo videos are missing.

## Check the export method and file types

First, confirm how you exported. If you used Finder or iTunes to copy the library, Live Photos may be split into separate files: a JPEG/HEIC still and a MOV video. Look in the same folder for a .MOV file with the same base name. If it is absent, the export did not include the video component.

Next, verify the external drive format. A drive formatted as exFAT or FAT32 can handle the files, but some export tools skip non-image files. Check that the drive has enough free space for the video files, which are larger than stills.

## Inspect the source library

On your iPhone, open Photos and find a Live Photo. Tap Edit and confirm the Live Photo badge is present. If the badge is missing, the photo may have been captured without Live Photo enabled, or the video component was removed. In that case, the export is behaving correctly.

## Run a verification test

Export a single known Live Photo to a new folder on the drive. Then check for both the still and the .MOV file. If the .MOV appears, your bulk export method is the issue. If it does not, the source file lacks the video.

## Rollback and recovery

If you moved files and the videos are missing, do not delete the originals. Re-export from the iPhone using a method that preserves Live Photos, such as exporting via Photos app with "Include Live Photo" enabled. Keep a backup of the original library until you confirm the videos are present.

If these steps do not resolve why **live photos not exporting**,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with your export method and drive format.
