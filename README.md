# arceo

``` text
> A soft-blocklist against social media, news, entertainment & consumerism
```
## Use blocklist

[![uBO — add this filter](ubo.svg)](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fcodeberg.org%2Fpolarhive%2Farceo%2Fraw%2Fbranch%2Fmain%2Flists%2Fall.txt&title=arceo)

<details>
<summary>Import uBlock filters manually</summary>


  1. Open uBlock Origin settings
  2. Under the "Filter lists" tab, scroll to the bottom where it says “Custom” and click the “Import” checkbox to reveal the custom URL textbox
  3. Append the URL `https://codeberg.org/polarhive/arceo/raw/branch/main/lists/all.txt` in the textbox
  4. Press `Apply Changes` in the upper left

</details>

Alternatively, append the domains to your `/etc/hosts` file for hard-blocking sites.

## What's soft-blocking? 

When you use uBlock Origin — you can temporarily whitelist the site to load content should you need it. Cold Turkey? Block websites system-wide. Append the blocklist to your `/etc/hosts` file. But unblocking sites takes a bit more time. This friction should work to your advantage.

## Wanna add a site? 

Sure send me an [email](mailto:polarhive@riseup.net?subject=arceo-entry) or use [this](https://polarhive.ml/contact/) form.

## Criteria?

Anything that has a feed, primarily news sites & mainstream social media, sites that have anti-user behavior like tracking or unwanted `recommendation engines` waiting to feed you more content, wasting your time. Feel free to fork this project & use tune it to your needs. I block Facebook, Reddit, Twitter, YouTube & other mainstream social media in my config.

## Why did you make this?

Generally I get all my news via RSS feeds via [newsboat](https://polarhive.ml/dots), in pure plain-text, so I don't hard block sites in my hosts file. I don't like recommendation engines when I'm browsing. I want things to be static, not disturb my workflow. [Here's](https://polarhive.ml/blog/rss-feeds/) a blog post I've written about it.

### What's with the name?

``` text
arceo: Latin word meaning — 'keeping away' or 'preventing'
```
---
This repo is hosted on [Codeberg](https://polarhive.ml/arceo) & mirrored to [GitHub](https://polarhive.ml/github) for traffic.

[![license: GPLv3 or Later](https://polarhive.ml/assets/badges/gpl-3.svg)](https://www.gnu.org/licenses/gpl-3.0.txt)

