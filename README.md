# fractal-shopware-demo
Shopware 6 demo shop playground installation

This main directory will ignore the shopware repositories
- development
- shopware

Generated files from production server are checked in to
- generated

while new themes and plugins below `development`
should probably have their own repositories below `custom`.

## changelog

### prod(uction) installation online

- installed directly on the shared host
- cloned 6.3 repository
- composer install
- clicked through web installer...
- ...issue: no admin app but white screen
- CLI: bin/build.sh
- back in admin app,
- installed demo data
- and finished basic configuration
- running demoshop!

## development installation on localhost (dockware)

- ...