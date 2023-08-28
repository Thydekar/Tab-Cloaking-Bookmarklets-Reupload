# Tab-Cloaking-Bookmarklets
Bookmarklets to cloak your tab to look like almost anything

This is an updated version of my previous repository for tab cloaking.

Here are the instructions

1. the javascript:

javascript:(function() {var l = document.querySelector("link[rel*='icon']") || document.createElement('link');l.type = 'image/x-icon';l.rel = 'shortcut icon';l.href = '(insert url here)';document.getElementsByTagName('head')[0].appendChild(l);document.title = '(insert name here)';})();

2. get the image url
Images(i will take requests to add more tab icons*)
drag these into a new tab and get the url

![rizz](https://user-images.githubusercontent.com/130446887/236890346-a33ab9eb-5493-4da8-af8d-b97a3414b458.png)

![Screenshot 2023-05-05 12 42 22 PM](https://user-images.githubusercontent.com/130446887/236891345-ec4905f8-22da-4441-9352-df95b265737a.png)

![Screenshot 2023-05-05 12 50 02 PM](https://user-images.githubusercontent.com/130446887/236891374-3e7dc887-96e6-4082-aa54-3a1343a38938.png)

![Screenshot 2023-05-05 1 07 40 PM](https://user-images.githubusercontent.com/130446887/236898756-c8e32bc6-6a26-4f57-bfcb-5e054b62021e.png)

![Screenshot 2023-05-05 2 08 40 PM](https://user-images.githubusercontent.com/130446887/236898790-94ba9cbe-32db-4b58-b2d8-66ce6e0227fa.png)

![Screenshot 2023-05-05 4 05 39 PM](https://user-images.githubusercontent.com/130446887/236898826-0df7e9b8-e09b-49e8-b164-35319b5a60e1.png)

![Screenshot 2023-05-22 12 36 46 PM](https://github.com/Thydekar/Tab-Cloaking-Bookmarklets-Reupload/assets/130446887/fb6cc7d0-5f1e-4421-91aa-15211ff50538)

![Screenshot 2023-05-05 12 45 50 PM](https://github.com/Thydekar/Tab-Cloaking-Bookmarklets-Reupload/assets/130446887/11ac8387-f512-45c4-9bb2-ebadfe71914a)


![Screenshot_2023-05-15_2 50 37_PM-removebg-preview](https://github.com/Thydekar/Tab-Cloaking-Bookmarklets-Reupload/assets/130446887/9290be7d-b160-4f12-af27-eb016666f4a8)



link to other images:

https://pesd.getalma.com/favicon.ico

https://www.google.com/favicon.ico

https://www.youtube.com/favicon.ico

https://mail.google.com/favicon.ico

https://drive.google.com/favicon.ico

https://carnegielearning.com/favicon.ico

https://or-pesd.edupoint.com/favicon.ico


3. name your tab in the insert name section(or for you more experienced people, the document.title section :) )

Example:

javascript:(function() {var l = document.querySelector("link[rel*='icon']") || document.createElement('link');l.type = 'image/x-icon';l.rel = 'shortcut icon';l.href = 'https://www.google.com/favicon.ico';document.getElementsByTagName('head')[0].appendChild(l);document.title = 'Google';})();


4. Copy your finished javascript into your bookmarks bar and enjoy your tab cloaking Bookmarklet!



*My email is dallingeurts@gmail.com (got that off a random name generator)
