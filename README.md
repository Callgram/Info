# CallGram

CallGram is a Telegram client, based on Telegram-FOSS with features added.



## CallGram Features

- Unlimited login accounts
- **Proxy**
    - Built-in VMess, Shadowsocks, SSR, Trojan-GFW proxies support (No longer maintained)
    - Built-in public proxy (WebSocket relay via Cloudflare CDN), [documentation and for PC](https://github.com/arm64v8a/CallGramProxy)
    - Proxy subscription support
    - Ipv6 MTProxy support
    - Able to parse all proxy subscription format: SIP008, ssr, v2rayN, vmess1, shit ios app formats, clash config and more
    - Proxies import and export, remarks, speed measurement, sorting, delete unusable nodes, etc
    - Scan the QR code (any link, can add a proxy)
    - The ( vmess / vmess1 / ss / ssr / trojan ) proxy link in the message can be clicked
    - Allow auto-disabling proxy when VPN is enabled
    - Proxy automatic switcher
    - Don't alert "Proxy unavailable" for non-current account
- **Stickers**
    - Custom [Emoji packs](https://github.com/CallGram-Dev/CallGram/wiki/emoji)
    - Add stickers without sticker pack
    - Sticker set list backup / restore / share
- **Internationalization**
    - OpenCC Chinese Convert
    - Full InstantView translation support
    - Translation support for selected text on input and in messages
    - Google Cloud Translate / Yandex.Translate support
    - Force English emoji keywords to be loaded
    - Persian calendar support
- **Additional Options**
    - Option to disable vibration
    - Dialog sorting is optional "Unread and can be prioritized for reminding" etc
    - Option to skip "regret within five seconds"
    - Option to not send comment first when forwarding
    - Option to use CallGram chat input menu: replace record button with a menu which contains an switch to control link preview (enabled by default)
    - Option to disable link preview by default: to prevent the server from knowing that the link is shared through Telegram.
    - Option to ignore Android-only content restrictions (except for the Play Store version).
    - Custom cache directory (supports external storage)
    - Custom server (official, test DC)
    - Option to block others from starting a secret chat with you
    - Option to disable trending
- **Additional Actions**
    - Allow clicking on links in self profile
    - Delete all messages in group
    - Unblock all users support
    - Login via QR code
    - Scan and confirm the login QR code directly
    - Allow clearing app data
    - Proxies, groups, channels, sticker packs are able to be shared as QR codes
    - Add "@Name" when long-pressing @user option
    - Allow creating a group without inviting anyone
    - Allow upgrading a group to a supergroup
    - Mark dialogs as read using tab menu
    - Enabled set auto delete timer option for private chats and private groups
    - Support saving multiple selected messages to Saved Messages
    - Support unpinning multiple selected messages
    - View stats option for messages
- **Optimization**
    - Keep the original file name when downloading files
    - View the data center you belong to when you don't have an avatar
    - Enhanced notification service, optional version without Google Services
    - Improved session dialog
    - Improved link long click menu
    - Improved hide messages from blocked users feature
    - Don't process cleanup draft events after opening chat
- **Others**
    - OpenKeychain client (sign / verify / decrypt / import)
    - Text replacer
- **UI**
    - Telegram X style menu for unpinning messages
    - Built-in Material Design themes / Telegram X style icons
- And more :)



## FAQ

#### What is the differences between CallGram and Nekogram?

Developed by different developers, read the feature list above to understand the differences.

#### What is the difference between the Full and Mini version?

The full version comes with built-in proxy support for v2ray, shadowsocks, shadowsocksr, and trojan, which is usually provided to advanced users to help friends who have no computer knowledge in mainland China to bypass censorship. Don't complain about imperfect functions or ask to add other rare proxy types, you can use their clients directly.

#### What if I don't need a proxy?

Then it is recommended to use the `Mini` version.

#### What is the noGcm version?

Google Cloud Messaging, also known as gcm / fcm, message push service by google used by original Telegram android app, it requires your device to have Google Service Framework (non-free) installed.

#### I've encountered a bug!

First, make sure you have the latest version installed (check the channel, Play store versions usually have a delay).

Then, if the issue appears in the official Telegram client too, please submit it to the officials, (be careful not to show CallGram in the description and screenshots, the official developers doesn't like us!).

Then, please *detail* your issue, create an issue or submit it to our [group](https://t.me/CallGramChat) with #bug.

If you experience a *crash*, you also need to click on the version number at the bottom of the settings and select "Enable Log" and send it to us.

### Privacy Policy

Callgram will not share any user data or device information with anyone. It is based on the official Telegram, so in order to learn more about it, please check [Telegram Privacy Policy](https://telegram.org/privacy)
