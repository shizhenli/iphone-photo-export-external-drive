---
title: "Live Photos Not Exporting: Stop the Stall Before Your Copy Completes"
description: "Troubleshoot a stalled iPhone photo export to an external drive when live photos not exporting prevents the copy from finishing. Step-by-step checks and a verification test."
seo_title: "Live Photos Not Exporting? Fix the Stall Before Copy Completes"
seo_description: "Troubleshoot a stalled iPhone photo export to an external drive when live photos not exporting prevents the copy from finishing. Step-by-step checks and a verification test."
keywords:
  - "live photos not exporting"
date: 2026-11-21T17:18:32+08:00
publishDate: 2026-11-21T17:18:32+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You start copying your iPhone photo library to an external drive, but the progress bar freezes or the export stops before the full library is copied, leaving you unsure whether it is a live photo issue or a drive problem.

## Check the drive and connection first

Open Finder on your Mac and confirm the external drive mounts and shows free space. If it does not appear, reconnect the cable directly to the Mac, not through a hub, and check again. A drive that mounts but shows less free space than the library size will stall partway through. Compare the library size in Photos (File > Get Info) with the drive's available space. If free space is smaller, the export cannot complete; move other files off the drive or use a larger one.

## Isolate the live photo pair

A common cause is a live photo whose paired video cannot be written. In Photos, create a small test album of 20–30 photos that includes several live photos. Export only that album to a folder on the drive. If it completes, the stall is tied to a specific item or to drive capacity, not the whole library. If it stalls again, note the last file name shown before the freeze; that item is the likely culprit. This is where **live photos not exporting** becomes visible as a single stuck pair rather than a general failure.

## Verification test

After removing or converting the suspect live photo (duplicate it, then disable Live in the duplicate), export the same test album again. A clean finish confirms the fix. Then export the full library in smaller batches of 500–1,000 items.

## Rollback and recovery

Do not delete anything from the iPhone until the drive copy is verified. If a batch fails, delete only the partial folder on the drive and re-export that batch. Keep the original library intact as your rollback source. For a guided diagnosis,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult).
