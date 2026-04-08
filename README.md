# JYL: An After Story Launcher (Unofficial Android Port)

<!-- [![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]() -->
[![Platform](https://img.shields.io/badge/platform-Android-blue.svg)]()

> **STRICT LEGAL DISCLAIMER & IMPORTANT NOTICE**
> 
> **1. UNOFFICIAL PROJECT:** This is a strictly unofficial, fan-made Android wrapper/launcher. It is not affiliated with, endorsed by, or associated with Team Salvato or the official Just Yuri development team. 
>
> **2. SCOPE:** This repository solely contains the Android project structure, the Ren'Py engine wrapper, and custom tools designed to facilitate the execution of legally obtained mod files on Android devices.

## Overview

JYL (An After Story Launcher) is a custom-engineered Android port designed to run the Just Yuri mod seamlessly on mobile environments. Rather than distributing copyrighted material, this project provides a robust, optimized launcher based on a customized fork of Ren'Py's RAPT (Ren'Py Android Packaging Tool).

## Technical Architecture

This project is built upon a modified RAPT environment to ensure compatibility and stability on modern Android architectures.

### The `unrpa` Kotlin Implementation

To handle Ren'Py Archive (`.rpa`) extraction natively within the Android environment, we have developed a custom `unrpa` utility written in Kotlin. This implementation is designed for performance and seamless integration with the Android file system.

* **Logic Attribution:** The core structural logic for the `unrpa` utility is heavily based on the original Python implementation by Lattyware. 
* **Reference:** [Lattyware/unrpa](https://github.com/Lattyware/unrpa)

## Acknowledgments & Credits

* **[Team Salvato](https://teamsalvato.com/):** For creating the incredible *Doki Doki Literature Club!*
* **[Just Yuri Team](https://discordapp.com/invite/RUdwW7q):** For the original mod and their continuous hard work.
* **[Ren'Py](https://www.renpy.org/):** For the visual novel engine and the RAPT framework.
* **Lattyware:** For the foundational `unrpa` logic.

### Notes

This project is a direct fork of our original MASL app.\
You can view the original repo [here](https://github.com/New-Traduction-Club/MonikaAfterStory-Android-port).

---
*Developed and maintained by Traduction Club!*
