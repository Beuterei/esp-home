[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT HEADER -->
<br />
<p align="center">
  <h3 align="center">ESPHome</h3>

  <p align="center">
    My ESP home configs.
    <br />
    <br />
    ·
    <a href="https://github.com/Beuterei/esp-home/issues">Report Bug</a>
    ·
    <a href="https://github.com/Beuterei/esp-home/issues">Request Feature</a>
    ·
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

Those are my personal ESP home configs so they probably won't have much use for others. However, it may help someone.

## Usage

```bash
esphome -h
```

## Setup

1. Create a secret file at `config/secrets.yaml` add all secrets from [Secrets](#secrets) according to [Storing secrets](https://www.home-assistant.io/docs/configuration/secrets/)

## Secrets

To configure secrets

| Name                   | Description                              |
| ---------------------- | ---------------------------------------- |
| `wifi_ssid`            | SSID to connect to                       |
| `wifi_password`        | Password for the AP                      |
| `fallback_ap_password` | Password for the fallback AP             |
| `web_password`         | Password for web interface on port `80`  |
| `api_key`              | API encryption key for the native HO API |
| `ota_password`         | Password for updates                     |

## Projects

| Name                  | Description                                      |
| --------------------- | ------------------------------------------------ |
| `emergency-exit-sign` | A fancy emergency exit sign as light             |
| `dnd-light-remote`    | A small remote to control the light mood for dnd |
| `door-buzzer`         | Relay to control my door buzzer                  |
| `water-tracker`       | A tracker for my daily water consumption         |

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/Beuterei/esp-home.svg?style=flat-square
[contributors-url]: https://github.com/Beuterei/esp-home/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Beuterei/esp-home.svg?style=flat-square
[forks-url]: https://github.com/Beuterei/esp-home/network/members
[stars-shield]: https://img.shields.io/github/stars/Beuterei/esp-home.svg?style=flat-square
[stars-url]: https://github.com/Beuterei/esp-home/stargazers
[issues-shield]: https://img.shields.io/github/issues/Beuterei/esp-home.svg?style=flat-square
[issues-url]: https://github.com/Beuterei/esp-home/issues
[license-shield]: https://img.shields.io/github/license/Beuterei/esp-home.svg?style=flat-square
