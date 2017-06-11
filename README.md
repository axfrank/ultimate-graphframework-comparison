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

## License

The code is licensed under [MIT], the content (located at `comparison-elements`) under [CC0-1.0].

  [CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/

<hr />

See [README-THING.template](https://github.com/ultimate-comparisons/ultimate-comparison-BASE/blob/master/README-THING.template.md) for a README skeletton for your ultimate-THING-comparison.

  [MIT]: https://opensource.org/licenses/MIT
  [CC-BY-SA-4.0]: http://creativecommons.org/licenses/by-sa/4.0/
