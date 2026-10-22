# OpenPatAndMat
PseudoAPI with Pat & Mat (A je to! / Sąsiedzi) episodes.

# Source
Slovak version of the "A je to!" (Czech-Slovak animation) series. Contains 130 episodes in `.mp4` format.

# How to use?
The `data.json` file contains a full episode index with:
- `num` - episode number (1-130)
- `sk` - title in Slovak
- `url` - path to the file relative to the project directory

Example entry:
```json
{ "num": 1, "sk": "Kutaci", "url": "data/001 Kutaci.mp4" }
```

The MP4 files are located in the `data/` folder.
