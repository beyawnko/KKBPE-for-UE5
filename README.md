# KK Blender Porter Pack

![image](https://raw.githubusercontent.com/FlailingFog/flailingfog.github.io/master/assets/images/readme.png)

Plugin pack for exporting and cleaning up Koikatsu characters in Blender.  

The ```KKBP exporter for Koikatsu``` exports the character's mesh, armature and color data from the game. The ```KKBP importer for Blender``` processes that data to setup the character in Blender. Once characters are setup in Blender, they can be saved as FBX files for use in other programs. 

*    **Download:** https://github.com/FlailingFog/KK-Blender-Porter-Pack/releases  
*    **How to use the plugins:** https://kkbpwiki.github.io/.  
*    **Changelog:** https://github.com/FlailingFog/KK-Blender-Shader-Pack/blob/master/Changelog.md  
*    **Alternate download (this is a live snapshot of the repo that might not work!):** https://github.com/FlailingFog/KK-Blender-Porter-Pack/archive/refs/heads/master.zip  

## Video walkthrough of the plugins

[(Click for playlist!)  
![ ](https://raw.githubusercontent.com/kkbpwiki/kkbpwiki.github.io/master/assets/images/readmeyt.png)](https://www.youtube.com/watch?v=hib8NWBvgvA&list=PLhiuav2SCuveMgQUA2YqqbSE7BtOrkZ-Q&index=1)

## Help
[Check the wiki for FAQ and basic info.](https://kkbpwiki.github.io/)  
If you're still having trouble please [create a new issue](https://github.com/FlailingFog/KK-Blender-Porter-Pack/issues).

## Contributing
If you're interested in contributing, please check [the issues page](https://github.com/FlailingFog/KK-Blender-Porter-Pack/issues) or [make a pull request!](https://github.com/FlailingFog/KK-Blender-Porter-Pack/pulls)  
If you want to add or make changes to [the wiki site](https://kkbpwiki.github.io/), click the add / edit buttons on the top right of any page, then make a pull request.  
If you're interested in translating the plugin's interface into another language, [check this folder for examples](https://github.com/FlailingFog/KK-Blender-Porter-Pack/tree/master/interface).   
This project does not accept donations.

### Code style
This project uses [black](https://github.com/psf/black) and
[flake8](https://flake8.pycqa.org/) to keep the codebase consistent.
Their configuration lives in `pyproject.toml` and can be run automatically
via [pre-commit](https://pre-commit.com/).

```bash
pip install pre-commit
pre-commit install
```

Running these commands will enable automatic formatting and linting on each
commit.

## Similar Projects

* [KKBP Exporter](https://github.com/FlailingFog/KKBP_Exporter)
* [SKLX-creator](https://www.patreon.com/posts/sklx-lite-118039975)
* [KKPMX](https://github.com/CazzoPMX/KKPMX)
* [Koikatsu Pmx Exporter (Reverse Engineered & updated)](https://github.com/Snittern/KoikatsuPmxExporterReverseEngineered)
* [Grey's mesh exporter for Koikatsu](https://github.com/FlailingFog/KK-Blender-Porter-Pack/tree/9fcef4127ba56b4e8e8718fb546945fc00eaaad9/GME)

