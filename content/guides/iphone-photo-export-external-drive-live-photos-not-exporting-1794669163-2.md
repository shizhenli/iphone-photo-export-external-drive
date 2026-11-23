---
title: "Live Photos Not Exporting: Stop the Stall Before Completion"
description: "When your iPhone photo export to an external drive stalls before completion, use these checks to isolate live photos not exporting and resume safely."
seo_title: "Live Photos Not Exporting: Fix the Export Stall"
seo_description: "When your iPhone photo export to an external drive stalls before completion, use these checks to isolate live photos not exporting and resume safely."
keywords:
  - "live photos not exporting"
date: 2026-11-23T09:14:09+08:00
publishDate: 2026-11-23T09:14:09+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You are copying your iPhone photo library to an external drive, and the export starts but stalls or stops before the whole library is copied.

## Check the export source and destination

First, confirm the drive has enough free space for the entire library plus overhead. On iPhone, open Files, long-press the drive, choose Get Info, and compare available space to your photo library size. If free space is less than the library size, the export can stop partway. Free space or use a larger drive, then retry.

Next, verify the drive format is writable. APFS or Mac OS Extended works; NTFS or read-only volumes will fail. If the drive is read-only, reformat it after backing up existing data.

## Isolate **live photos not exporting**

Live Photos are a common stall point because each one is a photo plus a paired video. In Photos, filter by Live Photos and try exporting a small batch of 10 to a test folder on the drive. If that batch completes, the issue is volume or a specific item, not the format. If it stalls, note the last item copied and check whether it is a Live Photo with a large video component.

## Verification test

Create a new folder on the drive named test-export. Export 20 mixed items, including at least five Live Photos. Confirm the folder contains both .HEIC and .MOV files for each Live Photo. If all 20 complete, the export path is healthy.

## Rollback and recovery

If the export stalled, do not delete the source library. Remove only the partial test-export folder, then retry the full export in smaller batches. If the stall repeats at the same item, skip that item and export the rest, then handle it separately.

If these checks do not resolve the stall,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with the last item copied and the drive format.
