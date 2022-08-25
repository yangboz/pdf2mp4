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

## html2mp4
html2pdf2jpgs2gif2mp4... 
```
wkhtmltopdf input.url output.pdf

```

## references



https://stackoverflow.com/questions/24961127/how-to-create-a-video-from-images-with-ffmpeg

https://wkhtmltopdf.org/


