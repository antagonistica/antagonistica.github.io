# Deduplicating Backups using Borg under NixOS (locally)

1. TOC
{:toc}

## The goal

We want to have a way to automatically and reliable create backups of our data in NixOS.
In my case I want to store the encrypted backups locally to upload them later on.
There are also solutions to store the backups remotely like [BorgBase](https://www.borgbase.com/) and you can find instructions on how to set it up in the [NixOS Wiki](https://nixos.wiki/wiki/Borg_backup). We'll keep it real simple and local here.

### What is Borg

[BorgBackup](https://www.borgbackup.org/) or in short Borg is a deduplicating backup program.
For my use case it's most important features are:

* Space efficient storage
* Speed
* Data encryption
* Compression
* Backups mountable as file system
* Easily configurable via [NixOS options](https://mynixos.com/nixpkgs/option/services.borgbackup.jobs)
* Free and Open Source Software

### The Setup

I currently run on NixOS 23.11 (Darwin) with home-manager.
But I installed `borgbackup` in my `environment.systemPackages`.
I have spare hard drive in my computer that I want to use for saving my backups locally.

### The Result

## The Preparation

## The Execution

## Wrapping Up