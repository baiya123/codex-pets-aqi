# Codex Pets - Ranger

This repository contains **Ranger**, an original blue-and-gold rescue pup mascot for Codex pets.

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
