# BRUTEFOX - Firefox with Steroids
#### 💬 Tutorial on YouTube [here](https://www.youtube.com/embed/FlC7b2z4kHQ)
🇧🇷 Para o tutorial em português clique [aqui](https://github.com/cristiancmoises/brutefox/blob/main/LEIA-ME.md)

![bRUTE(1)](https://github.com/cristiancmoises/brutefox/assets/86272521/15afb340-af3f-4c3b-b029-d80ab0da59a0)

## For More Privacy Use:
<img src="https://github.com/cristiancmoises/torando/assets/86272521/045451b7-545a-4798-9df8-980b122b829d" href="https://github.com/cristiancmoises/torando" width="350" height="220"/>

> ### START FIREFOX AND TYPE IN THE SEARCH BOX:
             about:config
_*Then press enter_
> ### Paste the command and search, then change the value:
| COMMAND                                    | VALUE  | PURPOSE                                                                 |
|--------------------------------------------|--------|-------------------------------------------------------------------------|
| network.http.pipelining                    | True   | Enables HTTP pipelining to improve page load speed.                      |
| network.http.pipelining.maxrequests        | 32     | Increases max pipelined requests for faster data transfer.               |
| network.http.proxy.pipelining              | True   | Enables pipelining over proxies for performance.                        |
| network.dns.disableIPv6                    | True   | Disables IPv6 to reduce potential tracking via IPv6 addresses.           |
| plugin.expose_full_path                    | True   | Exposes full plugin paths for transparency (use cautiously).             |
| nglayout.initialpaint.delay                | 0      | Reduces delay before rendering pages for faster display.                 |
| content.notify.backoffcount                | 5      | Limits content notification frequency to improve performance.            |
| ui.submenuDelay                            | 0      | Eliminates submenu display delay for faster navigation.                  |
| browser.cache.memory.capacity               | 32768  | Increases memory cache for faster page loads.                            |
| layout.spellcheckDefault                   | 2      | Enables spellchecking in all text fields for usability.                  |
| browser.download.animateNotifications       | False  | Disables download notification animations for minimal distractions.      |
| security.dialog_enable_delay               | 0      | Removes delay for security dialogs to improve responsiveness.            |
| network.prefetch-next                      | False  | Disables prefetching to prevent unnecessary data requests.               |
| browser.newtabpage.activity-stream.feeds.telemetry | False | Disables telemetry for new tab page activity feeds.                     |
| browser.newtabpage.activity-stream.telemetry | False | Disables telemetry for new tab page features.                           |
| browser.ping-centre.telemetry              | False  | Disables telemetry ping center data collection.                         |
| toolkit.telemetry.archive.enabled           | False  | Prevents archiving of telemetry data.                                    |
| toolkit.telemetry.bhrPing.enabled          | False  | Disables background hang reporting telemetry.                           |
| toolkit.telemetry.enabled                  | False  | Disables general telemetry collection.                                  |
| toolkit.telemetry.firstShutdownPing.enabled | False | Prevents telemetry ping on first shutdown.                              |
| toolkit.telemetry.hybridContent.enabled    | False  | Disables hybrid content telemetry.                                      |
| toolkit.telemetry.newProfilePing.enabled   | False  | Prevents telemetry ping for new profiles.                               |
| toolkit.telemetry.reportingpolicy.firstRun | False  | Disables telemetry reporting policy on first run.                       |
| toolkit.telemetry.shutdownPingSender.enabled | False | Prevents telemetry ping on shutdown.                                    |
| toolkit.telemetry.unified                 | False  | Disables unified telemetry system.                                      |
| toolkit.telemetry.updatePing.enabled       | False  | Prevents telemetry ping for updates.                                    |
| reader.parse-on-load.enabled               | False  | Disables reader mode parsing on load to reduce data exposure.           |
| reader.parse-on-load.force-enabled         | False  | Prevents forced reader mode parsing.                                    |
| browser.pocket.enabled                     | False  | Disables Pocket integration to reduce data sharing.                     |
| loop.enabled                                | False  | Disables Firefox Hello (loop) feature to prevent tracking.              |
| privacy.resistFingerprinting               | True   | Limits data like screen size and fonts to reduce fingerprinting.        |
| privacy.firstparty.isolate                 | True   | Isolates identifiers to first-party domains to prevent cross-site tracking. |
| dom.battery.enabled                        | False  | Blocks battery status access to prevent fingerprinting.                 |
| dom.event.clipboardevents.enabled          | False  | Disables clipboard event notifications to reduce tracking.              |
| geo.enabled                                | False  | Disables geolocation to prevent location-based tracking.                |
| media.navigator.enabled                    | False  | Blocks microphone/camera status detection to reduce fingerprinting.     |
| webgl.disabled                             | True   | Disables WebGL to prevent fingerprinting (may break graphics-heavy sites). |
| network.http.referer.trimmingPolicy        | 2      | Sends only the origin in referer headers to limit tracking via referers. |
| network.http.referer.spoofSource           | True   | Spoofs referer headers to obscure the true source page.                  |
| media.webrtc.enabled                       | False  | Disables WebRTC to prevent IP leaks and peer-to-peer tracking.           |
| beacon.enabled                             | False  | Disables beacon API to prevent background data sends.                    |
| browser.send_pings                         | False  | Prevents ping attributes in HTML from sending tracking data.             |
| network.http.speculative-parallel-limit    | 0      | Disables speculative connections to prevent unnecessary data requests.  |
| privacy.trackingprotection.enabled         | True   | Enables built-in tracking protection to block known trackers.            |
| privacy.trackingprotection.socialtracking.enabled | True | Blocks social media trackers specifically.                              |
| browser.sessionstore.privacy_level         | 2      | Prevents session data from being saved for cross-site tracking.          |
| dom.storage.enabled                        | False  | Disables DOM storage to prevent tracking via local/session storage.      |
| security.mixed_content.block_active_content | True  | Blocks insecure active content on HTTPS pages for security.             |
| security.mixed_content.block_display_content | True | Blocks insecure display content on HTTPS pages for security.            |

### INSTALL SOME ADDONS TO INCREASE SECURITY:
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/f93b99c3-b7dc-40a8-8a80-9eb7bc007fe5)
[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/f9c52e17-b859-4318-80a0-8d45f26da806)
[Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/dccd79b3-c58b-404e-a30b-deba0b8abeab)
[CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/)
![image](https://github.com/user-attachments/assets/c83c872f-1fdb-483e-bb85-624c8f01a788)
[LibRedirect](https://addons.mozilla.org/en-US/firefox/addon/libredirect/)
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/cfb0b18a-bd20-4754-ad88-72ee4cd48d2c)
[BrowSec](https://addons.mozilla.org/en-US/firefox/addon/browsec/)

### VPN Recommendation for System-Wide Privacy:
<img src="https://mullvad.net/press/MullvadVPN_logo_Round_RGB_Color_positive.png" width=30% height=30%>

[Mullvad VPN](https://mullvad.net/en)
- **Purpose**: Masks your IP address, a key fingerprinting component, protecting all internet traffic.
- **Steps**: Visit [Mullvad VPN](https://mullvad.net/en), generate an account, pay €5/month, download the app, and connect to a server.

### LibRedirect Configuration:
      [Reddit]: https://libre.securityops.co
      [YouTube]: https://yt.securityops.co
      [Wikipedia]: https://wiki.securityops.co

### FOR PARANOIDS:
<img src="https://github.com/cristiancmoises/brutefox/assets/86272521/0a0512cb-2672-4e79-bf84-7be9772adae2" width=60% height=60%>

![image](https://github.com/cristiancmoises/brutefox/assets/86272521/e6aa98fd-6dc8-4a2f-abe5-79f822e131f5)
[NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/)
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/724a9ca5-3943-4441-8dcb-3e344a1242b8)
[LibreJS](https://ftp.gnu.org/gnu/librejs/librejs-7.21.0.xpi)

### Tor Configuration:
Go to network settings > Manual proxy configuration:
![torando](https://github.com/user-attachments/assets/229176a8-fad5-4cfa-8001-0d4253699195)

### BONUS - A TRUE DARK BROWSER
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/db293502-20d8-45ea-be6b-c417f6160371)
[AmoledTheme](https://addons.mozilla.org/en-US/firefox/addon/all-back-no-highlight/)
![image](https://github.com/cristiancmoises/brutefox/assets/86272521/2fcb5977-8270-48cd-9307-f363ee0bdbc3)
[DarkBG](https://addons.mozilla.org/en-US/firefox/addon/dark-background-light-text/)

# 🌟 Star History
[![Star History Chart](https://api.star-history.com/svg?repos=cristiancmoises/brutefox&type=Date)](https://star-history.com/#cristiancmoises/brutefox&Date)
