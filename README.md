# arceo

``` text
> A soft-blocklist against social media, news, entertainment & consumerism
```

[![uBO: add this filter](ubo.svg)](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fcodeberg.org%2Fpolarhive%2Farceo%2Fraw%2Fbranch%2Fmain%2Flists%2Fall.txt&title=arceo)

<details> <summary>Import uBlock filters manually</summary>

  1. Open uBlock Origin settings
  2. Under the "Filter lists" tab, scroll to the bottom where it says “Custom” and click the “Import” checkbox to reveal the custom URL textbox
  3. Paste the URL `https://codeberg.org/polarhive/arceo/raw/branch/main/lists/all.txt` into the textbox
  4. Press `Apply Changes` in the upper left hand corner

</details>

Note: For some reason the add to uBlock-Origin button only works when you view
this repository on [GitHub](https://github.com/polarhive/arceo), proceed to add
the URL manually. Alternatively, append the blocklist to your `/etc/hosts` file
for hard-blocking sites.

## Why did you make this?

Nowadays, I get all my social media updates using RSS feeds: using
[newsboat](https://polarhive.net/dots). I block Facebook, Reddit, Twitter,
YouTube & other mainstream social media in this blocklist.

I can browse and search articles locally, in pure plain-text. Paired with
newsboat macros, I can archive videos with yt-dl, maintain a weekend binge-list
or save articles for-later. I don't like recommendation engines when I'm
browsing. I want things to be static & not disturb my [workflow](https://polarhive.net/blog/rss-feeds/).
I've blocked news sites, streaming sites, e-commerce and sites that
have anti-user behaviour — à la tracking, recommendation engines that
keep you hooked. Feel free to fork this project & tune it to your needs.

## Want to add a site?

Did I miss any site? Send me an
[email](mailto:mail@polarhive.net?subject=arceo-entry) or use my
[/contact](https://polarhive.net/contact/) form.

## What's soft-blocking?

When you use uBlock Origin — you can temporarily whitelist the site to load
content should you need it. Want to go Cold Turkey? — block websites
system-wide by appending the blocklist to your `/etc/hosts` file.

Note: Unblocking sites takes a bit more time as you need to clear your local
DNS cache / rebooting. This friction should work to your advantage.

### What's with the name?

``` text
arceo: Latin word meaning — 'keeping away' or 'preventing'
```

---
This repo is hosted on [Codeberg](https://polarhive.net/arceo) & mirrored to [GitHub](https://polarhive.net/github) for traffic.

[![license: GPLv3 or Later](https://polarhive.net/assets/badges/gpl-3.svg)](https://www.gnu.org/licenses/gpl-3.0.txt)
