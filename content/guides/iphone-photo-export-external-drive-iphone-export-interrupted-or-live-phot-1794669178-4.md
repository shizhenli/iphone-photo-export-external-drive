---
title: "Reconciling an Interrupted iPhone Export When Live Photos Are Missing"
description: "Export stalls before completion and Live Photos go missing? Follow these technician steps to diagnose, reconcile, and resume your iPhone photo export to an external drive."
seo_title: "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
seo_description: "Export stalls before completion and Live Photos go missing? Follow these technician steps to diagnose, reconcile, and resume your iPhone photo export to an external drive."
keywords:
  - "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
date: 2026-11-23T11:14:28+08:00
publishDate: 2026-11-23T11:14:28+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You started copying your iPhone photo library to an external drive, but the export stalled before finishing, and now some Live Photos appear missing. This is a common reconciliation issue, not a sign of permanent loss. Here’s how to diagnose and recover.

## Check the export log and drive connection
First, confirm the export actually stopped. On your Mac, open the Finder window for the external drive and check the modification date of the last copied file. If it’s older than the export start time, the process is stalled. Next, verify the drive is still mounted and has free space. A drive that dismounts mid-copy will silently halt the export. If the drive shows less than 10% free space, the export may have stopped due to insufficient room.

## Inspect for Live Photo pairs
Live Photos consist of a still image and a short video file. In the export folder, look for files with the same name but different extensions (e.g., IMG_1234.HEIC and IMG_1234.MOV). If the .MOV is missing, the export was interrupted before the paired video was written. This is the **iPhone Export Interrupted or Live Photos Missing: How to Reconcile** scenario—the still copied but the video didn’t.

## Verification test
Create a small test album on your iPhone with five Live Photos. Export only that album to a new folder on the drive. After completion, confirm each still has a matching .MOV file. If all five pairs are present, your export method works; the original stall was likely a connection or space issue.

## Rollback and recovery
Do not delete the original photos from your iPhone. If the export is incomplete, safely eject the drive, reconnect it, and re-export only the missing items. For persistent stalls,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) to review your setup. Always keep a backup until you’ve verified every Live Photo pair.
