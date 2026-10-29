# Smart Policy Assistant

A simple chat-style assistant that answers questions from a library of policies.

## Run
Open `index.html` in any browser. No installation or server needed.

## Customise
- Edit the `SAMPLE` array in `index.html` to add your own policies.
- Or use the "Add a policy" panel in the app (saved in your browser).

## How it works
Keyword search with simple stemming, synonyms and TF-IDF-style scoring.
Matches in a section heading are weighted higher than matches in the body.
