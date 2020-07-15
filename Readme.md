# How to use

```
docker pull pan1c/yamllint
```

## yaml lint
```
docker run \
    --rm \
    -v ${PWD}:/work \
    -w /work pan1c/yamllint \
    sh -c 'yamllint roles/*/tasks roles/*/handlers roles/*/defaults group_vars/*/ group_vars/ host_vars/*/ '

```
