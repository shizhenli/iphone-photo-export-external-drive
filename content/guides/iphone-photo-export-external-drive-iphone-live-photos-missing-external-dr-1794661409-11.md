---
title: "iPhone Live Photos Missing on External Drive: Diagnose the Paired Video Loss"
description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose and restore the paired video."
seo_title: "iPhone Live Photos Missing External Drive: Fix Paired Video"
seo_description: "Still images copy but Live Photo videos are missing on your external drive? Follow these checks to diagnose and restore the paired video."
keywords:
  - "iphone live photos missing external drive"
date: 2026-11-17T09:40:25+08:00
publishDate: 2026-11-17T09:40:25+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but now the still images are there while the paired Live Photo videos are missing.

## Check the export method and file types

First, confirm how you exported. If you used Finder or iTunes to drag photos, Live Photos often arrive as separate .HEIC and .MOV files. Look for a .MOV file with the same name as each .HEIC. If you see only .HEIC files, the paired video was not copied. Next, check the drive's format. A drive formatted as exFAT or FAT32 may drop resource forks or metadata that link the pair. Open the drive on a computer and enable hidden files to see if .MOV files exist but are hidden.

## Verify the source on the iPhone

On your iPhone, open Photos, select a Live Photo, and tap the Live badge. If it plays, the pair exists on the phone. Then export that single Live Photo again using the Files app: tap Share > Save to Files, choose the external drive, and enable All Photos Data. Check if both .HEIC and .MOV appear. If only .HEIC appears, the export process is stripping the video.

## Run a verification test

Create a new folder on the drive. Export three known Live Photos using the Files app method above. Eject the drive safely, reconnect it, and inspect the folder. You should see six files: three .HEIC and three .MOV. If the .MOV files are absent, the issue is the export method, not the drive.

## Rollback and recovery

Before retrying, do not delete the original photos from your iPhone. If you used a third-party tool, revert to the default Files app export. If the drive shows .MOV files but they are zero bytes, the copy was interrupted; reformat the drive and recopy. For persistent **iphone live photos missing external drive** cases,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with your drive format and export steps.
