---
title: "iPhone Live Photos Missing on External Drive: A Step-by-Step Diagnosis"
description: "Still images copy but Live Photo videos are missing from your external drive? Follow these checks to diagnose and restore the paired video."
seo_title: "iPhone Live Photos Missing on External Drive: Fix the Paired Video"
seo_description: "Still images copy but Live Photo videos are missing from your external drive? Follow these checks to diagnose and restore the paired video."
keywords:
  - "iphone live photos missing external drive"
date: 2026-11-15T19:26:40+08:00
publishDate: 2026-11-15T19:26:40+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You copied your iPhone photo library to an external drive, but now the still images are there while the paired Live Photo videos are nowhere to be found. This is a common export issue, and we can work through it together.

## Check the export method and file structure

First, confirm how you exported. If you used Finder (macOS) or File Explorer (Windows) to drag photos, Live Photos may appear as separate .HEIC and .MOV files. On the external drive, open the folder and look for files with the same name but different extensions (e.g., IMG_1234.HEIC and IMG_1234.MOV). If you only see .HEIC files, the videos were not copied. Also, check whether your drive is formatted as exFAT or APFS; FAT32 can cause large files to be skipped silently.

## Verify the source on your iPhone

On your iPhone, open Photos, select a Live Photo, and tap the Live badge to ensure it plays. Then go to Settings > Photos and confirm “Transfer to Mac or PC” is set to “Keep Originals” (not “Automatic”). If it was set to Automatic, the export may have converted Live Photos to stills. Change it and re-export a small test batch.

## Run a verification test

Create a new folder on the external drive. Export just five known Live Photos using the same method. After copying, check for both .HEIC and .MOV files. If the .MOV files are present, your original export likely missed them due to a settings or format issue. If they are still missing, the problem is with the export process itself.

## Rollback and recovery note

Before making further changes, keep your original iPhone library intact. Do not delete anything from the phone until you have verified the external drive copy. If you need to re-export, use a new folder to avoid overwriting existing files.

If these steps don’t resolve your **iphone live photos missing external drive** issue,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) for a guided diagnosis.
