# D-word

Free Danish vocabulary trainer for Modul 4 and Prøve i Dansk 3 (PD3) reading.

- About 4,000 Danish words with English meanings
- A Danish example sentence with English translation for every word
- Study mode with simple spaced repetition (Again, Hard, Easy, Back, Next)
- True/false Test mode and a timed 20-word Quiz
- Danish to English and English to Danish
- Search, favorites, word lists, pronunciation, dark mode
- Works offline after loading; progress is saved in the browser only

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app, including all words |
| `privacy.html` | Privacy page linked in the footer |
| `favicon.svg` | Browser tab icon |
| `README.md` | This description |
| `robots.txt` | Asks search engines not to crawl the site |

## Updating the word list

Open `index.html`, find `const vocabulary = [` and replace the lines up to `];`.
The built-in common and news words are in a separate block (`builtInVocabulary`) and stay in place.

## Owner view

Add `#admin` to the end of the address to see detailed statistics and the built-in word switch.

## Search engines

`index.html` and `privacy.html` contain `<meta name="robots" content="noindex, nofollow, noarchive">`, so the site is kept out of search results. Remove that line from both files to allow indexing.
