---
title: "Reconciling an Interrupted iPhone Export When Live Photos Go Missing"
description: "Stalled iPhone photo export to an external drive with missing Live Photos? Follow these technician checks to diagnose the interruption and recover the paired video files."
seo_title: "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
seo_description: "Stalled iPhone photo export to an external drive with missing Live Photos? Follow these technician checks to diagnose the interruption and recover the paired video files."
keywords:
  - "iPhone Export Interrupted or Live Photos Missing: How to Reconcile"
date: 2026-11-21T17:21:38+08:00
publishDate: 2026-11-21T17:21:38+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You started copying your iPhone photo library to an external drive, but the export stalled before finishing and some Live Photos appear to be missing. This is a common interruption pattern, and it can be reconciled without re-copying everything from scratch.

## Check the Drive and Cable First

Disconnect the drive, then reconnect it directly to your Mac or PC (avoid hubs). Open Disk Utility or File Explorer and confirm the drive mounts and shows free space. If the drive disappears or reports errors, stop here: the interruption is a hardware or connection fault, not a photo issue. If it mounts cleanly, proceed.

## Inspect the Partial Export

Open the destination folder and sort by date. Look for a cluster of files ending at a specific timestamp. That timestamp marks where the copy stopped. Now check whether any .HEIC files in that cluster lack their paired .MOV file. A Live Photo is two files; if the .MOV is absent, the export was interrupted between the still and its video.

## Run the Verification Test

Copy just five photos from that timestamp range to a test folder on the drive. If all five copy completely, the original stall was likely a temporary read error. If the copy stalls again at the same point, the source file is damaged or the drive has a bad sector. Note the exact file name where it stops.

## Recover and Resume

For missing Live Photos, re-export only the affected date range using Photos' export original command, not a full library copy. Keep the partial folder intact until the new export verifies. If the drive shows errors, copy the partial export to a second drive before reformatting. This reconciliation step prevents losing already-transferred originals.

If the stall repeats at the same file, the source may need repair. For a guided diagnosis of **iPhone Export Interrupted or Live Photos Missing: How to Reconcile**,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
