<a name="Title"></a>
# Adding Ads to your AppStudio App #

---
<a name="Overview"></a>
## Overview ##

This hands on lab will walk you through the process of adding ads to your AppStudio app.

<a name="Prerequisites"></a>
### Prerequisities ###

The following is required to complete this hands-on lab:
- An app built with AppStudio. If you haven't built an app with app studio, you can follow [this step-by-step hands on lab](https://github.com/agrocholski/windows-phone-app-studio-hol/blob/master/build-your-first-app/hol.md) to do so.
- The source code for your AppStudio app. If you haven't downloaded and built the srouce code for your app, you can follow [this step-by-step hands on lab](https://github.com/agrocholski/windows-phone-app-studio-hol/blob/master/build-the-source-code-for-your-app/hol.md) to do so.
- Visual Studio 2012 or Visual Studio 2013 with the Windows Phone SDK installed.

---
<a name="Exercises"></a>
## Exercises ##

This hands-on lab includes the following exercises:
- [Exercise 1: Registering with pubCenter](#Exercise1)
- [Exercise 2: Add the Windows Phone ad control to your App](#Exercise2)

<a name="Exercise1"></a>
### Exercise 1: Registering with pubCenter ###

In this exercise you will learn how to
- [Sign up for a pubCenter account](#Ex1Task1)
- [Register a mobile application with pubCenter](#Ex1Task2)
- [Create a mobile application ad unit with pubCenter](#Ex1Task3)

<a name="Ex1Task1"></a>
##### Task 1: Sign up for a pubCenter account ####

In this task you will learn how to sign up for a pubCenter account.

1. Open Internet Explorer and navigate to [http://pubcenter.microsoft.com/](http://pubcenter.microsoft.com/).

1. Click the **Sign up now** button

1. If prompted, **Sign in** with your Microsoft account.

1. Confirm or change the information displayed, check the checkbox, and click **Continue**

That's it! You're registered with pubCenter. Proceed to [Task 2](#Ex1Task2) to register your mobile application with pubCenter.

<a name="Ex1Task2"></a>
##### Task 2: Register a mobile application with pubCenter ####

In this task you will learn how to register a mobile application with pubCenter.

1. Open Internet Explorer and navigate to [http://pubcenter.microsoft.com/](http://pubcenter.microsoft.com/).

1. Click the **Sign in with your Microsoft account** link.

1. Enter the credentials associated with your Microsoft account and click the **Sign in** button.

1. Click the **Setup** link at the top of the page

1. Click the **Register application** link

1. Enter the **Name** of your application, select **Windows Phone** for the **Device type**, and click the **Save** button.

1. Once your application is registered, copy the **Application Id**, as you will need it for [Exercise 2](#Exercise2).

<a name="Ex1Task3"></a>
##### Task 3: Create a mobile application ad unit with pubCenter ####

In this task you will learn how to create a mobile application ad unit with pubCenter.

1. Open Internet Explorer and navigate to [http://pubcenter.microsoft.com/](http://pubcenter.microsoft.com/).

1. Click the **Sign in with your Microsoft account** link.

1. Enter the credentials associated with your Microsoft account and click the **Sign in** button.

1. Click the **Setup** link at the top of the page

1. Click the **Create ad unit** link.

1. Enter the **Ad unit name**, select your **Application**, and select the **Ad unit size**.

1. Select the appropriate **Dev Center app category** and **Dev Center app subcategory** (if applicable), then click the **Save** button.

1. Once the ad unit is created, copy the **Ad Unit Id**, as you will need it for [Exercise 2](#Exercise2).

<a name="Exercise2"></a>
### Exercise 2: Add the Windows Phone ad control to your App ###

In this exercise you will learn how to add the Windows Phone advertising control to your app to display ads.

If you have not already downloaded and built the source code for your AppStudio app, please follow this step-by-step guide before proceeding: [https://github.com/agrocholski/windows-phone-app-studio-hol/blob/master/build-the-source-code-for-your-app/hol.md](https://github.com/agrocholski/windows-phone-app-studio-hol/blob/master/build-the-source-code-for-your-app/hol.md).

1. Open the **Solution** file for your source code.

1. Using **Solution Explorer**, open the **1 - UI** folder, expand the **WP8App** project, expand the **View** folder, and double-click the **.xaml** file that corresponds to the menu you create in AppStudio.

1. If the file opens in the visual designer, click the **XAML** button to view the markup of the page.

1. Press **Ctrl + G**, enter **65**, and press the **OK** button.

1. Remove the **comment tags** that surround lines 67-70.

1. Update the **Height** and **Width** attributes of the **AdControl** to match the dimensions of the ad unit you created in [Exercise 1, Task 3](#Ex1Task3).

1. Update the **AdUnitId** attribute of the **AdControl** to the value for the ad unit you created in [Exercise 1, Task 3](#Ex1Task3).

1. Update the **ApplicationId** attribute of the **AdControl** to the value for the mobile application you registered in [Exercise 1, Task 2](#Ex1Task2)

**Note:** You can run your app using the emulator by pressing the **Emulator WVGA 512MB** button in the toolbar. However, live ads will not display in the emulator. In order to view live ads, you need to deploy the app to a Windows Phone.

That's it! You've successfully added ads to your AppStudio app. You can now package it up and submit it to the store.