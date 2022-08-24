# pdf2mp4
pdf2jpgs2gif2mp4... in a simply way. maybe named it as fastpdfviewer

commandlines:

## PDF2jpgs
```
convert input.pdf  pages.jpg

```

## jpgs2gif
```
convery --delay 100 *.jpg output.gif

```
## gif2mp4

```
ffmpeg -f gif -i input.gif output.mp4
```

hopfully it helps.
