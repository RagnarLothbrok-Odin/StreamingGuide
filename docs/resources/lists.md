---
title: Lists
description: Discover popular lists and how to add them to your setup
---

# Lists

Adding lists to your configuration can enhance the user experience. It’s a standout feature of the platform and an easy way to keep your streaming catalogs fresh.

This is just a small sample of some available lists.

## Installing MDBLIsts Lists

This guide features a curated set of lists that can be accessed through [AIOMetadata](/addons/aiometadata).

While AIOMetadata itself cannot import Trakt lists directly, it does support importing lists from [MDBLists](https://mdblist.com).

To add MDBLists to AIOMetadata:

1. Open your AIOMetadata configuration.
2. Enter your AIOMetadata password.
3. In the navigation bar, click `Catalogs`.
4. Click on `Manage MDBList Integration`.
5. Follow the on-screen prompts. For most users, `Add Single List by URL` will be the main option, but you can also import more lists as explained in the interface.
6. When finished, select `Save & Close`.
7. In the navigation bar, click `Configuration`.
8. Click `Save Configuration`.
9. Reinstall AIOMetadata: Click `Install` and choose your preferred installation method.

:::: warning
This step is essential, your app will only display your catalogs correctly if you follow this process.
::::

12. Remove the original `AIOMetadata` addon instance, and ensure the new one appears above `AIOStreams`.

:::: danger
Remove the previous `AIOMetadata` instance to prevent duplicate catalogs.
::::

## Installing Trakt Lists

Although this guide doesn’t provide built-in support for importing Trakt lists directly, there are several popular community addons that make it possible:

- [StremThru List](https://stremthru.13377001.xyz/stremio/list/configure)
- [AIOLists](https://aiolists.elfhosted.com/configure)

You can use these addons in a few different ways:
- Add them to AIOMetadata (recommended)
- Add them to AIOStreams
- Add them directly to your app

We recommend using the AIOMetadata method. Here’s how it works:  
First, configure one of the Trakt-capable list addons above and add your desired Trakt lists. Once set up, open [AIOMetadata](/addons/aiometadata), go to the `Catalogs` page, and select `Import Custom Manifest`. Paste the manifest URL from the lists addon to import your Trakt lists into AIOMetadata catalogs.