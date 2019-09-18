# Kosm: Classic FPS Pack For Unreal Engine 4
> Classic Arena First Person Shooter Mechanics for Unreal Engine.<br><br>A powerful tool with fully customizable Blueprints to tune your project up - this Pack includes 2 Character Blueprints defined as VQ3 (imagine Visor from Quake) and CPMA (Full Air Control Support), an AI Bot and Ragdoll, 3 Projectiles (Rocket Launcher, Railgun and Nailgun), 2 Maps for you to make all your testing, plus an Health/Armor System and much more, all replicated for online gameplay.<br><br>
This Pack is composed by a <strong>.uproject file</strong> which you can freely customize using Unreal Engine 4.<br><br>

**Showcase Teaser:** <a href="https://www.youtube.com/watch?v=udRW0fI7Cvk">Watch Video</a><br>
**Current Development Build:** v1.2.0<br>
**Supported Operating System:** Windows 32/64-bit, Linux and Oculus-Rift ready<br>
**Unreal Engine Compatibility Version:** v4.22.3 - v4.23.0<br><br>
<img src="https://kosm.vtxfactory.org/imgs/banner_git3.png" /><br><br>
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
- <a href="#licensing">Licensing</a><br><br>
# Kosm-DEMO
You can test our PACK functionalities with our DEMO showcase below, on Testing_Grounds Map.
&#9675; ## DEMO download:
Check our <a href="https://github.com/vtx-factory/Kosm-FPS-Movement-Pack/releases">Releases</a> section to download the binaries for your platform.<br><br>
# Kosm-PACK
<img src="https://www.vtxfactory.org/imgs/pack-prvw1.gif" width="66%" />
## &#9675; PACK includes:
<strong>&#8226; VQ3 movement Character</strong> (Green Actor) <a href="https://www.vtxfactory.org/video/vq3-mov.mp4">(preview movement)</a><br>Longer the Bunny-hop, faster the travel.<br><br>
<strong>&#8226; CPMA movement Character</strong> (Red Actor) <a href="https://www.vtxfactory.org/video/cpma-mov.mp4">(preview movement)</a><br>Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse.<br><br>
<strong>&#8226; Rocket Launcher, Railgun and Nailgun Projectiles</strong><br><br>
<strong>&#8226; Artificial Intelligence Bot with Sight and Hearing Perception</strong><br><br>
<strong>&#8226; Player's HUD</strong><br>
<strong>&#8226; Health/Armor System & Pickups</strong><br>
<strong>&#8226; Radial/Splash Damage</strong><br>
<strong>&#8226; Damage Indicators</strong><br><br>
<strong>&#8226; Custom Crosshairs and Speedometer</strong><br>
<strong>&#8226; Footsteps, Misc Sounds and Attenuation Settings</strong><br><br>
<strong>&#8226; Toggle Crouch</strong><br>
<strong>&#8226; Bunny-hop</strong><br>
<strong>&#8226; Weapon Zoom</strong><br>
<strong>&#8226; Double Jump</strong><br>
<strong>&#8226; Dash</strong><br>
<strong>&#8226; Walk</strong><br><br>
<strong>&#8226; Fortress Map:</strong><br><br>
<img src="https://www.vtxfactory.org/imgs/level_showcase.gif" width="66%" />
<p><strong>&#8226; Testing_Grounds Map:</strong><br><br>
<img src="https://www.vtxfactory.org/imgs/test_grounds.png" width="66%" /></p>
## &#9675; PACK patch_notes:
<strong>&#8226; v1.2.0:</strong><br>
&nbsp;&nbsp;- Further tuned VQ3 Character movement.<br>
&nbsp;&nbsp;- Enabled Raw Input Support.<br>
&nbsp;&nbsp;- Added Damage Indicators.<br>
&nbsp;&nbsp;- Added Sound Attenuation over distance.<br>
&nbsp;&nbsp;- Added Radial/Splash Damage.<br>
&nbsp;&nbsp;- Added AI with Sight and Hear Perception.<br>
&nbsp;&nbsp;- Added Footsteps Audio.<br>
&nbsp;&nbsp;- Added Health/Armor System.<br>
&nbsp;&nbsp;- Added Health and Armor Pickups.<br>
&nbsp;&nbsp;- Added Nailgun and Railgun Projectiles.<br>
&nbsp;&nbsp;- Added Individual HUDs for each Character.<br>
<strong>&#8226; v1.1.0:</strong><br>
&nbsp;&nbsp;- Optimized Mouse Acceleration detection for the VQ3 character to work better. (further updates will be coming on next patch)<br>
&nbsp;&nbsp;- Revamped Rocket Launcher Projectile animations and particles.<br>
&nbsp;&nbsp;- Aligned Projectile with Crosshair.<br>
&nbsp;&nbsp;- Fixed a SpawnedDecal error.<br>
&nbsp;&nbsp;- Upgraded Project compatibility to support Unreal Engine v4.23.0 Preview 6.<br>
<strong>&#8226; v1.0.8:</strong><br>&nbsp;&nbsp;- Added an extra ragdoll for you to test collision and physics.<br>
<strong>&#8226; v1.0.7:</strong><br>&nbsp;&nbsp;- Each character has its own HUD and individual speedometer, which now displays and works correctly when switching Characters.<br>
<strong>&#8226; v1.0.6:</strong><br>&nbsp;&nbsp;- Removed jump cooldown node so CPMA character won't stay glued to the ground when jumping on the edge of a slope or when the space between stairs is too narrow.<br>
<strong>&#8226; v1.0.5:</strong><br>&nbsp;&nbsp;- Increased map Bound Scale limits to remove artifacts from viewport.<br>
<strong>&#8226; v1.0.4:</strong><br>&nbsp;&nbsp;- Checked Use Flat Base for Floor to avoid the situation where characters slowly lower off the side of a ledge. (as their capsule "balances" on the edge)<br>
<strong>&#8226; v1.0.3:</strong><br>&nbsp;&nbsp;- Increased trimp multiplier on slopes.<br>
<strong>&#8226; v1.0.2:</strong><br>&nbsp;&nbsp;- Added Character and Weapon Switch capability.<br>
<strong>&#8226; v1.0.1:</strong><br>&nbsp;&nbsp;- Increased step height so character can step up stairs.<br>
<strong>&#8226; v1.0.0:</strong><br>&nbsp;&nbsp;- First build deployed.<br>
## &#9675; PACK known_issues:
<strong>&#8226; as of v1.2.0: <i>(to be fixed in subsequent updates)</i></strong><br>
&nbsp;&nbsp;- AI Bot is still Experimental, but will be upgraded overtime.<br>
&nbsp;&nbsp;- Correct AI and Player Animations to be added (e.g. when Crouching, Shooting, Strafing, Walking, etc).<br>
&nbsp;&nbsp;- On Weapon Zoom, Crosshair slightly misaligned with fired Projectile.<br>
&nbsp;&nbsp;- All Characters' Tap-Jump Acceleration will work as if it was Bunny-hop.<br>
&nbsp;&nbsp;- VQ3 Acceleration Gain Detection will be upgraded.<br>
&nbsp;&nbsp;- Theres a delay on the next fired Projectile when firing any weapon and immediately switching to another at the same time.<br>

