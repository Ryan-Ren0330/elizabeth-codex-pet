# Elizabeth Codex Pets

Two custom Elizabeth pets for the Codex desktop app, based on Elizabeth from *Gintama*.

## Choices

### Elizabeth

The original approved set.

![Elizabeth original contact sheet](preview/original/contact-sheet.png)

### Elizabeth Classic

A second set with classic Elizabeth moments:

- walking in the rain with a red umbrella
- corrected idle eyes with only round-eyed frames and a single blink
- active processing state holding a sign that says 「お待ちください」
- waiting state using the small busy pose
- fixed rounded-head waving with Elizabeth's normal round-eyed expression
- failed/crying state uses round or closed eyes with small tear beads beside the eyes
- wigged Elizabeth holding the 「ヅラじゃない / 桂だ！」 sign

![Elizabeth Classic contact sheet](preview/classic/contact-sheet.png)

中文说明见 [README.zh-CN.md](README.zh-CN.md).

## Install

Clone the repository, then copy the pet folders into your Codex pets folder:

```bash
git clone https://github.com/Ryan-Ren0330/elizabeth-codex-pet.git
mkdir -p ~/.codex/pets
cp -R elizabeth-codex-pet/pets/elizabeth ~/.codex/pets/
cp -R elizabeth-codex-pet/pets/elizabeth-classic ~/.codex/pets/
```

Then open Codex:

1. Go to **Settings > Appearance > Pets**.
2. Choose **Refresh custom pets**.
3. Select **Elizabeth** or **Elizabeth Classic**.
4. Run `/pet` or **Wake Pet** from the command menu.

## Files

- `pets/elizabeth/` contains the original pet package.
- `pets/elizabeth-classic/` contains the second classic-action pet package.
- `preview/original/contact-sheet.png` previews the original set.
- `preview/classic/contact-sheet.png` previews the classic set.

## License

MIT
