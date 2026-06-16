HighSecurity Bot – Terms of Service (ToS)
Last Updated: June 16, 2026
These Terms of Service ("Terms") govern the use of the HighSecurity Bot ("Bot"), operated by NitroXHost.
By inviting, installing, or using the Bot, you agree to these Terms.
If you do not agree with these Terms, you must remove the Bot from your Discord server.

1. Definitions


Bot: The HighSecurity Discord Bot.


User: Any person interacting with the Bot.


Server Owner: The owner or administrator of a Discord server using the Bot.


Service: All features and functionality provided by the Bot.



2. Purpose of the Bot
HighSecurity Bot is designed to help protect Discord communities against:


Spam


Raid attacks


Scam links


Unauthorized invite links


Emoji spam


Harmful or blocked words


Suspicious user activity


The Bot provides moderation and security tools to assist server administrators.

3. Eligibility
You must comply with:


Discord Terms of Service


Discord Developer Policies


Applicable local laws and regulations


The Bot may not be used for unlawful activities.

4. Availability of Service
We strive to keep the Bot online and operational at all times.
However, we do not guarantee uninterrupted availability.
Maintenance, updates, outages, or Discord API issues may temporarily affect service.

5. Subscription and Premium Features
Certain features may require an active subscription.
If a subscription expires:


Premium functionality may become unavailable.


Stored server data may be scheduled for deletion after a grace period.


Server owners are responsible for maintaining active subscriptions where required.

6. Server Administrator Responsibilities
Server owners and administrators are responsible for:


Correctly configuring the Bot.


Assigning appropriate permissions.


Reviewing moderation actions.


Complying with privacy laws.


Moderation decisions remain the responsibility of the server staff.

7. Prohibited Use
Users may not use the Bot for:


Illegal activities


Harassment or discrimination


Abuse of moderation systems


Privacy violations


Circumventing Discord policies


Misuse may result in suspension or removal of access.

8. Cross-Server Security Alerts
When enabled, HighSecurity Bot may generate security alerts regarding users previously moderated on other HighSecurity servers.
Example:

"Previously banned on 2 other HighSecurity servers."

To protect privacy:


Server names are not disclosed.


Private messages are never shared.


Only moderation-related information is used.


These alerts are intended solely for security purposes.

9. Intellectual Property
The HighSecurity Bot, its code, branding, and associated materials remain the property of NitroXHost unless otherwise specified.
Unauthorized copying, resale, or redistribution is prohibited.

10. Limitation of Liability
NitroXHost and the developers of HighSecurity Bot shall not be liable for:


Moderation errors


Data loss


Discord outages


Misconfiguration by server administrators


Damages arising from use of the Bot


The Service is provided "as is" without warranties of any kind.

11. Termination
We reserve the right to suspend or terminate access to the Bot for:


Abuse


Violations of these Terms


Illegal activities


Actions that threaten the security or integrity of the Service



12. Changes to Terms
These Terms may be updated at any time.
Continued use of the Bot after updates constitutes acceptance of the revised Terms.

HighSecurity Bot – Privacy Policy
Last Updated: June 16, 2026
This Privacy Policy explains how HighSecurity Bot processes information.

1. Data We Process
The Bot may process the following data:
Discord Information


User IDs


Guild (Server) IDs


Channel IDs


Role IDs


Message IDs


Moderation Data


Warnings


Mutes


Temporary bans


Permanent bans


Security logs


Configuration Data


Server settings


Anti-spam settings


Anti-raid settings


Log channel configuration


Word filters


Invite filters



2. Message Processing
The Bot may inspect message content solely for moderation purposes, including:


Spam detection


Invite detection


Blocked word filtering


Emoji limit enforcement


Regular chat messages are not permanently stored unless required for moderation, security, or logging purposes.

3. Cross-Server Security Alerts
When a user is banned through HighSecurity Bot, a security record may be stored.
Other participating servers may receive alerts such as:

"Previously banned on 2 other HighSecurity servers."

To protect privacy:


Server names are hidden.


Private messages are never stored.


Only moderation events are processed.



4. Data Retention
Data is retained only as long as necessary for:


Security


Moderation


Bot functionality


Server owners may request deletion of their server data using:
/deletedata
Certain data may be automatically removed after subscription expiration or inactivity.

5. Data Sharing
We do not sell user data.
We do not share personal data with third parties except where legally required.
Information is used solely for operating and improving HighSecurity Bot.

6. Security Measures
We implement reasonable technical and organizational measures to protect stored information.
However, no system can guarantee 100% security.

7. User Rights (GDPR/Privacy Rights)
Depending on applicable law, users or server owners may request:


Access to stored data


Correction of inaccurate data


Deletion of server data


Information regarding data processing



8. Children's Privacy
The Bot is not intended for users under the minimum age required by Discord's Terms of Service.

9. Contact Information
For support, privacy requests, or legal inquiries:
NitroXHost
HighSecurity Bot Support

By using HighSecurity Bot, you acknowledge that you have read and understood these Terms of Service and Privacy Policy.

