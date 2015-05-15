# Mail
Library for sending Emails


## Calling the library

    include 'autoload.php';

## Send the Email

    Mail::send("<b>The Message</b>",function($message)
	  {
	          $message->to("reciver@gmail.com")
	          ->subject("Hello World")
	          ->type("HTML");
	  });

