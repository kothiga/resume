# Resume

Source for my personal resume. This repository is equipped with a `devcontainer` environment for local development, along with GitHub actions for building and release the compiled $\LaTeX$.

## Updating Docker container for GitHub actions

The GitHub actions utilize an image pulled from Docker Hub to build the repository. When updating the `Dockerfile`, it is necessary to build and push the updated image.

``` bash
docker build . --file .devcontainer/Dockerfile --tag kothiga/resume:latest
docker push kothiga/resume:latest
```
