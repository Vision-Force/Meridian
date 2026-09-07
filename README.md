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

---

## What this is

Rocket Racing was removed from Fortnite. **Rocket Racing Reborn** keeps it playable, and Meridian is the
program that sets it up: it points the game at our servers instead of Epic's, starts it, and puts everything
back the way it was when you close it.

This repository holds **no source code**. It exists so the installer has a permanent, public home that the
launcher's own updater can reach. Releases are on the [releases page](https://github.com/Vision-Force/Meridian/releases).

## Getting in

Meridian **signs you in, it never signs you up**, and it will not let you past the first screen without a key.

1. Make a Vision Force account at [visionforceofficial.com/rrr/login](https://visionforceofficial.com/rrr/login)
2. Ask to play at [visionforceofficial.com/rrr/rocketracingreborn](https://visionforceofficial.com/rrr/rocketracingreborn)
3. A person reads every request, so it is not instant. We email you either way
4. Once approved, generate your key on that same page and paste it into Meridian

**It does not download the game.** You need the build already. That part is being worked on and this page
will say so plainly when it changes, rather than quietly implying otherwise.

## Before you install, read this part

Meridian has to change some things on your computer while you play, because the game was built to talk to
Epic's servers and the only way to point it at ours is locally. All of it is undone when you close the
launcher, with two exceptions named below.

- **Windows asks your permission twice per session.** Once to redirect about 119 Epic hostnames to your own
  machine, once to put them back. That work is done by a separate small program, so the launcher itself
  never runs with those rights.
- **A certificate is created and trusted**, in your user account's store rather than the computer's. It is
  restricted to five Epic domains and cannot vouch for any other site, or for any IP address at all.
- **Anti-cheat is switched off**, and our code runs inside the game. That is what makes this work, and it is
  also why your antivirus may object: loading code into a running program is exactly the behaviour it is
  built to notice.
- **Epic's launcher and Fortnite are closed** when you press Launch and again when Meridian exits. Anything
  unsaved in those is lost.

Two things survive a clean close: a copy of your original hosts file, left beside the real one as
`hosts.rrr-backup`, and, if Meridian was killed rather than closed, the certificate, until the next time you
run and close it normally.

The full detail is in [the terms](https://visionforceofficial.com/legal), sections 12 to 14. They are written
to be read rather than agreed to.

## Updates

Meridian checks for a new version on start and installs it after verifying a signature against a public key
compiled into the launcher. An update that is not signed by us is refused before anything is run, which is
what makes an unauthenticated update feed safe.

## Not open source

The source is private and stays private. This repository is a distribution point, not a mirror.

**All rights reserved.** See [LICENSE](LICENSE). In short: you may download Meridian and run it to play
Rocket Racing Reborn for as long as you have access, and that is the whole of the permission. You may not
redistribute it, modify it, or work around the sign-in.

Rocket Racing Reborn is a fan preservation project. Vision Force Studio is **not affiliated with, endorsed
by, or sponsored by Epic Games, Inc. or Psyonix LLC**. "Rocket Racing", "Fortnite" and "Unreal Engine" and
all related names, logos and assets belong to Epic Games, Inc. or their respective owners. We do not
distribute Epic's game files.

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
