# ublacklist-pinterest

A [uBlacklist](https://github.com/iorate/ublacklist) blocklist to remove Pinterest from your search results. It won't make Google useable, but still sligtly less worse.

|               | Normal           | Overkill option  |
|---------------|------------------|------------------|
| Basic list    | [Basic list](https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest.txt) / [Subscribe](https://iorate.github.io/ublacklist/subscribe?name=ublacklist-pinterest-basic&url=https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest.txt) | [Basic list overkill](https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest-ovk.txt) / [Subscribe](https://iorate.github.io/ublacklist/subscribe?name=ublacklist-pinterest-basic-overkill&url=https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest-ovk.txt) |
| Extended list | [Extended list](https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest-ext.txt) / [Subscribe](https://iorate.github.io/ublacklist/subscribe?name=ublacklist-pinterest-extended&url=https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest.txt) | [Extended list overkill](https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest-ext-ovk.txt) / [Subscribe](https://iorate.github.io/ublacklist/subscribe?name=ublacklist-pinterest-extended-overkill&url=https://raw.githubusercontent.com/rjaus/ublacklist-pinterest/main/ublacklist-pinterest.txt) |

## Basic list

The basic blocklist removes the Pinterest website and all its aliases that always show up in all your completely unrelared searches.

## Extended list
The extended blocklist also adds rules to remove all apps, socials and other services from the Pinterest, Inc. company.

## Overkill option

The overkill option adds a regex rule that block any URL containing `.pinterest.`. It will block all future TLDs like `pinterest.pin`, but will also block your favorite subdomain `pinterest.example.com`. [This is a regex rule as it is not supported by match pattern for security reasons.](https://developer.chrome.com/docs/extensions/mv3/faq/#faq-dev-16)

## References

[How Pinterest utterly ruined photo search on the internet](https://www.inverse.com/input/culture/pinterest-sucks-google-image-photo-search-ruining-internet)

## Alternatives

Both Chrome and Google only.
- [Unpinterested](https://github.com/sellomkantjwa/unpinterested)
- [Pinbusters](https://github.com/bzx/pinbusters)
