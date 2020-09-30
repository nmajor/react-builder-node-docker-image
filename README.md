# Node React Builder Docker Image

This image was created because react-snap requires a bunch of libraries that are not included in the typical node docker images.

## Build

```bash
docker build -t nmajor/react-builder:node-12.16 .
```

### Push

```bash
docker push nmajor/react-builder:node-12.16
```
