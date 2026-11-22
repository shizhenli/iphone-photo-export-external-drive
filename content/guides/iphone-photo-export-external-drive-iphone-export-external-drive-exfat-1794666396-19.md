---
title: "iPhone Export to External Drive: Fix 'Format Not Writable' with exFAT"
description: "Troubleshoot the 'format not writable' error when exporting iPhone photos to an external drive. Learn how to check exFAT compatibility and restore write access."
seo_title: "iPhone Export External Drive exFAT: Fix 'Format Not Writable'"
seo_description: "Troubleshoot the 'format not writable' error when exporting iPhone photos to an external drive. Learn how to check exFAT compatibility and restore write access."
keywords:
  - "iphone export external drive exfat"
date: 2026-11-22T11:14:32+08:00
publishDate: 2026-11-22T11:14:32+08:00
draft: false
categories:
  - "Photo Transfer"
category_slug: "photo-transfer"
---

You're copying your iPhone photo library to an external drive, but at the format step, the drive mounts yet neither the iPhone nor your PC can write the export, leaving you stuck before a controlled diagnosis.

## Check the Drive's Format

Connect the drive to your PC. Open Disk Management (Windows) or Disk Utility (Mac). Look at the file system. If it shows NTFS, APFS, or Mac OS Extended, the iPhone cannot write to it. The iPhone requires exFAT or FAT32 for external drives. If it's exFAT, proceed to the next check. If not, you'll need to reformat—but first, back up any data.

## Verify Write Permissions

On Windows, right-click the drive, choose Properties, then Security. Ensure your user account has 'Write' permission. On Mac, right-click the drive, choose Get Info, and check 'Sharing & Permissions' at the bottom. If your account is set to 'Read only', change it to 'Read & Write' and apply to enclosed items. This is a common cause of the **iphone export external drive exfat** failure when the drive is correctly formatted but permissions are wrong.

## Test with a Small File

Create a small text file on your PC and drag it to the drive. If it copies successfully, the drive is writable from the PC. Then, on your iPhone, open Files, navigate to the drive, and try saving a single photo. If it fails, the issue is likely the drive's format or the iPhone's connection. Try a different cable or port.

## Rollback and Recovery

If you reformatted the drive and lost data, stop using it immediately. Use data recovery software to attempt retrieval. If the drive was previously working and you changed permissions, revert them to the original state. Always keep a backup before making changes.

If these steps don't resolve the issue,

![A laptop showing an iPhone photo export folder and file count](/images/service-detail-960.webp "iPhone photo export verification on a laptop")

[Ask for help](/#consult) for a guided diagnosis.
