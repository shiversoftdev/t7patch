# Black Ops 3 Community Patch
A new and improved community patch for a large list of Black Ops III exploits. 

**After reading the FAQ**, please report any issues with the tool not working or new crashes to @anthonything on discord.

You can contact me by joining [my server](https://discord.gg/gsc). Please be aware that this is not a support server, so please direct questions to my DMs, not the general chat of the server. Sending messages about support for the patch in general chat may result in a ban.

Please do not try to use any public cheats with this patch. Almost all of them are incompatible.
# Instructions

1. Download [the patch](https://github.com/shiversoftdev/t7patch/releases/tag/Current).
2. Watch the [video tutorial](https://youtu.be/jDQkNV5J4SM?t=394). Read the FAQ for additional info before asking questions.
3. If not playing in matchmaking, set a network password to enable the best protection. Note that anyone who wants to play with you needs to have the same network password. If you want to play in normal matchmaking again, clear the network password.

# Known Incompatibilities
1. Overwolf OBS plugin causes fatal crash in BO3 when patch is loading.

# Frequently Asked Questions

### Q: Does this patch fix the FPS issue?
A: Yes
### Q: Do I need to run the patch if I am playing solo offline?
A: Simple answer, no. Technical answer, maybe. If you are high profile, run it regardless because steam networking is complicated.
### Q: Does this fix the RCE vulnerabilities you mentioned in your video?
A: Yes. This fixes 4 of the known RCE vulnerabilities. Additionally, the BO3 update recently patched RCE.
### Q: Do I need a VPN?
A: If you are high profile or a streamer, yes. Otherwise, not likely. If you are getting hit offline (internet) often, run a VPN.
### Q: Do I need an alternate steam profile? My stats don't transfer over!
A: Steam alts are only recommended for high profile players or streamers. If you are not being attacked, you don't need an alt.
Your stats will not transfer to your new account, and if you wish to retain stats you may need to resort to third party tools.
### Q: Does this patch work on Steam deck? Mac OS? Linux?
A: No. This patch is only designed to work on PC (Windows computers). I do not have plans to support other platforms at this time.
### Q: Can you make this patch compatible with other mod menus, cheats, or third party tools?
A: No. The patch uses a lot of complicated techniques to patch the game that interfere with most third party tools. This is due to the fact that Black Ops III is heavily resistant to patching by non-official sources. Additionally, I consider it a bonus that cheaters must choose to play unprotected to the griefing mechanisms that they have used against the community for so long.
### Q: Does the patch work with custom maps?
A: Yes.
### Q: Will you ever post source code?
A: No. The patch is the same project as ZBR which means I cannot release the source without also releasing the ZBR source, which will not happen.
### Q: Why does my anti-virus say this is malware?
A: The code is protected against reverse engineering. This protection unintentionally prevents anti-virus scans from identifying whether the tool is safe or not. Modern anti-virus will, by default, label anything that it cannot scan completely as malware to protect users.
### Q: What is the LPC file for?
A: The LPC file is to fix the A.B.C error on sign in. Not necessary for most users.
### Q: Who should I send crash reports to?
A: serious#9999 on discord. You must be in my server and allow dms from server members to message me. I will not accept friend requests.
### Q: Is this tool still updated?
A: Yes.
### Q: Are the security concerns still valid?
A: Partially. The RCE vulnerabilities are no longer a concern, but the patch fixes many remote crashes which can be used to grief people.
### Q: Is there a ban risk when using this tool?
A: No.
### Q: Will this affect other games? Can another anticheat ban me for using this on BO3?
A: No.
### Q: What is the network password for?
A: [Please watch this video.](https://www.youtube.com/watch?v=ykoH31p61_E)
### Q: Will this work for Linux? Will this work for Windows 7?
A: The patch only supports Windows 10 and Windows 11 for now. I tried to add support to proton, but it is not currently working.
### Q: Error at hooking API "LoadStringA"
A: [Install the visual c++ redistributables](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
### Q: I was in a public game and still got crashed!
A: You can report your crashes.log to me, but as I have explained in the [video tutorial](https://youtu.be/jDQkNV5J4SM?t=394), multiplayer matchmade lobbies are going to continue to have crashing issues (among others such as aimbot, godmode cheaters, etc), and I do not plan to continue playing cat and mouse with the cheating community. They may not have a life, but I do. 


# Credits
Serious - Creator of the patch
# Special Thanks
SyGnUs - Exception handler help\
momo5502 - Report of critical RCE method and how it works\
ItsFebiven, Kai, ssno - Testing\
Kenshin9977, Obey, Dawson - Crash Reports\
Snowy. - Crash Report for CL_HandleRelayPacket\
Lerggy, Vortex - Additional information\
Mikey0006 - UI Error report\
Aqua - Name spoofing bug report and friends only bug report\
IceGrenade - Reported Server Browser IP Leaking\
FragsAreUs - Proton and Win7 ntdll binaries
