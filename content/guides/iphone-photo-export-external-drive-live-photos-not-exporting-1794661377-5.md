---
title: "Live Photos Not Exporting: Stopping the Stall Before the Copy Completes"
description: "Live Photos not exporting and the copy stalls before completion? Check the drive, file system, and paired video handling, then verify with a small test batch."
seo_title: "Live Photos Not Exporting: Fix the Export Stall Before Completion"
seo_description: "Live Photos not exporting and the copy stalls before completion? Check the drive, file system, and paired video handling, then verify with a small test batch."
keywords:
  - "live photos not exporting"
date: 2026-11-16T09:13:48+08:00
publishDate: 2026-11-16T09:13:48+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You start copying your iPhone photo library to an external drive, but the export stalls or stops before the whole library is copied, leaving you unsure whether the job is paused or broken.

## Check the drive and connection first
Open Finder or File Explorer and confirm the external drive still mounts and has free space larger than the estimated library size. If the drive disappears or shows read-only, stop the export and reconnect it directly, not through a hub. A drive that drops offline mid-copy is the most common reason a copy stops before completion.

## Confirm the file system accepts the files
Check the drive format. ExFAT or APFS handles large libraries and Live Photo pairs. If the drive is FAT32, a single file over 4 GB or a long path can halt the copy. Reformat only after backing up existing drive contents.

## Handle Live Photo pairs as a unit
A Live Photo is a still plus a short video. If your export tool copies only the still, the paired video may be skipped, and the job can appear to stall on that item. When **live photos not exporting** is the symptom, export a small batch containing one Live Photo and confirm both the image and its .mov companion arrive on the drive.

## Verification test
Create a folder with five ordinary photos and one Live Photo. Export that folder to the drive. If all six items appear and the copy finishes, the stall is likely library size or a single corrupt item; retry the full export in smaller batches.

## Rollback and recovery
If the export stopped partway, do not delete the source library. Remove the partial destination folder, remount the drive, and resume from the last completed batch. Keep the original library intact until the full copy verifies.

If the stall repeats at the same item,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with the drive format and the failing file name.
