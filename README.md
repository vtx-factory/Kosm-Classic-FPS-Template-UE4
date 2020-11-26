# Kosm: Classic FPS Pack For Unreal Engine 4
> Classic Arena First-Person-Shooter Mechanics.<br><br>Project with fully customizable Blueprints to tune your project up - this Pack includes 2 Character Blueprints defined as VQ3 (imagine Visor from Quake) and CPMA (Full Air Control Support), an AI Bot and Ragdoll, 6 Projectiles (Rocket Launcher, Nailgun, Lightning Gun, Shutgun, Portal Gun and Railgun), 2 Maps for you to make all your testing, plus an Health/Armor System and much more, all replicated for online gameplay.<br><br>
This Pack is composed by a <strong>.uproject file</strong> which you can freely customize using Unreal Engine 4.<br><br>

<img src="https://kosm.vtxfactory.org/imgs/loading.gif" />

**Current Published Build:** v0.6 <a href="#patch-notes">(view Changelog)</a><br>
**Unreal Engine Compatibility Version:** v4.25<br>
**Network Replicated:** Yes. <i>(WIP)</i><br>
**Platform Compatibility:** PC, PS4, Xbox and VR (Oculus, Steam, Valve Index, Vive).<br>
**Input Compatibility:** Keyboard/Mouse, Gamepad Controller and VR Set Compatible.<br>
**Supported Operating System:** Windows 32/64-bit, Linux and Oculus-Rift ready.<br>
- <a href="https://www.youtube.com/watch?v=fKr9Qey_Jk8">Watch Teaser</a><br>
- <a href="#download-demo">Download Demo</a><br>
- <a href="https://vtxfactory.org/dl/Kosm_Documentation.zip">Manual Guide and Documentation</a><br><br>
<br><img src="https://vtxfactory.org/imgs/kosm2.png" /><br><br><br>
- <a href="#kosm-classic-fps-pack">Kosm: Classic FPS Pack</a><br>
<a href="#patch-notes">Patch Notes</a><br>
<a href="#bug-tracker">Bug Tracker</a><br>
<a href="#installation">Installation</a><br>
<a href="#buy">Buy</a><br>
- <a href="#unreal-engine-4-qol-improvements">Unreal Engine 4 QoL Improvements</a><br>
- <a href="#contributing">Contributing</a><br>
- <a href="#contact">Contact</a><br>
- <a href="#licensing">Licensing</a><br><br><br>
# Download Demo
Check <a href="https://github.com/vtx-factory/Kosm-Classic-FPS-Pack-UE4/releases">Releases</a> section to download the binaries for your platform.<br><br><br>
# Kosm: Classic FPS Pack

**&#9632; 2 CHARACTERS** with distinct movement:
- **VQ3 Strafe-Jumping movement Character** <br>Longer the Bunny-hop, faster the travel.<br>
- **CPMA Air Control movement Character** <br>Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse.

**&#9632; 8 PROJECTILES:** 
- **Rocket Launcher Projectile**<br>
- **Nailgun Projectile**<br>
- **Railgun Projectile**<br>
- **Lightning Gun Projectile** <i>(WIP)</i><br>
- **Shotgun Projectile**<br>
- **Portal Gun Projectile** <i>(WIP)</i><br>
- **Machinegun Projectile**<br>
- **Grenade Launcher Projectile**<br>

**&#9632; AI BOT** with Hearing/Sight Perception System

**&#9632; HEALTH/ARMOR/AMMO** Pickup System <br>

**&#9632; 2 MAPS:**
- **Fortress FFA/TDM Map** <i>(based on dm20)</i> <br>
- **Testing Grounds Map**

**&#9632; OTHER FEATURES:**
- **Footsteps, Misc Sounds and Attenuation Settings**
- **Custom Crosshairs and Speedometer**
- **Respawn System**
- **Camera Toggle**
- **Cycle Center/Right Weapons**
- **Player HUD** 
- **Visual Damage & Blood Splashes**
- **OnDamage Audio Indicator** 
- **Radial/Splash Damage** 
- **Damage Indicator**
- **Healthbar** 
- **JumpPad**
- **Bunny-hop**
- **Crouch/Crouch Slide**
- **Weapon Zoom**
- **Double Jump** 
- **Dash** 
- **Walk**<br>

## Patch Notes:
Below you'll find all changes and tweaks made from previous to current version of the project:
<details>
<summary><strong>(In Development...)</strong> v0.7 <strong><i>- ETA: December, 2020</i></strong> </summary>
  
- Added Melee Weapon.<br>
- Added Main Menu.<br>
- Added Options Menu.<br>
- Added Spectator Mode.<br>
- Added Grapple Hook.<br>
- Added Keyboard Arrow Navigation on Menus.<br>
- Added Killfeed.<br>
- Added Kill log.
- Simplified Crouch and Crouch Slide Mechanics.<br>
- Damage Indicators are now relative to World Space instead of Player Screen.<br>
- Added Scoreboard Widget - for now it will only show the names of Actors spawned in level.<br>
- Save/Load Game System to keep variables value between Editor/Packaged sessions.<br>
</details>
<details>
  <summary>v0.6 <strong><i>- Release#15.07.2020</i></strong> </summary>
  
