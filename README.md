# Cinemania

Cinemania exports TrackMania United Forever MediaTracker videos as MP4 instead of AVI, with optional sound.

Video rendering was about 10× faster in our tests. The comparison used different clips and excludes audio recording time.

## Requirements

- 64-bit Windows
- TrackMania United Forever 2.12.0
- [TMLoader 1.0.1 or newer](https://tomashu.dev/software/tmloader/)

## Install

1. Close TMLoader.
   
2. Open `%LOCALAPPDATA%\TMLoader\config.yaml` and add the URL under `servers:`, keeping any existing entries:

   ```yaml
   servers:
     - 'https://raw.githubusercontent.com/mediocre-q/Cinemania/master/modloader/'
   ```

3. Reopen TMLoader and select Cinemania in your profile.
   
4. Export a video normally through MediaTracker.
