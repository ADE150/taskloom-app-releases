# TaskLoom App releases

Compiled app artifacts only. The app source is private.

- Windows: `TaskLoom.exe` (Tauri, WebView2 required; Windows 10/11)
- Android: `TaskLoom.apk` (Android 10+, API 29+)
- Web: https://aix150.com/taskloom/
- iOS: no prebuilt binary yet; build from source on macOS/CI.

## Windows

Download `TaskLoom.exe` from the latest release and run it. First launch asks for a
workspace folder; you can also run:

```bat
TaskLoom.exe --workspace "C:\path\to\vault"
```

## Android

Download and install `TaskLoom.apk`. It uses an app-private workspace by default;
use the Sync dialog to connect to `https://aix150.com/taskloom-api`.

## License

Proprietary; see `LICENSE`. Binaries may be installed for personal use.
