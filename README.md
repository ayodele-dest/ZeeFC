# Fashion Connect Hot Takes

A self-contained local website with a selection homepage and two interactive presentation decks.

## Run locally

From the project directory:

```powershell
python -m http.server 4173 --directory dist
```

Then open `http://localhost:4173`.

## Controls

- Left and right arrows: change slide
- N: toggle presenter notes
- F: toggle slide fullscreen
- Escape: return to the homepage when not fullscreen

No build step or internet connection is required.
