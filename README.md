# Minion for Linux

Minion is an addon manager for The Elder Scrolls Online.

Website: [https://minion.gg/]

This is a set of shell scripts and requirements to facilitate running Minion
on Linux.

## Requirements

- zsh
- Oracle JDK/JRE 8 under `/opt/oracle-jdk-8`

Unfortunately, it is very difficult to run Minion on OpenJDK due to JavaFX (OpenJFX)
not being bundled with Java anymore. Any solution to overcome this limitation robustly
will be highly appreciated.

## Installation

0. Ensure you meet the requirements.
1. Clone this repository anywhere.
2. Run `./install` to download and extract Minion.
3. Run `./bin/minion` to launch the app.

You can add `./bin/` to your PATH to be able to run Minion anytime from your terminal.

Sometimes the app prompts you to update and restart, then exits while failing to
finish the update. Simply run `./fix-update` to fix this.

