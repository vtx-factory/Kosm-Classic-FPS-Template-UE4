# Kosm: Classic FPS Pack For Unreal Engine 4
> Classic Arena First Person Shooter Mechanics for Unreal Engine.<br><br>A powerful tool with fully customizable Blueprints to tune your project up - this Pack includes 2 Character Blueprints defined as VQ3 (imagine Visor from Quake) and CPMA (Full Air Control Support), an AI Bot and Ragdoll, 3 Projectiles (Rocket Launcher, Railgun and Nailgun), 2 Maps for you to make all your testing, plus an Health/Armor System and much more, all replicated for online gameplay.<br><br>
This Pack is composed by a <strong>.uproject file</strong> which you can freely customize using Unreal Engine 4.<br><br>

**Showcase Teaser:** <a href="#">Soon</a><br>
**Current Development Build:** v1.2.0<br>
**Supported Operating System:** Windows 32/64-bit, Linux and Oculus-Rift ready<br>
**Unreal Engine Compatibility Version:** v4.23.0<br><br>
<img src="https://kosm.vtxfactory.org/imgs/banner_git1.jpg" /><br><br>
- <a href="#kosm-demo">Kosm-DEMO</a><br>
<a href="#demo-download">Download</a><br>
- <a href="#kosm-pack">Kosm-PACK</a><br>
<a href="#pack-includes">Includes</a><br>
<a href="#pack-patch_notes">Patch Notes</a><br>
<a href="#pack-known_issues">Known Issues</a><br>
<a href="#pack-installation">Installation</a><br>
<a href="#pack-buy">Buy</a><br>
- <a href="#unreal-engine-4-qol-improvements">Unreal Engine 4 QoL improvements</a><br>
- <a href="#contributing">Contributing</a><br>
- <a href="#contact">Contact</a><br>
- <a href="#licensing">Licensing</a><br><br><br>
# Kosm-DEMO
You can test our PACK functionalities with our DEMO showcase below, on Testing_Grounds Map.
## DEMO download:
Check our <a href="https://github.com/vtx-factory/Kosm-Classic-FPS-Pack-UE4/releases">Releases</a> section to download the binaries for your platform.<br><br><br>
# Kosm-PACK
<img src="https://kosm.vtxfactory.org/imgs/includes_1.jpg" />

## PACK includes:
**&#9632; 2 CHARACTERS** with distinct movement:
- **VQ3 movement Character** <a href="https://kosm.vtxfactory.org/vid/vq3-mov.mp4">(preview)</a><br>Longer the Bunny-hop, faster the travel.<br>
- **CPMA movement Character** <a href="https://kosm.vtxfactory.org/vid/cpma-mov.mp4">(preview)</a><br>Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse.

**&#9632; 3 PROJECTILES:** 
- **Rocket Launcher, Nailgun and Railgun Projectiles** <a href="https://kosm.vtxfactory.org/vid/projectiles.mp4">(preview)</a><br>

**&#9632; AI BOT** with Perception System <a href="https://kosm.vtxfactory.org/vid/AI_bot.mp4">(preview)</a>

**&#9632; HEALTH/ARMOR** Pickups & System <a href="https://kosm.vtxfactory.org/vid/healthsysandpickups.mp4">(preview)</a><br>

**&#9632; 2 MAPS:**
- **Fortress Map** <a href="https://kosm.vtxfactory.org/vid/.mp4">(preview)</a><br>
- **Testing Grounds Map** <a href="https://kosm.vtxfactory.org/vid/.mp4">(preview)</a>

**&#9632; OTHER INCLUDES:**
- **Custom Crosshairs and Speedometer**
- **Footsteps, Misc Sounds and Attenuation Settings**
- **Player's HUD** 
- **Radial/Splash Damage** 
- **Damage Indicators** 
- **Toggle Crouch** 
- **Bunny-hop** 
- **Weapon Zoom**
- **Double Jump** 
- **Dash** 
- **Walk**<br><br>

## PACK patch_notes:
Below you can find all changes and tweaks made from previous to current version of the project:
<details>
  <summary>v1.2.0 <strong><i>- #28-09-2019</strong></i></summary>
  
