# pxlfall's custom ruleset for use in Stash (iOS) rule-based proxy application
[Click here](https://link.stash.ws/install-override/raw.githubusercontent.com/pxlfall/pxlfall-ruleset/main/pxlfall.stoverride) to install the override configuration file
## To-do list:
- [x] Implement good-enough all-around rule-set
- [ ] Figure out how to manually list servers in 'proxy-groups' from 'proxy-provider'
- [ ] Add 'url-test' proxy group for the following:
    - [x] TikTok
    - [x] YouTube (done by GEOSITE)
    - [x] Spotify (done by GEOSITE)
    - [x] Netflix (done by GEOSITE, look [here](https://github.com/Z-Siqi/Clash-for-Windows_Rule/blob/main/Rule/Netflix) for better implementation)
    - [ ] VK
    - [x] Telegran
    - [x] Instagram (use only music-supported servers) (done by GEOSITE)
    - [x] WhatsApp (make sure audio calls have no issues) (done by GEOSITE)
    - [ ] Twitch
    - [ ] Reddit (may be hidden)
    - [ ] Locket (US/UK servers)
    - [ ] 1Password (may be hidden)
    - [ ] Discord
    - [ ] Steam
- [ ] Rewrite the service provider config, so that only 'proxy-provider' is being used
- [ ] Create a mirror config for use in Clash for Windows
- [ ] Add custom specific Windows PC rules (i.e. '- PROCESS-NAME,迅游加速器.exe,DIRECT')
- [x] Create a basic tile, on/off switch, total data received/sent in the last 24h (if possible), current selected general purpose server (latest update implemented iOS 17 Widgets)
- [ ] End goal is impossible to achieve, but continously fix rare-case issues with routing rules.

## Acknowledgements
I would like to express my sincere appreciation to the contributors of the following projects, whose robust foundation and innovative features have significantly enhanced the functionality of this override config.
- Special thanks to [Stash](https://stash.ws/) rule-based proxy app for iOS and their extensive [wiki](https://stash.wiki/en)
- Loyalsoldier for incredible work on [clash-rules](https://github.com/Loyalsoldier/clash-rules)
- v2fly for providing an open [domain-list-community](https://github.com/v2fly/domain-list-community), which is widely recognized by client apps as a go-to source for GEOSITE rules.
- Koolson for making [Qure](https://github.com/Koolson/Qure) icon pack, which can be used in this current override config.
- Z-Siqi for creating an extensive list of [custom rules](https://github.com/Z-Siqi/Clash-for-Windows_Rule/) per service
- Clash team and their [wiki](https://en.clash.wiki/)