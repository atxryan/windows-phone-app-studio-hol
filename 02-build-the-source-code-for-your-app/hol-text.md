<a name="Title"></a>
# Building the Source Code for your AppStudio App #

---
<a name="Overview"></a>
## Overview ##

This hands on lab will walk you through the process of downloading and building the source code for your AppStudio app.

<a name="Prerequisites"></a>
### Prerequisities ###

The following is required to complete this hands-on lab:
- An app built with AppStudio. If you haven't built an app with app studio, you can follow [this step-by-step hands on lab](https://github.com/agrocholski/windows-phone-app-studio-hol/blob/master/01-build-your-first-app/hol.md) to do so.
- Visual Studio 2012 or Visual Studio 2013 with the Windows Phone SDK installed.

---
<a name="Exercise"></a>
## Exercise ##

1. Open Internet Explorer and sign in to [AppStudio](http://apps.windowsstore.com). Go to your **Dashboard** and select the app you want to download the source code for.

1. Click the **Download Source Code** link.

1. Read the guidance provided for publishing your app, then click **Download**.

1. Right-click on the downloaded zip file and select **Properties**. In the properties dialog that displays click **Unblock**, then click **OK**.

1. Extract the zip file, navigate to the **src** folder and open the **Solution** file using Visual Studio.

1. In Visual Studio, go to the **TOOLS** menu and select **Options**.

1. In the **Options** dialog, find **Package Manager** and make sure the following options are checked:
	- **Allow NuGet to download missing packages**
	- **Automatically check for missing packages during build in Visual Studio**

1. Clean the solution by using the **BUILD** menu.

1. Build the soultion by either pressing **Ctrl+Shift+B** or by using the **BUILD** menu.

1. The solution should now build successfully.