# image_display
Tool to show images to multiple screens with control via one screen

Quick and dirty little picture-showing tool I put together. Run the python somewhere that all the picture viewers can access; put the control and view html files on webserver (or download locally). You will need to change the ip address in the two html files.

The script will send a list of images (by name) to the controller, and when the controller picks one, will encode that image and send it to all the viewers, who will present it on their webpages.

I use this setup with two smartphones that I have in little brackets on the GM screen, so that my players can get an image of the monster, NPC, or significant item that they are currently engaged with.
