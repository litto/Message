# Message Library

Display Message Simple Library for PHP projects like Errors, Warning, Success , Notices.etc..

##How to Install?

Install Using Composer or Direcly you can download from the Github Code
You can install via composer by using this command:-

composer require litto/message


##How to Use?

1) Always remember to start session in your application using session-start();
2) Copy the Message.php in Vendor folder or in your folder of your choice
3) Include The file using autoload or using include function
4) For Setting Message pass like:-

$message  =   new Message('Your Message Text','Messagetype string');
$message->setMessage();

Message Type Strings -
error,message,warning

5) To Display call it like:-

<?php 
$message  =   new Message('','');
$message->showMessage();
$message->clearmessage();
?>

6) The message display will be using the boostrap alert styles. if you want to change the design class, you can chnage in the Message.php file

