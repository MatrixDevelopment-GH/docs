---
description: Welcome to the docs for Atriox!
coverY: -780.9691629955948
---

# Atriox

{% hint style="warning" %}
#### Both this page and the bot is still in development.
{% endhint %}

Meet Atriox. A multipurpose staff management bot. Atriox can help you manage your group/server and keep all of your staff members active and on-task. Atriox makes having a staff team simple due to the wide variety of staff-related features it has to handle the responsibilities one would normally have to deal with. The default prefix for atriox is `m!` you can change it by doing `m!prefix <new prefix>`

#### How-To Setup Atriox.

1. **Invite the** [**bot**](https://atriox.matrixdev.xyz/add) **to your server**
2. **Make two different channels (One for the Check-in logs and the other to use the commands)**&#x20;
3. **Get the Logs channel id and the commands channel id.**
4. **First do `m!from <Channel Id>` (we are working on the channel mentioning currently this is a beta build.)**
5. **After you do that, you can set the channel were the check-ins will be logged by doing `m!to <Channel Id>`**
6. **After those steps are complete you can set the cooldown by using `m!cooldown <Time>` (Time is using hours not minuets)**

Note: Please make sure that the management channel is not general for all users to type in. Specify the permissions so just the server team can view and operate this channel.

#### How to setup the LOA system (OPTIONAL)

If the setup above is not completed, please go back and do that setup before continuing this setup.

1. **To set this system up please get your LOA role id (we are working on the role mentioning currently this is a beta build.)**
2. **The next step is to use `m!role <Role Id>`**
3. **`Finally use m!loa <time> (Time is set in hours manual Loa Removal required until system is completed.)`**

Note: Please make sure that the bot role is overall other roles in your discord server. And if you get this error Error\_20170 then the LOA role is not set, or the bot cannot set the user's role because its role is not above the user's current role.

Error Codes

47991 - Command not found

20170 - Failed to execute command&#x20;

67159 - No arguments provided command canceled

55904 - Not enough permissions to run this command

78143 - Development mode active command canceled&#x20;

\
_**General Commands**_

help | This page.&#x20;

invite | This command sends the bot invite link

ping | Bot & database pings&#x20;

website | Get the bots website



_**Staff Only Commands**_

checkin | this has to be used in this server usage channel. loa (time) | this has to be used in this server usage channel. This commands time is in hours.&#x20;



**Server Owner Commands**

to | Set the Send check-ins and staff loa channel.&#x20;

from | Set the Staff Only Command Usage Channel.&#x20;

cooldown | Set the Servers staff command cooldown.

role | Set the LOA system role.&#x20;
