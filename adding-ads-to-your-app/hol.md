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
- [Exercise 2: Adding the Ad Control to your App](#Exercise2)

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

	![Sign up now](images/ex1task1-01-sign-up.png "Sign up now")

	_Sign up now_

1. If prompted, **Sign in** with your Microsoft account.

	![Sign in](images/ex1task1-02-sign-in.png "Sign in")

	_Sign in_

1. Confirm or change the information displayed, check the checkbox, and click **Continue**

	![Contact information](images/ex1task1-03-information.png "Contact information")

	_Contact information_

That's it! You're registered with pubCenter. Proceed to [Task 2](#Ex1Task2) to register your mobile application with pubCenter.

<a name="Ex1Task2"></a>
##### Task 2: Register a mobile application with pubCenter ####

In this task you will learn how to register a mobile application with pubCenter.

1. Open Internet Explorer and navigate to [http://pubcenter.microsoft.com/](http://pubcenter.microsoft.com/).

1. Click the **Sign in with your Microsoft account** link.

	![Sign in with your Microsoft account](images/ex1task2-01-sign-in.png "Sign in with your Microsoft account")

	_Sign in with your Microsoft account_

1. Enter the credentials associated with your Microsoft account and click the **Sign in** button.

	![Sign in](images/ex1task2-02-sign-in.png "Sign in")

	_Sign in_

1. Click the **Setup** link at the top of the page

	![Setup](images/ex1task2-03-setup.png "Setup")

	_Setup_

1. Click the **Register application** link

	![Register application](images/ex1task2-04-register-application.png "Register application")

	_Register application_

1. Enter the **Name** of your application, select **Windows Phone** for the **Device type**, and click the **Save** button.

	![Application information](images/ex1task2-05-app-info.png "Application information")

	_Application information_

1. Once your application is registered, copy the **Application Id**, as you will need it for [Exercise 2](#Exercise2).

	![Application details](images/ex1task2-06-app-details.png "Application details")

	_Application details_

<a name="Ex1Task3"></a>
##### Task 3: Create a mobile application ad unit with pubCenter ####

In this task you will learn how to create a mobile application ad unit with pubCenter.

1. Open Internet Explorer and navigate to [http://pubcenter.microsoft.com/](http://pubcenter.microsoft.com/).

1. Click the **Sign in with your Microsoft account** link.

	![Sign in with your Microsoft account](images/ex1task3-01-sign-in.png "Sign in with your Microsoft account")

	_Sign in with your Microsoft account_

1. Enter the credentials associated with your Microsoft account and click the **Sign in** button.

	![Sign in](images/ex1task3-02-sign-in.png "Sign in")

	_Sign in_

1. Click the **Setup** link at the top of the page

	![Setup](images/ex1task3-03-setup.png "Setup")

	_Setup_

1. Click the **Create ad unit** link.

	![Create ad unit](images/ex1task3-04-create-ad-unit.png "Create ad unit")

	_Create ad unit_

1. Enter the **Ad unit name**, select your **Application**, and select the **Ad unit size**.

	![Ad unit details](images/ex1task3-05-ad-unit-details.png "Ad unit details")

	_Ad unit details_

1. Select the appropriate **Dev Center app category** and **Dev Center app subcategory** (if applicable), then click the **Save** button.

	![Dev Center app category](images/ex1task3-06-category.png "Dev Center app category")

	_Dev Center app category_

1. Once the ad unit is created, copy the **Ad Unit Id**, as you will need it for [Exercise 2](#Exercise2).

	![Ad unit details](images/ex1task3-07-ad-unit-id.png "Ad unit details")

	_Ad unit details_