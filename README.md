# Tab-Cloaking-Reupload-
Bookmarklets to cloak your tab to look like almost anything

This is an update version of my previous repository for tab cloaking.

Here are the instructions

1. the javascript:

javascript:(function() {var l = document.querySelector("link[rel*='icon']") || document.createElement('link');l.type = 'image/x-icon';l.rel = 'shortcut icon';l.href = '(insert url here)';document.getElementsByTagName('head')[0].appendChild(l);document.title = '(insert name here)';})();

2. get the image url
Images(i will take requests to add more tab icons*)
![rizz](https://user-images.githubusercontent.com/130446887/236890346-a33ab9eb-5493-4da8-af8d-b97a3414b458.png)
