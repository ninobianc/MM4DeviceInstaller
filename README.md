# MM4 Device Installer

Installs device plugins (DLLs) into MethodManager4 (MM4) for Dynamic Devices Lynx liquid handlers.

## Download

Get the latest version from the [Releases page](../../releases/latest). Download `MM4DeviceInstaller_v3.0.zip` (or the newest version listed).

## Install

1. Close MethodManager4.
2. Right-click the downloaded zip, choose **Properties**, tick **Unblock** if it's shown, then click **OK**.
3. Extract the zip to a folder, for example your Desktop.
4. Open the extracted folder and run `MM4DeviceInstaller.exe`.
5. Tick the device packages you want and click **Apply**.
6. Restart MethodManager4.

Keep the `Devices` folder next to `MM4DeviceInstaller.exe`. The installer reads its packages from there.

For more detail, see `MM4 Device Installer quick guide.docx` in the zip.

## Requirements

- Windows with .NET Framework 4.8
- MethodManager4 installed in `C:\Program Files (x86)\Dynamic Devices\MethodManager4` or `C:\Program Files\Dynamic Devices\MethodManager4`

## Included packages (v3.0)

| Package | What it does |
|---|---|
| AutoFill | AutoFill pump |
| Better Logic | Extra logic commands for methods |
| BioShake | QInstruments BioShake |
| Custom Dialog | Build custom operator dialogs in a method |
| Exypnos Turn Table | Exypnos turntable |
| Labware Elevator | Labware elevator |
| Linear Slide | Linear slide |
| Lunatic | Unchained Labs Lunatic reader |
| ProtoPress | ProtoPress |
| Stunner | Unchained Labs Stunner |
| Worktable Blink | Shows the worktable and blinks the labware the operator needs to load or check (new in v3.0) |

## Why a download link instead of email?

Gmail and most company mail servers block `.exe` and `.dll` files, even inside a zip. Share the Releases link instead.
