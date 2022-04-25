# BeeSwarmSimulator-1.4-TestRealm
This repository contains a test build of an upcoming version of the Bee Swarm Simulator Mod.

The current test realm build is for version 1.0.0 (Hive Expansion Update).

NOTE - I am releasing a test build of the mod for the migration to 1.4, and to allow you to use new features in the works. This is primarily because I am aware of a number of notable bugs that I'm not currently knowledgeable enough to fix, so much so that I don't want to create a public release until these bugs are fixed, but they function well enough that I'm willing to make it available to download as a test build.

I will update this when things are improved and fixed, but at the moment I'm really burnt out (As I've been working on this for over a month and while the content itself works, there are potentially devastating bugs that I have no idea how to deal with at present).

KNOWN MAJOR BUGS:

- Sometimes a bee will just despawn randomly. I'm not really sure why this happens.
- Hive slots might not update properly in multiplayer worlds, either not dropping their respective item (when evictions are used), or not saving. Due to me being new to working with tiles, I'm not sure what I can do about this just yet.
- Bees jitter A LOT in multiplayer if the owner has a poor connection to the server. This is likely due to the AI being run primarily on the owner's client.
- Projectile dust is really patchy for other clients in multiplayer.
- Certain projectiles cause notable amounts of lag - whether this is a 1.4 alpha issue or the number of extra updates on some of the projectiles, I'm not yet sure.
