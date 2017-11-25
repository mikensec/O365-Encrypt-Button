# O365-Encrypt-Button
This addin DOES NOT encrypt anything. It's creates a new email with the confidential flag and the subject line "Encrypted Email". The purpose is to keep the user from having to go to options and marking the email as confidential every time or having to enter the specific subject line. 

It's your responsibility to make sure you have setup the corresponding office 365 rules for sending this type of emails to Azure Rights Management or some type of real email encryption service. 

## Attention 
You might need to re-publish the solution with and code sign it in order for outlook to accept installing this addin. 

### Prerequisites
.NET Framework 4.6.1

### Installing
I have included a msi installer "Button.msi". 

## Built With
Visual Studio Community 2017

## Contact
Contact me on twitter for improvements etc. Twitter.com/mikensec

## Feedback
I'm a programmer in training. I appreciate feedback and guidance for this and future projects. 

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


