# Example Home Assistant add-on repository

[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-informational?style=flat)](COPYRIGHT.md)

This repository can be used as a "blueprint" for add-on development to help you get started.

Add-on documentation: <https://developers.home-assistant.io/docs/add-ons>

[![Add repo badge][add-rep-hass]][add-rep-link]

## Add-ons

### [Aria2 + AriaNg (WebUI)](./example)

[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-informational?style=flat)](COPYRIGHT.md)
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

_Aria2 Download Manager & AiraNg Web Interfacce All I One Solution_

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg?style=flat
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=flat
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg?style=flat
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg?style=flat
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg?style=flat
[add-rep-hass]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[add-rep-link]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FSiriosDev%2FSiriosDev-HomeAssistant-Add-On
