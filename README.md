# Kosm: A FPS Movement Pack For Unreal Engine 4
FPS mechanics to match the classical Quake franchise movement. This Pack includes 3 characters with distinct movements (which I call VQ3, QW and CPMA), a reimagined creation of a Quake fan-favorite (dm20) plus a smaller map for you to make all of your testing.<br><br>
<strong><i>Current development version:</i></strong> v1.0.8<br>
<strong><i>Unreal Engine compatibility:</i></strong> v4.22.2-v4.22.3<br><br>
<img src="https://www.vtxfactory.org/imgs/banner_gittt.jpg" /><br><br>
<a href="#kosm-demo">&#8226; Kosm-DEMO</a><br>
&nbsp;<a href="#demo-includes">- Includes</a><br>
&nbsp;<a href="#demo-preview">- Preview</a><br>
&nbsp;<a href="#demo-download">- Download</a><br><br>
<a href="#kosm-pack">&#8226; Kosm-PACK</a><br>
&nbsp;<a href="#pack-includes">- Includes</a><br>
&nbsp;<a href="#pack-patch_notes">- Patch Notes</a><br>
&nbsp;<a href="#pack-as-of-v108-known_issues">- Known Issues</a><br>
&nbsp;<a href="#pack-install">- Installation</a><br>
&nbsp;<a href="#pack-buy">- Buy PACK</a><br><br>
<a href="#unreal-engines-qol-improvements">&#8226; Unreal Engine QoL improvements</a><br>
<a href="#contributing">&#8226; Contributing</a><br>
<a href="#contact">&#8226; Contact</a><br>
<a href="#licensing">&#8226; Licensing</a><br><br>
<h1>Kosm-DEMO</h1>
You can test some of our PACK functionalities and physics with the DEMO showcase.
<h3>DEMO ./includes:</h3>
<strong><i>- VQ3 character movement </i></strong>- the longer the bunnyhop, the faster he travels;<br>
<strong><i>- Walk;</i></strong><br>
<strong><i>- Toggle Crouch;</i></strong><br>
<strong><i>- Bunnyhop;</i></strong><br>
<strong><i>- Weapon Zoom;</i></strong><br>
<strong><i>- Double Jump;</i></strong><br>
<strong><i>- Rocket Launcher Projectile;</i></strong><br>
<strong><i>- Real-time Physics Simulation;</i></strong><br>
<strong><i>- Sandbox.</i></strong><br>
<h3>DEMO ./preview:</h3>
<a href="https://za.gl/7Zeir5">Kosm-DEMO (HTML5)</a><br>
<h3>DEMO ./download:</h3>
Clone or Download this git for Windows (64-bit) or download Windows (32-bit) version <a href="https://za.gl/kbbR">here</a>.<br><br><br>
<h1>Kosm-PACK</h1>
<img src="https://www.vtxfactory.org/imgs/pack-prvw1.gif" width="66%" />
<i>** Kosm-PACK is composed of a folder which you can import to your own Unreal Engine project. **</i><br>
<h3>PACK ./includes:</h3>
<strong><i>- VQ3 character movement</i></strong> - the longer the bunnyhop, the faster he travels; <a href="https://www.youtube.com/watch?v=2cxf8LLgrd8">(preview movement)</a><br>
<strong><i>- QW character movement</i></strong> - Air Control on its own rotation axis - forward vector is being controlled by the position of character's shoulder; <a href="https://www.youtube.com/watch?v=nGmjSubCl_Q">(preview movement)</a><br>
<strong><i>- CPMA character movement</i></strong> - Full Air Control - forward vector is controlled by the direction of player's crosshair - character gains acceleration when swinging mouse. <a href="https://www.youtube.com/watch?v=HJiCq22BOOc">(preview movement)</a><br>
<strong><i>- Dash;</i></strong><br>
<strong><i>- Character and Weapon Switch;</i></strong><br>
<strong><i>- Walk;</i></strong><br>
<strong><i>- Toggle Crouch;</i></strong><br>
<strong><i>- Bunnyhop;</i></strong><br>
<strong><i>- Weapon Zoom;</i></strong><br>
<strong><i>- Double Jump;</i></strong><br>
<strong><i>- Rocket Launcher Projectile;</i></strong><br>
<strong><i>- Real-time Physics Simulation;</i></strong><br>
<strong><i>- DM20 map reimagined creation;</i></strong><br>
<strong><i>- Smaller testing grounds map. (as seen on character movement showcase)</i></strong><br><br>
<strong>DM20 reimagined:</strong><br><br><img src="https://www.vtxfactory.org/imgs/level_showcase.gif" width="66%" />
<h3>PACK ./patch_notes:</h3>
<strong>v1.0.8:</strong><br> Added an extra ragdoll for you to mess up with collision and physics.<br><br>
<strong>v1.0.7:</strong><br> Each character has its own HUD and individual speedometer, which now displays and works correctly when switching characters.<br><br>
<strong>v1.0.6:</strong><br> Removed jump cooldown node so CPMA character won't stay glued to the ground when jumping on the edge of a slope or when the space between stairs is to narrow.<br><br>
<strong>v1.0.5:</strong><br> Increased map Bound Scale limits to remove artifacts from viewport.<br><br>
<strong>v1.0.4:</strong><br> Checked Use Flat Base for Floor to avoid the situation where characters slowly lower off the side of a ledge. (as their capsule "balances" on the edge)<br><br>
<strong>v1.0.3:</strong><br>Increased trimp multiplier on slopes.<br><br>
<strong>v1.0.2:</strong><br>Added Character and Weapon Switch capability.<br><br>
<strong>v1.0.1:</strong><br>Increased step height so character can step up stairs.<br><br>
<strong>v1.0.0:</strong><br>First build deployed.<br>
<h3>PACK <i>[as of v1.0.8]</i> ./known_issues:</h3>
- Projectile trajectory is not aligned with the crosshair. (for now)<br>
- VQ3 character movement needs to be smoothed out - when jumping in order for the input forward impulse not to be so noticeable.
<h3>PACK ./install:</h3>
A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
<h3>PACK ./buy:</h3>
<a href="#">Unreal Marketplace</a><br><br><br>
<h1>Unreal Engine's QoL improvements:</h1>
<strong><i>t.maxfps 300</i> ></strong> When playing the active level in editor viewport, it caps your fps to the current monitor's refresh rate. To increse the cap, find your console toggle key <strong>- go to Edit > Project Settings > type "Console" in "Search Details" field and bind your "Console" key.</strong> Now click "Play" from the main toolbar, click your binded key and write <i>t.maxfps 300</i> in the newly open command prompt.)<br><br>
<strong><i>r.vsync 0</i> ></strong> With your "Console" key already binded, click "Play" and write <i>r.vsync 0</i> to turn off Vertical Sync.<br><br>
<strong><i>Uncheck FOV Scaling</i> ></strong> go into Project Settings and type "FOV Scaling" in Search Details, then uncheck it.<br><br>
<strong><i>Uncheck Mouse Smoothness</i> ></strong> go into Project Settings and type "Mouse Smooth" in Search Details, then uncheck it.<br><br>
<strong><i>Change Mouse Sensitivity</i> ></strong> go into Project Settings and select Input from the left column, then scroll down until you see "Turn" and "LookUp" inside Axis Mappings, then just change the "Scale" property.<br><br>
<strong><i>Enable Blutilities</i> ></strong> go to Editor Preferences and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser > Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
<h2>Contributing</h2>
If you'd like to contribute to this project in any way, feel free to pull a request.<br><br>
<h2>Contact</h2>
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>Feedback</strong><br>info@vtxfactory.org<br><br>
<strong>Support</strong><br>support@vtxfactory.org<br><br>
<h2>Licensing</h2>
This project supports the GNU v3.0 license.
<br>
