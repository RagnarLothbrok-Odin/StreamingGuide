---
title: Cinebye (Stremio app only)
description: Configure your Stremio addon list once—after you've installed AIOStreams and AIOMetadata
---

# Cinebye (Stremio app only)

## 1) Open Cinebye

- Go to [cinebye.dinsden.top](https://cinebye.dinsden.top/)
- In the category **1 Authenticate**, sign in with your Stremio account details.

## 2) Options (Cinemeta)

In **2 Options**, enable all three:

- ✅ Remove Cinemeta Search
- ✅ Remove Cinemeta Catalogs  
- ✅ Remove Cinemeta Metadata

:::: danger
Disabling Cinemeta is only safe because this guide uses **AIOMetadata** for metadata. Make sure AIOMetadata is installed first.
::::

## 3) Manage addons

- Scroll down to **📦 Manage Addons**
- Click ❌ on all **default** addons (not Cinemeta—leave Cinemeta installed but disabled above)
- Drag to get this order at the top:
  1. **AIOMetadata**
  2. **AIOStreams**
  3. **Cinemeta**

:::: warning
Don’t remove Cinemeta entirely. Keeping it installed (with features disabled) avoids edge cases and crashes.
::::

## 4) Sync

- Scroll up to **⚙️ Sync Addons** → **Sync to Stremio**
