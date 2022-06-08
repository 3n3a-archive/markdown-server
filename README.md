# markdown-server

[![.github/workflows/build-docker-image.yml](https://github.com/3n3a/markdown-server/actions/workflows/build-docker-image.yml/badge.svg)](https://github.com/3n3a/markdown-server/actions/workflows/build-docker-image.yml)

converts your markdown in the `docs` folder on the fly to html

## Docker

* Your Markdown files go into `/static`
* Your assets like images etc go into `/assets`
* Under `/generated` you'll find the html generated from the markdown

### Example

```sh
docker run -p 8000:8000 3n3a/markdown-server:latest
```
