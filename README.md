# blendOS Tracks

* GNOME: `gnome`
* COSMIC: `cosmic`

**NOTE**: The COSMIC track is not thoroughly tested. Things may not work for you.

## Example COSMIC `/system.yaml` (vanilla)

```
repo: 'https://pkg-repo.blendos.co/'

impl: 'https://github.com/retr0gr4d3/tracks/raw/main'

track: 'cosmic'
```

## Example COSMIC `/system.yaml` with Nvidia modules

```
repo: 'https://pkg-repo.blendos.co/'

impl: 'https://github.com/retr0gr4d3/tracks/raw/main'

track: 'cosmic'

packages:
    - 'nvidia-dkms'
    - 'nvidia-prime'
```
