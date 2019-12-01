## Sonarr Drobo Edition v2.0.0.5338

This is a modded version of Sonarr to run on Drobo.
I made this version because my older version did not run anymore.
This is more or less a clone of the Main github just with drobo start up

Version : 2.0.0.5338

## What is Sonarr?

Sonarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.

## Major Features Include:

* Support for major platforms: Drobo, Windows, Linux, macOS, Raspberry Pi, etc.
* Automatically detects new episodes
* Can scan your existing library and download any missing episodes
* Can watch for better quality of the episodes you already have and do an automatic upgrade. *eg. from DVD to Blu-Ray*
* Automatic failed download handling will try another release if one fails
* Manual search so you can pick any release or to see why a release was not downloaded automatically
* Fully configurable episode renaming
* Full integration with SABnzbd and NZBGet
* Full integration with Kodi, Plex (notification, library update, metadata)
* Full support for specials and multi-episode releases
* And a beautiful UI

## Configuring Development Environment:

### Requirements

* [MONO 5](https://www.mono-project.com/download/stable/)
* [Git](https://git-scm.com/downloads)
* [NodeJS](https://nodejs.org/en/download/)

### How to install

* Clone this github to a folder named : NzbDrone
* Place the NzbDrone folder in to : \DroboApps\ <-- Folder
* Reboot your drobo
* NzbDrone will be running under your app section
* http://DROBOIP:8989