---------------------------------------------------------------


HighSecurity Bot – Command Guide
Complete Command Overview & Usage

🛡️ Administration Commands
/setlogchannel
Sets the channel where security logs are sent.
Usage
/setlogchannel #security-logs
Example
/setlogchannel #mod-logs
The bot will send:


bans


mutes


spam detections


invite detections


raid alerts


cross-server alerts



/addadmin
Adds a HighSecurity bot administrator.
Usage
/addadmin @User
Example
/addadmin @Moderator
The user can now configure the bot without Discord Administrator permissions.

/removeadmin
Removes bot administrator access.
Usage
/removeadmin @User

📷 Image Protection
/setimagelimit
Limits how many images users may send.
Parameters
ParameterExampleamount10window_minutes10punishmentmutepunishment_minutes10
Example
/setimagelimit amount:10 window_minutes:10 punishment:mute punishment_minutes:10
Meaning
Users may send:


10 images


within 10 minutes


If they exceed the limit:
→ muted for 10 minutes.

/removeimagelimit
Disables image protection.
Usage
/removeimagelimit

💬 Anti-Spam Protection
/setspam
Configure anti-spam.
Parameters
ParameterExamplemax_messages5seconds10max_mentions5max_caps_percent80punishmentmutepunishment_minutes10
Example
/setspam max_messages:5 seconds:10 punishment:mute punishment_minutes:10
Meaning
If a user sends:


more than 5 messages


in 10 seconds


they receive the configured punishment.

/togglespam
Enable or disable spam protection.
Usage
/togglespam enabled:true
Disable:
/togglespam enabled:false

/removespam
Disable anti-spam entirely.
Usage
/removespam

😀 Emoji Protection
/setemojilimit
Limit emojis per message.
Example
/setemojilimit max_emojis:10 punishment:mute minutes:10
Meaning
Users may send up to:
10 emojis per message
More than 10:
→ punishment is applied.

/removeemojilimit
Disable emoji protection.
/removeemojilimit

🚨 Anti-Raid Protection
/setraid
Configure raid protection.
Parameters
ParameterExamplemax_joins10seconds30actionlockdown
Example
/setraid max_joins:10 seconds:30 action:lockdown
Meaning
If:
10 users join within 30 seconds
Bot performs:


log


lockdown


kick


ban



/removeraid
Disable anti-raid.
/removeraid

/unlockdown
Restore server permissions after lockdown.
/unlockdown

🚫 Word Filter
/blockword
Block a word.
Example
/blockword word:scam punishment:mute minutes:30
If someone types:
scam
Bot punishes them.

/removeword
Remove blocked word.
/removeword word:scam

🔗 Invite Protection
/allowinvite
Allow a Discord invite.
Example
/allowinvite invite:https://discord.gg/example

/removeinvite
Remove allowed invite.
/removeinvite invite:discord.gg/example

/setinvitepunishment
Configure invite punishment.
Example
/setinvitepunishment punishment:mute minutes:10

👮 Moderation Commands
/warn
Warn a user.
/warn @User reason:Spam

/mute
Timeout a user.
/mute @User minutes:10 reason:Spam

/unmute
Remove timeout.
/unmute @User reason:Appeal accepted

/ban
Permanently ban a user.
/ban @User reason:Scam

/tempban
Temporary ban.
/tempban @User minutes:1440 reason:Raid
Example:
1440 minutes = 1 day

/unban
Unban using User ID.
Example
/unban user_id:123456789012345678

🌍 Cross-Server Security
/globalalerts
Enable or disable cross-server alerts.
Enable
/globalalerts enabled:true
Disable
/globalalerts enabled:false
When enabled:
If a user was banned on other HighSecurity servers, admins receive a warning.
Example:
Previously banned on 2 other HighSecurity servers.
Server names remain private.

/globalbancheck
Check a member manually.
/globalbancheck @User

/globalbanremove
Bot Owner Only
Remove a user's global alert history.
/globalbanremove user_id:123456789012345678
Only works for:
BOT_OWNER_ID=YOUR_DISCORD_ID

👤 User Information
/userinfo
Display moderation history.
/userinfo @User
Shows:


warnings


mutes


bans


tempbans


account creation date


join date



/resetuserstats
Reset moderation statistics.
/resetuserstats @User

🗑️ Data Commands
/deletedata
Deletes all server data stored by the bot.
/deletedata
Deletes:


settings


logs


image counters


spam counters


moderation statistics


Administrator only.

📋 Available Punishments
The following punishments can be selected:
PunishmentDescriptionwarnWarning onlymuteTemporary timeouttempbanTemporary banbanPermanent ban

🔒 Permissions Required
The bot should have:


Administrator or


Manage Messages


Moderate Members


Ban Members


Kick Members


View Audit Log


Manage Channels


Bot role must be above member roles it moderates.

This guide covers the current HighSecurity Bot version including anti-spam, anti-raid, moderation tools, and cross-server security alerts.
