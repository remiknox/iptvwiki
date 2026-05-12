
Posted by u/gusestrella in r/IPTVGroupBuy on Mon Jan 06 2025 01:52:03 GMT+0

Have created a program to be able to search a provider service for a given channel name (or all channels within a category) and then check if they have EPG, if they have catchup capabilities and most importantly what resolution and frame rate they offer. Find it useful when looking for which is the best channel to favorite (ex. from the tons of ESPN or TSN options) and also get info on channels while checking a potential provider. So far seeing tremendous variability on what the provider names their channel (like 4k or FHD) and the resolutions they provide.

Here is a sample output of checking for TSN channels for a trial provider -

`find-iptv-channels-details - Running for server` [`xxxxx.cdngold.me`](http://xxxxx.cdngold.me) `on 2025-01-01 20:34`
`Name Category Archive EPG Codec Resolution Frame`
`=================================================================================`
`US: TSN SPORT 2 HD US| SPORT HD/4K 0 0 h264 1920x1080 60`
`US: TSN SPORT 3 HD US| SPORT HD/4K 0 0 h264 1920x1080 60`
`US: TSN SPORT 4 HD US| SPORT HD/4K 0 0 h264 1920x1080 60`
`US: TSN SPORT 5 HD US| SPORT HD/4K 0 0 h264 1920x1080 60`
`CA EN: TSN 1 CA| SPORTS EN 0 166 h264 1280x720 30`
`CA EN: TSN 2 CA| SPORTS EN 0 139 h264 1920x1080 60`
`CA EN: TSN 3 CA| SPORTS EN 0 158 h264 960x540 60`
`CA EN: TSN 4 CA| SPORTS EN 0 169 h264 1920x1080 30`
`CA EN: TSN 5 CA| SPORTS EN 0 166 h264 960x540 60`
`####### TSN SPORT ᴿᴬᵂ ####### CA| TSN SPORT HD/4K 0 0 h264 1920x1080 30`
`CA: TSN 1 ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 960x540 60`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1920x1080 60`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 640x360 30`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 960x540 60`
`CA: TSN 1 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 640x360 30`
`CA: TSN 2 ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 1280x720 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 960x540 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 640x360 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 960x540 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 1920x1080 60`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 1280x720 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 1280x720 30`
`CA: TSN 2 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 640x360 30`
`CA: TSN 3 ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 1280x720 60`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 960x540 60`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 640x360 30`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 960x540 60`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 1920x1080 60`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 1280x720 30`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 1280x720 30`
`CA: TSN 3 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 158 h264 640x360 30`
`CA: TSN 4 ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 1280x720 30`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 1280x720 60`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 960x540 60`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 1920x1080 60`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 139 h264 1280x720 30`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 1280x720 30`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 640x360 30`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 1280x720 30`
`CA: TSN 4 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 169 h264 640x360 30`
`CA: TSN 5 ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 960x540 60`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 960x540 60`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1920x1080 60`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 1280x720 30`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 640x360 30`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 640x360 30`
`CA: TSN 5 ⁽ᴮᴷ⁾ ᴿᴬᵂ CA| TSN SPORT HD/4K 0 166 h264 640x360 30`

The program is at [https://github.com/estrellagus/iptv-tools](https://github.com/estrellagus/iptv-tools)