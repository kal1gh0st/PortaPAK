# PortaPAK
PortaPack Mayhem
Build Status buddy pipeline CodeScene Code Health GitHub All Releases GitHub Releases Docker Hub Pulls Discord Chat Check bounties!

This is a fork of the Havoc firmware, which itself was a fork of the PortaPack firmware, an add-on for the HackRF. A fork is a derivate, in this case one that has extra features and fixes when compared to the older versions.

 

PortaPack H2+HackRF+battery (clone) with a custom 3d printed case

![immagine](https://user-images.githubusercontent.com/56889513/117020309-9cf27600-acf6-11eb-84b0-2e47178601df.png)

Quick overview
If you are new to HackRF+PortaPack+Mayhem, there is an awesome introductory video by Tech Minds available:

Setup and overview

Frequently Asked Questions
This repository expands upon the previous work by many people and aims to constantly add new features, bugfixes and generate documentation to make further development easier. Collaboration is always welcomed and appreciated.

Does it work on H1/H2 PortaPack?
Yes, both devices are the same. The one I am using to test all changes is this PortaPack H2+HackRF+battery, which is a kit that includes everything you need. Sadly, the people making the H2 never made the updated schematics available, which is not ideal (and goes against the terms of the license). Most members of the community are using a clone of the PortaPack H1+HackRF+metal case, which does not include any battery functionality, but it is a cheaper alternative.

To support the people behind the hardware, please buy a genuine HackRF and PortaPack.

Where is the latest firmware?
The current stable release is on the GitHub release (latest by date) page. Follow the instructions you can find in the release description. There is also nightly builds generated periodically, which include the latest commits, but they may contain incomplete or buggy functionality.

Is this the newest firmware for my PortaPack?
Most probably: YES. If you find new features somewhere else, please suggest them.

Which one is actually the newest?
There is a lot of confusion of which is the latest version because no old version used any actual "version number". Additionally, since the files were distributed on facebook groups, github issue links and similar temporal sources, then there was no central location for them.

This fork (Mayhem) uses major.minor.release semantic versioning, so you can always compare your current version with the latest from Releases.

What about Havoc/GridRF/jamesshao8/jboone's?
jboone's PortaPack: the vanilla experience
Havoc: It was the most popular fork of jboone's PortaPack, currrently, it is not being maintained nor updated
jamesshao8: He keeps his own version of the fork, while not attached as a fork to anything. Latest functions do not follow the license and are not being published with source code, so keep this in mind
GridRF: They sell PortaPack clones with their own firmware based on a old version, which has no sourcecode available
How can I collaborate
You can write documentation, fix bugs and answer issues or add new functionality. Please check the following guide with details.

Consider that the hardware and firmware has been created and maintain by a lot of people, so always try colaborating your time and effort first. For coding related questions, if something does not fit as an issue, please join our Discord by clicking the chat badge on top.

What if I need help?
First, check the documentation. If you find a bug or you think the problem is related to the current repository, please open an issue.

You can reach the official community in Facebook, and our Discord by clicking the chat badge on top.

What if I find incongruencies, or grammatical errors in the text?
If is on the Wiki, you can modify it directly. If is on files of the repository, you can send corrections as pull requests. As a last resource, open an issue.
