# VideoTitle
This plugin allows you to put a video at the background of the Title Screen instead of a static image.

### Installation
* Download the JS file and include it into the ```/plugins``` folder of your project.
* Open the Plugin Manager, select the file **PH_VideoTitle.js**, and turn it on.
* Use the ```Video Name``` parameter to define the name of the video you want to exhibit in the background. This video must be inside the ```/movies``` folder of your project (Only ``webm`` extension is allowed).
* You may want to define an optional poster image in the variable ``Video Poster Name``. The image should be located into the ``/img/pictures`` folder of your project.

### How to Use
* You can check out the full documentation with an example in [HERE](http://primehover.gufernandes.com.br/ph-video-title).

### Parameters
* ``Video Name``: Name of the video.
* ``Video Muted``: Mutes the video in the title (0: No, 1: Yes)
* ``Video Loop``: Makes the video plays in a loop (0: No, 1: Yes)
* ``Video Poster Name``: Name and extension of the image to be shown when the video is loading (E.g. "poster.png")
* ``Video Width``: Width of the video in the canvas (Default: 816)
* ``Video Height``: Height of the video in the canvas (Default: 624)
* ``Video Coord X``: Coordinate X of the video in the canvas (Default: 0)
* ``Video Coord Y``: Coordinate Y of the video in the canvas (Default: 0)

### Example
* Download the video from [this website](http://video.webmfiles.org/big-buck-bunny_trailer.webm) and save it into your ``movies`` folder.
* Set the value of the variable ``Video Title`` to **big-buck-bunny_trailer**.
* Execute your game and you will see the video in background.

### ChangeLog
* 11/12/2015: Version 1.1
* 11/03/2015: README.md updated
* 11/02/2015: Version 1.0
