---
title: "Live Photos Not Exporting: Recover the Missing Paired Video After Copy"
description: "Still images copy but the Live Photo video is missing on your external drive? Follow these checks to confirm whether the paired video was skipped and recover it safely."
seo_title: "Live Photos Not Exporting: Restore the Paired Video After Export"
seo_description: "Still images copy but the Live Photo video is missing on your external drive? Follow these checks to confirm whether the paired video was skipped and recover it safely."
keywords:
  - "live photos not exporting"
date: 2026-11-25T11:14:18+08:00
publishDate: 2026-11-25T11:14:18+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, and while the still images arrived, the paired video for each Live Photo did not.

## Confirm what actually landed on the drive

Open the export folder and look at a known Live Photo. On a Mac or PC, a complete pair usually appears as a still (HEIC or JPG) plus a short MOV file sharing the same base name. If you see only the still, the video was skipped, not renamed. If you see both but the video is 0 KB, the copy was interrupted mid-file. Note which case you have before changing anything.

## Check the source before blaming the drive

On the iPhone, open Photos, select that same item, and confirm the LIVE badge is present and the photo plays with motion. If the badge is missing at the source, the item was never a Live Photo and nothing was lost in export. If the badge is present, the export step dropped the video.

## Rule out the drive and cable

The drive must be formatted exFAT or APFS to hold both file types; a FAT32 volume rejects files over 4 GB and can silently skip large videos. Reconnect the drive directly, without a hub, and retry a small batch of five Live Photos. If those five arrive as complete pairs, your earlier batch hit a transfer limit rather than a library problem. This is the most common cause of **live photos not exporting** in bulk.

## Verification test

Export a single Live Photo to a fresh folder. Confirm the still and MOV share a base name and the MOV is larger than 0 KB. Play the MOV to confirm motion.

## Rollback and recovery

Do not delete anything from the iPhone until the verification test passes. If a batch is incomplete, delete only the partial export folder on the drive and re-copy from the iPhone; the originals remain untouched. If pairs still fail after a direct retry,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
