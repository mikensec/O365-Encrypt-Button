# O365-Encrypt-Button
This addin DOES NOT encrypt anything. It's creates a new email with the confidential flag and the subject line "Encrypted Email". The purpose is to keep the user from having to go to options and marking the email as confidential every time or having to enter the specific subject line. 

It's your responsibility to make sure you have setup the corresponding office 365 rules for sending this type of emails to Azure Rights Management or some type of real email encryption service. 

## Attention 
You have to resign the code in order to publish it. 

### Prerequisites
.NET Framework 4.6.1
Microsoft Visual Studio 2010 Tools for Office Runtime

### Installing
Open the O365 Encrypt Button.sln in visual studio community 2017.
Open the properties file 
Edit the Signing and the Publish sections
Build the solution

I have included an unsigned prebuilt installer in install/ 
-Download all contents of the install folder
-Run setup.exe to install

## Built With
Visual Studio Community 2017

## Contact
Contact me on twitter for improvements etc. Twitter.com/mikensec

## Feedback
I'm a programmer in training. I appreciate feedback and guidance for this and future projects. 

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


