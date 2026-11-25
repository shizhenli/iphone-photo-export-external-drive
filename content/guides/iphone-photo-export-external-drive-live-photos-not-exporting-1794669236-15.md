---
title: "Live Photos Not Exporting? Stop the Stall Before the Copy Finishes"
description: "Troubleshoot iPhone photo export to external drive when it stalls before completion. Check Live Photos settings, drive format, and resume safely."
seo_title: "Live Photos Not Exporting: Fix iPhone Export Stalls Before Completion"
seo_description: "Troubleshoot iPhone photo export to external drive when it stalls before completion. Check Live Photos settings, drive format, and resume safely."
keywords:
  - "live photos not exporting"
date: 2026-11-25T10:14:13+08:00
publishDate: 2026-11-25T10:14:13+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You're copying your iPhone photo library to an external drive, but the export starts and then stalls or stops before the whole library is copied.

## Check the Live Photos setting first

Open Settings > Photos on your iPhone. Look at the section for transferring to Mac or PC. If it's set to Keep Originals, Live Photos export as paired .HEIC and .MOV files. If it's set to Automatic, the iPhone may convert them, and some drives or cables choke on the conversion mid-copy. Set it to Keep Originals, then try a small test export of 20–30 photos that include Live Photos. If that batch completes, the setting was the trigger.

## Verify the drive can hold the paired files

Live Photos take roughly twice the space of a still image. On the drive, check free space against your library size. If free space is less than the library size plus 10 percent, the copy will stop near the end. Free up space or use a larger drive, then retry.

## Confirm the drive format

Connect the drive to a computer and check its format. If it's NTFS, the iPhone can often read it but not write reliably, which causes stalls. Reformat to exFAT or APFS after backing up existing data. This is a common reason for **live photos not exporting** while stills copy fine.

## Verification test

Export a folder of 50 photos containing at least 10 Live Photos to the drive. Then open the drive on a computer and confirm each Live Photo has both a .HEIC and a .MOV file with matching names. If all pairs are present, the export path is working.

## Rollback and recovery

If the export stalls again, stop it, eject the drive safely, and delete the partial folder on the drive before retrying. Don't overwrite a partial copy. If the stall repeats after these checks,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with your drive format and the last file name shown before the stop.
