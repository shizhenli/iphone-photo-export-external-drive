---
title: "Live Photos Not Exporting: Why the Video Track Is Left Behind"
description: "Still images copy but the paired Live Photo video is missing? Diagnose the export setting, file pairing, and drive format that cause live photos not exporting."
seo_title: "Live Photos Not Exporting: Fix Missing Video Track on External Drive"
seo_description: "Still images copy but the paired Live Photo video is missing? Diagnose the export setting, file pairing, and drive format that cause live photos not exporting."
keywords:
  - "live photos not exporting"
date: 2026-11-23T10:14:22+08:00
publishDate: 2026-11-23T10:14:22+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but while still images appear, the paired Live Photo video is missing. This usually means the export process treated Live Photos as stills, or the drive could not accept the paired video file. Here are the checks to run before you assume the clips are lost.

## Check the export source setting

Open the export dialog or the app you used and confirm that the option to include Live Photos or associated media is enabled. If you exported from the Photos app, verify that the selected items show the LIVE badge before copying. If the badge is absent, the source selection is wrong, not the drive.

## Inspect the drive format

Connect the drive and check its format in Finder or Disk Utility. If it is formatted as exFAT or FAT32, the drive may reject the .MOV companion files or split the pair. Reformatting to APFS or Mac OS Extended is the reliable fix, but back up first.

## Verify file pairing

On the drive, each Live Photo should appear as a still (HEIC or JPG) plus a matching .MOV with the same filename stem. If the .MOV is absent, the export skipped the video track. This is the common cause of **live photos not exporting** correctly.

## Run a verification test

Export a single known Live Photo to a test folder on the drive. Confirm that both the still and the .MOV appear and that the filename stems match. If only the still appears, repeat the export with the Live Photo option explicitly enabled.

## Rollback and recovery

Do not delete the original library. Re-export the affected items to a new folder rather than overwriting. If the drive was reformatted, restore the previous backup before retrying. For guided diagnosis,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