&nbsp;&nbsp;- ~~When pogo jumping with VQ3 Character, sometimes you'll hear two jump Audio Cues at the same time.~~<br>
## &#9675; PACK installation:
Kosm-PACK is composed of a <strong>.uproject file</strong> that you can open on-the-fly using Unreal Engine. A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
## &#9675; PACK buy:
<a href="#">Unreal Engine Marketplace</a> (soon)<br><br><br>
# Unreal Engine 4 QoL improvements:
Here's some tips to improve your experience using Unreal Engine:<br><br>
<strong>&#8226; Show Frame Rate and Memory in Editor</strong><br>Go into <strong>Edit > Editor Preferences</strong> and type "Show Frame Rate and Memory" in <strong>Search Details</strong>, then check it.<br><br>
<strong>&#8226; t.MaxFPS 300</strong><br>When playing the active level in editor viewport, it caps your fps to 60. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly open command prompt.)<br><br>
<strong>&#8226; r.VSync 0</strong><br>With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br><br>
<strong>&#8226; Uncheck FOV Scaling</strong><br>Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br><br>
<strong>&#8226; Uncheck Mouse Smoothness</strong><br>Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br><br>
<strong>&#8226; Change Mouse Sensitivity</strong><br>Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br><br>
<strong>&#8226; Enable Blutilities</strong><br>Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser > Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
# Contributing
If you'd like to contribute to this project in any way, please feel free to pull a request or contact us directly.<br><br>Feel free to contact support if you have any suggestions or run into any trouble editing the blueprints. <br><br>
# Contact
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>General Info & Feedback</strong><br>info@vtxfactory.org<br><br>
<strong>Support</strong><br>support@vtxfactory.org<br><br>
# Licensing
This project supports the GNU v3.0 license.
