Page for download original firmware:
https://samfw.com/firmware/SM-M156B/MXD


To umcompress .md5 files:
tar -xvf AP_XXX.tar.md5

Also to decompress lz4 files you need to do :
lz4 -d recovery.img.lz4


## Experimental
Create TWRP device tree 

Create venv with twrpdtgen
$$$ 
python -m venv venv
source venv/bin/activate
pip install twrpdtgen
$$$


Execute twrpd gen python3.13 -m twrpdtgen 

python3.13 -m twrpdtgen recovery.img