![Title image](/img/title_image.png)

# MQTT Push Client app online help

This is the web-based online help for the MQTT Push Client app that can be published on a web server and viewed in any common web browser.

The online help files are available in the “MQTTPushClient_OnlineHelp” folder which contains the help files per language (“en”, “de”), the index files per language (“index.en.html”, “index.de.html”), the images folder (“img”), the style file (“style.css”), and some extra files which manage the correct display of the help files depending on the user agent (iOS or Android) and the used language (“htaccess”, “index.var”).


## Implementation

 -	Clone the “MQTTPushClient_OnlineHelp” repository from GitHub
 -	Make the content available on the web server, e.g. Apache

The online documentation can be tested in any web browser. By default, the Android version is displayed. However, when accessing the online help from an iOS device, the content will display the iOS illustrations flavor of this app. Alternatively the user agent can be set to iPod/iPhone/iPad to display the iOS content.

The MQTT Push Client app help menu uses a web view which redirects to this online help. The documentation utilizes JavaScript (with jQuery libraries) for image enlargement and user agent selection. The documentation content itself is basic HTML/CSS.


## Links

 - RadioShuttle MQTT basics: https://www.radioshuttle.de/en/mqtt-en/the-basics/
 - RadioShuttle MQTT Push Client app online help: https://help.radioshuttle.de/mqttapp/1.0/index.en.html
 - MQTT Push Client (app) https://www.radioshuttle.de/en/mqtt-en/mqtt-push-client-app/
 - Android app: https://github.com/RadioShuttle/MQTTPushClient_Android
 - Google Play: https://play.google.com/store/apps/details?id=de.radioshuttle.mqttpushclient&hl=en
 - App Store: https://apps.apple.com/us/app/mqtt-push-client/id1454678876
