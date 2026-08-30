---
title: "The stack I use every day"
description: "Phone, machines, identity, and how I publish. What I use and why."
pubDate: 2026-08-29
tags: ["systems", "privacy"]
translationKey: "stack"
---

This article is an inventory of what I am using right now: Pixel, Debian, Proton, and hosting for the static pages. I write it so I do not have to repeat it in every conversation and so I have a good excuse for people to visit my blog.

## Phone: Pixel 10 and GrapheneOS

I carry a Pixel 10 with [GrapheneOS](https://grapheneos.org/). The system brings its own patch cycle, memory hardening, and per-app sandbox; user profiles are meant to isolate data for real and to get the maximum privacy on my device.

GrapheneOS stays on Pixel because the hardware fits that model: Titan M2, verified boot, and an update cadence the project can follow. I do not use Samsung, Xiaomi, or other brands because I cannot have the control I have on my GrapheneOS.

The phone has two profiles.

**Clean profile.** Owner. F-Droid, Graphene apps, Proton, the browser, and whatever can run without a Google account. It is the profile I spend the day on when Google Play is not needed.

**Sandbox profile.** Secondary user with Google services inside its own storage. Maps, the bank apps that require Play Integrity, Instagram, etc. Google is still on the phone, but on another user and without collecting information about me 24x7.

GrapheneOS already splits the device by users. Signing out of the sandbox cuts that environment off without installing a second system or putting a “firewall” on top of a stock Android.

Why I do not use an iPhone or a Mac. Basically because the system is not audited the way I want, storage is not controlled the same way, and the account is part of the product. I like having absolute control of all my devices and with Apple I could not do whatever I want whenever I want.

## Debian on the laptop and the desktop

The laptop runs Debian. The desktop does too (that is the one I use to play on Steam and GOG Galaxy).

I stay on Debian because of the repositories, the cycle, and the fact that I can follow a package back to its origin. Every six months another immutable distro shows up with another pitch. I want a system that survives updates without turning me into a beta tester for whoever’s installer.

Also, to play I use Steam and GOG Galaxy, two game stores and launchers that treat the user well, you do not have to pay online, and I genuinely think they do a very good job for the consumer.

## Identity: Proton and my own domain

Mail, calendar, drive, and passwords are on Proton, hanging off `francisespejo.com`. The public mailbox is `fran@francisespejo.com`. For everything I use the Proton suite; for very little per year you get VPN, Drive, email, password manager... So far they have not let me down.

The domain is mine. If Proton goes down or I switch providers, the MX records point somewhere else and the address stays the same

## Code and web: GitHub, public

The landing ([francisespejo.com](https://francisespejo.com)) and this blog are static: generated HTML, GitHub, and GitHub Pages.

An article is a Markdown file and a commit. I skip WordPress; I used it a lot before but I now prefer something simpler for what I want to put here. The repo is public. If you want to see how it is put together, clone it. The site you are reading can be copied whole.

## Conclusion

In the end, my wish is the same on the phone, on the laptop, and on the web. I want to know who updates, where things are stored, and what runs next to what. GrapheneOS splits the Pixel into profiles. Debian lets me follow a package to the repo. Proton hangs off a domain I can repoint. And with GitHub I can upload my code and put up a simple but effective blog to share interesting things.

Obviously they are always going to steal data from me and at some point something I use will let me down because a provider can change its terms or disappear. If you want more details, write to me by email or on my socials :)
