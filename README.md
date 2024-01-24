[![HA integration usage](https://img.shields.io/badge/dynamic/json?color=41BDF5&logo=home-assistant&label=integration%20usage&suffix=%20installs&cacheSeconds=15600&url=https://analytics.home-assistant.io/data.json&query=current.integrations.knx)](https://www.home-assistant.io/integrations/knx/)
[![Discord](https://img.shields.io/discord/338619021215924227?color=7289da&label=Discord&logo=discord&logoColor=7289da)](https://discord.gg/62UcpH3Y92)

# Home Assistant KNX integration
Hi 👋! This is a proxy repository for the Home Assistant KNX integration to track issues, feature requests, discussions etc.

Since KNX is a core integration, its code is hosted in the [Home Assistant Core repository](https://github.com/home-assistant/core/tree/dev/homeassistant/components/knx).
The [integrations unit tests](https://github.com/home-assistant/core/tree/dev/tests/components/knx) can also be found there and the [official KNX integration documentation](https://www.home-assistant.io/integrations/knx/) is sourced from the [Home Assistant documentation repo](https://github.com/home-assistant/home-assistant.io/blob/current/source/_integrations/knx.markdown).

The integration uses following libraries:
- [`xknx`](https://github.com/XKNX/xknx) the library used for KNX IP connection handling, DPT decoding and providing device abstractions
- [`knx-frontend`](https://github.com/XKNX/knx-frontend) the Home Assistant KNX panel
- [`xknxproject`](https://github.com/XKNX/xknxproject) the ETS project file parser
