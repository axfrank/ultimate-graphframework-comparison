# Ultimate Graphframework Comparison

[![Build Status](https://travis-ci.org/ultimate-comparisons/ultimate-graphframework-comparison.svg?branch=master)](https://travis-ci.org/ultimate-comparisons/ultimate-graphframework-comparison)

This is an ultimate comparison of different Javascript Graphic Frameworks. This has been implement as a part of a student project.
The following frameworks are used in this project (not sorted in any particular order)

[JointJS](https://www.jointjs.com/)

[Raphaël](http://dmitrybaranovskiy.github.io/raphael/)

[Draw2D](http://www.draw2d.org/draw2d/home/index.html)

[D3](https://d3js.org/)

[FabricJS](http://fabricjs.com/)

[PaperJS](http://paperjs.org/)

[JSPlumb](https://jsplumbtoolkit.com/)

If you found an error in the comparison, please open a ticket in the github repository of this project.

## Run it
1. Install [node.js](https://nodejs.org/en/)
2. Intall [Java JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
3. Install [pandoc](http://pandoc.org/installing.html) (Version 1.17.2) [pandoc-citeproc](https://hackage.haskell.org/package/pandoc-citeproc)
        
        wget https://github.com/jgm/pandoc/releases/download/1.17.2/pandoc-1.17.2-1-amd64.deb
        sudo dpkg -i pandoc-1.17.2-1-amd64.deb
        
4. Update npm (sudo): `npm install -g npm`
5. Test dependencies:

        java -version
        npm -version

6. `npm install`
7. `npm start` (starts the web page)
8. [Setup automatic deployment of `www` directory using Travis CI](https://github.com/ultimate-comparisons/ultimate-comparison-BASE/wiki/Build-and-deploy-project-with-Travis-CI)

## Ultimate-Graphframework-Comparison Element Specification
The code below shows a sample element.

    # Template - http://www.example.com

    ## Drag & Drop
    - Yes
    - Manually

    ## Angular2 Support
    - Yes
    - No

    ## Straight Line
    - Yes
    - Manually

    ## Label On Line
    - Yes
    - Manually

    ## Arrow Heads
    - Yes
    - Manually

    ## Scaling
    - Yes
    - Manually

    ## Rendering Method
    - SVG
    - Canvas
    - HTML

    ## Different Edge Types
    - Yes
    - No

    ## Explicit Data Model
    - Yes
    - No
    - Partially

    ## Docking Points
    - Yes
    - No

    ## Connection Types
    - Orthogonal
    - Other

    ## Performance
    - Fast
    - Slow

    ## License

    The code is licensed under [MIT], the content (located at `comparison-elements`) under [CC0-1.0].

  [CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/

<hr />

See [README-THING.template](https://github.com/ultimate-comparisons/ultimate-comparison-BASE/blob/master/README-THING.template.md) for a README skeletton for your ultimate-THING-comparison.

  [MIT]: https://opensource.org/licenses/MIT
  [CC-BY-SA-4.0]: http://creativecommons.org/licenses/by-sa/4.0/
