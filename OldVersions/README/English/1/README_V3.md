
***

# Seanpm2001 DRM Blocklist

## Draft 3: 2024, Friday, April 19th

- Repository (coming April 20th) [:octocat: `Seanpm2001-DRM-Blocklist`](https://github.com/seanpm2001/Seanpm2001-DRM-Blocklist/)
- The issue that helped start this project [:octocat: `BlocklistProject#1213`](https://github.com/blocklistproject/Lists/issues/1213)

### Notes

- I am new to hosting/maintaining a blocklist, and this is my first time using the `Hosts file` language. Things likely won't work perfectly the first time, so please give feedback if you notice something isn't going right.
- Right now, the list mainly consists of mainstream sites.
- I plan to accept issues with new entries, but for the beginning, I am only going to accept issues that have the most links, as I want to build this list to be massive early on, then gradually increase and maintain it.
- - Please post issues with links, but add more links in replies to increase the chance of me accepting it. I won't always selectively target large troves, and will go for individual links at times as well.
- During the first 3 drafts, I didn't put forth 100% effort into this project, as I had other things to work on, and this project was too negative to be done at certain times of the day.

### Files/lists

- **Overview**
- 1. [`Sites that produce DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-produce-DRM/Sites-that-produce-DRM.txt)
- 2. [`Sites that use DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-use-DRM/Sites-that-use-DRM.txt
- 3. [`Sites that use EME (Light DRM)`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-use-EME-light-DRM/Sites-that-use-EME-light-DRM.txt)
- 4. [`Sites that used to use EME`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-used-to-use-EME/Sites-that-used-to-use-EME.txt)
- 5. [`Sites that used to use DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-used-to-use-DRM/Sites-that-used-to-use-DRM.txt)
- 6. [`Sites that used to produce DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-used-to-produce-DRM/Sites-that-used-to-produce-DRM.txt)
- 7. [`Sites that promote DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-promote-DRM/Sites-that-promote-DRM.txt)
- 8. [`Sites that used to promote DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-used-to-promote-DRM/Sites-that-used-to-promote-DRM.txt)
- 9. [`{DO NOT BLOCK} Sites that stand against DRM`](/Seanpm2001/DRM-Blocklist/Anti-blocklist/DO-NOT-BLOCK-Sites-that-stand-against-DRM.txt)
- 10. [`Sites that used to stand against DRM`](/Seanpm2001/DRM-Blocklist/Blocklist/Sites-that-used-to-stand-against-DRM/Sites-that-used-to-stand-against-DRM.txt)

> **Sites-that-produce-DRM.txt**

```hosts-file
# Sites that produce DRM
# WideVine
0.0.0.0 widevine.com/
# Adobe
0.0.0.0 www.adobe.com/
# FairPlay
0.0.0.0 www.apple.com/
# Valve Anti-Cheat
0.0.0.0 store.steampowered.com/
# Denuvo
0.0.0.0 irdeto.com/
```

> **Sites-that-use-DRM.txt**

```hosts-file
# Sites that use DRM
# Streaming services
0.0.0.0 www.netflix.com/
0.0.0.0 www.disneyplus.com/
0.0.0.0 www.apps.disneyplus.com/
0.0.0.0 help.disneyplus.com/
0.0.0.0 disney.com/
0.0.0.0 ondisneyplus.disney.com/
0.0.0.0 www.hulu.com/
0.0.0.0 help.hulu.com/
0.0.0.0 tv.youtube.com/
0.0.0.0 www.max.com/login
0.0.0.0 auth.max.com/
0.0.0.0 www.peacocktv.com/
0.0.0.0 www.espn.com/
0.0.0.0 plus.espn.com/
0.0.0.0 www.hbo.com/
0.0.0.0 movies.youtube.com/
# Music streaming services
0.0.0.0 music.youtube.com/
0.0.0.0 myspace.com/
0.0.0.0 www.napster.com/
# Video sharing sites
0.0.0.0 www.youtube.com/
0.0.0.0 www.youtubekids.com/
# Wiki sites
0.0.0.0 www.fandom.com/
# Digital storefronts
0.0.0.0 store.steampowered.com/
0.0.0.0 steamcommunity.com/
0.0.0.0 www.apple.com/itunes/
# Other social media
0.0.0.0 www.reddit.com/
```

> **Sites-that-use-EME-light-DRM.txt**

```hosts-file
# Sites that use EME (Encrypted Media Extensions) (a form of light DRM)
# Video sharing sites
0.0.0.0 www.youtube.com/
0.0.0.0 www.youtubekids.com/
# VoIP services
0.0.0.0 discordapp.com/
0.0.0.0 discord.com/
# Music sharing sites
0.0.0.0 bandcamp.com/
# Other social media sites
0.0.0.0 www.facebook.com/
0.0.0.0 www.twitter.com/
0.0.0.0 www.x.com/
0.0.0.0 www.instagram.com/
0.0.0.0 www.reddit.com/

```

> **Sites-that-used-to-use-EME.txt**

```hosts-file
# Sites that used to use EME (Encrypted Media Extensions) (a form of light DRM)
# Currently empty
```

> **Sites-that-used-to-use-DRM.txt**

```hosts-file
# Sites that used to use DRM
# Currently empty
```

> **Sites-that-used-to-produce-DRM.txt**

```hosts-file
# Sites that used to produce DRM
# Currently empty
```

> **Sites-that-promote-DRM.txt**

```hosts-file
# Sites that promote DRM
# Record labels
0.0.0.0 www.riaa.com/
# Film studios
0.0.0.0 www.motionpictures.org/
# Journalism
0.0.0.0 www.digitalguardian.com/
0.0.0.0 www.businessinsider.com/
0.0.0.0 www.digitaltrends.com/
# Blogs
0.0.0.0 www.howtogeek.com/
0.0.0.0 www.g2.com/
# Uncategorized
0.0.0.0 business.adobe.com/blog/basics/digital-rights-management
```

> **Sites-that-used-to-promote-DRM.txt**

```hosts-file
# Sites that used to promote DRM
# Currently empty
```

> **DO-NOT-BLOCK_Sites-that-stand-against-DRM.txt**

```hosts-file
# [DO NOT BLOCK] Sites that stand against DRM
# Free Software Foundation
0.0.0.0 www.gnu.org/
0.0.0.0 defectivebydesign.org/
0.0.0.0 fsfe.org
0.0.0.0 www.fsf.org//
# Electronic Frontiers Foundation
0.0.0.0 www.eff.org/
```

> **Sites-that-used-to-stand-against-DRM.txt**

```hosts-file
# Sites that used to stand against DRM
# Before being occupied by another company
0.0.0.0 www.napster.com/
```

#### Subcategories:

```hosts-file
# Streaming services
# Video sharing platforms
# Imaeg sharing platforms
# NFT Marketplaces
# Blogs
# Porn streaming services
# Music sharing platforms
# Document sharing platforms
# Digital storefronts
# Video games
# Activation servers
# Paywalls (split out)
```

> **TODO:**

- [ ] Sort A-Z

### Gitattributes

Replace `Plain text` with

```gitattributes
*.txt linguist-detectable=true
*.txt linguist-documentation=false
*.txt linguist-language=Hosts-file
```

***

## Qualifications

- Almost any current video/music streaming service in existence
- Sites that write articles with a pro-DRM stance

***

## Definitions

Common definitions within this project.

### DRM

- Stands for: `Digital Restrictive Measures` or `Digital restrictions management` (GNU definition)
- Does not stand for: `Digital Rights Management`
- Forms: `WideVine` `FairPlay` `Adobe Digital Editions` `Valve Anti-Cheat` `PrimeTime` `EME` `etc.`

Digital software/malware that attempts to take away the ownership rights and prevent the copying of files that the user has received through a digital distribution medium. DRM is constantly cracked, it is wasteful to both the environment (computing resources required to implement it) and talent (billions of dollars and millions of hours of time wasted per year on something that is not necessary, and can be cracked within days)

### EME

- Stands for: `Encrypted Media Extensions`
- Does not stand for: `Extended Media Encryption`
- Forms: `EME` `DRM`

A type of DRM (light DRM) that was controversially accepted as an Internet standard (due to support from sites like Netflix) but has caused monopolization of Internet software development, and hindered the progress of innovation (as all DRM does) this DRM tries to prevent users from right clicking/copying a file on a webpage, but isn't as heavy as a DRM scheme like WideVine. This type of DRM typically doesn't have to be asked to be used, and will run from the browser itself (even in Firefox)

### Light DRM

- Stands for: `Light Digital Restrictive Measures`
- Does not stand for: `Light Digital Rights Management`
- Forms: `EME` `DRM`

DRM that tries to prevent users from right clicking/copying a file on a webpage, but isn't as heavy as a DRM scheme like WideVine. This type of DRM typically doesn't have to be asked to be used, and will run from the browser itself (even in Firefox)

***

## Testing

### How to test for heavy presence of DRM

1. Load the website in Firefox (without DRM installed/enabled)
2. If there is a yellow popup by Firefox that says "you must enable DRM to access certain parts of this page" (non-verbatim text) then the site uses DRM and should be added to the list.

### How to test for presence of light DRM (EME)

1. Load the website in Firefox (without DRM installed/enabled)
2. Try right clicking various pieces of media on the page
3. If the save as option is græyed out or not present, the site likely uses EME
4. Additionally, if there is a yellow popup by Firefox that says "you must enable DRM to access certain parts of this page" (non-verbatim text) then the site uses DRM and should be added to the DRM list as well.

***

## Sources

TODO: Make citations regarding why websites were put on the blocklist.

***

## Internal usage

Other projects by me that plan to use this project

- [:octocat: `Bliss Browser`](https://github.com/seanpm2001/Bliss_Browser/)

***

# File info

**File version:** `3 (2024, Friday, April 19th at 06:13 pm PST)`

***

# File history

## Version 1 (2024, Wednesday, April 17th at 9:16 pm PST)

This version was created by [:octocat: @seanpm2001](https://github.com/seanpm2001/)

> Changes

- [x] Started the file
- [x] Added the `Title` section
- [x] Added the `Files/lists` section
- - [x] Added the `Sites that produce DRM` list
- - [x] Added the `Sites that use DRM` list
- - [x] Added the `Sites that use-EME light-DRM` list
- - [x] Added the `Sites that used-to use EME` list
- - [x] Added the `Sites that used-to use DRM` list
- - [x] Added the `Sites that used-to produce DRM` list
- - [x] Added the `Sites that promote DRM` list
- - [x] Added the `[DO NOT BLOCK] Sites that stand against DRM` list
- - [x] Added the `Sites that used to stand against DRM` list
- [x] Added the `Subcategories` section
- [x] Added the `Gitattributes` section
- [x] Added the `File info` section
- [ ] No other changes in version 1

## Version 2 (2024, Thursday, April 18th at 12:21 pm PST)

This version was created by [:octocat: @seanpm2001](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Title` section
- [x] Added the `Testing` section
- - [x] Added the `How to test for heavy presence of DRM` subsection
- - [x] Added the `How to test for presence of light DRM (EME)` subsection
- [x] Updated the `File info` section
- [x] Added the `File history` section
- - [x] Added an entry for versions 1 and 2
- [x] No other changes in version 2

## Version 3 (2024, Friday, April 19th at 06:13 pm PST)

This version was created by [:octocat: @seanpm2001](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Title` section
- [x] Added the `Notes` section
- [x] Updated the `Files/lists` section
- - [x] Improved formatting
- - [x] Added a link list of the 10 blocklist files
- [x] Added the `Qualifications` section
- [x] Added the `Sources` section
- [x] Added the `Definitions` section
- - [x] Added definition: `DRM`
- - [x] Added definition: `EME`
- - [x] Added definition: `Light DRM`
- [x] Added the `Internal usage` section
- [x] Updated the `File info` section
- [x] Updated the `File history` section
- - [x] Added an entry for versions 3
- [x] No other changes in version 3

***
