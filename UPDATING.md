# Switch between Cera and Cera Lite

[Cera Lite is the recommended download](https://github.com/penny-dealer-fr/Cera/releases). It has the same candles, Hall, seasons, connectors, and progression as Cera, with a lower-power renderer. Both editions use one profile per computer login.

## Cera → Cera Lite

1. Quit Cera if you're coming from 0.1.3 or earlier.
2. Download Cera Lite for your platform. On macOS, move **Cera Lite.app** into Applications. On Windows, extract it to its own folder and open **Cera Lite.exe**.
3. Open Cera Lite. Your current candle, pins, Hall, unlocks, and settings are already there. A normal lit candle continues burning while you switch.

## Cera Lite → Cera

1. Install or update **Cera** to 0.2.0 or later. Use **Cera.app** on macOS or **Cera.exe** in a separate extracted folder on Windows.
2. Open Cera. It takes over the same profile and active candle.

Keep both editions installed if you like. With 0.2.0 or later, opening the other edition closes the current one and passes it the same profile. The Hall and Table reopen on demand. The special purple challenge follows its usual rule when its window closes, so switch after that burn if you want to keep the attempt.

The profile stays on your computer. Replacing an app bundle or an extracted Windows folder leaves it in place. Both editions use `~/Library/Application Support/cera-un-pomodoro` on macOS and `%APPDATA%\cera-un-pomodoro` on Windows. Keep that folder and, on macOS, its Keychain entries. Switch between the current builds so both understand new candle styles.

## Cera Flame and Clear Wax

Cera Flame runs alongside either edition. It keeps its own candle and stats. Fully burn a Flame candle and its actual burn duration earns Clear Wax in both full editions under the matching candle's appearance picker.

| Completed Flame burn | Clear Wax unlocked |
| --- | --- |
| Under 30 min | White and tea light |
| 30 min to under 1 h | White |
| 1 h to under 3 h | Blue |
| 3 h to under 5 h | Red |
| 5 h to under 10 h | Black |
| 10 h or longer | Purple and gold |

Uncertainty can move a burn into a neighboring band. A short burn still qualifies if it finishes below five minutes because of uncertainty. Purple, tea, and gold variants become selectable once their base candles are unlocked through the usual progression. Flame shares these rewards locally, including ones earned before you install a full edition.

The plate and wick show through Clear Wax with its default settings. To distort the desktop behind the candle, right-click a Clear Wax candle and enable **Refract Desktop (Screen Capture)**. Grant the operating system's Screen Recording permission if prompted. The refraction feed is used locally and stops when you turn it off or switch to another candle appearance.
