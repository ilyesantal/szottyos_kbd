# Szottyos keyboard
## Prerequisites

* Node
* Docker
* Soldering tools
## Bill of Materials
* <a href="https://docs.google.com/spreadsheets/d/14zfck-Etdlp5-raBP9K-4Nxd6nClEs_cWekAMFLIVm4/edit?usp=sharing" target="_blank">Link to BOM</a>

## Getting Started

```bash
git clone https://github.com/ilyesantal/szottyos_kbd.git
cd szottyos_kbd
npm i
```

## Ergogen

### Build

This will run Ergogen and build all of the output files.

```bash
npm run ergogen:build
```

### Watch

This will watch the `config.yaml` file and the `footprints` directory and run the build command whenever there are changes.

```bash
npm run ergogen:watch
```

## ZMK

### Init

Downloads ZMK dependencies

```bash
npm run zmk:update
```

### Build

Builds the ZMK firmware

```bash
npm run zmk:build
```

### Down

Shuts down the ZMK docker services

```bash
npm run zmk:down
```

## Thanks

* <a href="https://github.com/ergogen/ergogen" target="_blank">Ergogen</a>
* <a href="https://discord.gg/nbKcAZB" target="_blank">Absolem Club Discord</a>
* <a href="https://github.com/tsteffek/Ergogen-V4-Migration-Guide" target="_blank">V4 Migration Guide</a>
* <a href="https://github.com/Narkoleptika/josukey" target="_blank">Josukey</a>
* <a href="https://github.com/zmkfirmware/zmk" target="_blank">ZMK</a>
