---
title: Emails
taxonomy:
    category: docs
---

![Emais Template Manager](emails-template.png)

In the Settings Emails tab  in the upper right corner is the **Email Templates Manager** button, leading to the view where you can create new email notification templates or manage existing ones with the following options:

![Emails page](emails.png)

| Field       | Description |
| :---------- | :---------- |
| **Type** | The template email type. |
| **Language** | The language the template will be applied to. |
| **User Groups** | The User Groups the email will be sent to. |
| **Subject** | The email subject. |
| **CC** | Carbon Copy, send a copy of each email to another address. Separate multiple addresses with commas. |
| **BCC** | Blind Carbon Copy, same as Carbon Copy but with recipient email hidden. Use this option if you don't want other recipients to know an email copy is being sent somewhere else. |
| **Template** | The email body content. |
| **Status** | publication status. |

>>> Please take into account that CC and BCC work only with SMTP(Win32) mailing mode.

You can use the following placeholders in Subject and Body content:

| Placeholder | Replaced with |
| :---------- | :---------- |
| **{sitename}** | Your site name. |
| **{siteurl}** | Your site URL. |
| **{user}** | The User full name. |
| **{username}** | The User username . |
| **{order_number}** | The Order number. |
| **{order_link}** | The Order link. |
| **{order_state}** | The Order state. |
| **{order_summary}** | The Order items list and summary. |
| **{billing_address}** | The User Billing Address provided for that Order. |
| **{shipping_address}** | The User Shipping Address provided for that Order. |
| **{admin_notes}** | The admin notes field content. |

>>> **Notification emails** are only sent to Super Users if their **Receive System Emails** option is enabled.

In order to prevent some email type to be sent, please override this email type and leave unpublished.
 
![Disable email type]( emails-disable.png)
