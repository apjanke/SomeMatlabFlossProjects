SomeMatlabFlossProjects
=======================

This is a list of FLOSS ("Free/Libre/Open Source Software") projects for Matlab that I’ve found.
I put this list together because there doesn’t seem to be a good central resource for finding FLOSS Matlab software.

I haven’t actually used all the libraries on this list, so I can’t vouch for their quality.
I’m just noting their existence.

Submissions to this list are welcome.
Make a [Pull Request](https://github.com/apjanke/SomeMatlabFlossProjects/pulls) with them.

## FLOSS Matlab Projects

* [GUI Layout Toolbox](https://www.mathworks.com/matlabcentral/fileexchange/47982-gui-layout-toolbox) – Richer controls for arranging Matlab GUI widgets
* [GRAMM](https://github.com/piermorel/gramm) – Advanced data visualization based on Grammar of Graphics
* [PRMLT](https://github.com/PRML/PRMLT) – Machine learning algorithms
* [DeepLearnToolbox](https://github.com/rasmusbergpalm/DeepLearnToolbox) – Deep Learning toolbox (deprecated)
* [FieldTrip](http://www.fieldtriptoolbox.org/) – A toolbox for MEG and EEG (brain imaging) analysis
* [TDT – The Decoding Toolbox](https://sites.google.com/site/tdtdecodingtoolbox/) – Multivariate analysis of functional and structural MRI data
* [MathWorks Reference Architectures](https://github.com/mathworks-ref-arch) – MathWorks’ own open source tools for deploying Matlab systems on cloud providers like AWS and Azure
* [T-MATS](https://github.com/nasa/T-MATS) – A NASA-developed library for modeling thermodynamic systems
* [matImage](https://github.com/mattools/matImage) – Image processing library
  * Note: there’s [no LICENSE](https://github.com/mattools/matImage/issues/3) in this one; I’m just assuming it’s open source
  * The [`mattools` GitHub group](https://github.com/mattools) has several other libraries
* [Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-matlab) – Robotics-specific functionality
* [Physical Units Toolbox](https://www.mathworks.com/matlabcentral/fileexchange/38977-physical-units-toolbox)
* [Treemap](https://www.mathworks.com/matlabcentral/fileexchange/17192-treemap) – Displays data using relative areas of nested rectangles
* [findjobj](https://www.mathworks.com/matlabcentral/fileexchange/14317-findjobj-find-java-handles-of-matlab-graphic-objects) – find Java handles in Matlab graphic objects
* [export_fig](https://www.mathworks.com/matlabcentral/fileexchange/23629-export_fig) - Exports figures to various formats
* [tfigure](https://github.com/curtisma/MATLAB_tfigure) – A tabbed figure control
* [Lenia](https://github.com/Chakazul/Lenia) – Mathematical lifeforms: cool 2D cellular automata visualization
* [Matlab Schemer](https://github.com/scottclowe/matlab-schemer) – Color themes for the Matlab desktop
* [Historical Stock Data Download](https://www.mathworks.com/matlabcentral/fileexchange/37502-historical-stock-data-download-alternate-method) by Captain Awesome – Downloads Yahoo Finance data
* [Process Manager](https://www.mathworks.com/matlabcentral/fileexchange/48164-process-manager) – Launch and manage external processes from Matlab
* [MOxUnit](https://github.com/MOxUnit/MOxUnit) – a unit test framework
* [GIBBON](https://www.gibboncode.org/) – The Geometry and Image-Based Bioengineering add-ON
* [TopoToolbox](https://topotoolbox.wordpress.com/topotoolbox/) – Analysis of digital elevation models
* [TAPAS](https://github.com/translationalneuromodeling/tapas) – Translational Algorithms for Psychiatry-Advancing Science – A neuroscience library

### My own FLOSS Matlab Projects


* [Janklab](https://github.com/apjanke/janklab) ![Not Octave Compatible][no-octave] – My general-purpose tools & tricks Matlab library
* [SLF4M](https://github.com/apjanke/SLF4M) – A simple logging framework for Matlab, built on top of SLF4J and Log4J
* [MCodeNavigator](https://github.com/apjanke/MCodeNavigator) ![Not Octave Compatible][no-octave] – A GUI for browsing Matlab source code trees
* [matlab-bench](https://github.com/apjanke/matlab-bench) – Benchmarks performance of basic Matlab language operations
* [dispstr](https://github.com/apjanke/dispstr) ![Octave Compatible][octave] – An API for polymorphic customizable object display

![Octave Compatible][octave] = Octave-compatible
![Not Octave Compatible][no-octave] = Not Octave-compatible

## Resources

### Matlab Help places

* ["matlab" tag on Stack Overflow](https://stackoverflow.com/questions/tagged/matlab)
* [Matlab Ansers on Matlab Central](https://www.mathworks.com/matlabcentral/answers/index/) – Official MathWorks forum, like a clone of Stack Overflow
* [#matlab channel on freenode IRC](https://matlab-freenode.fandom.com/wiki/Matlab_on_Freenode_Wiki)
* [Matlab Café Slack](https://matlabcafe.slack.com) – A public Slack for discussing Matlab programming

### Other Lists of Matlab Projects

* [mikecroucher/awesome-MATLAB](https://github.com/mikecroucher/awesome-MATLAB)
* [uhub/awesome-matlab](https://github.com/uhub/awesome-matlab)

### Finding FLOSS Matlab Projects

[MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/) is the classic location for sharing Matlab code.
Everything on there is required to be FLOSS licensed.
It seems to be mostly used for smaller projects and single scripts, though.
The [File Exchange Pick of the Week](https://blogs.mathworks.com/pick/) highlights notable submissions.

There’s a [Matlab tag on GitHub](https://github.com/topics/matlab).
It lists over 4,000 repos as of March 2019.
Most of them appear to just be student homework, though, so they don’t all represent significant projects.

[MathWorks has a GitHub page](https://github.com/mathworks).

I prefer projects that are hosted on GitHub to those on File Exchange, because there’s no good way to submit PRs or bug reports on File Exchange.

GitHub user `kaxap` maintains a [list of popular Matlab repos on GitHub](https://github.com/kaxap/arl/blob/master/README-MATLAB.md).

Yair Altman posts a bunch of stuff on [Undocumented Matlab](https://undocumentedmatlab.com/) and [his File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/?term=authorid%3A27420).

## Author

This list was put together by [Andrew Janke](https://apjanke.net).

[octave]: images/octave-16px.png "Octave Compatible"
[no-octave]: images/no-octave-16px.png "Not Octave Compatible"
