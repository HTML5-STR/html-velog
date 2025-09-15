# 멀티 미디어 태그란?

멀티 미디어 태그는 이미지, 비디오, 오디오 등을 포함하는 태그입니다. 멀티 미디어를 사용 하면 웹 문서에 이미지나 비디오를 추가할 수 있습니다.

## 1. 오디오 태그(audio)

오디오 태그는 오디오 파일을 사용하여 재생할 수 있는 태그입니다. 오디오 태그는 이미지 태그와 다르게 사용하면 됩니다.

```html
<audio src="./audio/horse.mp3" controls></audio>
```

## 2. 비디오 태그(video)

비디오 태그는 비디오 파일을 사용해 재생할 수 있는 태그로 <video> 태그를 사용합니다.

```html
<video width="320" height="240" controls>
  <source src="./video/movie.mp4" type="video/mp4" />
</video>
```

## 3. iframe 태그

iframe 태그는 웹 페이지 내에서 동영상을 재생하거나 이미지를 보여주는 태그입니다.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>iframe</title>
  </head>
  <body>
    <iframe
      width="400"
      height="315"
      src="https://www.youtube.com/embed/jNQXAC9IVRw?si=fnLaGFXajeH_WLag"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen
    ></iframe>
  </body>
</html>
```
