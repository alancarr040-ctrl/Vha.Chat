# Vha.Chat

Vha.Chat is a standalone Windows chat client for **Anarchy Online**, originally developed by [Vhab](https://github.com/Vhab).

This repository is a community fork of the original [Vha.Chat project](https://github.com/Vhab/Vha.Chat), preserving the existing application while introducing optional improvements.

## Dark Mode — Available on Feature Branch

The optional Dark-mode implementation is currently available on the [`feature/dark-mode`](https://github.com/alancarr040-ctrl/Vha.Chat/tree/feature/dark-mode) branch.

The default master branch retains the original application while the changes are under review by the original developer.

To build or examine the Dark-mode version, use the feature branch rather than master.

The changes have been submitted upstream as [Pull Request #15 — Add optional Dark theme support](https://github.com/Vhab/Vha.Chat/pull/15).

## What's New in This Fork?

### Optional Dark Mode

This fork introduces an optional Dark theme for Vha.Chat.

Features include:

- Light and Dark theme selection under **Options → Appearance**
- Persistent theme preferences across application restarts
- Dark styling for the main chat window and supporting windows
- Dark-themed chat output, dropdown controls, and supported Windows title bars
- Preservation of the original Light theme

**Light remains the default.** Users who prefer the original appearance do not need to change anything.

## Screenshots
<p align="center">
  <img src="https://github.com/user-attachments/assets/b70fe5c4-27ad-4cd4-956b-20f8977ad8ce"
       alt="Vha.Chat Dark Mode"
       width="49%" />
  <img src="https://github.com/user-attachments/assets/31247fbf-834e-4c86-8aa5-136287ab913d"
       alt="Vha.Chat Light Mode"
       width="49%" />
</p>

## Building from Source

Vha.Chat is a Windows application targeting **.NET Framework 4.7.2**.

The fork has been successfully built using Visual Studio 2026 Community and MSBuild.

To build the Release configuration, open `Solution.sln` in Visual Studio or run:

```powershell
MSBuild.exe Solution.sln -restore -t:Build -p:Configuration=Release -m
```

The resulting application executable is located at:

`Vha.Chat/bin/Release/net472/Vha.Chat.exe`

## Development Status

The optional Dark-mode implementation is available on the [`feature/dark-mode`](https://github.com/alancarr040-ctrl/Vha.Chat/tree/feature/dark-mode) branch.

The changes have also been submitted to the original project for consideration:

[Pull Request #15 — Add optional Dark theme support](https://github.com/Vhab/Vha.Chat/pull/15)

Further development of this fork will depend on community interest, compatibility requirements, and future maintenance decisions.

## Original Project and Credits

**Original application:** [Vhab/Vha.Chat](https://github.com/Vhab/Vha.Chat)

**Original developer:** Remco van Oosterhout (Vhab)

**Dark-mode contribution:** Alan Carr ([alancarr040-ctrl](https://github.com/alancarr040-ctrl))

Vha.Chat and its related libraries have benefited from contributions by multiple developers over the years. The original contributor acknowledgments, library credits, and licensing notices have been preserved.

See [Vha.Chat/Credits.txt](Vha.Chat/Credits.txt) for the original acknowledgments.

Anarchy Online and its associated trademarks belong to their respective owners. This fork is an independent community contribution and is not affiliated with or endorsed by Funcom.

## License

Vha.Chat is distributed under the GNU General Public License, version 2 only (GPL-2.0-only), as specified in the original source-code notices.

The original license text is available in [Vha.Chat/License.txt](Vha.Chat/License.txt).

Original copyright notices and third-party licensing terms are preserved, including the separate notices applicable to the Starksoft.Net.Proxy library.

Modifications introduced by this fork are distributed under the applicable GPL terms.
