# WowUp Flatpak

Unofficial [Flatpak](https://flatpak.org/) of the [WowUp](https://wowup.io/) app (CurseForge variant).

This repo will be maintained until the WowUp team launches their own official Flatpak on [Flathub](https://flathub.org).

## Installation

*1. Add the repository*

	flatpak remote-add --if-not-exists wowup https://p3lim.github.io/wowup-flatpak/index.flatpakrepo

*2. Install*

	flatpak install wowup io.wowup.WowUp

*3. Run*

	flatpak run io.wowup.WowUp

Once installed it can be updated with `flatpak update`.
