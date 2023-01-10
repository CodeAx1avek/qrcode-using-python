## CodeAx

 - [Telegram](https://t.me/avekgaming)
 - [instagram](https://instagram.com/codeax1?utm_medium=copy_link)
 - [Youtube](https://youtube.com/channel/UC-Q6ZcOtcx1gZ9fI5MDDt3w)


## Deployment

Import python library named qrcode from terminal or cmd 
pip install qrcode

```bash
#Write this Code in file with .py extension
#pip install qrcode......
#CodeAx1
import os
os.system('pip install qrcode')
import qrcode

#run code directly on terminal

avek = input("Enter Your Barcode Words: ")

img = qrcode.make(avek)

img.save("myQrcosde.jpg")

```

