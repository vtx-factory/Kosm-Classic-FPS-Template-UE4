# Kosm: A FPS Movement Pack For Unreal Engine 4
FPS mechanics to match our good and old-fashioned Quake franchise movement, on Unreal Engine. This Pack includes 3 Characters with distinct movements (defined as VQ3, QW and CPMA), a reimagined creation of a Quake fan-favorite Map (dm20) plus a smaller one for you to make all your testing.<br><br>
<strong><i>Current development version:</i></strong> v1.0.8<br>
<strong><i>Unreal Engine compatibility:</i></strong> v4.22.3 - v4.23.0<br><br>
<img src="https://www.vtxfactory.org/imgs/banner_gittt.jpg" /><br><br>
<a href="#kosm-demo">&#8226; Kosm-DEMO</a><br>
&nbsp;<a href="#demo-includes">- Includes</a><br>
&nbsp;<a href="#demo-preview">- Preview</a><br>
&nbsp;<a href="#demo-download">- Download</a><br>
<a href="#kosm-pack">&#8226; Kosm-PACK</a><br>
&nbsp;<a href="#pack-includes">- Includes</a><br>
&nbsp;<a href="#pack-patch_notes">- Patch Notes</a><br>
&nbsp;<a href="#pack-as-of-v108-known_issues">- Known Issues</a><br>
&nbsp;<a href="#pack-install">- Installation</a><br>
&nbsp;<a href="#pack-buy">- Buy</a><br>
<a href="#unreal-engines-qol-improvements">&#8226; Unreal Engine 4 QoL improvements</a><br>
<a href="#contributing">&#8226; Contributing</a><br>
<a href="#contact">&#8226; Contact</a><br>
<a href="#licensing">&#8226; Licensing</a><br><br>
<h1>Kosm-DEMO</h1>
You can test some of our PACK functionalities and physics in the <a href="#demo-preview">DEMO Showcase</a>.
<h3>DEMO ./includes:</h3>
<strong>- VQ3 movement Character;</strong><br>
<strong>- Custom Crosshair and Speedometer;</strong><br>
<strong>- Walk;</strong><br>
<strong>- Toggle Crouch;</strong><br>
<strong>- Bunny-hop;</strong><br>
<strong>- Weapon Zoom;</strong><br>
<strong>- Double Jump;</strong><br>
<strong>- Rocket Launcher Projectile;</strong><br>
<strong>- Real-time Physics Simulation;</strong><br>
<strong>- Small Sandbox.</strong><br>
<h3>DEMO ./preview:</h3>
<a href="https://za.gl/7Zeir5">Kosm-DEMO (HTML5)</a><br>
<h3>DEMO ./download:</h3>
Clone or Download this git for Windows (64-bit) or download Windows (32-bit) version <a href="https://za.gl/kbbR">here</a>.<br><br><br>
<h1>Kosm-PACK</h1>
<img src="https://www.vtxfactory.org/imgs/pack-prvw1.gif" width="66%" />
<h3>PACK ./includes:</h3>
<strong>- VQ3 movement Character</strong> (Green Actor) - Longer the Bunny-hop, faster the travel; <a href="https://www.youtube.com/watch?v=2cxf8LLgrd8">(preview movement)</a><br>
<strong>- QW movement Character</strong> (Red Actor) - Air Control on its own rotation axis - input forward vector is relative to the position of Character's <i>shoulder</i>; <a href="https://www.youtube.com/watch?v=nGmjSubCl_Q">(preview movement)</a><br>
<strong>- CPMA movement Character</strong> (Blue Actor) - Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse; <a href="https://www.youtube.com/watch?v=HJiCq22BOOc">(preview movement)</a><br>
<strong>- Custom Crosshairs and Speedometer;</strong><br>
<strong>- Dash;</strong><br>
<strong>- Character and Weapon Switch;</strong><br>
<strong>- Walk;</strong><br>
<strong>- Toggle Crouch;</strong><br>
<strong>- Bunny-hop;</strong><br>
<strong>- Weapon Zoom;</strong><br>
<strong>- Double Jump;</strong><br>
<strong>- Rocket Launcher Projectile;</strong><br>
<strong>- Real-time Physics Simulation;</strong><br>
<strong>- Smaller Testing Grounds Map</strong> - as seen on <a href="https://www.youtube.com/watch?v=2cxf8LLgrd8">Character Movement Showcase</a>;<br>
<strong>- DM20 Reimagined Map</strong> - Revisit this old masterpiece, now in Unreal Engine 4.<br><br>
<img src="https://www.vtxfactory.org/imgs/level_showcase.gif" width="66%" />
<h3>PACK ./patch_notes:</h3>
* Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2
<strong>&#8226; v1.0.8:</strong><br> - Added an extra ragdoll for you to mess up with collision and physics.<br>
<strong>&#8226; v1.0.7:</strong><br>- Each character has its own HUD and individual speedometer, which now displays and works correctly when switching characters.<br>
<strong>&#8226; v1.0.6:</strong><br>- Removed jump cooldown node so CPMA character won't stay glued to the ground when jumping on the edge of a slope or when the space between stairs is to narrow.<br>
<strong>&#8226; v1.0.5:</strong><br>- Increased map Bound Scale limits to remove artifacts from viewport.<br>
<strong>&#8226; v1.0.4:</strong><br>- Checked Use Flat Base for Floor to avoid the situation where characters slowly lower off the side of a ledge. (as their capsule "balances" on the edge)<br>
<strong>&#8226; v1.0.3:</strong><br>- Increased trimp multiplier on slopes.<br>
<strong>&#8226; v1.0.2:</strong><br>- Added Character and Weapon Switch capability.<br>
<strong>&#8226; v1.0.1:</strong><br>- Increased step height so character can step up stairs.<br>
<strong>&#8226; v1.0.0:</strong><br>- First build deployed.<br>
<h3>PACK <i>[as of v1.0.8]</i> ./known_issues:</h3>
- Projectile trajectory is not aligned with the crosshair. (for now)<br>
- VQ3 character movement needs to be smoothed out - when jumping in order for the input forward impulse not to be so noticeable.
<h3>PACK ./install:</h3>
Kosm-PACK is composed of a folder which you can import to a new or existing Unreal Engine project. A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
<h3>PACK ./buy:</h3>
<a href="#">Unreal Marketplace</a><br><br><br>
<h1>Unreal Engine 4 QoL improvements:</h1>
<strong>&#8226; t.maxfps 300</strong><br>- When playing the active level in editor viewport, it caps your fps to the current monitor's refresh rate. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly open command prompt.)<br>
<strong>&#8226; r.vsync 0</strong><br>- With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br>
<strong>&#8226; Uncheck FOV Scaling</strong><br>-  Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br>
<strong>&#8226; Uncheck Mouse Smoothness</strong><br>- Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br>
<strong>&#8226; Change Mouse Sensitivity</strong><br>- Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br>
<strong>&#8226; Enable Blutilities</strong><br>- Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser > Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
<h2>Contributing</h2>
If you'd like to contribute to this project in any way, feel free to pull a request.<br><br>
<h2>Contact</h2>
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>General Info & Feedback</strong><br>info@vtxfactory.org<br><br>
<strong>Support</strong><br>support@vtxfactory.org<br><br>
<h2>Licensing</h2>
This project supports the GNU v3.0 license.
<br>
