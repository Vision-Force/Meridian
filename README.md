<div align="center">
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/mark.svg" width="96" alt="Vision Force">

  <h1>Meridian</h1>

  <p><strong>The launcher for Rocket Racing Reborn.</strong><br>
  A Vision Force Studio preservation project.</p>

  <p>
    <a href="https://github.com/Vision-Force/Meridian/releases/latest"><img src="https://img.shields.io/github/v/release/Vision-Force/Meridian?style=flat-square&label=latest&color=47d1ff" alt="Latest release"></a>
    <img src="https://img.shields.io/badge/platform-Windows-303034?style=flat-square" alt="Windows only">
    <a href="https://visionforceofficial.com/rrr/rocketracingreborn"><img src="https://img.shields.io/badge/access-invite%20only-a855f7?style=flat-square" alt="Invite only"></a>
  </p>
</div>

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
</div>

## What this is

Rocket Racing was removed from Fortnite. [**Rocket Racing Reborn**](https://visionforceofficial.com/documentation/rocket-racing-reborn) keeps it playable, and Meridian is the
program that sets it up. Means it points the game at our servers instead of the ones that got sunseted, then starts it, and puts everything back the way you know Rocket Racing

This repository holds **NO source code**. This only exists so the installer has a permanent, public place that the
launcher's own auto updater can reach. Releases are on the [releases page](https://github.com/Vision-Force/Meridian/releases).

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
</div>

## How to play

Meridian **signs you in, it never signs you up**, and it wont let you do any action before you enter your Vision Force token.

- VISION FORCE TOKEN
1. Make a [Vision Force account](https://visionforceofficial.com/rrr/login)
2. Request permission [here](https://visionforceofficial.com/rrr/rocketracingreborn) to play [RRR](https://visionforceofficial.com/documentation/rocket-racing-reborn)
3. Someone eventually will read your request, so it is not instant. We email you either way if you get perms or not so you dont feel ignored
4. Once you are approved, generate your key on the same [page](https://visionforceofficial.com/rrr/rocketracingreborn) you requested access to [RRR](https://visionforceofficial.com/documentation/rocket-racing-reborn)

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
</div>

## Read this before you install

Meridian has to change some things on your machine while you play, because the game was built to talk to
Epic's servers and the only way to point it at ours is locally. All of it is undone when you close the
launcher, with two exceptions named below.

- **Windows asks your permission twice per session.** Once to redirect about 119 Epic hostnames to your own
  machine, once to put them back. That work is done by a separate small program, so the launcher itself
  never runs with those rights.
- **A certificate is created and trusted**, in your user account's store rather than the computer's. It is
  restricted to five Epic domains and cannot vouch for any other site, or for any IP address at all.
- **EMake sure that you dont have any Epic services open while before launching Meridian.** when you press Launch and again when Meridian exits. Anything unsaved in those is lost

However if Meridian was killed rather than closed correctly, the certificate gets discarded the next time you open Meridian and close it normally. So please close the launcher correctly, otherwise you wont be able to use Epics services.

The full detail is in [our terms](https://visionforceofficial.com/legal), sections 12 to 14. They are written
to be read rather than agreed to

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
</div>

## Updates

Meridian checks for its new version on start and installs it after verifying a signature against a public key
compiled into the launcher. An update that is not signed by us is refused, which is basically what makes an unauthenticated update feed safe

**All rights reserved.** See [LICENSE](LICENSE). In short: you may download Meridian and run it to play
Rocket Racing Reborn for as long as you have access to our services. You may NOT redistribute it, modify it, or work around the signin

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
</div>

## Important
Rocket Racing Reborn is a fan made preservation project. Vision Force Studio is **not affiliated with, endorsed
by, or sponsored by Epic Games, Inc. or Psyonix LLC**. "Rocket Racing", "Fortnite" and "Unreal Engine" and
all related names, logos and assets belong to Epic Games, Inc. or their respective owners. We do NOT distribute, own or sell Epic's game files

## Something wrong?

Security issues: see [SECURITY.md](SECURITY.md).

Anything else: [contact@visionforceofficial.com](mailto:contact@visionforceofficial.com), or the
[Discord](https://discord.com/invite/Kn3yY2vYGY).

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
  <sub>Vision Force Studio &middot; <a href="https://visionforceofficial.com">visionforceofficial.com</a></sub>
</div>
