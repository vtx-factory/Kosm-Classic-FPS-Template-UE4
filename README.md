# Kosm: FPS Movement Pack For Unreal Engine 4
FPS mechanics to match our good and old-fashioned Quake movement, on Unreal Engine. This Pack includes 3 Characters with distinct movement mechanics (defined as VQ3, QW and CPMA), plus 2 maps for you to make all your testing and much more.<br><br>
<strong><i>Showcase Teaser:</i></strong> <a href="https://www.youtube.com/watch?v=udRW0fI7Cvk">Watch Video</a><br>
<strong><i>Current Development build:</i></strong> v1.1.0<br>
<strong><i>Unreal Engine compatibility version:</i></strong> v4.22.3 - v4.23.0 Preview 6<br><br>
<img src="https://www.vtxfactory.org/imgs/banner_gittt.jpg" /><br><br>
<a href="#kosm-demo">&#8226; Kosm-DEMO</a><br>
&nbsp;<a href="#demo-includes">- Includes</a><br>
&nbsp;<a href="#demo-preview">- Preview</a><br>
&nbsp;<a href="#demo-download">- Download</a><br>
<a href="#kosm-pack">&#8226; Kosm-PACK</a><br>
&nbsp;<a href="#pack-includes">- Includes</a><br>
&nbsp;<a href="#pack-patch_notes">- Patch Notes</a><br>
&nbsp;<a href="#pack-known_issues">- Known Issues</a><br>
&nbsp;<a href="#pack-installation">- Installation</a><br>
&nbsp;<a href="#pack-buy">- Buy</a><br>
<a href="#unreal-engine-4-qol-improvements">&#8226; Unreal Engine 4 QoL improvements</a><br>
<a href="#contributing">&#8226; Contributing</a><br>
<a href="#contact">&#8226; Contact</a><br>
<a href="#licensing">&#8226; Licensing</a><br><br>
<h1>Kosm-DEMO</h1>
You can test some of our PACK functionalities and physics in the <a href="#demo-preview">DEMO Showcase</a>.
<h3>DEMO ./includes:</h3>
<strong>&#8226; VQ3 movement Character</strong><br>
<strong>&#8226; Custom Crosshair and Speedometer</strong><br>
<strong>&#8226; Walk</strong><br>
<strong>&#8226; Toggle Crouch</strong><br>
<strong>&#8226; Bunny-hop</strong><br>
<strong>&#8226; Weapon Zoom</strong><br>
<strong>&#8226; Double Jump</strong><br>
<strong>&#8226; Rocket Launcher Projectile</strong><br>
<strong>&#8226; Testing Grounds Map</strong><br>
<h3>DEMO ./preview:</h3>
<a href="https://www.vtxfactory.org/main/Kosm-DEMO/">Kosm-DEMO (html5 version)</a><br>
<h3>DEMO ./download:</h3>
<strong>&#8226; Windows 64-bit/32-bit executables</strong><br>
Check our <a href="https://github.com/vtx-factory/Kosm-FPS-Movement-Pack/releases">Releases</a> section to download the binaries for your platform.<br><br>
<strong>&#8226; HTML5 version</strong><br>
Clone this git for the html5 version. <strong><i>(you'll have to host it on your own webserver)</i></strong><br><br>
<h1>Kosm-PACK</h1>
<img src="https://www.vtxfactory.org/imgs/pack-prvw1.gif" width="66%" />
<h3>PACK ./includes:</h3>
<strong>&#8226; VQ3 movement Character</strong> (Green Actor) <a href="https://www.vtxfactory.org/video/vq3-mov.mp4">(preview movement)</a><br>Longer the Bunny-hop, faster the travel.<br><br>
<strong>&#8226; QW movement Character</strong> (Red Actor) <a href="https://www.vtxfactory.org/video/qw-mov.mp4">(preview movement)</a><br>Air Control on its own rotation axis - input forward vector is relative to the position of Character's <i>shoulder</i>.<br><br>
<strong>&#8226; CPMA movement Character</strong> (Blue Actor) <a href="https://www.vtxfactory.org/video/cpma-mov.mp4">(preview movement)</a><br>Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse.<br><br>
<strong>&#8226; Custom Crosshairs and Speedometer</strong><br>
<strong>&#8226; Dash</strong><br>
<strong>&#8226; Character and Weapon Switch</strong><br>
<strong>&#8226; Walk</strong><br>
<strong>&#8226; Toggle Crouch</strong><br>
<strong>&#8226; Bunny-hop</strong><br>
<strong>&#8226; Weapon Zoom</strong><br>
<strong>&#8226; Double Jump</strong><br>
<strong>&#8226; Rocket Launcher Projectile</strong><br><br>
<strong>&#8226; Fortress Map:</strong><br>
<img src="https://www.vtxfactory.org/imgs/level_showcase.gif" width="66%" />
<p><strong>&#8226; Testing Grounds Map:</strong><br>
<img src="https://www.vtxfactory.org/imgs/test_grounds.png" width="66%" /></p>
<h3>PACK ./patch_notes:</h3>
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
<h3>PACK ./known_issues:</h3>
<strong>&#8226; as of v1.1.0:</strong><br>
&nbsp;&nbsp;- On Weapon Zoom, Crosshair slightly misaligned with fired Projectile.<br>
&nbsp;&nbsp;- All Characters' Tap-Jump Acceleration will work as if it was Bunny-hop in subsequent patch.<br>
&nbsp;&nbsp;- VQ3 Acceleration Gain Detection will be upgraded in subsequent patch.<br>
<h3>PACK ./installation:</h3>
Kosm-PACK is composed of a <strong>.uproject file</strong> that you can open on-the-fly and a content folder which you can <strong>import to a new or existing Unreal Engine project</strong>. A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
<h3>PACK ./buy:</h3>
<a href="#">Unreal Engine Marketplace</a><br><br><br>
<h1>Unreal Engine 4 QoL improvements:</h1>
Here's some tips to improve your experience using Unreal Engine:<br><br>
<strong>&#8226; Show Frame Rate and Memory in Editor</strong><br>Go into <strong>Edit > Editor Preferences</strong> and type "Show Frame Rate and Memory" in <strong>Search Details</strong>, then check it.<br><br>
<strong>&#8226; t.MaxFPS 300</strong><br>When playing the active level in editor viewport, it caps your fps to 60. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly open command prompt.)<br><br>
<strong>&#8226; r.VSync 0</strong><br>With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br><br>
<strong>&#8226; Uncheck FOV Scaling</strong><br>Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br><br>
<strong>&#8226; Uncheck Mouse Smoothness</strong><br>Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br><br>
<strong>&#8226; Change Mouse Sensitivity</strong><br>Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br><br>
<strong>&#8226; Enable Blutilities</strong><br>Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser > Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
<h2>Contributing</h2>
If you'd like to contribute to this project in any way, please feel free to pull a request or contact us directly.<br><br>
<h2>Contact</h2>
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>General Info & Feedback</strong><br>info@vtxfactory.org<br><br>
<strong>Support</strong><br>support@vtxfactory.org<br><br>
<h2>Licensing</h2>
This project supports the GNU v3.0 license.
<br>
