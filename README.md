# MalDDalPatcher
Umamusme patching tool for Android (translation/game enhancement patch).

# Link
[![Discord](https://img.shields.io/discord/1222345682749493259?logo=discord&logoColor=000000label=Discord)](https://discord.gg/b2TDQKpu9v)

# Requirements
- Android 9.0 or above

# Download
Download the latest release from the [Releases page](https://github.com/Seungpyo1007/MalDDalPatcher/releases).

# How to use
## Patching the app
APK file of the already installed app, or select an APK file and patch it.

### Rooted
You can use the **Direct install** option on rooted devices. This will mount a modified APK file on
top on your existing one, which will keep the original app safe and does not require reinstalling the
app.

### Non-root
You must choose to **save the patched APK file** and install it manually. If you've already had the
app installed before, you must uninstall it before installing the patched APK, because it is signed
with a different key. The signing key is reused the next time you patch another one, so you can update
the app later on. This also means that once you've started using it, everytime there's a new update,
you have to patch the updated APK to able to install it.

**Note 1:** If you've already had an account on the game and you don't want to lose it when reinstalling
the app, you can use the game's Data Link feature.

**Note 2:** The signing key is unique for each installation of UmaPatcher. It is also a self-signed
key; during installation, Google Play Protect will warn you of installing an untrusted app. **You
can safely ignore this and tap on More Info -> Install anyways to continue installation.**

# License
[Apache License 2.0](LICENSE)

#Thanks to
[UmaPatcher][https://github.com/LeadRDRK/UmaPatcher]
[All translators][fprtkdl][vanaBV]  
[The original umamusume-db-translate](https://github.com/FabulousCupcake/umamusume-db-translate)  
[umamusume-localify]
[umamusu-translate]
[Umamusume Translation Discord](https://discord.gg/b2TDQKpu9v)  
Link

[umamusume-localify]: https://github.com/GEEKiDoS/umamusume-localify
[tlg]: https://github.com/MinamiChiwa/Trainers-Legend-G
[db-translate project]: https://github.com/noccu/umamusume-db-translate

[tl-progress]: docs/tl-progress.md
[translating]: docs/translating.md
[id-structure]: docs/id-structure.md
