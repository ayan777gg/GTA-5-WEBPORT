# GTA V Browser Port — Mac & Windows

Run this unofficial GTA V browser port locally on your computer.

DOWNLOAD HERE 👇
https://mega.nz/file/RQwnBQKL#zuC0SvBqDmSrmgoIKtQnGkcismyoy8XeDmIVzTATXbA

The game runs using your computer’s hardware. Performance depends on your processor, graphics hardware, and available memory.

## Requirements

- A Mac or 64-bit Windows PC.
- A recent version of Google Chrome or Microsoft Edge with WebGPU support.
- Browser hardware acceleration enabled.
- A compatible graphics processor.
- 16 GB RAM recommended. Lower-memory computers have not been tested with this package.
- Around 22 GB of storage for the extracted game.
- Around 45 GB of free space before downloading if keeping both the ZIP and extracted files.

### Python

- Windows: A Python runtime is included. No separate Python installation is needed.
- Mac: Python 3 is required. The launcher uses `/usr/bin/python3`.
- The Mac setup was tested with Python 3.9.6.

## Download and Extract

### Single ZIP download

1. Download `GTA5.zip`.
2. Extract it completely.
3. Open the extracted `GTA5` folder.

Do not launch the game from inside the ZIP.

### Multiple ZIP download

1. Download all 13 `GTA5-Mac-part-XX-of-13.zip` files.
2. Download `Extract-All-Mac.zip` and `SHA256SUMS.txt`.
3. Keep all these files in the same folder.
4. On Mac, unzip `Extract-All-Mac.zip`.
5. Put `Extract-All-Mac.command` alongside the 13 game ZIPs.
6. Double-click it to verify and extract the files into one `GTA5` folder.

On Windows, extract all 13 game ZIPs into the same destination, merging the GTA5 folders.

All 13 parts are required.

## Play on Mac

1. Open the `GTA5` folder.
2. Double-click `Play GTA5.command`.
3. Keep the Terminal window open while playing.
4. The launcher opens Google Chrome if it is installed.

To stop the server, select its Terminal window and press Control-C.

### If the Mac launcher cannot find Python

Open Terminal in the GTA5 folder and run:

    python3 launch_mac.py

If that command cannot find Python either, install Python 3 first.

## Play on Windows

1. Open the `GTA5` folder.
2. Double-click `Launch-Local.cmd`.
3. Keep its server window open while playing.
4. If the browser does not open, visit:

    http://localhost:8000/

Use Chrome or Edge.

## Important

- Start the game using the launcher. Do not open `index.html` directly.
- Keep the folder structure intact.
- First loading and shader preparation can take several minutes.
- Click inside the game to enable sound and capture the mouse.
- Press Esc to release the mouse.

## Graphics

The Mac launcher starts at 1280×720 with a 30 FPS cap.

You can edit these options in the browser address:

- `res=1280x720`: 720p resolution.
- `res=1920x1080`: 1080p resolution.
- `fps=30`: 30 FPS cap.
- `fps=60`: 60 FPS cap.
- Add `&low=1` for the lower-memory graphics profile.

Press Return after changing the address. This reloads the game.

Higher settings require more powerful hardware. An FPS cap does not guarantee that frame rate.

## Troubleshooting

### Blank page or missing files

Confirm that extraction completed and that every ZIP part was included.

### WebGPU unavailable

Update Chrome or Edge, enable hardware acceleration, and update your operating system or graphics drivers. Some older hardware is incompatible.

### Crashes or slow performance

Close other applications and browser tabs. Try 720p, a 30 FPS cap, and `&low=1`.

### Address already in use

A game server may already be running. Close its Terminal or command window before starting another.

## Compatibility and Testing

The game was confirmed to load into the map on an Apple M2 MacBook Air with 16 GB RAM using Chrome.

Other computers, extended gameplay, and every mission have not been tested. Bugs, crashes, and incomplete features may occur.

This package is intended for desktop computers. Phones and tablets are not supported by these launchers.

## Credits

Browser-game package:
https://github.com/alihammoud21/playgta5

This is an unofficial project and is not affiliated with Rockstar Games or Take-Two Interactive. GTA V and its game assets belong to their respective owners.
