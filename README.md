# TownScaper Maps

![Mountain Ville](./resources/main-photo.png)

![Game](https://img.shields.io/badge/Game-Townscaper-blue)
![Type](https://img.shields.io/badge/Type-Map%20Hash-darkcyan)
![Supports](https://img.shields.io/badge/Supports-Desktop,%20Mobile-teal)

A collection of maps I made in the game Townscaper. These are more or less a collections of cool maps I built with each of them having their own theme going for them. 

## Contents

* [**Information**](#townscaper-maps)
    * [Mobile vs Desktop: Why Separate?](#mobile-vs-desktop-why-separate)
    * [Downloading Maps](#downloading-maps)
    * [Requirements](#requirements)

* [**Maps**](#maps)
    * [Mountain Ville](#mountain-ville)
    * [Rainbow Riviera](#rainbow-riviera)
    * [Riverland](#riverland)
    * Default Starter Map


## Mobile vs Desktop: Why separate?

The repo is split into two folders for two different versions of the game. one for the mobile version of the games and one for desktop installations. The reason for this is I've realised after playing on both platforms that the map boundaries (Height and area) are actually significantly different on these two platforms, so maps made on desktop are likely not to fully load on mobile as any blocks beyond the map boundaries get removed when loaded in the mobile app. 

Therefore, I split my maps into two directories based on which platform I used to build them. Any maps in the mobile directory can safely be loaded on desktop clients, but the other way round will almost certainly result in a map missing a large part of the build, so I would advice against doing that.

**TLDR:**

* Mobile users: Recommended only to use maps in [Mobile](./Mobile/) due to desktop having larger map sizes
* Desktop users: Can load any maps from [Mobile](./Mobile/) and [Desktop](./Desktop/) safely.

## Downloading Maps

Downloading a map to explore on your own device is extremely simple: 

* First, navigate to the chosen map's corresponding file in this repository
* Choose a version (Typically the one ending in `-final.txt`) and open the file
* Copy the full file's contents (These are usually all just a single really long line)
* Open your app on Mobile or Desktop
* In your settings, just click on "Load from Clipboard"

## Requirements

* The Townscaper App on either Mobile (From App Store, Playstore, etc.) or Desktop (From Steam, etc.)

Thats it!

---

# Maps

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
