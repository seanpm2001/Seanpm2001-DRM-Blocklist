
***

# Seanpm2001 DRM Blocklist

## Draft 1 2024, Wednesday, April 17th

Right now, it mainly consists of mainstream sites. I plan to accept issues with new entries, but for the beginning, I am only going to accept issues that have the most links, as I want to build this list to be massive early on, then gradually increase and maintain it.

### Files/lists

**Sites-that-produce-DRM.txt**

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

**Sites-that-use-DRM.txt**

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

**Sites-that-use-EME-light-DRM.txt**

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

**Sites-that-used-to-use-EME.txt**

```hosts-file
# Sites that use EME (Encrypted Media Extensions) (a form of light DRM)
# Currently empty
```

**Sites-that-used-to-use-DRM.txt**

```hosts-file
# Sites that used to use DRM
# Currently empty
```

**Sites-that-used-to-produce-DRM.txt**

```hosts-file
# Sites that used to produce DRM
# Currently empty
```

**Sites-that-promote-DRM.txt**

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

**Sites-that-used-to-promote-DRM.txt**

```hosts-file
# Sites that used to promote DRM
# Currently empty
```

**DO-NOT-BLOCK_Sites-that-stand-against-DRM.txt**

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

**Sites-that-used-to-stand-against-DRM.txt**

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

**TODO:**

- [ ] Sort A-Z

### Gitattributes

Replace `Plain text` with

```gitattributes
*.txt linguist-detectable=true
*.txt linguist-documentation=false
*.txt linguist-language=Hosts-file
```

***

# File info

**File version:** `1 (2024, Wednesday, April 17th at 09:16 pm PST)`

***
