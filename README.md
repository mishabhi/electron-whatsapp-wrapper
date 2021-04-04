# Electron wrapper WhatsApp Web
It is an unofficial desktop client using Electron to wrap WhatsApp Web. While it should work on Windows, Mac and Linux, development was targeted for Linux.

## Run
Use yarn or npm.
`npm install` or `yarn install` to install dependencies, then run `npm run start` or `yarn start`.

## Compilation
`npm run build` or `yarn build` to build AppImage inside dist folder.

#### Running AppImage
    1. Download AppImage file detector: wget "https://github.com/AppImage/appimaged/releases/download/continuous/appimaged-x86_64.AppImage"
    2. chmod +x appimaged-x86_64.AppImage
    3. ./appimaged-x86_64.AppImage --install
    4. Copy whatsapp AppImage from dist folder and keep it inside any of below folders:
        ~/Downloads, ~/.local/bin, ~/bin, /opt, /usr/local/bin fol