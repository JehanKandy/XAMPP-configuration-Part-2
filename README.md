# XAMPP-configuration-Part-2
increase file upload limit PHP
<br>
In here 
  1. go to php.ini configuration file <br>
    (path : Xampp/php/php.ini)
  2. then open file with any code editor <br>
    (notpad, VS code....)
  3. find followings and change<br>
      3.1 upload_max_filesize (using Ctrl + f)<br>
          upload_max_filesize = 2M -- change to --> upload_max_filesize = 99999999999999M

      3.2 post_max_size <br>
          post_max_size = 8M -- change to --> post_max_size = 99999999999999M


