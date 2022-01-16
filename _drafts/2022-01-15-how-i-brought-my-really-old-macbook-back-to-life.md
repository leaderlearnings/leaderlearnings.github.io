---
layout: post
published: true
categories:
  - personal
mathjax: false
featured: false
comments: false
title: How I brought my really old Macbook back to life
---
## Intro

I have an old Macbook Black Mid-2007 (macbook2,1) that I don't use for real since 2014, when I replaced it by a new Mac. Recently I decided to sell it and get a few bucks. Before selling I turned it on to check if it still works and is useful for browsing the internet.

It is a Core 2 Due 2.16 GHz notebook, with 4GB RAM (but only can uses 3GB), has a 320GB HD, and Intel GMA 950 integrated ([max 224MB shared memory](https://en.wikipedia.org/wiki/Intel_GMA)). Detailed specs [here](https://everymac.com/systems/apple/macbook/specs/macbook-core-2-duo-2.16-black-13-mid-2007-specs.html). The lastest MacOS version it runs is Lion/10.7, released in 2011 and unsupported since Oct/2014. It also runs Windows via bootcamp, however the latest supported version is Windows 7 32-bit, released in 2009 and unsupported since Jan/2020. As both operating systems are no longer supported, users don't get security updates and forced to run old applications.

And that endded up being a big issue. Modern internet requires encryption to work (did you notice most websites are reachable via HTTPS instead of HTTPS nowadays?). HTTPS already existed back in 2011, however a lot has changed lately. SSL and TLS 1.0 and TLS 1.1 protocols are now deprecated for security reasons. That means modern websites no longer support SSL, TLS 1.0 and TLS 1.1. On the other hand newer TLS versions still didn't exist when MacOS Lion support ended. That means you won't be able to find a mainstream browser that works on Lion and and opens a modern website via HTTPS. I could find some obcure browsers for such an old MacOS version but all of them had problems: no Javascript support, no HTML 5 support, etc. In the end, the browsing experience with them was terrible. Forget about accessing YouTube, GMail, Facebook, etc.

As I looked for a long term solution I didn't spend much time on Windows 7. It's no longer supported and soon the scenario will be the same as for MacOS Lion. I needed to find a good and lightweight Linux distro to install. In the past I had MacOS and Gentoo installed at the same time in that computer. However after many years I gave up on baby siting Gentoo. Those were other times, when I was a student with endless time for playing with the computer. Also I'm looking for a Linux distro that could fit the computer buyer. Ubuntu used to be a good choice, however it no longer fits the job. From [Ubuntu's wiki](https://help.ubuntu.com/community/Installation/SystemRequirements):

```
From 17.10 onwards the desktop uses GNOME Shell. In order to run these environments the system needs a more capable graphics adapter – see more here or below:

- 4096 MiB RAM (system memory) for physical installs.
- 3D Acceleration Capable Videocard with at least 256 MB
```

That computer doesn't have minimum RAM and video memory required for running a recent Ubuntu disto :(
After spending some time reading about low demanding Linux distros I endded up choosing Zorin OS Lite. It only requires 1GB RAM, is beautiful, has a solid basis (Ubuntu) and has been professionally maintained for a long time (since 2008).

## Getting things done

Now things start to get more complicated.
1) DVD drive is not working
2) Macbook 2,1 (and probably other old ones) does not boot from USB if it uses MBR/BIOS.

That means 

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
