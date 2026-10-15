# Trigger Animation Preview [TAP]

By Shar. Preview trigger animations by scrubbing the Geometry Dash editor camera.

## Download

Download **[TAP.geode](https://github.com/shar-mark/trigger-animation-preview/releases/download/v1.0.0/TAP.geode)**. This is the package submitted to Geode Index.

Earlier preparation packages remain attached to the release; use **TAP.geode**.

Windows only. Requires Geometry Dash 2.2081 and Geode 5.11.1.

**Scrub through your animations without leaving the editor.**

Move the camera left or right to preview your level like a timeline. Adjust a trigger, scrub back, and see the result. Play Music works too.

## <c-9EDDD0>Get started</c>

1. Enable the editor's **Preview Animations** option.
2. Select the triggers you want to preview and press **ANIM** to mark them orange.
3. Move the camera to scrub through the animation.

<c-E6C77A>By default, only ANIM-marked triggers are previewed.</c> No marks means no animation from this mod.

Open **Anim Preview** below **View Groups & Item IDs**, to the left of **Edit Extras**. The ANIM button is directly underneath.

## <c-9EDDD0>What you can preview</c>

- **Move, Scale, Rotate and Follow**, with duration and easing.
- **Stop, Pause and Resume**, plus deterministic Spawn chains.
- **Move Target Mode** with group targets.
- **Area Move, Area Scale and Area Rotate**, including Edit Area and Area Stop controls.

Scrubbing works in both directions. ANIM marks are retained when you save the level and carried through copy/paste.

## <c-9EDDD0>Choose what animates</c>

In **Anim Preview**, switch between:

- **Animate only selected triggers**: preview the orange ANIM-marked triggers.
- **Animate except selected triggers**: preview everything supported except those marks.

Here, "selected" means **marked with ANIM**, regardless of your current editor selection. Select several triggers to change all their marks at once.

## <c-9EDDD0>Make it your workspace</c>

- **Time Line** shows a yellow time marker with seconds.
- **Force touch trigger** previews Touch triggers as ordinary timeline triggers, without simulating contact.
- **Force Y to center** lets Area P1/P2 references follow the current screen center on Y. With it off, their influence uses X only; authored Area Move Y still works. This option applies to Area triggers only.

## <c-9EDDD0>Keep in mind</c>

This is an editing aid; playtest to check the final result. Ordinary Move player/camera Y following and P1/P2 Target Mode are excluded. Advanced Spawn modes and nonzero channels/orders are not supported. Area effects that move the source of an ordinary Follow or Target Mode may differ from gameplay.

---

Made by **Shar** | [GitHub](https://github.com/shar-mark)


## Source code

This repository distributes compiled releases only. Source code is private and can be provided privately to Geode staff for verification.
