# CUSTOM Piwik PRO Analytics template for Google Tag Manager

*Important note:* this template used to serve as a fork of the [original template by Piwik PRO](https://github.com/PiwikPRO/analytics-template-for-gtm) with the goal to add ecom functionality and better compatibility.  

The former [pull request](https://github.com/PiwikPRO/analytics-template-for-gtm/pull/1) is closed and instead I contributed directly to a new template version that is [currently in development](https://github.com/PiwikPRO/analytics-template-for-gtm/tree/development) and will hopefully get submitted and published in the *Community Template Gallery* soon. 

## Why this custom version?
The reason why this fork still exists is currently just a single feature: during development we added an option to **"Follow Consent Mode"** when configuring privacy settings. The goal of this option is to be able to run just one single tag and either use cookies if there is consent granted for `analytics_storage` when firing... or fire the tag without cookies if no consent was given and documented as a *Google Consent Mode* setting. 

That option - as handy as it is - was complicated to use and confused testers. So we decided to kill the feature for the official template from Piwik PRO and I updated this fork to include the last version that still has this feature. 

## Should I use it?
It is up to you to decide but it is always a good idea to use templates from the gallery instead of importing local templates. So if you do not need the feature described above, there is simply no reason why this version should be used instead of the regular one (from the [Community Template Gallery](https://tagmanager.google.com/gallery/#/owners/PiwikPRO/templates/analytics-template-for-gtm)).  
