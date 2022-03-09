Activation of Microsoft Office 2016, 2019 and 2021
Manually:

Log into your computer with an administrator account.
Type into the search field
cmd.exe
Click with the right mouse button on cmd.exe and select “Run as Administrator”
Change to the directory where Microsoft Office is installed.
If you are running a 32bit Office on a 32bit Windows or an 64bit Office on a 64bit Windows, enter
cd \Program Files\Microsoft Office\Office16
if you are running a 32bit Office on a 64bit Windows, enter
cd \Program Files (x86)\Microsoft Office\Office16
Enter
cscript ospp.vbs /sethst:ug-kms.uni-goettingen.de to connect to our KMS server
Finally enter
cscript ospp.vbs /act to complete the activation process.
