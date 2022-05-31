## Setting up MCPG
1. Create a folder for your project and unzip this there.
2. Open terminal and type `cd [project folder]`
3. Type 
```
chmod +x BuildProject.sh
```
4. Type 
```
./BuildProject.sh
```
and wait

## Setting up the workspace
1. Drag the build.gradle file onto the IntellJ icon
2. It will show a prompt; click Open as Project
3. Open the `build.gradle` file and change the `group id` to yours.
4. Change the `version` as well.
5. Click the dino icon at the top right.

## Launch Args
1. Go to `Start.java` and click the green arrow.
2. It'll show a few errors but ignore those for now.
3. Click on `Start` at the top right of your screen.
4. Click `Edit Configurations`
5. Add 
```
-Djava.library.path=versions/1.8.8/1.8.8-natives/
``` 
to the VM options.
7. Add `/.minecraft` to your working directories.

