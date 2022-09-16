# AMBA's Lameathon
This is a set of APIs with very different objectives. I had a lot of fun in writing them!

In total there are 6 hacks in one:

1. Dynamic Okta Badges
2. Bring the Action! (CLI abuse)
3. "Progessiver"
4. Action's Engine Explorer - Web shell (Platform abuse)
5. Tenant Token Request (CLI abuse)
6. FGA Preview* (Not everything is what it seems, CLI abuse)

After submitting this, I have to open two security tickets so that the team, who are specialists in this, could analyse concerns that I was left with.

### 1. Dynamic Okta Badges

This generated dynamic SVG badges including Okta's common Okta Icons. The parameters can be changed, but three default ones have been created (Auth0, Okta, FGA). The text has to be URL encoded.

Query Params:
- label
- labelColor
- color
- icon

![Badge 1](https://lt.a0.gg/api/badges/bta/This+is+the+first+badge)


### 2. Bring the Action

[![Bring the Action!](https://lt.a0.gg/api/badges/bta/%22Send%20to%20a%20webhook-this-is-dynamic%22)](https://bta.a0.gg?URL=https%3A%2F%2Fraw.githubusercontent.com%2Famba-sandbox%2Fdangerous-frog%2Fmain%2Fa0%2Factions%2Flogin%2Fforward-to-a-webhook.js&trigger=post-login&defaultName=Sensssssd%20to%20a%20webhook&dependency=qs&dependency=axios%40latest&secret=APIKEY&secret=BIN%3Dasd)
