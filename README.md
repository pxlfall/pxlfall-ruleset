# pxlfall's custom ruleset for use in Stash (iOS) rule-based proxy application
[Click here](https://link.stash.ws/install-override/raw.githubusercontent.com/pxlfall/pxlfall-ruleset/main/pxlfall.stoverride) to install the override configuration file
## To-do list:
- [x] Implement good-enough all-around rule-set
- [ ] Figure out how to manually list servers in 'proxy-groups' from 'proxy-provider'
- [ ] Add 'url-test' proxy group for the following:
    - [x] TikTok
    - [ ] YouTube
    - [ ] \(Optional) Spotify
    - [ ] VK
    - [x] Telegran
    - [ ] Instagram (use only music-supported servers)
    - [ ] WhatsApp (make sure audio calls have no issues)
    - [ ] Twitch
    - [ ] Reddit (may be hidden)
    - [ ] Locket (US/UK servers)
    - [ ] 1Password (may be hidden)
    - [ ] Discord
    - [ ] Steam
- [ ] Rewrite the service provider config, so that only 'proxy-provider' is being used
- [ ] Create a mirror config for use in Clash for Windows
- [ ] Add custom specific Windows PC rules (i.e. '- PROCESS-NAME,迅游加速器.exe,DIRECT')
- [ ] Create a basic tile, on/off switch, total data received/sent in the last 24h (if possible), current selected general purpose server
- [ ] End goal is impossible to achieve, but continously fix rare-case issues with routing rules.