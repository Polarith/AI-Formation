# Polarith AI Formations

![](Images/polarith-ai.png)

[Polarith AI](https://polarith.com/ai/) offers all you need for achieving
state-of-the-art movement AI with just a few clicks. Design complex movement
behaviours and create immersive games or astonishing simulations by taking
advantage of the sophisticated workflow.

This repository is an extension to Polarith AI which is entirely written in C# and
supports all Unity platforms, whereby Unity versions starting from 2018.4 up 
to 2020.4 are officially supported.

This package adds additional behaviours to enable placing agents in formations in 2d and 3d.
You are welcome to explore the code and to add additional formations.
Feel free to create issues, add branches and create pull requests if you find a bug and want to provide a fix.
Since the source code is publicly available, there is only very *limited support*.
The source code is available under the MIT license. See the license file for more information.

MIT License

Copyright © 2021 Polarith.


## Developers

+ Martin Zettwitz


## Dependencies

+ [Unity](https://unity3d.com/) | required: 2018.4.30+
+ [Polarith AI](https://assetstore.unity.com/publishers/23798) | required: 1.7.2+


## Project Structure

The code needs the Polarith DLL files that are available in the [Unity Asset Store](https://assetstore.unity.com/publishers/23798).
The folder structure of this repo is the same as in the packages from asset store.
Simply add the DLLs in the \Assets\Polarith\AI\Plugins or copy the whole repo to 
your that contains Polarith AI. The `master` branch of this repository represents 
the latest stable release of Polarith AI Formations.

The `develop` branch of this repository reflects the latest development work
which is considered stable enough to be prepared for the next release. Be
warned, never use this branch in a production environment. Feel free to branch from develop
to add your own extensions or fixes to Polarith AI Formations.

All other branches might contain highly experimental work which might be under
heavy development at the moment. Use at your own risk only.


## Source Code

The full source code of Polarith AI Formations lives within
[`Assets/Sources`](Assets/Sources) and [`Assets/Editor`](Assets/Editor).
Justdrop the sources directly into your Unity project but keep in mind, you need
either the DLLs of Polarith AI Free or Polarith AI Pro.


## Documentation

The online documentation of the latest stable release is available on
https://docs.polarith.com/ai/. The same documentation is bundled with the
provided Unity package for the offline use.


## Issue Tracker

The associated [issue tracker](https://github.com/Polarith/AI-Formation/issues) can be
found within the [public repository](https://github.com/Polarith/AI-Formation),
which offers you the possibility to discuss features, track bugs, and create pull requests 
for enhancements. With its help, you can retrace our development progress.


## License

All parts of Polarith AI Formations are licensed under the [MIT License](LICENSE) which can be found at the root of this
repository.

The appropriate image material to comply with the license can be found under the
[`Images/`](Images/) directory.