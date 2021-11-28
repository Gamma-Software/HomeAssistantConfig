# PiVal's Home Assistant Configuration

[![GitHub Actions][actions-shield]][actions]
[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

![GitHub Stars][stars-shield]
![GitHub Watchers][watchers-shield]
![GitHub Forks][forks-shield]

## About

This is my personal Home Assistant configuration, running my home automations.

Follow me on my journey and be sure to hit the GitHub :star2:

## Hardware and integration
TL;DR: [RaspberryPi4] [Yeelight] [Hue Light] [Sonoff with Tasmota managed by ESPHome]

My hardware and itegration setup is the following:
* I use a RaspberryPIi4 with a pre-built
HomeAssistant image (you can find it [here](https://www.home-assistant.io/installation/raspberrypi/))
The RaspberryPi 4 is connected to my router with an Ethernet cable. 
* 13 Hue Lights connected by ZygBee protocol to a Hue bridge (find out more [here](https://www.philips-hue.com/fr-fr/p/hue-hue-bridge/8719514342620)).
The Hue bridge is connected to the router via a Ethernet cable.
* 3 Yeelight lights connected via Wifi
* 4 Sonoff mini flashed with Tasmota firmware and managed and programmed through ESPHome. The Sonoff mini is used to switch on and off the Hue lights with traditionnal switches. The Sonoff Mini also integrates a temperature and humidity sensor. 

## Contributing

I consider my personal Home Assistant configuration an active open-source project.
So if you feel like adding an improvement, feel free to contribute.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original setup of this repository is by [Valentin Rudloff][valentin] and largely inspired by [Franck's homeassistant config][frenck's home].

## License

MIT License

Copyright (c) 2018-2020 Valentin Rudloff

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[commits-shield]: https://img.shields.io/github/commit-activity/y/gamma-software/homeassistantconfig.svg
[commits]: https://github.com/gamma-software/homeassistantconfig/commits/master
[contributors]: https://github.com/gamma-software/homeassistantconfig/graphs/contributors
[valentin]: https://github.com/gamma-software
[frenck's home]: https://github.com/frenck/home-assistant-config
[actions-shield]: https://github.com/gamma-software/homeassistantconfig/workflows/Home%20Assistant%20CI/badge.svg
[actions]: https://github.com/gamma-software/homeassistantconfig/actions
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/gamma-software/homeassistantconfig/issues
[license-shield]: https://img.shields.io/github/license/gamma-software/homeassistantconfig.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/gamma-software/homeassistantconfig.svg
[stars-shield]: https://img.shields.io/github/stars/gamma-software/homeassistantconfig.svg?style=social&label=Stars
[forks-shield]: https://img.shields.io/github/forks/gamma-software/homeassistantconfig.svg?style=social&label=Forks
[watchers-shield]: https://img.shields.io/github/watchers/gamma-software/homeassistantconfig.svg?style=social&label=Watchers
