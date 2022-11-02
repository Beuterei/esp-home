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
    <a href="https://github.com/beuluis/esp-home/issues">Report Bug</a>
    ·
    <a href="https://github.com/beuluis/esp-home/issues">Request Feature</a>
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

| Name          | Description                                                            |
| ------------- | ---------------------------------------------------------------------- |
| `power-meter` | Measure your energy consumption with the pulse LED on your smart meter |

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->

## Contact

Luis Beu - me@luisbeu.de

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/beuluis/esp-home.svg?style=flat-square
[contributors-url]: https://github.com/beuluis/esp-home/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/beuluis/esp-home.svg?style=flat-square
[forks-url]: https://github.com/beuluis/esp-home/network/members
[stars-shield]: https://img.shields.io/github/stars/beuluis/esp-home.svg?style=flat-square
[stars-url]: https://github.com/beuluis/esp-home/stargazers
[issues-shield]: https://img.shields.io/github/issues/beuluis/esp-home.svg?style=flat-square
[issues-url]: https://github.com/beuluis/esp-home/issues
[license-shield]: https://img.shields.io/github/license/beuluis/esp-home.svg?style=flat-square
