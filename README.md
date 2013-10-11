aspshell
========
Same aspshell with FileSystem and Database querying capabilities.

Change Log:
=============
 * Addition of File System commands which does not rely on WScript.Shell.
 * Query directly with a database through the asp shell using :dbquery <query> command.

Contribute by Vikas Singhal (2013)

Original Author (C) 2007 Kurt Hanner

ASPShell - Web based shell for Microsoft IIS web servers


Table of Contents

  1. About
  2. Installation
  3. Usage
  4. Terms of Use
  5. Reporting Problems


*1 About*

  The ASP script "aspshell.asp" is a simple web application that provides
  a shell like environment for administering Microsoft IIS web servers.
  Commands submitted from a web browser are executed on the web server.
  The output is transfered back and dumped in the browser window.

  It makes use of AJAX technology for an interactive user experience.

  Visit the web page "http://aspshell.sourceforge.net" for current
  information about the project.


*2 Installation*

  * Copy the file "aspshell.asp" into a folder on your Microsoft IIS web
    server.
  * Create a virtual directory
      - Grant read and script execute permissions
      - Associate the virtual directory with the newly created folder
      - Disable anonymous authentication and enable "Integrated Windows
        Authentication" and/or "Basic Authentication" in order to grant
        access to authenticated users only.
      - Optional: require SSL connections (to encrypt data transmission
        between browser and server).

*3 Usage*

  Open a web browser and navigate to the URL that points to the ASP script.

  Example:

    http://webserver/admin/aspshell.asp

  Execute shell commands like in a "Command Prompt" window.

  To get basic help type in "?".

*4 Terms of Use*

  This  software  is provided "as is", without any guarantee made as to its
  suitability  or  fitness  for any particular use. It may contain bugs, so
  use  of  this  tool is at your own risk.  I take no responsilbity for any
  damage that may unintentionally be caused through its use.


*5 Reporting Problems*

  If  you  encounter problems, please raise an issue here.

