# Scarlet Display Studio

Scarlet is a lightweight Windows app for adjusting desktop vibrance, saturation, brightness, contrast, gamma, and color temperature on SDR displays. It works with NVIDIA, AMD, and Intel graphics through documented Windows display APIs.

## Download

Download official builds from [GitHub Releases](https://github.com/silentzaottk/scarlet/releases). Extract the full ZIP to a permanent folder and run `Scarlet.exe`. No installer or administrator rights are required.

## Requirements

- Windows 10 version 1903 or later, or Windows 11, 64-bit
- .NET Framework 4.8
- SDR mode with HDR and Auto HDR disabled
- Borderless or windowed fullscreen for games

## Features

- Six calibrated color controls with exact numeric entry
- Built-in and custom presets
- Shareable `SCARLET1-` preset codes and `.scarlet` files
- Full and compact views, ten themes, and a configurable global shortcut
- Optional Start with Windows
- Automatic crash recovery and display conflict detection
- Optional persistent look after the Scarlet window closes
- Payhip purchase activation with encrypted local license storage
- Optional current-preset memory when Scarlet closes
- Update notifications that open the exact official GitHub release page

## Persistent colors

The setting **Keep my active look after Scarlet closes** is enabled by default. Closing the window keeps an active look on through a sleeping Scarlet helper process. Reopen Scarlet to edit the look, or select **Pause** before closing to restore the original matrix and gamma ramps. Disabling the setting also restores the original colors on exit.

## License, updates and privacy

Enter the key from your Payhip receipt on first launch. One license activates one Windows account. Scarlet sends that key directly to Payhip for activation and refund or revocation checks, stores the local record with Windows user encryption, rechecks at most daily, and allows up to seven days offline after a successful check. Deactivate from Settings before moving the license.

Scarlet also checks this repository's public latest-release endpoint at most once every 24 hours when automatic checks are enabled. It sends no presets, display settings, analytics, or telemetry. The app never downloads or executes an update itself; the update button opens the verified GitHub release page in your browser.

## Display and game safety

Scarlet uses the Windows Magnification fullscreen color effect and display gamma ramps. It does not access game processes, inject code, install drivers, add overlays or hooks, capture the screen, read memory, or generate input. No third-party tool can guarantee how every anti-cheat system or tournament will classify desktop software, so check the rules for organized competition.

## Support

Read the `README.txt` included with every release for setup, troubleshooting, privacy, and uninstall instructions.

For help, join the [Scarlet Discord](https://discord.gg/edCsjWJcY) and open a ticket.

## Source availability

This is a release-only repository. Scarlet's proprietary source code is not published here.
