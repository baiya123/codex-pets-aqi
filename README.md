# Codex Pets - Ranger

[中文说明](README.zh-CN.md)

This repository contains **Ranger**, an original blue-and-gold rescue pup mascot for Codex pets.

## Preview

![Ranger contact sheet](qa/ranger/contact-sheet.png)

| Idle | Waving | Waiting |
| --- | --- | --- |
| ![Idle preview](qa/ranger/previews/idle.gif) | ![Waving preview](qa/ranger/previews/waving.gif) | ![Waiting preview](qa/ranger/previews/waiting.gif) |

| Running Right | Running Left | Review |
| --- | --- | --- |
| ![Running right preview](qa/ranger/previews/running-right.gif) | ![Running left preview](qa/ranger/previews/running-left.gif) | ![Review preview](qa/ranger/previews/review.gif) |

## Install

Copy the `pets/ranger` folder into your Codex pets directory:

```powershell
Copy-Item -Recurse -Force .\pets\ranger $env:USERPROFILE\.codex\pets\ranger
```

Then restart Codex or reload the pet picker and choose `Ranger`.

## Files

- `pets/ranger/pet.json` - Codex pet manifest
- `pets/ranger/spritesheet.png` - validated 9-state sprite atlas
- `qa/ranger/contact-sheet.png` - visual contact sheet
- `qa/ranger/previews/*.gif` - per-state animation previews
- `qa/ranger/validation.json` - atlas validation result

## States

- `idle` - standing by
- `running-right` - drag/move right
- `running-left` - drag/move left
- `waving` - greeting
- `jumping` - jump response
- `failed` - blocked or failed
- `waiting` - waiting for input
- `running` - active task processing
- `review` - reviewing output
