# Pipeline: from footage to a posted reel

1. **Source.** Twitch VOD, YapZ recording, fractal call, phone clip. Download to the work folder (not in this repo).
2. **Transcript.** whisper.cpp locally. Read the transcript, mark 3 to 5 moments with timestamps. A moment is one idea that stands alone in under 90 seconds.
3. **Cut.** ffmpeg, vertical 1080x1920, the speaker centred, captions burned in (white, bottom third, 2 lines max). No logo wall, no AI label, no watermark. Two threads on this PC so it stays cool.
4. **Caption.** Line one says the subject in plain words. Two to three lines max. 3 to 5 hashtags. Tag everyone in it.
5. **Review.** Zaal sees the cut and the caption before it posts. One message, reel plus caption.
6. **Schedule.** Meta Business Suite (free, from the Instagram business login) schedules reels and carousels up to 75 days ahead. Stories post from the phone.
7. **Post time.** When Zaal can answer comments for an hour. Default 12:00 ET.
8. **Log.** Add a row to `log/YYYY-MM.md`: date, pillar, source, link, then after 48 h: views, shares, saves, comments, new followers.

## Who does what

| Step | Who |
|---|---|
| Pick moments, cut, caption | IMan (Feliq from Sunday if the collab lands) |
| Review and yes | Zaal |
| Stories, comments, Lives | Zaal from the phone |
| Weekly log and the Sunday review | IMan |
