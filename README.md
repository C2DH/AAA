# AAA

Prototype for AAA project.

## Development

We use the offical docker image to run the development environment. To start the development environment, run the following command:

```bash
docker run -it --rm -p 8080:80 \
  -v $(pwd):/usr/share/nginx/html/swagger/ \
  -e SPEC_URL=swagger/openapi.yaml -e LOG_LEVEL=debug redocly/redoc

```

Without Docker, just create the index.html unsing [redocly](https://redocly.com/docs/cli/installation) from the command line:

```bash
redocly build-docs openapi.yaml -o index.html
```

## deployment

```bash
docker run --rm -v $(pwd):/api --workdir /api ghcr.io/redocly/redoc/cli:latest build openapi.yaml -o dist/index.html
netlify deploy --dir=dist --prod
```



image you're started always visible
highlighted similarity by area, like pinterest