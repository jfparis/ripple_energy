# ripple_energy Custom Integration

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]

[![License][license-shield]][license]

[![hacs][hacsbadge]][hacs]
[![Project Maintenance][maintenance-shield]][user_profile]

A custom component for Ripple Energy.

## Installation

1. Use [HACS](https://hacs.xyz/docs/setup/download), in `HACS > Integrations > Explore & Add Repositories` search for "Ripple Energy". After adding this `https://github.com/ryanbdclark/ripple_energy` as a custom repository.
2. Restart Home Assistant.
3. [![Add Integration][add-integration-badge]][add-integration] or in the HA UI go to "Settings" -> "Devices & Services" then click "+" and search for "Ripple Energy".
4. When configuring you ripple energy API key is required, to retrieve this follow [this link](https://community.rippleenergy.com/new-feature-requests-yyqtfatb/post/ripple-api-yH0cTzuQ4GJMaYV).


<!---->

## Usage

The `Ripple Energy` integration offers integration with the Ripple Energy cloud service.

## Options

- Seconds between polling - Number of seconds between each call for data from the Ripple Energy cloud service, default is 5 seconds.

---

[commits-shield]: https://img.shields.io/github/commit-activity/w/ryanbdclark/ripple_energy?style=for-the-badge
[commits]: https://github.com/ryanbdclark/ripple_energy/commits/main
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[license]: LICENSE
[license-shield]: https://img.shields.io/github/license/ryanbdclark/ripple_energy.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Ryan%20Clark%20%40ryanbdclark-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/ryanbdclark/ripple_energy.svg?style=for-the-badge
[releases]: https://github.com/ryanbdclark/ripple_energy/releases
[user_profile]: https://github.com/ryanbdclark
[add-integration]: https://my.home-assistant.io/redirect/config_flow_start?domain=ripple_energy
[add-integration-badge]: https://my.home-assistant.io/badges/config_flow_start.svg
