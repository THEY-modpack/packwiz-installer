# packwiz-installer
An installer for launching packwiz modpacks with MultiMC. You'll need [the bootstrapper](https://github.com/THEY-modpack/packwiz-installer-bootstrap) to actually use this.

## What's New?

- **Java 17**

  Java 17 is now required. This means Minecraft 1.18 and newer are supported, as well as forks running on Java 17–25.

  For example, Cleanroom and Outlands for Minecraft 1.12.2:
  [Cleanroom](https://github.com/CleanroomMC/Cleanroom) / [Outlands](https://github.com/Project-Outlands/Outlands)

- **`.disabled` Support**

  Mods disabled through the launcher will no longer be lost during updates.

  For example, if the modpack contains `zume-1.2.2.jar.disabled`, while the index specifies `zume-1.2.3.jar`, Packwiz will recognize them as the same mod. The update will be skipped, the old file will remain disabled, and a warning about the available update will be displayed in the log.

- **W.I.P. — First-Run Menu**

  A menu explaining the new `--low-ram` and `--low-gpu` options.

  These flags will be enabled by default, and players will be able to confirm or change which flags they want to use.
