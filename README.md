# blendOS Tracks

* GNOME: `gnome` - Useful for recovery when experimenting with the Cosmic branch.
* COSMIC: `cosmic`

**NOTE**: The COSMIC track is not thoroughly tested. Cosmic Epoch is a work-in-progress desktop environment by System76, so bugs you encounter are probably a result of their development cycle. It worked for me, it may not work for you. If you encounter any bugs, let them know, and help them out.

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
    - 'nvidia-open'
    - 'nvidia-open-dkms'
```
