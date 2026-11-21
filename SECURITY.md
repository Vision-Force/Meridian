# Reporting a security problem

**Email [contact@visionforceofficial.com](mailto:contact@visionforceofficial.com).** Please do not open a public issue for anything that could be used against a player before we have had a chance to fix it.

We will confirm we have it, tell you what we think, and tell you when it is fixed. We are a small volunteer team, so we cannot promise a timeline, only that a person at least reads it.

## What should be reported

Meridian is unusual, so it is worth being specific about which parts we consider a real problem:

- **The certificate.** It is created locally and trusted in the user's own store, restricted by name
  constraints to 5 Epic domains and excluded from every IP address. If you can make it vouch for anything outside that, that is a serious bug and we would like to know that

- **The local proxy.** It listens on 127.0.0.1 only. If it can be reached from another machine, or made to forward somewhere it should not, that is a bug

- **The hosts file.** It should be restored on close, and on the next system reboot if the launcher was killed.
- **Access control.** Keys, sign in, or anything that lets one player act as another.

## What is not a bug

- Windows antivirus may complain which is expected.
- The hosts file is modified while you play, and Windows asks for permission to do it.

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Vision-Force/.github/main/profile/assets/divider.svg" width="100%" alt="">
  <br>
  <sub>Vision Force Studio &middot; <a href="https://visionforceofficial.com">visionforceofficial.com</a></sub>
</div>
