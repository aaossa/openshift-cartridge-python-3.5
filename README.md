# OpenShift cartridge [Python 3.5](https://docs.python.org/3.5/)

Forked from [Grief](https://github.com/Grief/openshift-cartridge-python-3.5), who forked it from [Changaco](https://github.com/Changaco/openshift-cartridge-python-lite). Use this URL to install this cartridge:

    https://raw.githubusercontent.com/aaossa/openshift-cartridge-python-3.5/master/metadata/manifest.yml


### Useful commands

##### Create new app

```
rhc app create <project> https://raw.githubusercontent.com/aaossa/openshift-cartridge-python-3.5/master/metadata/manifest.yml diy-0.1
```

#### Create new app from code

```
rhc app-create <project> https://raw.githubusercontent.com/aaossa/openshift-cartridge-python-3.5/master/metadata/manifest.yml diy-0.1 --from-code <code.git>
```