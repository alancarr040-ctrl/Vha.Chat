# Vha.Chat

Vha.Chat is a standalone Windows chat client for **Anarchy Online**, originally developed by [Vhab](https://github.com/Vhab).

This repository is a community fork of the original [Vha.Chat project](https://github.com/Vhab/Vha.Chat), preserving the existing application while introducing optional improvements.

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

<img width="1920" height="1032" alt="vha chat darkmode" src="https://github.com/user-attachments/assets/b70fe5c4-27ad-4cd4-956b-20f8977ad8ce" />

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

Further development of this fork will depend on community interest,
