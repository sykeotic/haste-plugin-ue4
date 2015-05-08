# Haste Plugin - UE4 Editor Mode for Rapid Mesh Placement

**Haste** is a Custom Unreal Engine 4 Editor Mode that lets you place static meshes all over your map with point and click

## Installation
* Create a folder named Plugins in your UE4 game root directory
* Extract the contents of this repository into a directory named Haste
* The final directory structure should look like this

![Imgur](http://i.imgur.com/SWjVGg2.png)


### Example
<pre>
cd ShooterGame
mkdir Plugins
cd Plugins
git clone https://github.com/coderespawn/haste-plugin-ue4.git Haste
</pre>

This would create a folder named Haste inside the Plugins folder and clone the repository into it

### Example (if your main game code is already in git)
You can clone the plugin into your game's existing git repository as a sub module
<pre>
cd ShooterGame
mkdir Plugins
git submodule add https://github.com/coderespawn/haste-plugin-ue4.git Plugins/Haste
</pre>

