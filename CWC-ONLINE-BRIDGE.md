# From CwC Online to Prototype 0

Prototype 0 is intentionally **next to** Unity Learn's Create with Code course,
not inside it. Use this sequence so the web lessons, Unity project, and
Classroom50 submission reinforce one another.

| Do this first | It gives you | Then do this in Prototype 0 |
| --- | --- | --- |
| [CwC: Getting Started](https://learn.unity.com/course/create-with-code/unit/getting-started?version=6.0) | Unity Hub, Unity 6 LTS, a Unity ID, and a code editor | Clone this repository and open it in Unity Hub. |
| [CwC Unit 1: Player Control](https://learn.unity.com/course/create-with-code/unit/unit-1-driving-simulation?version=6.0), especially the introduction and Lesson 1.1 | Familiarity with the Unity Editor, GameObjects, components, and the first C# script workflow | Add a ground and a player in `Prototype0_HelloPlayer`, then attach `PlayerHello.cs`. |
| CwC's explanation of methods and frame-by-frame behavior | Why `Start()` runs once and `Update()` runs repeatedly while the game runs | Write a meaningful Console message in `Start()` and one small movement, rotation, or oscillation behavior in `Update()`. |
| Resume CwC Unit 1 | The driving simulator curriculum continues in its own project | Keep this small project as your Prototype 0 submission and reference point. |

## The boundary to keep straight

- **CwC web course:** learning activities, course videos, tutorials, quizzes,
  and any Unity Learn project download.
- **Prototype 0 repository:** your independently built, private Classroom50
  submission.

If Unity Learn asks you to download its Unit 1 materials, place them in a
different local folder. You may complete those CwC exercises, but do not merge
their assets or files into this repository. Prototype 0 needs only the clone
you received from Classroom50 and Unity's built-in primitive objects.

## Working rhythm for this week

1. Use CwC to learn the editor operation or C# idea.
2. Switch to `Prototype0_HelloPlayer.unity` and reproduce the small required
   idea yourself using only a plane, cube/capsule, camera, and script.
3. Press Play, read the Console, and fix one issue at a time.
4. Commit the working checkpoint. Do not wait until the last night to make the
   first commit.
5. When Prototype 0 is complete, return to CwC Unit 1 for the driving
   simulator lessons.

## Do not substitute one for the other

Completing a CwC web page or Unit 1 exercise does not submit Prototype 0.
Likewise, a successful Git push does not mark a CwC page complete. The course
uses both: CwC for guided learning and Classroom50 for your submitted work.
