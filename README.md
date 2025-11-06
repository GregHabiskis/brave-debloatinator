# What is disabled in Brave Debloatinator?

The following items are disabled, blocked, or changed by appling brave debullshitinator:

* Brave Rewards, Wallet, & VPN
* Brave AI/Leo (some people may like Leo, in which case you can reenable it following the [customization guide](https://github.com/MulesGaming/brave-debullshitinator/wiki/Customization))
* Built-in password manager & autofill (I recommend using a third party password manager such as [Bitwarden](https://bitwarden.com) or [Proton Pass](https://proton.me/pass) that isn't tied to Brave sync or any one browser.)
* Brave's Tor integration, as it is insecure.
* Brave Web Discovery Project
* Safe Browsing Protection, to enhance privacy. I highly recommend using NextDNS with Hagezi Multi Pro Plus Blocklist inside Portmaster or RethinkDNS Firewall. If you want to keep using Google's protection, follow the [customization guide](https://github.com/MulesGaming/brave-debullshitinator/wiki/Customization))
* JavaScript Optimizer, to enhance security. Sites may load slower, But I didn't notice much difference.
* Video Autoplay
* Brave Search is the Default Search Engine
* Memomy Saver is set to Maximum
* Non Proxied UDP connections are blocked

Brave and most other browsers disable “Send Do Not Track Request” by default. It's recommended to keep it as is. Because most websites don't respect that request, and in most cases, it's used for further fingerprinting the user.

-------

# What Brave Debloatinator does NOT improve?

The following items are not applied due to policies for these items being nonexistent. These options can be found in Settings -> Shields. Kindly follow the recommendations:

* Trackers & ads blocking        :  Aggressive
* Upgrade connections to HTTPS   :  Strict
* Social media blocking          :  Uncheck All

-------

# How does it work?

Brave debloatinator uses [group policies](https://support.brave.com/hc/en-us/articles/360039248271-Group-Policy) typically used to manage organisations browsers to force disable fetures. Group policies are the only way to completly hide these fetures from settings and context menus.

-------

# Installation

Windows: https://github.com/MulesGaming/brave-debullshitinator/wiki/Installation-instructions#windows
Note: I recommend using Slim Brace if your on windows as it does a similar thing as [brave debullshitinator](https://github.com/ltx0101/SlimBrave) but provides more customization via a gui.

MacOS: We currently do not officaly support MacOS, however testers for it would be appreciated. Please see [pull request #6](https://github.com/MulesGaming/brave-debullshitinator/pull/6) for more information if you are interested in bringing this tool to Mac.

Linux: https://github.com/MulesGaming/brave-debullshitinator/wiki/Installation-instructions#linux

-------

# Customizing

[Please see the wiki for instructions on how to change modifications.](https://github.com/MulesGaming/brave-debullshitinator/wiki/Customization)

# Additional Resources

You can check out similar tools [here](https://github.com/MulesGaming/brave-debullshitinator/wiki/Additional-Resources#other-tools) and see domains to blacklist with your dns [here](https://github.com/MulesGaming/brave-debullshitinator/wiki/Additional-Resources#brave-telemetrytracking-dns-blacklists)
