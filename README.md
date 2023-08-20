# life.bolls.bolls

For source code go to https://github.com/Bohooslav/bolls-electron

## Install

```bash
npm install
```

## Run

```bash
npm start
```

## Build

```bash
npm run dist
```

Then upload AppImage to https://console.cloud.google.com/storage/browser/resurrecting-cat.appspot.com;tab=objects?forceOnBucketsSortingFiltering=true&project=resurrecting-cat&prefix=&forceOnObjectsSortingFiltering=false

After run `sha256sum` to generate checksum for flatpak manifest. `ls -l` to see file size.

Then open PR against fluthub repo