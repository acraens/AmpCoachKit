# AmpCoachKit

Free browser tools for coaches of crutch-based amputee football (7v7, 60 x 40 m pitch).

**Status: v0 prototype, seeking coach feedback.** One tool exists so far; a training session builder is planned and not built.

## What works now: tactics board

Open `index.html` in any current browser. No install, no account, no dependencies.

- Pitch drawn to the WAFF Laws of the Game measurements, with 7v7 tokens (goalkeeper plus 6 outfield players) and an optional opponent team.
- Run arrows and pass arrows, multiple frames per play, animated playback with optional looping.
- Play cards: name, situation (kick-in, corner, free kick and others), per-role notes, source, and a review status (unreviewed or reviewed by another coach).
- A library on your own device, with JSON export and import, and PNG export of a frame.

## Privacy

Plays are stored in your browser's local storage on your own device. The page makes no network requests. A play leaves your device only if you export a file and choose to send it to someone. Use role labels only. Do not put player names, injuries or private club details in the notes.

## Known limits

- **Rules reference is unverified.** The in-page rules summary was produced by an automated reader from two WAFF Laws of the Game PDFs and has not been checked against the PDFs by a person. The two versions disagree on substitutes (5 in the 2017 version, 6 in a later upload) and squad size (15 on the roster with 12 dressed, or 13 maximum). Check the current WAFF Laws for your competition.
- **Penalty area is not drawn.** Law 9 mentions it, but neither PDF text gives its size.
- **Tested:** drag, arrows, frames, save, reload, JSON and PNG export, and a malformed import, in headless Chrome on desktop. Mobile layout width checked at 390 px.
- **Not tested:** real phones and tablets, Firefox, Safari, and the in-between positions during animation. There is no offline install (PWA) yet.
- No tactical or training content is shipped. Plays are whatever coaches draw. Anything about player load, fatigue or crutch strain needs review by a physiotherapist, not a coach.

## Sharing feedback

Send exported plays and feedback to ampfootballfit@tutanota.com.

## Planned

- Training session builder (session length, team level, players present, space), based on published amputee football training literature and coach contributions.
- Dutch and English interface.
- Offline install (PWA).

## Licence

MIT, see `LICENSE`.
