---
title: "Use Plugins Offline (Use Plugins with KSE License)"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/offline-plugin.html
---
Katalon Plugin is to extend Katalon Studio's capabilities and integrate the software with your favorite tools. Together with offline features of Katalon Studio Enterprise, using plugins without Internet access is an excellent complimentary feature for you to:

* Install and use all the plugins that are available on Store without the Internet required (Offline Plugins).
* Build your plugins and use them directly in Katalon Studio without publishing on Store ([Private Plugins](https://docs.katalon.com/katalon-studio/docs/private-plugins.html)).

> **Requirements**:
>
> * Your Katalon Studio version must be 7.0 or later.
> * You need an [active license for Katalon Studio Enterprise](https://docs.katalon.com/katalon-studio/docs/license.html#paid-license).

## Using offline plugins

To use any plugins published on Store without accessing the Internet, follow these steps:

1. Get a plugin package from Katalon Store. [Learn more](https://docs.katalon.com/katalon-store/docs/user/getting-started.html#download-plugin-packages).
2. Unzip your downloaded plugin package
3. Move the plugin package to **<project_name>/plugins**
   > Please be noted that *Platform* plugins need storing in the **<project_name>/plugins/platform** folder.
4. Open your project in Katalon Studio and specify the local **Plugins** folder as the plugin repository in Project Settings
5. Click **Reload Plugins**

## Using private plugins

You can learn more about [Private Plugins](https://docs.katalon.com/katalon-studio/docs/private-plugins.html) and how to build them. After having developed a plugin successfully, move the plugin to your project folder **<project_name>/plugins**.

> **Note**: Katalon Studio treats all offline and private plugins stored in your project folder **<project_name>/plugins** as local plugins. In **Project > Settings > Plugins**, specify where Katalon Studio will download plugins.

## Plugin Repository

You're allowed to decide where Katalon Studio will download plugins for a project. Go to **Project > Settings > Plugins**, select one of the following options:

* **Katalon Store and Local**: Katalon Studio will install plugins from Store and the Plugins folder of each project.
* **Katalon Store**: Katalon Studio will install plugins from Katalon Store only.
* **Local**: Katalon Studio will install plugins from the Plugins folder only.
