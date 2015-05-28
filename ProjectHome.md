SOURCE WILL COME SOON!

To install: just download and run the provided ParamRun.exe and it will automatically install to C:\Program Files\Param Run\ along with a readme.txt

Once you run the application, an option in the context menu (right click menu) will appear on EXE files, named "Run With Parameters." When you click this option, you will be prompted with an input box to enter your parameters. Type your parameters in, and click OK.

Examples:
> Let's say you want to open Firefox's profile manager. In this case, right click on either the Firefox EXE OR a shortcut to Firefox, and hit "Run With Parameters." When prompted to enter the parameters, you would type the following and hit OK: **-ProfileManager**

> Let's say you want to use PuTTY to connect to a server. Right click on either a shortcut or the actual EXE, and select "Run With Parameters." Now type the following, with your own information, and hit OK: **-ssh -l root -pw alpine 192.168.1.128**
> where "root" is your username, "alpine" is your password, and "192.168.1.128" is your server IP

Features:
  * asily uninstall by passing "-u" (without quotes) to the ParamRun.exe
  * ingle item history for each unique filename ("c:\apache\httpd.exe" and "c:\wos\apache2\httpd.exe" are seen as the same filename)

**NOTE: Since this program adds an entry to the Windows registry, it might be neccessary to run it with administrative privileges.**