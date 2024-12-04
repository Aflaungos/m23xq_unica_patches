![1000019785](https://github.com/Aflaungos/m23xq_unica_patches/blob/main/m23xq_unica_patches_logo.jpg)
# M23XQ UN1CA Patches
## Usage
1. Clone [UN1CA](https://github.com/salvogiangri/UN1CA) repository:
> git clone https://github.com/salvogiangri/UN1CA
3. Clone [this repository](https://github.com/Aflaungos/m23xq_unica_patches) inside Unica 'target' folder
> git clone https://github.com/Aflaungos/m23xq_unica_patches
4. Build UN1CA ROM
5. Done

## Building UN1CA ROM
1. Init All Submodules:
> git submodule update --init --recursive
2. Prepare Build Environment:
> source buildenv.sh <your device codename, ex: m23xq>
3. Start Build Process:
> run_cmd make_rom

## Troubleshooting
1. Any submodule related issue? Reset all submodules and update them:
> git submodule foreach --recursive git reset --hard (**This is a single command**)
> git submodule update --recursive
