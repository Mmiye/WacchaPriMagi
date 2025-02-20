# Party Ranking Sorter

This project is a simple single-page application template that allows users to rank songs from a list by comparing them in duels.

## Project Structure

```
party-ranking-sorter-template/
├── index.html
├── style.css
├── script.js
├── songList.json
└── README.md
```

## Features

- Autosave to the local storage after each duel.
- Can load saved result or show final result if sorter was previously completed.
- Options for choosing between mp3 and video files when sorting
- Region selection for catbox links (EU, NA1, NA2)

## Setting Up a Custom Sorter

To set up a custom sorter for your specific party ranking, follow these steps:

1. **Update `songList.json`:**
   - Replace the content of `songList.json` with your own list of songs. Each song should have an `id`, `anime`, `name`, `video`, and optionally an `mp3` field.
   - Example:
     ```json
     [
         {
             "id": 1,
             "anime": "Your Anime Title",
             "name": "Your Song Name",
             "video": "https://your-video-url.com",
             "mp3": "https://your-mp3-url.com"
         },
         {
             "id": 2,
             "anime": "Another Anime Title",
             "name": "Another Song Name",
             "video": "https://another-video-url.com",
             "mp3": "https://another-mp3-url.com"
         }
     ]
     ```

2. **Optionally Update the Title in `index.html`:**
   - Open `index.html` and change the content of the `<title>` tag to match your custom sorter.
   - Example:
     ```html
     <title>Your Custom Party Rank Sorter</title>
     ```