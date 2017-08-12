---
layout: post
title: Fixing Apple TV Home Sharing
---
I have an [Apple TV](https://www.apple.com/tv/) (3rd Gen) that could not play music from my home iTunes library nor view photos from iCloud.  Symptoms included:
  * Attempts to enable Remote app on IOS device shows a message "Turn on home sharing..."
  * Apple TV Photos app does not show photos from your library
  * Apple TV Music app does not have access to your iTunes music library.
  * Using Actiontec MI424WR router on Frontier FIOS

This turns out to be a network issue.  My router was filtering some traffic between network devices.  The fix is obscure, so here are the specific steps to resolve it:

### Step 1: Login to your router's admin interface at [https://192.168.1.1](https://192.168.1.1)

### Step 2: Click on "Advanced"
![Step 2]({{ site.url }}/assets/Home_sharing_fix_step1.png)

### Step 3: Click on "Routing"
![Step 2]({{ site.url }}/assets/Home_sharing_fix_step2.png)

### Step 4: Uncheck "Internet Group Management Protocol"
![Step 2]({{ site.url }}/assets/Home_sharing_fix_step3.png)

### Step 5: Reboot router.  I had to power-cycle it.

### Step 6: On your Apple TV, sign out of iTunes store and sign back in.

