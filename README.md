# Ultimate Graphframework Comparison

[![Build Status](https://travis-ci.org/ultimate-comparisons/ultimate-graphframework-comparison.svg?branch=master)](https://travis-ci.org/ultimate-comparisons/ultimate-graphframework-comparison)

This is an ultimate comparison of different Javascript Graphic Frameworks. This has been implement as a part of a student project.

If you found an error in the comparison, please open a ticket in the github repository of this project.

## Run it
1. Install [node.js](https://nodejs.org/en/) 
  - Windows: `choco install nodejs` via [chocolatey](https://chocolatey.org/)
2. Install [Java JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  - Windows: `choco install jdk8`
3. Install [pandoc](http://pandoc.org/installing.html) (Version 1.17.2)
   - Linux:
     1. `wget https://github.com/jgm/pandoc/releases/download/1.17.2/pandoc-1.17.2-1-amd64.deb`
     2. `sudo dpkg -i pandoc-1.17.2-1-amd64.deb`
   - Windows: `choco install pandoc`
4. Install [pandoc-citeproc](https://hackage.haskell.org/package/pandoc-citeproc)
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
