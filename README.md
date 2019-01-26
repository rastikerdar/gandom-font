# Gandom-Font
A Persian (Farsi) Font  
فونت (قلم) فارسی گندم  
[نمایش فونت - صفحه رسمی پروژه](https://rastikerdar.github.io/gandom-font/)  
[صفحه دریافت (دانلود) بسته فونت شامل فایل های ttf,woff,eot](https://github.com/rastikerdar/gandom-font/releases)  
با تشکر از برنامه [FontForge](https://fontforge.github.io)  
بر مبنای فونت [صمیم](https://rastikerdar.github.io/samim-font)  
نسخه های «بدون حروف لاتین» و «تمام ارقام فارسی» درون بسته فشرده موجود می‌باشد.  

## طریقه استفاده در صفحات وب:
<p lang="fa" dir="rtl">کد زیر را در قسمت style یا فایل css وارد نمایید:</p>

```css
@font-face {
  font-family: Gandom;
  src: url('Gandom.eot');
  src: url('Gandom.eot?#iefix') format('embedded-opentype'),
       url('Gandom.woff') format('woff'),
       url('Gandom.ttf') format('truetype');
  font-weight: normal;
}
```

## Install
#### Arch Linux

Arch user's could use [gandom-fonts](https://aur.archlinux.org/packages/gandom-fonts/) package from [AUR](https://aur.archlinux.org/) repository to install gandom font. Use your favourite [AUR helper](https://wiki.archlinux.org/index.php/AUR_helpers) like pacaur or yaourt for installing package:

```shell
pacaur -S gandom-fonts
```

## License
2015 Saber Rastikerdar ([@rastikerdar](https://github.com/rastikerdar)). See the `LICENSE` file.
