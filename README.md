# Robocop-ng

An attempt to rewrite the bloated ReSwitched bot with dpy rewrite.

Based on https://gitlab.com/ao/dpybotbase


---

## TODO

ALL FEATURES OF KURISU/ROBOCOP USED IN RESWITCHED ARE NOW SUPPORTED!

- [x] .py configs
- [x] membercount command
- [x] Meme commands and pegaswitch (honestly the easiest part)
- [x] source command
- [x] robocop command
- [x] Verification: Actual verification system
- [x] Verification: Reset command
- [x] Logging: joins
- [x] Logging: leaves
- [x] Logging: role changes
- [x] Logging: bans
- [x] Logging: kicks
- [x] Moderation: ban
- [x] Moderation: silentban
- [x] Moderation: kick
- [x] Moderation: userinfo
- [x] Moderation: approve-revoke (community)
- [x] Moderation: addhacker-removehacker (hacker)
- [x] Moderation: probate-unprobate (participant)
- [x] Moderation: lock-softlock-unlock (channel lockdown)
- [x] Moderation: mute-unmute
- [x] Moderation: playing
- [x] Moderation: botnickname
- [x] Moderation: nickname
- [x] Moderation: clear/purge
- [x] Moderation: restrictions (people who leave with muted role will get muted role on join)
- [x] Warns: warn
- [x] Warns: listwarns-listwarnsid
- [x] Warns: clearwarns-clearwarnsid
- [x] Warns: delwarnid-delwarn
- [x] .serr and .err (thanks tomger!)

---

Main goal of this project is to get Robocop functionality done, secondary goal is adding new features. The following entries are secondary, less "urgent" goals:

- [ ] New verification feature: Using log module from akbbot for logging attempts and removing old attempts
- [ ] New moderation feature: mutetime (mute with time)
- [ ] New feature: Highlights (problematic words automatically get highlighted)
- [ ] New feature: Modmail
- [ ] New feature: Submiterr
- [ ] New moderation feature: Display of mutes on listwarns
- [ ] New moderation feature: User notes
- [ ] New moderation feature: watch-unwatch (using log module from akbbot)
- [ ] New moderation feature: timelock (channel lockdown with time)
- [x] Remove sh, remove risky stuff from eval
