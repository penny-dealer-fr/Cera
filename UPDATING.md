# Updating Cera

Cera currently updates manually. Download the newest preview from [GitHub Releases](https://github.com/penny-dealer-fr/Cera/releases). Choose Apple silicon Mac, Intel Mac, or Windows x64 as appropriate.

Your candle, deeds, and unlocks are saved separately from the application. Replacing the application keeps that progress.

## macOS

1. Quit Cera, including any older copy that is still running.
2. Download and extract the new ZIP.
3. Drag the new **Cera.app** into **Applications**, replacing the previous Cera.
4. Open Cera from Applications. Keep just one normal Cera app so you always launch the updated copy.

The Mac previews are signed with Apple Development and are not notarized. macOS may ask you to approve opening the app.

## Windows

1. Quit Cera.
2. Download the new Windows ZIP and extract it into a new folder.
3. Replace the old application folder with the complete new folder. Keep its supporting files together; replacing only Cera.exe is insufficient.
4. Run Cera.exe. Update any shortcut that still points to the previous folder.

The Windows preview is unsigned.

## Keeping your progress

Do not delete Cera's saved application data when updating:

- **macOS:** `~/Library/Application Support/cera-un-pomodoro/`
- **Windows:** `%APPDATA%\cera-un-pomodoro\`

You can make a copy of that folder after quitting Cera as a precaution. Normal and development builds can use different profiles; changing which build you open does not merge their saved progress.

There is no automatic update checker or update notification yet. Check the release page for new versions.
