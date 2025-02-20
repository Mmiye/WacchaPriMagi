# Anime Song Party Ranking Sorter Template

This is a template sorter for anime song party rankings. To adjust it for your party ranking, add JSON objects of songs. Below is an example of how a JSON model of a song looks like:

```json
{
    "title": "Song Title",
    "artist": "Artist Name",
    "audio": "audio_link.mp3",
    "video": "video_link.mp4",
    "catbox_region": "region_code"
}
```

You can also adjust the title inside the head of the main `index.html` document.

The sorter supports switching between audio and video (fallback to video if audio is null) and can switch Catbox regions for Catbox links.

Credit goes to FlatoItou for making a nice rehauled UI of the old sorter.