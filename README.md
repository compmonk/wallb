# wallb
*wallb* is wallpaper background slideshow maker for Ubuntu and derivatives

install *wallb* and use it to make wallpaper slideshows

use ```wallb --help``` for options

```
$ python wallb --help
usage: wallb [-h] [-d DIRECTORY] [-s STATIC] [-t TRANSITION] [-v] name

Make background wallpaper slideshow

positional arguments:
  name                  name of slideshow

optional arguments:
  -h, --help            show this help message and exit
  -d DIRECTORY, --directory DIRECTORY
                        directory containing images
  -s STATIC, --static STATIC
                        static time intevral in seconds
  -t TRANSITION, --transition TRANSITION
                        transition time intevral in seconds
  -v, --verbose         verbose
```

```sudo``` permissions might be needed to create directory and files

#### Note:

*wallb* creates ```/usr/share/backgrounds/{name}``` directory,

```/usr/share/backgrounds/contest/{name}.xml``` and 

```/usr/share/gnome-background-properties/{name}-wallpapers.xml```
