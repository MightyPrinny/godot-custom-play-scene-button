Hides the "Play Scene" button and adds a custom button, useful for games with custom scene switching, 
I personally use this to make sure playing a scene from the editor is the same as loading
it normally in the game.

The plugin sets a project setting to the scene that has to be played and then runs the game normally from the main scene,
you have to load the scene manually in your code using this project setting.


The project setting used to store the scene path is "application/run/custom_first_scene", this string is
a constant stored at CustomPlayButton.scene_setting.