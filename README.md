# Word Pebble card library

Flashcard images for Word Pebble, a vocabulary trainer for a child learning
English, displayed on an M5StickS3 (Muse Gadget) via its display command.

- `cards/<word>-<level>.jpg`: 270x480 baseline JPEG. The word in amber on a
  near-black background, its part of speech, and its Leitner level (0-4) as a
  row of five dots.
- 120 words x 5 levels = 600 images. Generated locally by a small Python
  script (PIL) from a fixed word bank; no personal data.
- `index.json` lists the base URL and the word list. The stick fetches a card
  directly from the raw GitHub URL, nothing is uploaded at run time.
