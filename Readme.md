# Flux demo repo

This repo is used for personal flux usage

## Command to bootstrape:

`flux bootstrap github \
--owner=$GITHUB_USER \
--repository=flux2-demo \
--branch=main \
--path=app-cluster \
--personal`


## Command to add new source

`flux create source git flux-demo-source \
--url=https://github.com/sushant08/flux-demo-source \
--branch=master \
--interval=30s \
--export > file-name.yaml`

## Command to create kustomization

`flux create kustomization 