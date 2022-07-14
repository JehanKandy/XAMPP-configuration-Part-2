# XAMPP-configuration-Part-2
increase file upload limit PHP
<br>
In here 
  1. go to php.ini configuration file <br>
    (path : Xampp/php/php.ini)
  2. then open file with any code editor <br>
    (notpad, VS code....)
  3. find followings and change<br>
      3.1 upload_max_filesize ::: line number : 835 <br>
          upload_max_filesize = 2M -- change to --> upload_max_filesize = 99999999999999M

      3.2 post_max_size ::: line number : 673 <br>
          post_max_size = 8M --> post_max_size = 99999999999999M

      3.3 max_execution_time ::: line number : 378 <br>
          max_execution_time = 30 --> max_execution_time = 100000000
