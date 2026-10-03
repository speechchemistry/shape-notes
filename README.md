# shape-notes
Software associated with coloured shape notes for music. The shape notes use the popular Aikin convention to show tonic solfa. Colours are based on the circle of fifths and are optimised for colour blindness.

For now I've made the Wicki–Hayden multi-touch keyboard available at [https://speechchemistry.github.io/shape-notes/major_notes_with_touch_online.html](https://speechchemistry.github.io/shape-notes/major_notes_with_touch_online.html) .

## Options

Settings go in the page address rather than on screen, so they stay out of the way (and out of reach of curious fingers). Add them after a `?`, joined with `&`.

| Option | Values | Default | Effect |
|---|---|---|---|
| `start` | A note name such as `C3`, `D3`, `Eb3`, `Fs2` | `C3` | Pitch of the bottom-left *do* hexagon. Middle C is `C4`. Write sharps with `s` (`Fs2`), because `#` has a special meaning in web addresses. Unrecognised values fall back to `C3`. |
| `sustain` | `on` | off | Off: a note sounds only while it's being touched. On: like a piano's sustain pedal, each note rings for about 4 seconds after it's played. |

Examples:

- [Start on D3](https://speechchemistry.github.io/shape-notes/major_notes_with_touch_online.html?start=D3)
- [Start on G2 with sustain](https://speechchemistry.github.io/shape-notes/major_notes_with_touch_online.html?start=G2&sustain=on)

The work relies on the shapes defined in Musescore, and makes use of the WebAudioFontPlayer.js . This is why the license is GPL.
