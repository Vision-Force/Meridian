<div align="center">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/logo.svg" width="128" alt="Meridian">

  <h1>Meridian</h1>

  <p><strong>The launcher for Project Rocket Racing Overdrive</strong><br>
  A Vision Force Studio preservation project</p>

  <p>
    <a href="https://github.com/Vision-Force/Meridian/releases/latest"><img src="https://img.shields.io/github/v/release/Vision-Force/Meridian?style=flat-square&label=latest&color=e9bd74&labelColor=16130f" alt="Latest release"></a>
    <img src="https://img.shields.io/badge/platform-Windows-e9bd74?style=flat-square&labelColor=16130f" alt="Windows only">
    <a href="https://visionforceofficial.com/rrr/overdrive"><img src="https://img.shields.io/badge/access-invite%20only-e9bd74?style=flat-square&labelColor=16130f" alt="Invite only"></a>
  </p>

  <a href="https://github.com/Vision-Force/Meridian/releases/latest"><img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/btn-download.svg" width="30%" alt="Download the latest release"></a>
  <a href="https://visionforceofficial.com"><img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/btn-website.svg" width="30%" alt="Website: visionforceofficial.com"></a>
  <a href="https://discord.com/invite/Kn3yY2vYGY"><img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/btn-discord.svg" width="30%" alt="Discord"></a>
</div>

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
</div>

<a id="what-this-is" name="what-this-is"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-what-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-what-light.svg" width="100%" alt="What this is">
</picture>

Rocket Racing was removed from Fortnite. [**Project Overdrive**](https://visionforceofficial.com/documentation/project-overdrive) keeps it playable, and Meridian is the
program that sets it up. Means it points the game at our servers instead of the ones that got sunset, then starts it, and configures everything by itself so you can play Overdrive the way you know Rocket Racing

This repository holds **NO** *source code*. This only exists so the installer has a temporar, public place that the launcher's own auto updater can reach. Releases are on the [releases page](https://github.com/Vision-Force/Meridian/releases).

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
</div>

<a id="how-to-play" name="how-to-play"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-play-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-play-light.svg" width="100%" alt="How to play">
</picture>

Meridian **signs you in, it never signs you up**, and it wont let you do anything in it before you enter your Vision Force key.

- VISION FORCE KEY
1. Make a [Vision Force account](https://visionforceofficial.com/rrr/login)
2. Request permission [here](https://visionforceofficial.com/rrr/overdrive) to play [Project Overdrive](https://visionforceofficial.com/documentation/project-overdrive)
3. Someone eventually will read your request, so it is not instant. We email you either way if you get perms or not so you dont feel ignored
4. Once you are approved, generate your key on the same [page](https://visionforceofficial.com/rrr/overdrive) you requested access to [Project Overdrive](https://visionforceofficial.com/documentation/project-overdrive)

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
</div>

<a id="read-this-before-you-install" name="read-this-before-you-install"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-install-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-install-light.svg" width="100%" alt="Read this before you install">
</picture>

Meridian has to change some things on your machine while you play, because the game was built to talk to
Epic's servers and the only way to point it at ours is locally. All of it is undone when you close the
launcher, with two exceptions named below.

- **Windows asks your permission twice per session.** Once to redirect about 119 Epic hostnames to your own
  machine, once to put them back. That work is done by a separate small program, so the launcher itself
  never runs with those rights.
- **A certificate is created and trusted**, in your user account's store. It is
  restricted to 5 Epic domains and cannot vouch for any other site, or for any IP address at all.
- **NMake sure that you dont have any Epic services open while/before launching Meridian.** when you press Launch and again when Meridian exits. Anything unsaved in those will be lost

However if Meridian was killed rather than closed correctly, the certificate gets discarded the next time you open Meridian and close it normally. So please close the launcher correctly, otherwise you wont be able to use any Epics services afterwards and will have to delete the certificate manually. See [how to delete the certificate manually in](https://meridian.visionforceofficial.com/#faq)

All other details can be found in [our terms](https://visionforceofficial.com/legal)

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
</div>

<a id="updates" name="updates"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-updates-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-updates-light.svg" width="100%" alt="Updates">
</picture>

Meridian checks for its new version on its start

**All rights reserved.** See [LICENSE](LICENSE). In short: you may download Meridian and run it to play
Project Overdrive for as long as you have access to our services. You may NOT redistribute it, modify it, or work around the signin and use it as advantage

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
</div>

<a id="important" name="important"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-important-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-important-light.svg" width="100%" alt="Important">
</picture>
Project Overdrive is a fan made preservation project. Vision Force Studio is **not affiliated with, endorsed
by, or sponsored by Epic Games, Inc. or Psyonix LLC**. "Rocket Racing", "Fortnite" and "Unreal Engine" and
all related names, logos and assets belong to Epic Games, Inc. or their respective owners.

<a id="something-wrong" name="something-wrong"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-help-dark.svg">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/section-help-light.svg" width="100%" alt="Something wrong">
</picture>

Security issues: see [SECURITY.md](SECURITY.md).

Anything else: [contact@visionforceofficial.com](mailto:contact@visionforceofficial.com), or the
[Discord](https://discord.com/invite/Kn3yY2vYGY).

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/repository/Meridian/assets/divider.svg" width="100%" alt="">
  <br>
  <sub>Vision Force Studio &middot; <a href="https://visionforceofficial.com">visionforceofficial.com</a></sub>
  <sub>Meridian &middot; <a href="https://github.com/Vision-Force/Meridian/releases/tag/v2.0.1">v2.0.1</a></sub>
</div>
 
