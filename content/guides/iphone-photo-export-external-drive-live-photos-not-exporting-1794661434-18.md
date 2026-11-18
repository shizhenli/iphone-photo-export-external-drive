---
title: "Live Photos Not Exporting: Fix a Stalled iPhone Photo Export to an External Drive"
description: "Live photos not exporting? Diagnose why your iPhone photo export to an external drive stalls before completion and resume the copy safely."
seo_title: "Live Photos Not Exporting: Fix a Stalled External Drive Export"
seo_description: "Live photos not exporting? Diagnose why your iPhone photo export to an external drive stalls before completion and resume the copy safely."
keywords:
  - "live photos not exporting"
date: 2026-11-18T11:33:31+08:00
publishDate: 2026-11-18T11:33:31+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You started copying your iPhone photo library to an external drive, but the export stalls or stops before the whole library is copied, and you need to know whether Live Photos are the cause.

## Check the drive and connection first

Connect the drive directly to your iPhone or Mac, not through a hub. In Files or Finder, confirm the drive mounts and shows free space larger than your library. If the drive disappears mid-copy, the stall is a connection or power problem, not a photo problem. Also confirm the drive format is writable (APFS or exFAT); a read-only format stops the export early.

## Isolate Live Photos

In Photos, open a stalled item and check whether it is a Live Photo. Then try exporting a small batch of still photos only. If stills finish and Live Photos stall, the paired video is the blocker. This is the common pattern behind **live photos not exporting** during a large external drive copy.

## Verification test

Create a small album of five Live Photos and export that album to a new folder on the drive. If it completes, the drive and cable are fine and the full-library stall is likely a single corrupt pair. If it stalls, export the same five as stills only to confirm the paired video is the trigger.

## Recovery note

Do not delete the original library. If the export stopped partway, delete only the incomplete export folder on the drive, then re-export in smaller batches. Keep the iPhone library intact until the copy verifies.

If the test still stalls,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) with the drive format, cable type, and the batch size that failed.
