# AuroralisStar by Jack

AuroralisStar is a stylized Minecraft shader fork focused on mood, atmosphere, and identity.

Built on top of Eclipse Shader and Bliss, this project pushes the look away from the original preset feel and toward a more cinematic direction: denser fog, stronger art direction, aurora-heavy skies, curated color grading, and hardware-specific variants for both performance and quality.

## What Makes AuroralisStar Different

AuroralisStar is not just a repack.

This fork adds its own visual direction and tuning philosophy:

- Stronger auroras with a purple and gold identity
- Darker, moodier forest presentation with more atmospheric fog
- Custom hardware-targeted variants instead of one generic pack
- Faster access to artistic controls from the shader menu
- Rebranded in-shader identity under `AuroralisStar by Jack`
- Spanish-facing menu layer for the fork's visible controls

The goal is to create scenes that feel dramatic, dense, magical, and more recognizable at a glance.

## Main Additions In This Fork

- `Auroralis MX450 (Objetivo 120 FPS)`
  Performance-oriented tuning for laptops with lower graphics headroom
- `Auroralis Fast (MX450)`
  Lightweight stylized preset with the fork's color direction
- `Auroralis RTX 4060 (Calidad Alta)`
  High-quality profile for stronger desktop GPUs
- `Auroralis Cinema (4060)`
  More cinematic color, stronger auroras, and richer atmosphere
- `Dark Fog Forest (Dia Bosque)`
  A themed preset designed around dense daytime forest fog, colder greens, muted highlights, and an almost End-like enveloping haze without making the night completely black

## Visual Direction

AuroralisStar leans into:

- Purple auroras
- Golden torchlight and warmer highlights
- Cooler greens in forests
- Slightly desaturated mids for a darker fantasy tone
- More visible haze and suspended fog in wooded areas
- A stronger sense of separation between gameplay-focused and cinematic presets

The intention is to make daytime forests feel heavy, deep, and layered instead of clean and flat.

## Fog And Atmosphere Work

One of the main goals of this fork is better atmosphere.

AuroralisStar expands the artistic use of fog through:

- Higher `Haze_amount`
- Stronger `TOD_Fog_mult`
- Time-of-day fog shaping
- Rain fog and cave fog access from the custom menu
- Lower fog start height in themed presets like `Dark Fog Forest`

The `Dark Fog Forest` theme specifically was tuned to feel more enveloping, closer in spirit to the End's oppressive air volume, but adapted for the Overworld and still playable at night.

## In-Shader Controls

The custom `AuroralisStar by Jack` menu exposes fast-access controls for the fork's artistic identity:

- Aurora settings
- Fog controls
- Color grading
- Tonemapping
- Flashlight
- Selection box styling
- Scene controller
- Bloom
- Sharpening
- White balance
- Saturation
- Crosstalk

This makes it much easier to push the shader toward fantasy, horror forest, dreamy haze, or cleaner cinematic looks without digging through the entire original menu structure.

## Recommended Loader And Mod Setup

AuroralisStar should be treated primarily as an Iris-oriented shader pack.

Recommended setup:

- `Iris + Sodium`
  Best default choice for most players
- `Iris Installer`
  Easiest way to get a working shader setup quickly

Also possible:

- `Oculus`
  Useful if you specifically play on Forge and need an Iris-style shader loader there
- `OptiFine`
  Some shader packs in this family are designed around compatibility with OptiFine-style packs, but this fork is developed and organized with Iris in mind first

Practical recommendation:

- If you want the most predictable experience, use `Iris + Sodium`
- If you are on a Forge-based modpack and need shader support, try `Oculus`
- Do not install `OptiFine` together with `Iris`

## Testing Notes

For this fork, the expected testing path is:

- Minecraft Java Edition
- Iris as the primary shader loader
- Sodium for rendering performance
- Hardware-specific profile selection inside the shader menu

When checking performance or visuals, test with:

- your target resolution
- your real render distance
- the biome or scene you care about most
- the exact preset you plan to use long-term

The `Dark Fog Forest` preset in particular should be tested in forest-heavy biomes because its fog shaping is intentionally stronger than the general presets.

## Variants Included

### `laptop-mx450/`

Performance-first branch intended for systems like the MX450.

Focus:

- Better FPS stability
- Lower-cost atmosphere
- Reduced heavy features where needed
- Retained identity of the fork without overloading weaker hardware

### `desktop-rtx4060/`

Higher-quality branch intended for stronger desktop GPUs like the RTX 4060.

Focus:

- Denser fog
- Better cloud presence
- Stronger auroras
- Higher shadow quality
- More cinematic grading and atmosphere

## Language Layer

AuroralisStar includes a visible Spanish-facing layer for the fork's main controls and presentation so the custom profiles and menu identity feel more personal and accessible.

## Credits

AuroralisStar does not erase its lineage.

This fork builds on:

- Eclipse Shader by Merlin1809
  https://github.com/Merlin1809/Eclipse-Shader
- Bliss Shader by X0nk
  https://github.com/X0nk/Bliss-Shader
- Chocapic13
  Historical shader base credited by the upstream projects

More attribution details are available in [CREDITS.md](./CREDITS.md).

## Repository Structure

- `laptop-mx450/`
  Laptop-focused shader variant
- `desktop-rtx4060/`
  Desktop-focused shader variant

## Status

AuroralisStar is currently an actively customized fork focused on visual identity, atmospheric presets, and ongoing experimentation.

This repo is the home for those changes as they keep evolving.
