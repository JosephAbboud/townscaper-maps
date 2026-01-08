# TownScaper Maps

![Mountain Ville](./resources/main-photo.png)

![Game](https://img.shields.io/badge/Game-Townscaper-blue)
![Type](https://img.shields.io/badge/Type-Map%20Hash-darkcyan)
![Supports](https://img.shields.io/badge/Supports-Desktop,%20Mobile-teal)

A collection of maps I made in the game Townscaper. These are more or 
less a collections of cool maps I built with each of them having their 
own theme going for them. 

## Contents

* [**Information**](#townscaper-maps)
    * [Mobile vs Desktop: Why Separate?](#mobile-vs-desktop-why-separate)
    * [Downloading Maps](#downloading-maps)
    * [Requirements](#requirements)

* [**Maps**](#maps)
    * [Hoverburg](#hoverburg)
    * [Meadowhaven](#meadowhaven)
    * [Mountain Ville](#mountain-ville)
    * [Rainbow Riviera](#rainbow-riviera)
    * [Riverland](#riverland)
    * [Tripolis](#tripolis)
    * Default Starter Map


## Mobile vs Desktop: Why separate?

The repo is split into two folders for two different versions of the
game. one for the mobile version of the games and one for desktop
installations. The reason for this is I've realised after playing on
both platforms that the map boundaries (Height and area) are actually
significantly different on these two platforms, so maps made on desktop
are likely not to fully load on mobile as any blocks beyond the map
boundaries get removed when loaded in the mobile app. 

Therefore, I split my maps into two directories based on which platform
I used to build them. Any maps in the mobile directory can safely be 
loaded on desktop clients, but the other way round will almost 
certainly result in a map missing a large part of the build, so I would 
advice against doing that.

**TLDR:**

* Mobile users: Recommended only to use maps in [Mobile](./Mobile/) due
to desktop having larger map sizes
* Desktop users: Can load any maps from [Mobile](./Mobile/) and 
[Desktop](./Desktop/) safely.

## Downloading Maps

Downloading a map to explore on your own device is extremely simple: 

* First, navigate to the chosen map's corresponding file in this repository
* Choose a version (Typically the one ending in `-final.txt`) and open the file
* Copy the full file's contents (These are usually all just a single really long line)
* Open your app on Mobile or Desktop
* In your settings, just click on "Load from Clipboard"

## Requirements

* The Townscaper App on either Mobile (From App Store, Playstore, etc.) 
or Desktop (From Steam, etc.)

Thats it!

---

# Maps

## Hoverburg

![Hoverburg as seen from above](./resources/hoverburg.png)
![Hoverburg side view](./resources/hoverburg-wide.png)

* **Platform:** Desktop
* [Map Download](./Desktop/hoverburg/hoverburg-final.txt)

### Description

Hoverburg is, as the name would suggest, a city in the sky. Leveraging 
one of the more hidden mechanics in the game, the entire map is fully 
levitating off the ground, with propellers holding the entire city in 
the sky. The map features a main central island with a castle at its centerpiece, and branches off into 6 arms. The islands themselves are as symmetric as the game allows (That is, not quite as symmetric as I would've liked, especially for the outermost islands) and all feature a large white building as a centerpiece for each branched island. 

### Development Notes

A hidden game mechanic exists whereby if you build a circle (Or any 
shape where the corners are triangle blocks) and fill the area in 
fully, as the triangle corners leave no place for stilts to be 
generated. A great instruction guide (And the one I followed to 
discover this trick) showing how this is achieved can be found at this 
[link](https://steamcommunity.com/sharedfiles/filedetails/?id=2586791516).

## Meadowhaven

![Meadowhaven as seen from above](./resources/meadowhaven.png)

* **Platform:** Desktop
* [Map Download](./Desktop/meadowhaven/mh-final.txt)

### Description

Meadowhaven is a fortified meadow-port set on a wide, irregular island, 
themed around the countryside. The map is themed on what you might 
expect to find in the countryside in countries like the UK, France, and 
the likes, or at least that was the intended vibe. The internal area 
includes 4 villages, 2 large villages/towns and 2 smaller clusters of 
houses, separated by what is intended to look like farmland and woods 
with houses scattered along the plains. Beyond the walls are several 
access points by sea to fit the oceanic theme of Townscaper, providing 
access to the map through fishing-town-like settlements. 

The theme of the build centers on a calm, architectural aesthetic with 
a painterly touch, aiming for a harmonic blend between open fields and 
cozy villages.

### Development Notes

Extra effort was put into ensuring that the build had a properly 
networked path system, since you cannot directly build the paths, and 
even one house placement could completely change the path and fence 
layout in a huge chunk of the map. Unfortunately, because of how 
Townscaper generates these paths, the villages do not have any paths 
going between the houses, which is the opposite of what you would want 
for a more densly populated area. 

This took a lot more effort and precision than you'd first think as 
even one incorrect house placement tended to mess up the entire path 
structure of the map, which really limited how the houses could be 
placed. Not only that, but some house placements could also completely 
break the landscape generation where some paths and fences just end 
abruptly and unnaturally, causing really weird visual glitches which 
aren't very pleasant to look at. 

## Mountain Ville

![Mountain Ville as seen from above](./resources/mountain-ville.png)

* **Platform:** Desktop
* [Map Download](./Desktop/mountain-ville/mountain-ville-final.txt)

## Rainbow Riviera

![Rainbow Riviera as seen from above](./resources/rr-thumbnail.png)

* **Platform:** Desktop
* [Map Download](./Desktop/rainbow-riviera/rr-final.txt)

## Riverland

* **Platform:** Mobile
* [Map Download](./Mobile/riverland-town/riverland-town-save-3.txt)

## Tripolis

![Tripolis as seen from above](./resources/tripolis.png)

* **Platform:** Desktop
* [Map Download](./Desktop/tripolis/tripolis-final.txt)
