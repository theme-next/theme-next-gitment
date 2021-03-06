# Hexo NexT EXIF

![Theme Version](https://img.shields.io/badge/NexT-v7.3.0+-blue?style=flat-square)
![Package Version](https://img.shields.io/github/package-json/v/theme-next/hexo-next-exif?style=flat-square)

[Exif.js](https://github.com/exif-js/exif-js) for NexT.

## Preview

![image](https://user-images.githubusercontent.com/16272760/70216651-f1e53200-177a-11ea-8417-0b23544a44c4.png)

From: https://unsplash.com/photos/2nNbx_fr4qU

## Install

```bash
npm install theme-next/hexo-next-exif
```

## Configure

You can config those in both **hexo** or **theme** `_config.yml`
```yaml
# JavaScript library for reading EXIF image metadata.
# For more information: https://github.com/exif-js/exif-js
exif:
  enable: false
  tags:
    FocalLength: "{value}mm"
    FNumber: "f/{value}"
    ExposureTime: "{value}s"
```
