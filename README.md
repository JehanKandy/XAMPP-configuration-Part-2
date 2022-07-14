# XAMPP-configuration-Part-2
increase file upload limit PHP
<br>
In here 
  1. go to php.ini configuration file <br>
    (path : Xampp/php/php.ini)
  2. then open file with any code editor <br>
    (notpad, VS code....)
  3. find followings <br>
      3.1 upload_max_filesize (using Ctrl + f)
          upload_max_filesize = 2M --> upload_max_filesize = 99999999999999
