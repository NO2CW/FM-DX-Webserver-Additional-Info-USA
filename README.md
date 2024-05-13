# FM-DX-Webserver-Additional-Info-USA
FM DX Webserver plugin to display additional info applicable to USA. Delivered function works well in Europe.

The placeholder for "additional Info" is populated from a file located in your web server. The code will:
(1) check for a valid PI Code
(2) if valid PI code exists, look up corresponding info from a local file that the user must supply
(3) rather than the delivered transmitter info, display the information that was looked up for the particular PI code.
Important:
The plugin is not optimized for duplicate PI codes such as FFFF or 0000. Make sure the values in your additional info file are unique.

Installation procedure:
Place the provided files in the corresponding folders.
In your "Plugins" folder you should have the following files:
(1) plugins\additionaInfo.js
(2) plugins\additionalInfo\frontend.js
(3) Update your frontend.js file -> Open the file in a text editor. You will see a long list of PI Code/ Additional Info. The file provided is relevant to South Florida. You need to make updates for your own location. Save.
