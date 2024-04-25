Python | QR code generator

First, we need to install 2 modules using the cmd

qrcode  (pip  install QRcode)
image (pip  install image)

This module attempts to follow the QR code standard as closely as possible.

>pip install image
>pip install qrcode


Now, let’s move on to the coding part…
qr = qrcode.QRCode(version ,box_size,border )

When creating a QR code only the content to be encoded is required, all the other properties of the code will be guessed based on the contents given. This function will return a QR object.
Here, is the version: This parameter specifies the size and data capacity of the code.

box_size: the size of the box where the QR code will be displayed.
border: it is the size of the border around the QRCode usually white in color.**
