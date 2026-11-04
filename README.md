# BeanRow Partner for macOS and Windows

Downloads for the BeanRow Partner desktop app. Open the
[latest release](https://github.com/beanrowDev/beanrow-desktop-release/releases/latest)
and download the file for your computer:

| Computer                          | File                                      |
| --------------------------------- | ----------------------------------------- |
| Mac with Apple chip (M1 or later) | `BeanRow-Partner-<version>-arm64.dmg`     |
| Mac with Intel chip               | `BeanRow-Partner-<version>-x64.dmg`       |
| Windows 10 or 11                  | `BeanRow-Partner-Setup-<version>-x64.exe` |

Not sure which Mac you have? Apple menu → **About This Mac**. "Chip: Apple M…"
means Apple chip; "Processor: Intel" means Intel.

The app opens on the sign-in page. Sign in with your email or Employee ID.

## Opening it the first time

The app isn't code-signed yet, so your computer warns you before it opens.

**Mac**

1. Open the `.dmg` and drag **BeanRow Partner** into **Applications**.
2. Open the app. macOS says it can't check the app; click **Done**.
3. Go to System Settings → **Privacy & Security**, scroll down, and click
   **Open Anyway** next to BeanRow Partner. Confirm with your password.

**Windows**

1. Run the `Setup` file.
2. If Windows shows "Windows protected your PC", click **More info**, then
   **Run anyway**.

You only do this once.

## Updates

- **Windows:** the app updates itself. A new version installs when you quit
  the app, overnight on an idle computer, or from Help → **Restart to update**.
- **Mac:** the app can't update itself yet. When a new version comes out,
  quit BeanRow Partner, download the new `.dmg` from the
  [latest release](https://github.com/beanrowDev/beanrow-desktop-release/releases/latest)
  and drag it into Applications again, replacing the old app. Your printer
  settings stay.

To see which version you have: Help → **About & diagnostics**.

The other files in each release (`.zip`, `.yml`, `.blockmap`) are used by the
app's automatic updates. You don't need to download them.

Help: support@beanrow.com
