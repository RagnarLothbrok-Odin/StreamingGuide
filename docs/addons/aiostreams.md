---
title: AIOStreams Addon
description: The main hub and core addon for your Stremio setup
---

# AIOStreams Addon

AIOStreams is the core hub of this setup. It aggregates sources, integrates your debrid provider, manages catalogs, and centralizes configuration - giving you a powerful experience through a single addon.

## Choose an Instance
Select which AIOStreams instance to use. Some are more stable, others get updates first.

- **Official**: [aiostreams.elfhosted.com](https://aiostreams.elfhosted.com) - *Torrentio disabled*
- **Community**: [aiostreams.fortheweak.cloud](https://aiostreams.fortheweak.cloud)
- **Community Nightly**: [aiostreams-nightly.fortheweak.cloud](https://aiostreams-nightly.fortheweak.cloud/)
- **Community**: [aiostreamsfortheweebsstable.midnightignite.me](https://aiostreamsfortheweebsstable.midnightignite.me)
- **Community Nightly**: [aiostreamsfortheweebs.midnightignite.me](https://aiostreamsfortheweebs.midnightignite.me)

:::: warning Recommended
Torrentio is a major addon but is disabled on the official instance. We recommend a stable community-hosted instance if you want Torrentio.
::::

## Install and Configure

### 1) Open Your Chosen Instance
Navigate to the instance you picked [here](#choose-an-instance).

### 2) Import the Template
- Click the save icon (💾) in the sidebar  
- Under “BACKUPS”, click “Import”  
- Click “Import Template”  
- Paste this URL (use the copy button):

  ```text
  https://share.valhalladev.org/u/streaming-guide-configuration-template.json
  ```

  Or [download directly](https://share.valhalladev.org/u/streaming-guide-configuration-template.json?download=true) and use “Import from File”.  
- Select `Go` followed by `Use This Template Now`

### 3) Select Services
Choose which service [providers](/accounts/debrid) you use, then click **Next**.

### 4) Add API Keys
- **Services**: Paste your API token(s) for your [debrid providers](/accounts/debrid#get-your-api-token-you-ll-paste-it-later)
- **TMDB**: Enter both TMDB [tokens](/accounts/tmdb#get-your-api-key)
- **TVDB**: Enter TVDB [token](/accounts/tvdb#get-your-api-key-create-an-app)

Then select **Load Template**.

::: warning
If the instance you selected does **not** support Torrentio, it will have been automatically removed.
:::

### 5) Create Your Configuration
In “CREATE CONFIGURATION”, set a password and click **Create**.

### 6) Install into your app

#### Stremio
Return to the save icon (💾) and click **Install**. Choose any method (e.g., **Stremio Web**) and confirm.

#### Nuvio
1. Return to the save icon (💾) and click **Install**. Copy the URL shown.
2. Open your [Nuvio addons page](https://nuvioapp.space/account?tab=addons) (sign in with your [Nuvio account](/install/nuvio) if needed).
3. Click **Add Addon** (in the **Addons** section), paste the URL, set the name (e.g. **AIOStreams**), then click **Save**.

#### Omni
TODO