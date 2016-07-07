Author: Vannakpanha Mao 
Country: Cambodia

*** Library configuration ***
------------------------------------------------------------------
1. Copy folder and file to past in Controller folder 
2. Include the file Mymail.php in side function that we want to process sending email 
	require 'Mymail/Mymail.php';
3. Use function send_helper() to send email 
 - function send_helper() require 4 parameters such as receiver email, receiver name, subject of email and the last is email content
***  example: send_helper($email ,$name, $subject, $body);    
4. this function return true if it is correct and return false if it is not correct 

*** setting up your email account ***
------------------------------------------------------------------
1. Enable POP and IMAP 
  > Go to setting -> Forwarding and POP/IMAP ->choose Enable
2. Enable less security 
  > Go to my account -> Signin & Security -> Scroll to the bottom ->Allow less secure apps: ON

Note: Should create an test account, don't use your personal email becuase it will affect to securty 
