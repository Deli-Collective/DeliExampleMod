# DeliExampleMod
This is an example mod for the Deli mod loading framework.
This example demonstrates the basic usage of the mod manifest, entrypoint, asset readers and asset loaders.

You'll find that creating code plugins in this format is extremely similar to BepInEx. The same loading method is used and Deli mods are passed BepInEx config and log sources. If you're porting a mod from BepInEx to Deli it shouldn't require many logical changes.