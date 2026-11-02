# Stillwater

A private, single-page companion for leaving lust behind, one calm day at a time.

- Day counter with milestones and a daily pledge
- Urge rescue: rate the urge, breathe, ground yourself, move, and read your own note
- Progress calendar, triggers, time-of-day patterns, and how urges fade
- Toolkit: if-then plans, safeguards, a trusted person, and a note to yourself
- Optional PIN lock

## Privacy

Everything is stored in your browser's local storage on your own device. There is no account,
no server, and no tracking. Clearing site data erases your progress, so use
**Settings → Copy my data** now and then, and **Restore from copied data** to bring it back.

## Run it

It is plain HTML, CSS and JavaScript with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publish on GitHub Pages

1. Put these files at the top level of a repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

On a phone, open that address and use **Add to Home Screen** to install it like an app.
