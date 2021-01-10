<img src="https://github.com/Appboy/appboy-cordova-sdk/blob/master/braze-logo.png" width="300" title="Braze Logo" />

# Cordova SDK

Effective marketing automation is an essential part of successfully scaling and managing your business. Braze empowers you to build better customer relationships through a seamless, multi-channel approach that addresses all aspects of the user life cycle. Braze helps you engage your users on an ongoing basis. View the following resources for details and we'll have you up and running in no time!

See our [Technical Documentation for Android](https://www.braze.com/docs/developer_guide/platform_integration_guides/cordova/android_and_fireos/initial_sdk_setup/) and [Technical Documentation for iOS](https://www.braze.com/docs/developer_guide/platform_integration_guides/cordova/ios/initial_sdk_setup/) for instructions on integrating Braze into your Cordova app.

# Customisation to plugin

If you need any customization to this plugin, please contact plugins@snapcommute.com. This plugin was customized for an Australian customer and below functions were created to handle push notifications and extract the data from the notification and pass it on to the app.

onMessageReceived - When a notification is received, the data will be passed on to the app through this function.
register - Function to register the Appboy SDK to receive notifications.
hasPermission - Checks if notification is enabled or has permission.
grantPermission - Requests permission to receive the notification.
