# Komal & Dhananjai — Wedding Invitation

10 – 12 December 2026 · MB Garden & Resort, Lucknow

Single-page site. No build step, nothing to install.
Open `index.html` in a browser and it runs.

## Files

```
index.html            everything — markup, styles, scripts
assets/
  godbharai.jpg       Chapter 01 · Godbharai & Rokai
  ring-sangeet.jpg    Chapter 02 · Ring Ceremony & Sangeet
  haldi.jpg           Chapter 03 · Haldi
  tilak.jpg           Chapter 04 · Tilak
  wedding.jpg         Chapter 05 · The Wedding
  vidai.jpg           Chapter 06 · Vidai
  music.mp3           background track
```

Keep `index.html` and `assets/` together — the paths are relative.

## Putting it online

Drag the whole folder onto **Netlify Drop** (app.netlify.com/drop) or
**Cloudflare Pages**. Free, and you get a URL in seconds. Nothing here
needs a server.

## The schedule

| | Ceremony | Day | When |
|---|---|---|---|
| 01 | Godbharai & Rokai | Thu 10 Dec | First half of the day |
| 02 | Ring Ceremony & Sangeet | Thu 10 Dec | Second half of the day |
| 03 | Haldi | Fri 11 Dec | Morning |
| 04 | Tilak | Fri 11 Dec | Evening |
| 05 | The Wedding | Fri 11 Dec | Night |
| 06 | Vidai | Sat 12 Dec | Morning |

Weekdays verified: 10, 11 and 12 December 2026 are Thursday, Friday, Saturday.

## Things you may want to change

**RSVP destination** — search `ENDPOINT`. Posts to Formspree form `mkjwvoql`.
Submit the form once yourself before sharing the link: Formspree keeps a new
form inactive until its first submission, then emails you a confirmation link.
Free tier caps at 50 submissions per month.

**Venue address** — set. Adj. Deen Dayal Upadhyaya Academy, BKT, Bakshi Ka
Talab, Rajapur Indaura, Uttar Pradesh 226202. Verified against the Google
listing (CID 7898981147865056497) that the map pin uses.

**Countdown target** — search `TARGET`. Currently 11 Dec 2026, 9:00 PM IST.
Set it to the actual muhurat time.

**Exact ceremony times** — the chapters currently read "Morning", "Evening",
"Night" and so on. Replace with clock times when they are fixed.

**Image crops** — each chapter panel carries a `--pos` value, e.g.
`--pos:66% 26%`. These are tall portraits with the couple off to one side,
so the crop is tuned per photograph. Nudge the percentages if one sits wrong.
Note that `godbharai.jpg` and `vidai.jpg` are the same photograph with
different crops — swap in a separate image for the Vidai if you have one.

**Music** — replace `assets/music.mp3` to change the track. It starts on the
visitor's first tap (browsers refuse autoplay with sound), crossfades so the
loop does not click, and the toggle sits bottom right. Delete the file and the
button removes itself automatically.

**Ganesha artwork** — the watermark behind the bride and groom names is a
lotus mandala drawn in SVG. Search `class="wm"` to swap in your own file.
