---
title: "iPhone Live Photos Missing on External Drive: A Controlled Diagnosis"
description: "Still images copy but the paired Live Photo video is missing on your external drive? Follow this controlled diagnosis to confirm whether the export dropped the .MOV half and recover it safely."
seo_title: "iPhone Live Photos Missing External Drive: Diagnose & Fix"
seo_description: "Still images copy but the paired Live Photo video is missing on your external drive? Follow this controlled diagnosis to confirm whether the export dropped the .MOV half and recover it safely."
keywords:
  - "iphone live photos missing external drive"
date: 2026-11-26T09:12:31+08:00
publishDate: 2026-11-26T09:12:31+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but the still images are there and the paired Live Photo videos are not.

## Confirm what actually landed on the drive

Open the export folder on a computer and switch to list view. A complete Live Photo appears as two files sharing a base name: a still (HEIC or JPG) and a short video (MOV). Sort by name and look for stills with no matching MOV. If every still is alone, the export copied only the image half. If some pairs exist, note which ones, because that tells you whether the failure is format-wide or selective.

## Check the source before blaming the drive

On the iPhone, open Photos, select one affected photo, and tap the Live badge. If it plays, the pair exists on the phone and the export is at fault. Then check the drive's format: exFAT or APFS handles both file types; FAT32 can silently drop files during large copies. Also confirm you exported originals, not compatibility versions, since some compatibility exports flatten Live Photos.

## Verification test

Create a new folder on the drive and export five known Live Photos there only. Eject safely, reconnect, and count files. Ten files means pairs survived; five means the video half is still being dropped. This isolates the cause before you touch the full library.

## Rollback and recovery

Do not delete the source library or overwrite the existing export. Keep the partial folder as-is, re-export the affected items into a fresh folder, and compare counts before replacing anything. If pairs still fail, stop and

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with your drive format and file counts. This is a common **iphone live photos missing external drive** symptom, and it is usually fixable without re-importing everything.
