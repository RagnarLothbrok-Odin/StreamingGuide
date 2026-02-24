---
title: AIOMetadata Addon
description: Enhanced metadata addon for better movie and TV show information
---

# AIOMetadata Addon

AIOMetadata replaces default metadata with richer info from TMDB/TVDB plus optional FanArt/RPDB visuals. It also provides a carefully curated collection of catalogs.

## Install and Configure

### 1) Download Prebuilt Config

- Download: [AIOMetadata config](https://share.valhalladev.org/u/aiometadata-config.json?download=true)

### 2) Open the Instance

- Go to: [aiometadata.fortheweak.cloud](https://aiometadata.fortheweak.cloud)

### 3) Import Configuration

- **Configuration** tab → **Import Configuration** → select the file from step 1

### 4) Add API Keys

- **Integrations** tab
  - **TMDB**: paste your [key](/accounts/tmdb#get-your-api-key)
  - **TVDB**: paste your [key](/accounts/tvdb#get-your-api-key-create-an-app)
  - **FanArt**: optional; paste key ([FanArt account](/accounts/fanart))
  - **RPDB**: optional; use `t0-free-rpdb` or your own key ([RPDB account](/accounts/rpdb#option-b-patreon-subscription))
  - **MDBList**: paste your [key](/accounts/mdblist#get-your-api-key)

### Catalog Management
Drag to reorder catalogs in the `Catalogs` page; disable by toggling the 👁️ icon on the corresponding catalog item.

:::: danger Important
Catalog changes aren’t pushed automatically. If you change catalogs in the future, uninstall and reinstall AIOMetadata in your app to refresh. 
::::

### 5) Save and Install

- **Configuration** tab → **Save Configuration** → set a password when prompted → **Save**

#### Stremio
Click **Install** and choose any method (e.g. **Stremio Web**). Confirm to add AIOMetadata.

#### Nuvio
1. Scroll down and copy your **Install URL**.
2. Open your [Nuvio addons page](https://nuvioapp.space/account?tab=addons) (sign in with your [Nuvio account](/install/nuvio) if needed).
3. Click **Add Addon** (in the **Addons** section), paste the URL, set the name (e.g. **AIOMetadata**), then click **Save**.

#### Omni
*Coming soon.*