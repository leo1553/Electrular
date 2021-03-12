## Electrular
Base project for creating and building Electron + Angular desktop apps based on [this Quick Start](https://www.sitepoint.com/build-a-desktop-application-with-electron-and-angular/) and [this Quick Build](https://www.electronjs.org/docs/tutorial/quick-start#package-and-distribute-the-application) guide.

### Development web server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Development build
Run `npm start:electron` for a dev build. The application will be automatically open and shown.

### Build
Run `npm make` to build the project. The build binaries will be stored in the `out/electrular-*` directory while the installer will be stored in the `out/make/*` folder. The built application uses the `--prod` flag for a production build.

## Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
