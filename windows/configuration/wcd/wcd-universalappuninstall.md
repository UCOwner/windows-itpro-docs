---
title: UniversalAppUninstall (Windows 10)
description: This section describes the UniversalAppUninstall settings that you can configure in provisioning packages for Windows 10 using Windows Configuration Designer.
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
author: greg-lindsay
ms.localizationpriority: medium
ms.author: greglin
ms.topic: article
ms.reviewer: 
manager: dansimp
---

# UniversalAppUninstall (reference)


Use UniversalAppUninstall settings to uninstall or remove Windows apps.


## Applies to

| Setting   | Desktop editions | Mobile editions | Surface Hub | HoloLens | IoT Core |
| --- | :---: | :---: | :---: | :---: | :---: |
| [RemoveProvisionedApp](#removeprovisionedapp) | ✔️ |  |  |  |   |
| [Uninstall](#uninstall) | ✔️ | ✔️ | ✔️ |  | ✔️  |

## RemoveProvisionedApp

Universal apps can be *provisioned*. Provisioned means that they're available on the device for installation in user context. When a user runs the provisioned app, the app is then installed for that user. 

Use **RemoveProvisionedApp** to remove app packages that are available on the device. Any instances of the app that have already been installed by a user aren't uninstalled. To uninstall provisioned apps that have been installed by a user, use the [Uninstall](#uninstall) setting.

1. Enter the PackageFamilyName for the app package, and then select **Add**.
2. Select the PackageFamilyName in the Available Customizations pane, and then select **RemoveProvisionedApp**.

## Uninstall

Use **Uninstall** to remove provisioned apps that have been installed by a user.

1. Enter the PackageFamilyName for the app package, and then select **Add**.
2. Select the PackageFamilyName in the Available Customizations pane, and then select **Uninstall**.
