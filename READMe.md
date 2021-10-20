# Documentation

This repo contains all the content for doc.cloudpilgrim.io, which is built using mkdocs had the mkdocs function `gh-deploy`.

## How-to-deploy

To deploy the site the site's repo must be pulled locally [repo](https://github.com/richardfurniss96/richardfurniss96.github.io).

CD into the repo, then run the following command `mkdocs gh-deploy --config-file ../documentation/mkdocs.yml --remote-branch master`.