# TR LAB (beta)

Every kit and pattern on your Roland TR-8S, laid out on your Mac.

TR LAB shows all 128 kits and 128 patterns at once. Move, copy and rename them like files, turn a folder of samples into a kit, and edit a kit's sound and a pattern's steps from the Mac. Nothing is written until you save, and every save backs up first and reads every byte back.

**[Download for Mac](https://github.com/pedrosepedrose/tr-lab/releases/latest/download/TR-8S-Lab-mac.zip)** · macOS 11+ · tested on Apple Silicon · needs a TR-8S on firmware 3.00, connected by USB

This is a beta, testing with friends. A page on tools.doralicedoralice.com is coming.

## Installing

1. Unzip the download and drag **TR LAB** into **Applications**.
2. Open it from Applications. macOS will say it can't verify the app. Click **Done**.
3. Open **System Settings › Privacy & Security**, scroll down to the message about TR LAB, and click **Open Anyway**.
4. Quit Roland's TR Editor if it's open: it holds the TR-8S's USB ports.
5. Connect the TR-8S by USB. The welcome guide opens; press **Back up now** before you change anything.

Steps 2 and 3 are only needed once, because this early build isn't notarized by Apple yet. To practise first, turn on **Safe mode** in the TR-8S menu: only kits 127–128 and patterns 8-01–8-16 can be written.

The zip also holds **TR-8S Lab Link**, a Max for Live device that switches the TR-8S's pattern and kit from Ableton Live scene names.

## Privacy

The app talks to your TR-8S over USB and nothing else: no account, no analytics, nothing sent to Doralice. Backups stay on your Mac, in `~/Library/Application Support/TR8S Lab/backups`.

## Feedback

Open an issue here, or tell Pedro.

---

Made by Pedro at [Doralice](https://doralicedoralice.com). Not made by, affiliated with or endorsed by Roland. This repository hosts releases only.
