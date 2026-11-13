# Switch between Cera and Cera Lite

[Cera Lite is the recommended download](https://github.com/penny-dealer-fr/Cera/releases/latest). It has the same candles, Hall, seasons, connectors, and progression as Cera, with a lower-power renderer. Both editions use one profile per computer login.

[Apple Silicon preview with terminal support](https://github.com/penny-dealer-fr/Cera/releases/tag/v0.2.6-preview.1)

## Cera → Cera Lite

1. Quit Cera if you're coming from 0.1.3 or earlier.
2. Download Cera Lite for your platform. On macOS, move **Cera Lite.app** into Applications. On Windows, extract it to its own folder and open **Cera Lite.exe**.
3. Open Cera Lite. Your current candle, pins, Hall, unlocks, and settings are already there. A normal lit candle continues burning while you switch.

## Cera Lite → Cera

1. Install or update **Cera** to 0.2.0 or later. Use **Cera.app** on macOS or **Cera.exe** in a separate extracted folder on Windows.
2. Open Cera. It takes over the same profile and active candle.

Keep both editions installed if you like. With 0.2.0 or later, opening the other edition closes the current one and passes it the same profile. The Hall and Table reopen on demand. The special purple challenge follows its usual rule when its window closes, so switch after that burn if you want to keep the attempt.

The profile stays on your computer. Replacing an app bundle or an extracted Windows folder leaves it in place. Both editions use `~/Library/Application Support/cera-un-pomodoro` on macOS and `%APPDATA%\cera-un-pomodoro` on Windows. Keep that folder and, on macOS, its Keychain entries. Switch between the current builds so both understand new candle styles.

## Cera Flame, Cera Smoke, and Clear Wax

Flame and Smoke both run alongside either full edition. They each have one white candle, with a duration from 5 minutes to 10 hours and a simple stats popup.

- **Cera Flame** uses Lite’s 3D white candle and brass saucer. Drag the candle’s top to set the duration.
- **Cera Smoke** is the original 2D Flame. It keeps your old Flame candle, pins, settings, and stats automatically. Set the duration with the slider or type the number of minutes. The new 3D Flame has its own stats. If the original 2D Flame is running, quit it before opening Smoke for the first time.

Update Cera or Cera Lite to 0.2.1 or later to receive rewards from both editions. A completed Flame or Smoke burn earns Clear Wax in both full editions. Starting with 0.2.4, each variant has a deed in the Hall of Candles. Existing burn rewards count automatically, and all seven deeds count toward Every Last Thing. The Clear Gold Wax deed can be earned before the gold candle is available.

| Completed Flame or Smoke burn | Clear Wax unlocked |
| --- | --- |
| Under 30 min | White and tea light |
| 30 min to under 1 h | White |
| 1 h to under 3 h | Blue |
| 3 h to under 5 h | Red |
| 5 h to under 10 h | Black |
| 10 h or longer | Purple and gold |

Uncertainty can move a burn into a neighboring band. A short burn still qualifies if it finishes below five minutes because of uncertainty. Purple, tea, and gold variants become selectable once their base candles are unlocked through the usual progression. Both editions share these rewards locally, including ones earned before you install a full edition.

The plate and wick show through Clear Wax with its default settings. To distort the desktop behind the candle, right-click a Clear Wax candle and enable **Refract Desktop (Screen Capture)**. Grant the operating system's Screen Recording permission if prompted. The refraction feed is used locally and stops when you turn it off or switch to another candle appearance.
