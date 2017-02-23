# rancher-metadata-listener

Container that runs the Rancher Metadata service listening on :80

## Examples

```
# Default skeleton answer file
docker run -p 80:80 nextrevision/rancher-metadata-listener
```

```
# Using your own answers
docker run -p 80:80 \
  -v $(pwd)/answers.json:/answers.json \
  nextrevision/rancher-metadata-listener --answers /answers.json
```
