---
title : How to Connect Email of cPanel to an Email Client 
date : 2024-08-12 14:00:00 +0000
cover : cover.png
author: Spideyhost
categories :
    - cPanel
    - Email
    - Tutorial
tags :
    - cPanel
    - Email Client
    - Setup
---

A step-by-step guide on how to connect your cPanel email account to an email client.
<!--more-->

## Introduction

Connecting your cPanel email account to an email client allows you to manage your emails efficiently from a single platform. Whether you use Outlook, Thunderbird, or any other email client, this guide will walk you through the necessary steps.

## Prerequisites

Before starting, ensure you have the following:
- Access to cPanel
- Email account created within cPanel
- The email client installed on your device

## Step 1: Access Email Accounts in cPanel

1. Log in to your cPanel account.
2. Navigate to the **Email** section and click on **Email Accounts**.
3. Locate the email account you wish to connect and click on **Connect Devices**.

## Step 2: Find Email Client Settings

1. Under the **Mail Client Manual Settings**, you'll find the information needed to set up your email client:
    - **Incoming Server** (IMAP/POP3): mail.yourdomain.com
    - **Outgoing Server** (SMTP): mail.yourdomain.com
    - **Username**: Your full email address
    - **Password**: The password for your email account
2. Note down the settings for either **Secure SSL/TLS Settings** or **Non-SSL Settings** based on your preference.

## Step 3: Set Up Your Email Client

1. Open your email client (e.g., Outlook, Thunderbird).
2. Go to the account setup or add new account section.
3. Enter the following details:
    - **Email Address**: Your full email address (e.g., user@yourdomain.com)
    - **Incoming Mail Server**: Enter the incoming server from cPanel
    - **Outgoing Mail Server**: Enter the outgoing server from cPanel
    - **Username**: Your full email address
    - **Password**: The password for your email account
4. Choose the account type (IMAP or POP3). IMAP is recommended for better synchronization.
5. Enter the port numbers as provided in cPanel:
    - **IMAP Port**: 993 (SSL) / 143 (Non-SSL)
    - **POP3 Port**: 995 (SSL) / 110 (Non-SSL)
    - **SMTP Port**: 465 (SSL) / 587 (Non-SSL)

## Step 4: Test the Connection

1. After entering the required information, click **Next** or **Test Account Settings**.
2. The email client will verify the settings. If successful, your account will be added, and you can start sending and receiving emails.

## Conclusion

Setting up your cPanel email in an email client can enhance your email management by consolidating your communications in one place. Follow these steps, and you’ll be connected in no time.

