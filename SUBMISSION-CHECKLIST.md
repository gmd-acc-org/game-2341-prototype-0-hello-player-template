# Prototype 0 submission checklist

Complete this in the cloned project before your final push.

## Unity check

- [ ] I opened `Assets/Scenes/Prototype0_HelloPlayer.unity` in Unity 6 LTS.
- [ ] The scene contains a ground/platform, a visible player, and a camera that
      shows the player in Play mode.
- [ ] `Assets/Scripts/PlayerHello.cs` is attached to the player object.
- [ ] `Start()` prints a message identifying my player in the Unity Console.
- [ ] `Update()` performs a visible frame-by-frame behavior.
- [ ] Under **Edit > Project Settings > Editor**, Asset Serialization is
      **Force Text** and Version Control Mode is **Visible Meta Files**.
- [ ] I pressed Play and saw no compiler errors or missing-script messages.

## Repository check

Run this from the project root:

```bash
git status --short
git add Assets ProjectSettings Packages README.md reflection.md
git status --short
```

- [ ] The staged list includes `Assets/Scenes/Prototype0_HelloPlayer.unity`,
      `Assets/Scripts/PlayerHello.cs`, and their `.meta` files.
- [ ] The staged list includes `ProjectSettings/`, `Packages/manifest.json`,
      `Packages/packages-lock.json`, `README.md`, and completed
      `reflection.md`.
- [ ] The staged list does **not** include `Library/`, `Temp/`, `Logs/`,
      `Build/`, a `.unitypackage`, an exported build, or a downloaded CwC
      project/asset package.
- [ ] I did not copy CwC/Synty assets from the web course into this project.

## Final push

```bash
git commit -m "Complete Prototype 0"
git push origin main
```

- [ ] The push completed successfully to my own private Classroom50 repository.
- [ ] I can see the new commit on the repository page.
- [ ] `reflection.md` answers every prompt and includes the required AI-use
      disclosure (including “I used no AI” when applicable).
