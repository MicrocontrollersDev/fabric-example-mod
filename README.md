# Fabric Example Mod

## Setup

For setup instructions please see the [fabric wiki page](https://fabricmc.net/wiki/tutorial:setup) that relates to the IDE that you are using.

## License

Fork of fabric-example-mod to add some things I find useful/necessary.

Changes:
- Remove client directory
- Add Mixin Extras (and JitPack maven)
- Add Mod Menu (and Terraformers maven)
- Add Vineflower (in your gradle Tasks/fabric, run genSourcesWithVineflower instead of genSources!)
- Create ModMenuIntegration class (delete/move if wanted)

Suggestions:
- If looking for a config library, consider [YetAnotherConfigLibrary](https://modrinth.com/mod/yacl)
- 