- Added Grenade Launcher Projectile.<br>
- Added Machine Gun Projectile.<br>
- Rigged 3rdPerson Mesh Animations using Blendspaces.<br>
- Updated Portals In/Out Behavior, Performance and Visuals - e.g. No render delay; PhysicsActor and Projectiles (not all of them) can now pass through Portals.
- Fixed some Replication issues related to Character's movement.
- Upgraded Project Compatibility to UE v4.25.
- 3rdPersonGun now changes material accordingly to selected Weapon.
- PhysicsActor now interact with JumpPad and Portals.
- You can now Step Up on Characters.
- Added Critical Damage when hitting the Head bone of the Opponent Mesh - it will do twice as Damage and the Indicator is displayed in red.
- Updated HealthBars behavior and visuals, now they only appear when crosshair is hovering the specific Actor. Jittery edges and Aliasing have been removed.
- Added Crouch Slide Mechanic.
- Further tuned Tap-Jump detection for both Characters.
- Added the ability to fire projectiles while using 3rdPersonCamera.
- Align Decals and Projectiles with Crosshair based on Hit Info and Line Trace.
- Added Weapon/Ammo Refill System - grab Ammo from the ground to refill your Weapon.
- Noobot now switches between Rocket Launcher and Nailgun Projectiles.
- Added Blood splashes on Event Hit and Visual damage to Skeletal Meshes.
- Added Hit Sound on Opponent Damage - Pitch is modulated by the amount of Damage done.
- Added Wind sound FX when falling over 4000 ZVelocity.
- Added Speed Blendspace to 1stPerson Mesh.
- Added Ground Accel when swinging mouse for greater jump impulse.
- Normalized Transform (Rotation and Scale) across all Characters.
- Added Instanced Static Mesh version of fortress.umap to decrease loading time and boost performance while level is open.
- Improved Accessibility and Readability by adding more important comments, collapsing nodes into functions and reorganized variables by category and type on main BPs.
- Attached Muzzle Sprites and Projectile Spawns to Muzzle Component so it follows weapon when moving.
- Added minimum Zvelocity you need to fall in order to produce on_land noise. This will help in reaching new heights without triggering any perceivable noise event.
- Added Ragdoll State when opponent is killed to Ragdoll_Noobot and Noobot_AI. VQ3 and CPMA still use the on_death animation.
- Added Hotkeys (I and O) for Double Jump Selection Mode - DoubleJump Active, DoubleJump Disabled and Infinite DoubleJump.
- Added Hotkey (L) to Refill Ammo.
- Characters will now pass under obstacles while Crouched.
- Linetrace to check if objects are above character while Crouched.
- Added Animated Meshes of Health and Armor to UI.
- Revamped Character Selection system (Tab key) - now it opens up a menu for you to choose active character.
- Added Switch Weapons sound FX.
- Added Weapon Sway on 1PersonMesh.
</details>
<details>
  <summary>v0.5 <strong><i>- Release#10.03.2020</i></strong> </summary>
  
- Added Network Replication for Online Gameplay.<br>
- Added Shotgun Bullet Sprites to Weapon Muzzle when firing.<br>
- Shotgun pellets are now traced, which increases its Spread.<br>
- Improved VQ3 and CPMA Acceleration detection.<br>
- Fixed various Audio duplicates on Network.<br>
- Fixed Lighting issues on Fortress map.<br>
- Changed maximum XY Velocity to 4000 for VQ3 and 4200 for CPMA.<br>
</details>
<details>
  <summary>v0.4 <strong><i>- Release#27.12.2019</i></strong></summary>
  
- Added Portal Gun Projectiles. (In/Out Flow)
- Added Shotgun Projectile. (Namely "Shutgun")
- Added Lightning Gun Projectile.
- Added JumpPads.
- Further upgraded VQ3 Character jump gained Acceleration.
- Aligned Projectile with Crosshair on Weapon Zoom-In.
- Added variable to reduce Zoom-In Mouse Sensitivity.
- Fixed applied Ground Friction on VQ3 Character Tap-Jump.
- Weapon won't change to the already selected one.
- Dash uses only X/Y Axis, now you won't be able to gain Height while using it.
- Speedometer aligned to center when number of digits increase.
- Fixed previous existing delay on the next fired Projectile when firing any weapon and immediately switching to another one at the same time.
- Added Audio Spatialization to Footsteps, Jump and Double Jump, Projectiles, On Hit Explosions and Landing so you can better perceive where the sound is coming from (behind, below, directional left/right, etc)
- Added 1st/3rd Person Camera Toggle.
- Added Deathcam.
- Player will no longer keep firing Projectiles if killed while shooting.
- Fixed Nailgun Splash Damage, now it won't propagate to characters that are really close to each other.
- Added diagonal Dash movement.
- Added Crouch movement Animation on 3rd Person Camera.
- Added smooth Crouch.
- Upgraded Project Compatibility to UE v4.24.
- Added Deathscream and Fatal Fall Damage.
- Bots no longer freeze when killed while in the air.
- Added Lightning Gun kickback impulse.
- Added Zoomout Animation on Deathcam.
- Added Center/Right Weapon Selection.
</details>
<details>
  <summary>v0.3 <strong><i>- Release#12.10.2019</i></strong></summary>
  
