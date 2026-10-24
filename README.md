# Plumb

A macOS app that shows where your disk space went, including the folders Finder and System Settings
hide, says in plain words what each one is and whether it's safe to remove, and clears only what you
pick.

This repository only holds the downloads. Get the latest version from
[Releases](https://github.com/DAdjadj/plumb-releases/releases/latest).

## Install

1. Download `Plumb.zip` from the latest release and unzip it.
2. Move **Plumb** to your Applications folder and open it.
3. The first time, macOS may say it can't verify the app. Open System Settings > Privacy & Security,
   scroll down and click **Open Anyway**. This is needed once.
4. Turn on Plumb in System Settings > Privacy & Security > Full Disk Access, then quit and reopen it,
   so it can measure folders macOS keeps private, like Mail and other apps' data. Without it, Plumb
   still works and leaves those folders closed.

Requires macOS 26 or later, on Apple Silicon or Intel. Plumb updates itself: it checks once a day, or
choose Check for Updates from the Plumb menu.

## Safety

Nothing moves until you confirm a cleanup. Files go to the Trash, and Plumb's History puts them back
where they were. Plumb never empties the Trash, never touches anything an app has open, and never
removes files that belong to macOS.

## Privacy

Your files and the scan stay on your Mac: no accounts, no analytics, no servers. The only network
request Plumb makes is the update check, which asks GitHub for the latest version number and contains
nothing about you.
