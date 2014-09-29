# Settings - Part C

## Privacy

These settings control privacy options that are applied at a system level.

>**info** For a full view of privacy, also refer to [privacy for members](../people/README.html#setting-privacy-options).

![Privacy Settings](../img/admin/settings-7.png)

Selecting the allow picture comments field will allow members to post comments to a picture.

You can configure the maximum number of signin attempts in a 15 minute period before an account is locked out. The account will be automatically unlocked after 15 minutes.

When a member's account is first created, the list below details privacy settings are initially applied to their information. Members can still choose to show or hide any of their information at any time, regardless of the settings.

The following items can be marked visible (or not :):
* Email
* Home Phone
* Mobile Phone
* Work Phone
* Fax
* Address
* Birthday
* Anniversary

## External Services

The external services page allows you to configure links to external websites or setup configuration values for external providers.

![External Services](../img/admin/settings-6.png)

| Field | Description |
| -- | -- |
| Visitor | URL for main website (visitors will be pointed here if they happen across the member site.) |
| News Feed | URL for external community news feed in RSS or Atom format (news will be imported periodically) |
| Analytics | If you use Google Analytics or some other JavaScript-based stats service, put the code here. The code will be inserted at the bottom of every page. |
| Email Host Name | A subdomain, e.g. mg.example.com, to use if your domain is already serving email. Defaults to the domain name. |
| Mailgun API Key | API Key to use mailgun.com as the email receiver.|

## Advanced

* Hit Reload Settings to force a refresh of all settings for OneBody.

If you're using Mailgun as your email provider, you can choose to simply use this button to create your catch-all route, which is required for setup.

Before you hit the button, you need to have the mailgun api key configured (private, not public) in the [External Services](#external-services) page.

Don't worry if you accidently hit the button again - OneBody checks to make sure a route is not already present.

Related Article: [Mailgun Setup - Point 2](https://github.com/churchio/onebody/wiki/MailgunEmailSetup)










