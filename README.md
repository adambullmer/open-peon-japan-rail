# OpenPeon - Japan Rail 🚄

A [CESP](https://openpeon.com)-compliant sound pack for [OpenPeon](https://openpeon.com) featuring authentic Japanese train station jingles and public address announcements.

## Description

Step onto the platform and let your coding sessions run on the Yamanote Line. This pack brings the iconic soundscape of Japanese rail travel to your agentic IDE with departure melodies, arrival chimes, gate beeps, and platform safety warnings all mapped to your AI assistant's event lifecycle.

Whether you're waiting for a tool call to complete or watching a task run off the rails, Japan Rail keeps you on schedule.

## Installation

Install via the [OpenPeon registry](https://openpeon.com) or manually:

1. Download or clone this repository.
2. Point your OpenPeon-compatible player at the directory containing `openpeon.json`.

## Supported Categories

| Category           | # Sounds | Description                                                    |
| ------------------ | -------- | -------------------------------------------------------------- |
| `session.start`    | 3        | Platform announcements played when a session opens             |
| `task.acknowledge` | 10       | Departure melodies played when a task is accepted and begins   |
| `task.complete`    | 3        | Arrival announcements played when a task finishes successfully |
| `task.error`       | 6        | Warning and trouble announcements played on failure            |
| `task.progress`    | 2        | Train-rolling ambience for long-running tasks                  |
| `input.required`   | 4        | Ticket gate chimes played when user input is needed            |
| `user.spam`        | 2        | Train screeching played when requests come in too fast         |

## Sound Details

### `session.start`

- Doors are closing announcement
- Train will depart shortly announcement
- Thank you for waiting announcement

### `task.acknowledge`

- Akabaneiwabuchi Departure Melody
- Akasakamitsuke Rain Shower Melody
- Asakusa Departure Melody
- Tokyo Train Station Departure Melody 6
- Akihabara Departure Melody
- Chikatetu Narimasu Departure Melody
- Edogawabashi Departure Melody
- Fuchu Bunbunbun Departure Melody
- Fujisawa Departure Melody
- Ginza Itchome Departure Melody 2

### `task.complete`

- Next stop is Tokyo announcement
- Terminal station Tokyo announcement
- We have arrived announcement

### `task.error`

- Stand behind the yellow line warning
- Dangerous rushing announcement
- Sudden stop warning announcement
- Trouble occurred announcement
- Train crossing bell (Voice/Onomatopoeia)
- Actual train railroad crossing chime

### `task.progress`

- Train rolling on tracks (Voice/Onomatopoeia)
- Train rolling on tracks (Clickety Clack / Gatan Goton)

### `input.required`

- Ticket gate chime 1
- Please touch your IC card announcement
- Please charge card announcement
- Train crossing intro

### `user.spam`

- Train screeching (Voice/Onomatopoeia)
- Actual train braking/screeching

## Copyright

The sounds in this pack are authentic recordings from Japanese railway operators (including JR East and Tokyo Metro). Copyright remains with the respective railway companies. This pack is an unofficial fan project with no claim of ownership over the audio content.

## Credits

- [Tokyo Train Station Departure Sounds](https://soundcloud.com/user-188398066/sets/tokyo-train-station-departure-sounds) via SoundCloud
- Original recordings &copy; respective Japanese railway operators
