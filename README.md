# (Python) Image to ANSI Converter

*Credit where credit is due.*

Original script was written by Torry Crass and is avalibe on his github (https://github.com/torrycrass/image-to-ansi). This fork provides image scaling to fit into terminal as well as script being ported to python3, rather than being python2 one.

This python script is based off of original work by Micah Elliott (MicahElliott) located in Gist colortrans.py which was then used to create image-to-ansi.py by K Lange (klange) and subsequently improved on by Takumi Sueda (puhitaku). A big thanks to those foundations.

## Purpose

This script uses python libraries to provide a way to take image files and make them color compatible for use in a shell (ANSI). Which allows display of terminal art such as that contained in the demo.png file. The original colortrans.py file (not included here) provides a way to translate RGB values into ANSI compatible terminal codes (i.e. color included), find that script if you plan to do this all manually.

![alt text](https://github.com/torrycrass/image-to-ansi/blob/master/demo.png "demo converted cli image")

### Prerequisites

This script requires python3 and  pillow python package:

```sh
pip install pillow --user
```


### Usage

Simpy ensure **image-to-ansi.py** has executable permissions (`chmod +x image-to-ansi.py`) and provide image path as an argument for this script. For maximum convenience i highly advise you to create an alias to this script, for example:

```sh
alias toansi='${HOME}/Projects/Personal/image-to-ansi/image-to-ansi.py'
```

#### Additional References/Resources

- http://patorjk.com/software/taag/ (An online text to ASCII art converter)
- https://16colo.rs (A library of ANSI art)
- https://www.ansilove.org (A software library for ANSI file conversion)
- http://www.roysac.com (A collection of ANSI/ASCII art and tools)
- http://vectorpoem.com/playscii/ (An ANSI/ASCII art editing tool)
- https://github.com/atdt/escapes.js/ (A library for rendering ANSI art in HTML5/JS)

#### Prior Author Credits
- Micah Elliott (MicahElliott): https://gist.github.com/MicahElliott/719710
- K Lange (klange): https://gist.github.com/klange/1687427
- Takumi Sueda (puhitaku): https://gist.github.com/puhitaku/7eaf6142fa5a42425f55
- Torry Crass (torrycrass): https://github.com/torrycrass/image-to-ansi
