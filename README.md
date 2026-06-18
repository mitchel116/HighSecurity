Terms of Service – HighSecurity Bot

Last Updated: June 18, 2026

1. Definitions

HighSecurity Bot ("the Service") is a Discord security and moderation bot developed and operated by NitroXHost.

By installing, using, subscribing to, or interacting with HighSecurity Bot, you agree to these Terms of Service.

2. Service Description

HighSecurity Bot provides security, moderation, and community management features, including but not limited to:

Anti-spam protection
Anti-raid protection
Moderation tools
Verification systems
Ticket management
Logging and monitoring
Word filtering
Image and media protection
Security alerts
Additional management and protection features

NitroXHost reserves the right to add, modify, improve, or remove features at any time.

3. Subscriptions and Payments

Certain features or access to the Service may require an active subscription.

Subscription fees must be paid in advance according to the selected billing period.

Failure to pay may result in suspension, limitation, or termination of access to the Service.

4. Price Changes

NitroXHost reserves the right to modify subscription pricing when necessary due to:

Development costs
Infrastructure and hosting expenses
Maintenance costs
New features and improvements
Market conditions
Legal or tax-related changes

Users may be notified of significant pricing changes through available communication channels, including:

Discord Direct Messages
The official NitroXHost Discord server
The NitroXHost website
Dashboard notifications
Other available communication methods

Continued use of the Service after a pricing change becomes effective constitutes acceptance of the new pricing.

5. Service Availability

While NitroXHost strives to maintain reliable service availability, uninterrupted operation is not guaranteed.

Maintenance, updates, security improvements, outages, third-party service failures, or unforeseen circumstances may result in temporary interruptions.

6. Acceptable Use

You agree not to use HighSecurity Bot for:

Illegal activities
Violations of Discord Terms of Service
Violations of Discord Community Guidelines
Abuse of security or moderation systems
Attempts to exploit, disrupt, or bypass Service functionality
7. Suspension and Termination

NitroXHost reserves the right to suspend or terminate access to the Service at its discretion in cases involving:

Abuse
Fraud
Security threats
Violations of these Terms
8. Limitation of Liability

HighSecurity Bot is provided on an "as available" and "as is" basis.

NitroXHost shall not be liable for:

Data loss
Discord server loss
Revenue loss
Indirect damages
Consequential damages
Actions of users or third parties

To the maximum extent permitted by law, total liability shall not exceed the amount paid by the customer during the previous twelve (12) months.

9. Changes to the Service

NitroXHost may update, modify, discontinue, or replace any aspect of the Service at any time without prior notice.

10. Governing Law

These Terms shall be governed by and interpreted under the laws of The Netherlands.

Any disputes arising from the use of the Service shall be submitted to the competent courts of The Netherlands.


---------------------------------------------------------------

Privacy Policy – HighSecurity Bot

Last Updated: June 18, 2026

1. Introduction

NitroXHost respects the privacy of all users and only processes data necessary for the operation, security, moderation, and functionality of HighSecurity Bot.

2. Information We Process

HighSecurity Bot may process the following information:

Discord User IDs
Discord Server IDs
Discord Channel IDs
Discord Role IDs
Moderation records
Verification records
Ticket records
Security logs
Audit logs
Subscription-related information

The bot does not process more data than necessary to provide its services.

3. Purpose of Processing

Data is processed solely for:

Moderation
Security protection
Verification systems
Ticket management
Logging and monitoring
Abuse prevention
Service operation
Customer support
4. Information We Do Not Collect

HighSecurity Bot:

❌ Does not sell personal information

❌ Does not read private direct messages between users

❌ Does not collect passwords

❌ Does not store payment card information

❌ Does not share private conversations

Payment information is handled exclusively by authorized payment providers.

5. Data Sharing

NitroXHost does not sell or rent user data.

Information may only be shared when:

Required by law
Necessary for payment processing
Necessary for hosting, infrastructure, or technical operations
Required to protect the security of the Service
6. Data Retention

Information is retained only as long as reasonably necessary to operate the Service.

Server owners may request deletion of server-related data.

Certain information may be automatically removed following subscription cancellation, bot removal, or extended inactivity.

7. Security Measures

NitroXHost implements reasonable technical and organizational measures designed to protect information against:

