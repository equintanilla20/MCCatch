# MCCatch
Play catch with your friends...in Minecraft!

### Resources:
1. [Minecraft Wiki](https://minecraft.fandom.com/wiki/Tutorials/Creating_Forge_mods#Things_not_to_do)
2. [MC Forge](https://docs.minecraftforge.net/en/latest/gettingstarted/)

### From MC Forge
1. To build your mod, run `gradlew build`. This will output a file in `build/libs` with the name `[archivesBaseName]-[version].jar`. This file can be placed in the `mods` folder of a Forge enabled Minecraft setup or distributed.
2. To test run your mod, the easiest way is to use the run configs that were generated when you set up your project. Otherwise, you can run `gradlew runClient`. This will launch Minecraft from the `\<runDir\>` location along with your mod’s code in any source sets specified within your run configurations. The default MDK includes the `main` source set, so any code written within `src/main/java` will be applied.
3. You can also run a dedicated server using the server run config or via `gradlew runServer`. This will launch the Minecraft server with its GUI. After the first run, the server will shut down immediately until the Minecraft EULA is accepted by editing `run/eula.txt`. Once accepted, the server will load and can be accessed via a direct connect to `localhost`.