- Increased Terminal Z Velocity.
- Corrected "Physics and Collisions" for Player Controlled Characters.
- Added Lifespan to Projectiles so they won't propagate infinitely.
- Added level restart on KillZ trigger.
- Added Auto-Respawn to Player Characters.
- Further tuned VQ3 Character movement.
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
  <summary>v0.2 <strong><i>- Release#25.08.2019</i></strong></summary>
  
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
  <summary>v0.1 <strong><i>- Release#05.08.2019</i></strong> </summary>
  
- First build deployed.<br>
</details>

## Bug Tracker:

- [ ] <strong>[NETWORK-CLIENT]</strong> Fix Lightning Gun delay issues.
- [ ] <strong>[NETWORK-CLIENT]</strong> Crouch Slide mechanic isn't replicating.
- [ ] <strong>[NETWORK-CLIENT]</strong> Projectiles appear to have different location offsets when spawned from client to server.
- [ ] <strong>[STANDALONE-GENERAL]</strong> Borderless Window Mode is not setting the chosen resolution in-game - instead, it's reading the current desktop's resolution.
- [ ] <strong>[STANDALONE-GENERAL]</strong> While firing, you may be able to spawn 2 projectiles almost at the same time if switching weapons too fast. 
- [ ] <strong>[STANDALONE-PORTALS]</strong> Projectiles that pass through Portals have a small deviation on direction.
- [ ] <strong>[STANDALONE-PORTALS]</strong> Sometimes, Projectiles won't Apply Damage when hitting a Character through Portals.
- [ ] <strong>[STANDALONE-PORTALS]</strong> Projectiles that are Insta Hit (Machine Gun, Railgun, Lightning Gun and Shotgun) won't pass through them.
- [ ] <strong>[STANDALONE-PORTALS]</strong> Portals need to be pre-allocated as Actors on the map.
- [ ] <strong>[STANDALONE-WEAPONS]</strong> Fix Lightning Gun beam, visually it should be Target Dynamic and not rely solely on distance.
- [ ] Found a bug? <a href="https://vtxfactory.org/main/#contact">Contact us</a>.

## Installation:
Kosm-PACK is composed of a <strong>.uproject file</strong> that you can open on-the-fly using Unreal Engine. <strong>A .pdf manual is included for further installation instructions, blueprint editing and network settings.</strong> <a href="https://vtxfactory.org/dl/Kosm_Documentation.zip">(Manual Guide and Documentation)</a>
## Buy:
- <a href="https://unrealengine.com/marketplace/en-US/slug/kosm-classic-fps-pack">Unreal Engine Marketplace</a><br><br><br>
# Unreal Engine 4 QoL Improvements<br>
Here's some tips to improve your experience using Unreal Engine:<br><br>
**&#9632; Show Frame Rate and Memory in Editor**<br>Go into <strong>Edit > Editor Preferences</strong> and type "Show Frame Rate and Memory" in <strong>Search Details</strong>, then check it.<br><br>
**&#9632; Use New Editor Window (PIE)**<br>Click the drop-down arrow near **Play** and select **New Editor Window (PIE)** - it is more responsive, boost performance and have less input lag.<br><br>
**&#9632; t.MaxFPS 300**<br>When playing the active level in editor viewport, it caps your fps to 60. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly opened command prompt.)<br><br>
**&#9632; r.VSync 0**<br>With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br><br>
**&#9632; Uncheck FOV Scaling**<br>Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Uncheck Mouse Smoothness**<br>Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Change Mouse Sensitivity**<br>Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br><br>
**&#9632; Enable Blutilities**<br>Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser and select Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
# Contributing
If you'd like to contribute to this project in any way, please feel free to pull a request or contact us directly.<br><br>Feel free to contact support if you have any suggestions or run into any trouble editing the blueprints.<br><br><br>
# Contact
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>Feedback & Information</strong><br>info@vtxfactory.org<br><br>
<strong>Bug Report & Dev Support</strong><br>support@vtxfactory.org<br><br><br>
# Licensing
This project is published under MIT License which allows very broad use for both academic and commercial purposes.

You are very welcome to modify these mechanics and use them for your own commercial use - if doing so, please keep a link to the original repository and refer to <a href="https://vtxfactory.org/dl/Kosm_Documentation.zip">Manual Guide and Documentation</a> for more information.
