# streamwall-assets
High-quality streaming network wallpapers for media dashboards — (Networks/Production Studios) Netflix, HBO, Disney+, Apple TV+ and more. High Quality.

# StreamWall Assets

A collection of cinematic wallpapers for streaming networks and movie studios,
designed for use in media hubs like Nuvio, Plex, Jellyfin, Infuse, and any app
with custom background support.

All wallpapers feature a tilted grid of show/movie artwork with a dark gradient
vignette — inspired by the Apple TV+ aesthetic.

## Available Networks

| Network | 1080p | 4K |
|---|---|---|
| Netflix | ✓ | ✓ |
| HBO / Max | ✓ | ✓ |
| Apple TV+ | ✓ | ✓ |
| Disney+ | ✓ | ✓ |
| Amazon Prime | ✓ | ✓ |
| ... | | |

## Usage

Download any wallpaper directly via raw URL

Or clone the whole pack:
```bash
git clone https://github.com/bramst0ne/streamwall-assets
```

## File Structure

streamwall-assets/
├── netflix/
│   ├── netflix_1080p.jpg
│   └── netflix_4k.jpg
├── hbo/
│   ├── hbo_1080p.jpg
│   └── hbo_4k.jpg
...

## Generate Your Own

Wallpapers are generated with [wallpaper.py](tools/wallpaper.py), a Python script
using the TMDB API. You need a free TMDB API key.

```bash
pip install Pillow requests
python3 wallpaper.py --network netflix
```

See the script header for full usage instructions.

## Credits

- Artwork data from [TMDB](https://www.themoviedb.org/) and [Fanart.tv](https://fanart.tv/)
- Generated with wallpaper.py

## License

Images are sourced from TMDB and Fanart.tv. Rights belong to their respective
studios and distributors. This repository is for personal and non-commercial use only.
