![Flourish: An open-source shaders mod compatible with OptiFine shaderpacks](docs/banner.png)

# Flourish

## Links

* **Visit [our website](https://kerberus.gg) for downloads and pretty screenshots!**
* Visit [our Discord server](https://discord.gg/kerberus) to chat about the mod and get support! It's also a great place to get development updates right as they're happening.
* Visit [the developer documentation](https://github.com/Kerberus-MC/Flourish/tree/1.19.4/docs/development) for information on developing, building, and contributing to Flourish!
* **Visit [Iris](https://irisshaders.net) for the original mod!**

## DISCLAIMER
Unfortunately Iris is no longer accessible on Curseforge, Flourish hopes to act as a stand-in for the modding community and be a solution for all the modders who had their packs impacted due to this change.

The current build of flourish does not hope to replace iris but is an alternative for creators who wish to stick to curseforge and comply by their regulations. Eventually we do plan on reworking iris from scratch to have our own mod independent of Iris which hopes to provide additional value to the community.

## FAQ

- Find answers to frequently asked questions on our [FAQ page](docs/faq.md).
- Flourish supports almost all shaderpacks, but a list of unsupported shaderpacks is available [here](docs/unsupportedshaders.md).
- A list of unfixable limitations in Flourish is available [here](docs/usage/limitations.md).

## Goals

These are the goals of Flourish. Flourish hasn't fully achieved all these goals, however we are getting close.

* **Performance.** Flourish should fully utilize your graphics card when paired with optimization mods like Sodium.
* **Correctness.** Flourish should try to be as issueless as possible in its implementation.
* **Mod compatibility.** Flourish should make a best effort to be compatible with modded environments.
* **Backwards compatibility.** All existing ShadersMod / OptiFine shader packs should just work on Flourish, without any modifications required.
* **Features for shader pack developers.** Once Flourish has full support for existing features of the shader pipeline and is reasonably bug free, I wish to expand the horizons of what's possible to do with Minecraft shader packs through the addition of new features to the shader pipeline. Unlimited color buffers, direct voxel data access, and fancy debug HUDs are some examples of features that I'd like to add in the future.
* **A well-organized codebase.** I'd like for working with Flourish code to be a pleasant experience overall.


## What's the current state of development?

Flourish has public releases for 1.18.2, 1.19.2, 1.19.3, and 1.19.4 that work with the official releases of Sodium. Flourish is generally usable on most shader packs, and most shader packs are being designed with Flourish support in mind.

However, Flourish is still not complete software. Performance can be improved, and more features are being added for shader developers. There are also some minor missing features from OptiFine that make the implementation incomplete.

## How can I help?

* The Kerberus Discord server is looking for people willing to provide support and moderate the server! Go to #applications on our server if you'd like to apply.
* Code review on open PRs is appreciated! This helps get important issues with PRs resolved before I give them a look.
* Code contributions through PRs are also welcome! If you're working on a large / significant feature it's usually a good idea to talk about your plans beforehand, to make sure that work isn't wasted.

## But where's the Forge version?

Flourish doesn't support Forge. This is for a few reasons:

* The Forge toolchain isn't really designed to play nice with mods like Flourish that need to make many patches to the game code. It's possible, but Fabric & Quilt are just *better* for mods like Flourish. It's no coincidence that the emergence of Fabric and the initial emergence of OptiFine replacements happened at around the same time.

Some users have already ported Flourish to Forge, however these ports generally come with mod compatibility issues and outdated updates.
The license of Flourish does permit others to legally port Flourish to Forge, and we are not strictly opposed to the existence of an Flourish Forge port created by others. However, what we are opposed to is someone doing a bare-minimum port of Flourish to Forge, releasing it to the public, and then abandoning it or poorly maintaining it while compatibility issues and bug reports accumulate. When that happens, not only does that hurt the reputation of Flourish, but we also ultimately get flooded by users wanting support with a low-effort Forge port that we didn't even make.

So, if you want to distribute a Forge port of Flourish, we'd prefer if you let us know. Please don't just name your port "Flourish Forge," "Flourish for Forge," or "Flourish Forge Port" either. Be original, and don't just hijack our name, unless we've given you permission to use one of those kinds of names. If a well-qualified group of people willing to maintain a Forge port of Flourish does appear, then a name like "Flourish Forge" might be appropriate - otherwise, it probably isn't appropriate.

## Credits for the original (Iris)

* **TheOnlyThing and Vaerian**, for creating the excellent logo
* **Mumfrey**, for creating the Mixin bytecode patching system used by Iris and Sodium internally
* **The Fabric and Quilt projects**, for enabling the existence of mods like Iris that make many patches to the game
* **JellySquid**, for creating Sodium, the best rendering optimization mod for Minecraft that currently exists, and for making it open-source
* **All past, present, and future contributors to Iris**, for helping the project move along
* **Dr. Rubisco**, for maintaining the website
* **The Iris support and moderation team**, for handling user support requests and allowing me to focus on developing Iris
* **daxnitro, karyonix, and sp614x**, for creating and maintaining the current shaders mods

## License

All code in this (Flourish) repository is completely free and open source, and you are free to read, distribute, and modify the code as long as you abide by the (fairly reasonable) terms of the [GNU LGPLv3 license](https://github.com/Kerberus-MC/Flourish/blob/1.19.4/LICENSE).

Dependencies may not be under an applicable license: See the [Incompatible Dependencies](https://github.com/Kerberus-MC/Flourish/blob/1.19.4/LICENSE-DEPENDENCIES) page for more information.

You are not allowed to redistribute Flourish commerically or behind a paywall, unless you get a commercial license for GLSL Transformer. See above for more information.

Though it's not legally required, I'd appreciate it if you could ask before hosting your own public downloads for compiled versions of Iris. Though if you want to add the mod to a site like MCBBS, that's fine, no need to ask me.
