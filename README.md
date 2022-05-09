Migration 2022
==============

Details of Migrating From Macs + Drobo to Mixed Windows (Primary)/Linux/Mac + Synology


For day to day computing tasks, 2012 Retina MacBook Pro is being replaced by 2022 Razer Blade 17

Common applications used on the RMBP and their replacements are:

- **Web Browsing**: Vivaldi (Mac) --> Vivaldi (Windows)
- **Spreadsheets**: Excel (Mac) --> Excel (Windows)
- **Text Editing (GUI)**: Visual Studio Code (Mac) --> Visual Studio Code (Windows)
- **Text Editing (Command Line)**: Vim (Mac) --> Vim (WSL (Ubuntu?))
- **Terminal**: iTerm (Mac) --> ??? WSL Ubuntu
- **Casual File Transfer from iOS**: Airdrop --> ??? TBD
- **Gaming**: N/A (Mac) --> Steam (Windows)


Also intend to gradually migrate functions from 2013 Mac Pro to the 2022 Razer Blade 17 and from Drobo 5D to Synology DS 1825+


Expected Challenges and Obstacles:

### 2013 Mac Pro/Drobo ###

- iTunes (Music)
  - 1: Migrate iTunes library from Drobo 5D to Synology (front-end still managed by 2013 Mac Pro)
  - 2: Migrate iTunes (Mac) to (??? TBD) (Windows) (preserving iTunes play counts, ratings, playlists and smart playlists)
- Migrate cable-sync of iOS devices (ensuring live photos are preserved)
- Migrate Lightroom Library (ideally taking the opportunity to have iPhone live photos preserved)
- Scansnap S1500M Scanner - Mac specific, does it work on Windows? Note only 32-bit (note, according to [Fujitsu's (Discontinued) Product Page][fuji01], the scanner is compatible with Windows). The Windows software seems to be available from the [Fujitsu Download Page][fuji02]



2022 Razer Blade 17 Initial Setup
---------------------------------

- WSL (see [Awesome WSL][gith01])
- Office 365
- Cloud Services (Dropbox/OneDrive)
- Git
- Vim










[fuji01]: https://www.fujitsu.com/ca/en/products/computing/peripheral/scanners/scansnap/discontinued/s1500m/s1500m.html
[fuji02]: https://www.fujitsu.com/global/support/products/computing/peripheral/scanners/scansnap/software/s1500.html
[gith01]: https://github.com/sirredbeard/Awesome-WSL
