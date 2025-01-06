---
layout: default
title: Resource-Pack-Updater
permalink: /resource-pack-updater
date: 2024-08-08
categories: tool
excerpt: A tool to update a directory of Minecraft resource packs to a desired version.
repo_link: https://gitlab.com/jkrr/Resource-Pack-Updater
---

# What?
When Minecraft releases a game update, it often makes [resource packs](https://minecraft.wiki/w/Resource_pack){:target="_blank" rel="noopener noreferrer"} outdated. This is because a specific version of the game is hard-coded into the packs' metadata. Assuming no actual changes have been made to the way resource packs are handled by the game, this script will go into a resource pack (which is stored as a compressed file), and change the hard-coded version to a desired game version, thereby updating the resource pack.

# Why?
Every time the game loads with an outdated resource pack, it halts you with a dialog box to confirm you wish to proceed. While not a major inconvenience, its simple solution just asked to be solved with a bit of automation.

# How?
The tool is a simple Python script that unpacks the compressed file, accesses its metadata, and changes the value of `pack_format`, which indicates which game version the pack is suitable for.
