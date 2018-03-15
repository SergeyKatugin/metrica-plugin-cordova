# AppMetrica Cordova Plugin

This fork might fix error `no such file of directive AndroidManifest.xml`.

## Documentation
Common documentation available on [AppMetrica official site][DOCUMENTATION].
Documentation for this plugin will be published soon. 

## Sample project
Sample project to use is available at [sample/][GitHubSAMPLE].

## Installation
```bash
cordova plugin add https://github.com/SergeyKatugin/metrica-plugin-cordova-android-stuido.git
```

It is also possible to install via repo url directly *(not recomended)*:
```bash
cordova plugin add https://github.com/yandexmobile/metrica-plugin-cordova.git
```

## AppStore submit notice
Starting from version 1.6.0 Yandex AppMetrica became also a tracking instrument and
uses Apple idfa to attribute installs. Because of that during submitting your
application to the AppStore you will be prompted with three checkboxes to state
your intentions for idfa usage.
As Yandex AppMetrica uses idfa for attributing app installations you need to select **Attribute this app installation to a previously served
advertisement**.

## Changelog

### Version 0.2.0
* Updated versions of the AppMetrica SDK (iOS 2.9.4 and Android 2.78)
* Added a method for getting the configuration of the AppMetrica Push Cordova plugin.
* Fixed installation of iOS part from NPM (#1).

### Version 0.1.0
* Implemented plugin for AppMetrica iOS (v2.8.0) and AppMetrica Android (v2.62).
* Provided sample.

## License
License agreement on use of Yandex AppMetrica is available at [EULA site][LICENSE]


[LICENSE]: https://yandex.com/legal/appmetrica_sdk_agreement/ "Yandex AppMetrica agreement"
[DOCUMENTATION]: https://tech.yandex.com/appmetrica/doc/mobile-sdk-dg/concepts/about-docpage/ "Yandex AppMetrica documentation"
[GitHubSAMPLE]: https://github.com/yandexmobile/metrica-plugin-cordova/tree/master/sample "Sample from reository"
