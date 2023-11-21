This is the tutorial for the endless ground spawning component of the game. This will help you create a platform that will infinitely spawn as you travel on it.

Start by deleting the previously created plane. Then create an empty game object and name it GroundTile. 
Right click on it and add a Plane, which will add it as it's child. Set the position on Z to 5.
Click again on the GroundTile and create an empty object, naming it NextSpawnPoint, with 10 as its Z position, which should match the end of the plane.

Now, create a new folder called Prefabs, and drag n drop the GroundTile in the prefab folder, which will store it.
Delete the GroundTile, since we will spawn them from a script. To do this, create a new script called GroundSpawner.
Delete the update function since we won't need it.
Now, add 2 variables that we will need.

![image](https://github.com/mihxi/RunnerGame/assets/146852911/b262f7f0-d257-4558-9bfe-8955da84afe1)

Back in Unity, create an empty game object and name it Ground Spawner, and add component, this being the Ground Spawner script. Then select the groundtile prefab and drag it onto the GroundTile slot in the script component. 


