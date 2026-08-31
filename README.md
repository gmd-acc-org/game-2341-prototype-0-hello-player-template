# Prototype 0: Hello, Player

**GAME-2341 — Game Scripting**  
**Unity:** Unity 6 LTS (6000.x)

This is a **complete, blank Unity 6 starter project** for Prototype 0. It is
separate from Unity Learn's Create with Code (CwC) course project. You will use
the CwC web course to learn the editor and C# concepts, then show that learning
in this small, version-controlled Unity project.

Start with [CwC: Getting Started](https://learn.unity.com/course/create-with-code/unit/getting-started?version=6.0), then use [CwC Unit 1: Player Control](https://learn.unity.com/course/create-with-code/unit/unit-1-driving-simulation?version=6.0)
as your parallel learning path. The exact handoff is in
[CWC-ONLINE-BRIDGE.md](CWC-ONLINE-BRIDGE.md).

## Start here

1. Complete CwC **Getting Started** in the browser. It covers Unity Hub, Unity
   6 LTS, your Unity ID, and a C# editor.
2. In Classroom50, accept **Prototype 0: Hello, Player**. Classroom50 creates
   your private repository; copy its clone URL.
3. Clone *your* private repository into a local development folder—not Google
   Drive, OneDrive, Dropbox, or the CwC course-project folder:

   ```bash
   git clone "https://github.com/YOUR-CLASSROOM50-REPOSITORY.git" GAME2341-Prototype0
   cd GAME2341-Prototype0
   ```

   Replace the quoted URL with the private repository URL Classroom50 gives
   you.

4. In Unity Hub, use **Add > Add project from disk** and select the cloned
   `GAME2341-Prototype0` folder. Open it in Unity 6 LTS.
5. Open `Assets/Scenes/Prototype0_HelloPlayer.unity`. Build the required ground,
   visible player, and player behavior in that scene.

The starter already uses **Force Text** serialization and **Visible Meta Files**.
Verify both under **Edit > Project Settings > Editor** before working. Do not
change them back.

## What you will make

In `Prototype0_HelloPlayer`, create:

- a ground plane or platform;
- a visible player object, such as a cube or capsule;
- a camera that shows the player when you press Play;
- `Assets/Scripts/PlayerHello.cs`, attached to the player;
- a `Start()` Console message that identifies the player; and
- an `Update()` behavior: keyboard movement, slow rotation, or a small
  oscillating motion.

The scene already contains a camera and lighting. You are responsible for the
player, ground, script, script attachment, behavior, and test run.

## CwC stays a separate learning project

The Unity Learn CwC website is the course material, not this assignment's
starter repository. If a CwC lesson asks you to download a course project or
assets, keep that material in a different local folder. Do **not** copy CwC or
Synty course assets into this repository, and do not submit CwC screenshots or
course downloads in place of this project.

This starter uses only Unity's stock 3D project configuration and primitive
objects, so it opens without any CwC package or asset download.

## Commit and submit

From the project root, use the same small loop as you work:

```bash
git status --short
git add Assets ProjectSettings Packages README.md reflection.md
git status --short
git commit -m "Complete Prototype 0"
git push origin main
```

Before each commit, inspect the second `git status --short`. It should include
your scene, script, companion `.meta` files, Unity text configuration, and
documentation. It should never include generated Unity folders or exported
packages.

Use [SUBMISSION-CHECKLIST.md](SUBMISSION-CHECKLIST.md) before the deadline. Your
final `git push` to the private Classroom50 repository is the submission.
