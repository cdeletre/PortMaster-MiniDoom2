## Notes

Thank to team [Calvera Studio](https://calaverastudio.itch.io/) for making this awesome game.

The music is not yet supported in the port, an update will come later when we'll have meet all the requirements. While you can listen to this awesome BGM in this Youtube [video](https://www.youtube.com/watch?v=yjQHXCoh2lY) from the music composer [Manuel Soruco](https://manuelsoruco.com/about/).

## Controls

| Button | Action |
|--|--| 
|Dpad / Left Stick|Movement|
|B|Jump|
|Y|Shot|
|X|Throw grenade|
|L1|Roll left|
|R1|Roll right|
|L2|Weapon menu|
|R2|Weapon menu|
|Option / Start|Menu|

## Acknowledgments

I cannot forget to thank warmly our fellow testers from the PortMaster Discord <3

And finaly a big thanks to:
* JohnnyOnFlame for making GMLoaderNext
* nate for the custom loading splash engine
* Jeod for the [EmulationStation-ImageMaker](https://github.com/JeodC/EmulationStation-ImageMaker)

## Build

Build custom version of gmloadernext that support `config.json`

```bash
git clone --recursive https://github.com/cdeletre/gmloader-next.git
cd gmloader-next
make -f Makefile.gmloader ARCH=aarch64-linux-gnu
ls build/aarch64-linux-gnu/gmloader
```