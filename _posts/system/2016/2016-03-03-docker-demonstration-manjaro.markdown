---
layout: post
title:  "Docker Demonstration (Manjaro), Running Multiple Guest OS"
date:   2016-03-03 13:01:15 +0700
categories: system
tags: [cloud, docker, package manager]
author: epsi

excerpt: 
  A cheap way to learn different package management 
  from major linux distribution using Docker.
  No need Virtual Machine nor Multiboot. Easy to setup.

related_link_ids: 
  - 16022800  # Learn LXC
  - 16030900  # Docker Debian   

---

**Description**: A cheap way to learn different package management from major linux distribution using Docker. No need Virtual Machine nor Multiboot. Easy to setup.
<br/><br/>

{% capture ss_content %}
<strong>Host OS</strong>: Manjaro<br/>
<strong>Container Service</strong>: Docker<br/>
  + Guest OS: Gentoo<br/>
  + Guest OS: Slackware<br/>
  + Guest OS: Fedora<br/>
  + Guest OS: Kali<br/>
  + Guest OS: Ubuntu<br/>
<br/>
<strong>WM</strong>: XMonad<br/>
  + Bar: Conky + Dzen<br/>
  + Terminal: XFCE Terminal<br/>
  + Script: Screenfetch<br/>
  + Wallpaper: Self Vexel (inkscape) with 3D background<br/>
{% endcapture %}

{% include part/screenshot.html ss_content = ss_content %}

[![Manjaro Docker Light: xmonad screenfetch (fedora, kali, ubuntu)][image-ss-fki]{: .img-responsive }][picasa-ss-fki]
<br/><br/>
[![Manjaro Docker Dark: xmonad screenfetch (gentoo, slackware)][image-ss-gs]{: .img-responsive }][picasa-ss-gs]
<br/>

Note: just another nix's porn. :-\ <br/>

**Reference**:<br/>

* <https://docs.docker.com/engine/quickstart/>

[//]: <> ( -- -- -- links below -- -- -- )

[image-ss-fki]: {{ site.url }}/assets/posts/system/2016/03/manjaro-docker-fki.png
[picasa-ss-fki]: https://lh3.googleusercontent.com/-j_6ANwMOhoo/VzmdhK000OI/AAAAAAAAAMk/F4HfQ71QX3w5fJUyDfQcNo2ZEUhKPa9OwCCo/s0/manjaro-docker-fki.png
[image-ss-gs]: {{ site.url }}/assets/posts/system/2016/03/manjaro-docker-gs.png
[picasa-ss-gs]: https://lh3.googleusercontent.com/-ZPn9TJf78Gw/VzmdkuxR7SI/AAAAAAAAAMk/IZi4ITsH8JUwKw3b77i5EEux39-krfXSgCCo/s0/manjaro-docker-gs.png
