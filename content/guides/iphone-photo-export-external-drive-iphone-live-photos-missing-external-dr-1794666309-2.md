---
title: "iPhone Live Photos Missing on External Drive: Fix the Paired Video"
description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose the export and recover the paired video."
seo_title: "iPhone Live Photos Missing External Drive: Fix Paired Video"
seo_description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose the export and recover the paired video."
keywords:
  - "iphone live photos missing external drive"
date: 2026-11-21T17:15:28+08:00
publishDate: 2026-11-21T17:15:28+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but the still images are there while the paired Live Photo videos are missing. This usually means the export method treated Live Photos as separate files or skipped the video component. Let's diagnose it step by step.

## Check the export method and file structure

First, confirm how you exported. If you used Finder or iTunes to drag photos, Live Photos may be exported as separate .jpg and .mov files. Open the drive and look for .mov files with the same name as your .jpg files. If they exist but are in a different folder, the pairing is broken, not lost. If no .mov files exist at all, the export likely ignored the video component.

## Verify the source on your iPhone

On your iPhone, open Photos, select a Live Photo, and tap the Live badge to confirm the video plays. Then check Settings > Photos > Transfer to Mac or PC. If it's set to Automatic, try changing it to Keep Originals and re-export a small test batch. This often preserves the paired video.

## Run a verification test

Export just five Live Photos using the revised setting. On the external drive, confirm each still has a matching .mov file of similar name. Play one .mov file to ensure it contains the Live Photo motion. If the videos appear, the issue was the export setting. If they still don't, the drive may be formatted in a way that drops metadata; check that it's exFAT or APFS.

## Rollback and recovery note

Before deleting anything from your iPhone, keep the original library intact. If the export is incomplete, delete only the copied files on the external drive and re-export with Keep Originals. For persistent cases where **iphone live photos missing external drive** remains unresolved,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) to review your export log and drive format.
