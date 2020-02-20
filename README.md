## Brave Browser Repository

## wellcome to @github pages
## https://github.com/52005723+ruzyysmartt/brave-browser-repository.git

## Overview

This repository holds the build tools needed to build the Brave desktop browser repository for macOS, Windows, and Linux.  In particular, it fetches and syncs code from the projects we define in `package.json` and `src/brave/DEPS`:

    - [Chromium](https://chromium.googlesource.com/chromium/src.git)
    - Fetches code via `depot_tools`.
    - sets the branch for Chromium (ex: 65.0.3325.181).
    - [brave-core](https://github.com/52005723+ruzyysmartt/brave/brave-browser-repository.core)
    - Mounted at `src/brave`.
    - Maintains patches for 3rd party Chromium code.
    - [ad-block](https://github.com/52005723+ruzyysmartt/brave-browser-repository/ad-block)
    - Mounted at `src/brave/vendor/ad-block`.
    - Implements Brave's ad-block engine.
    - [tracking-protection](https://github.com/52005723+ruzyysmartt/brave-browser-repository/tracking-protection)
    - Mounted at `src/brave/vendor/tracking-protection`.
    - Implements Brave's tracking-protection engine.

## Build instructions

See the [Brave Wiki](https://github.com/52005723+ruzyysmartt/brave/brave-browser-repository/wiki).

## Downloads

You can [visit our website](https://brave.com/download) to get the latest stable release.

## Other repositories

For other versions of our browser, please see:

* iOS - [brave/brave-browser-repository.ios](https://github.com/52005723+ruzyysmartt/brave/brave-browser-repository.ios)
* Android - [brave-browser-repository/android-tabs](https://github.com/52005723+ruzyysmartt/brave-browser-repository/android-tabs)

## Community

[Join the Q&A community](https://community.brave.com/) if you'd like to get more involved with Brave. You can [ask for help](https://community.brave.com/c/support-and-troubleshooting),
[discuss features you'd like to see](https://community.brave.com/c/brave-feature-requests), and a lot more. We'd love to have your help so that we can continue improving Brave.

Help us translate Brave to your language by submitting translations at https://www.transifex.com/brave/brave-browser-repository

Follow [@brave](https://twitter.com/brave-browser-repository) on Twitter for important news and announcements.
@GitHub.2020