- Increased Terminal Z Velocity.
- Corrected "Physics and Collisions" for Player Controlled Characters.
- Added Lifespan to Projectiles so they won't propagate infinitely.
- Added level restart on KillZ trigger.
- Added Auto-Respawn to Player Characters.
- Further tuned VQ3 Character movement.
- Enabled Raw Input Support.
- Added Damage Indicators.
- Added Sound Attenuation over distance.
- Added Radial/Splash Damage.
- Added AI with Sight and Hear Perception.
- Added Footsteps Audio.
- Added Health/Armor System.
- Added Health and Armor Pickups.
- Added Nailgun and Railgun Projectiles.
- Added Individual HUDs for each Character.
</details>
<details>
  <summary>v1.1.0 <strong><i>- #25-08-2019</strong></i></summary>
  
- Optimized Mouse Acceleration detection for the VQ3 character to work better. (further updates will be coming on next patch)<br>
- Revamped Rocket Launcher Projectile animations and particles.<br>
- Aligned Projectile with Crosshair.<br>
- Fixed a SpawnedDecal error.<br>
- Upgraded Project compatibility to support Unreal Engine v4.23.0 Preview 6.<br>
- Added an extra ragdoll for you to test collision and physics.<br>
- Each character has its own HUD and individual speedometer, which now displays and works correctly when switching Characters.<br>
- Removed jump cooldown node so CPMA character won't stay glued to the ground when jumping on the edge of a slope or when the space between stairs is too narrow.<br>
- Increased map Bound Scale limits to remove artifacts from viewport.<br>
- Checked Use Flat Base for Floor to avoid the situation where characters slowly lower off the side of a ledge. (as their capsule "balances" on the edge)<br>
- Increased trimp multiplier on slopes.<br>
- Added Character and Weapon Switch capability.<br>
- Increased step height so character can step up stairs.<br>
</details>
<details>
  <summary>v1.0.0 <strong><i>- #05-08-2019</strong></i> </summary>
  
- First build deployed.<br>
</details>

## PACK known_issues:

- [ ] AI Bot is still Experimental, but will be upgraded overtime.
- [ ] Correct Third-Person AI and Player Animations to be added (e.g. when Crouching, Shooting, Strafing, Walking, etc).
- [ ] On Weapon Zoom, Crosshair slightly misaligned with fired Projectile.
- [ ] All Characters' Tap-Jump Acceleration will work as if it was Bunny-hop.
- [ ] VQ3 Acceleration Gain Detection will be upgraded.
- [ ] Theres a delay on the next fired Projectile when firing any weapon and immediately switching to another at the same time.
- [x] ~~Physics Collisions to be added to VQ3 and CPMA Characters as they are on Ragdoll and Noobot_AI.~~
- [x] ~~When pogo jumping with VQ3 Character, sometimes you'll hear two jump Audio Cues at the same time.~~

## PACK installation:
Kosm-PACK is composed of a <strong>.uproject file</strong> that you can open on-the-fly using Unreal Engine. A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
## PACK buy:
- <a href="#">Unreal Engine Marketplace</a> (soon)
- <a href="#">Clickbank Store</a> (soon)<br><br><br>
# Unreal Engine 4 QoL improvements:<br>
Here's some tips to improve your experience using Unreal Engine:<br><br>
**&#9632; Show Frame Rate and Memory in Editor**<br>Go into <strong>Edit > Editor Preferences</strong> and type "Show Frame Rate and Memory" in <strong>Search Details</strong>, then check it.<br><br>
**&#9632; t.MaxFPS 300**<br>When playing the active level in editor viewport, it caps your fps to 60. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly open command prompt.)<br><br>
**&#9632; r.VSync 0**<br>With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br><br>
**&#9632; Uncheck FOV Scaling**<br>Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Uncheck Mouse Smoothness**<br>Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Change Mouse Sensitivity**<br>Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br><br>
**&#9632; Enable Blutilities**<br>Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser > Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
# Contributing
If you'd like to contribute to this project in any way, please feel free to pull a request or contact us directly.<br><br>Feel free to contact support if you have any suggestions or run into any trouble editing the blueprints.<br><br><br>
# Contact
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>General Info & Feedback</strong><br>info@vtxfactory.org<br><br>
<strong>Support</strong><br>support@vtxfactory.org<br><br><br>
# Licensing
This project supports the GNU v3.0 license.