Unauthorized access
Loss
Misuse
Alteration
Disclosure

No online system can guarantee absolute security.

8. User Rights

Where applicable under relevant privacy laws, users may request:

Access to their data
Correction of inaccurate information
Deletion of applicable data
Objection to certain processing activities

Requests may be submitted to:

📧 info@nitroxhost.com

9. Policy Changes

NitroXHost reserves the right to update or modify this Privacy Policy at any time.

Important changes may be communicated through:

Discord Direct Messages
The official NitroXHost Discord server
The NitroXHost website
Dashboard notifications
Other available communication channels

Continued use of the Service after changes become effective constitutes acceptance of the revised Privacy Policy.

10. Contact Information

NitroXHost
📧 info@nitroxhost.com
🌍 The Netherlands

HighSecurity Bot – Advanced Discord Security, Moderation, Verification, and Community Protection.
---------------------------------------------------------------

HighSecurity Bot Setup Guide

Follow these steps to properly configure HighSecurity Bot and unlock all security, moderation, verification, and ticket features.

Step 1 – Invite the Bot

Make sure the bot has the following permissions:

✅ View Channels
✅ Send Messages
✅ Read Message History
✅ Manage Messages
✅ Manage Channels
✅ Manage Roles
✅ Moderate Members
✅ Kick Members
✅ Ban Members
✅ Use Slash Commands

Important

The bot role must be positioned above:

Verified
Unverified
Member Roles

Otherwise, the bot will not be able to assign or remove roles.

Step 2 – Configure a Log Channel

Create a channel:

#logs

Run:

/setlogchannel channel:#logs

All moderation, security, and verification events will be logged here.

Step 3 – Enable the Verification System

Run:

/setupverification lock_server:true

The bot will automatically create:

#rules
Verified
Unverified

New members will automatically receive the Unverified role and will only be able to access the rules channel.

Step 4 – Configure Your Server Rules

Run:

/setrules channel:#rules

A popup window will appear.

Paste your server rules into the form.

Example:

1. Respect everyone.
2. No discrimination or hate speech.
3. No spam.
4. No scams or malicious links.
5. No NSFW content.
6. Follow staff instructions.
7. Rule violations may result in bans.

The bot will automatically create a rules message with a green:

✅ Accept Rules

button.

When users click the button:

Unverified Removed
↓
Verified Added
↓
Full Server Access Granted
Step 5 – Configure the Ticket System

Create a staff role:

Staff

Run:

/setticketpanel

Select:

Channel: #tickets
Role: @Staff

Members will now be able to create private support tickets.

Step 6 – Configure Anti-Spam Protection

Run:

/setspam

Example configuration:

5 messages
10 seconds
Punishment: mute
10 minutes

Users who exceed the limit will automatically be punished.

Step 7 – Configure Image Protection

Run:

/setimagelimit

Example configuration:

10 images
10 minutes
Punishment: mute
10 minutes

This helps prevent image flooding and media spam.

Step 8 – Configure Anti-Raid Protection

Run:

/setraid

Example:

10 joins
30 seconds
Action: lockdown

The bot will automatically respond to suspicious join activity.

Step 9 – Rule Violation System

When a member breaks the server rules, moderators can run:

/rulesviolation user:@User reason:Rule Violation

Violation System:

First Violation
Verified Removed
Unverified Added
User Must Accept Rules Again
Second Violation
Verified Removed
Unverified Added
User Must Accept Rules Again
Third Violation
Permanent Ban

This ensures members repeatedly review and accept the server rules after misconduct.

Step 10 – Test Everything

Use a second Discord account and verify that:

✅ New members only see #rules
✅ New members receive Unverified automatically
✅ Clicking the green ✅ button grants Verified
✅ Full server access is unlocked after verification
✅ Tickets can be created successfully
✅ Anti-spam protection works correctly
✅ Rule violations work correctly
✅ Logs are recorded in the log channel

🔒 Your Server Is Now Protected

Once these steps are completed, HighSecurity Bot will provide:

✅ Verification System
✅ Ticket System
✅ Anti-Spam Protection
✅ Anti-Raid Protection
✅ Image Spam Protection
✅ Word Filtering
✅ Moderation Tools
✅ Security Logging
✅ Rule Violation Tracking
✅ Automated Community Protection

Developed by NitroXHost
