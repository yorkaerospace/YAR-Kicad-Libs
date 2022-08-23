# YAR's Kicad Libraries

A collection of components, footprints and other things for use in YAR's kicad projects. Uploaded to github to make cooperation a bit easier.

## Usage

This repo can be included as a submodule within another repo by using the command:
    git add submodule https://github.com/yorkaerospace/YAR-Kicad-Libs.git
It is advised that you put this *within* the kicad project itself, as kicad really does not like relative paths.

If you've cloned a repo containing this library then you can download these libraries by running:
    git submodule init
    git submodule update

Either way, once you've got these libaries on your machine, you can add them to your project in the preferences menu. At this point, you can treat this as a git repo inside a git repo, and push/pull changes as you normally would.

Please note that this is a public repo (because I'm lazy) so refrain from committing anything sensitive/profane.
