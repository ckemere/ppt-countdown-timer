# PowerPoint Countdown Timer

A content add-in that puts a giant, auto-scaling countdown timer on a slide.

- In a slide show the timer starts by itself (on Mac, clicks there advance the slide instead of reaching the timer). While editing, click the digits to start/pause; hover to see controls (reset, ±1 min, settings).
- Keyboard (after clicking the timer): Space = start/pause, R = reset, ↑/↓ = ±1 minute.
- Settings (duration, colors, warning threshold, overtime, flash, beep, auto-start) are saved per timer in the presentation.

## Install (Mac)

```sh
mkdir -p ~/Library/Containers/com.microsoft.Powerpoint/Data/Documents/wef
cp manifest.xml ~/Library/Containers/com.microsoft.Powerpoint/Data/Documents/wef/
```

Restart PowerPoint, then go to **Home → Add-ins** (or **Insert → My Add-ins**), choose **Countdown Timer**,
and drag or resize the frame however you like.
