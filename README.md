## Hello Framework - Static "dist" files copied to repo root

In this test, the content of the "dist" folder are moved into the root of a repo.

Test results: Works!

Important: place a blank .nojekyll file in the root of your site.

The .nojekyll file allows files starting with _ to be used.

[model.earth/hello-framework-root](https://model.earth/hello-framework-root)

With this structure, the docs source content could be public (not typically desired).  
The /docs folder could contain an index.html file with an overview of the source files.  
Useful when source files are published for training and documentation.

[Related Posts](https://github.com/observablehq/framework/discussions/1030) - [Docs folder test](https://github.com/ModelEarth/hello-framework-docs)
