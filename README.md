# Gopro to GPX instructions for EXIFTOOL

0. Make sure you have `exiftool` installed

```
brew install exiftool
```

1. Put all your videos to the directory

2. Run exiftool

```
exiftool -ee -p gpx.fmt -fileOrder DateTimeOriginal . > out.gpx
```

3. Open Google Earth Pro

4. Import out.gpx