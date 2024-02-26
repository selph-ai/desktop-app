# Selph.ai Desktop App

Created using Tauri 1.60

## Development

### Installing Dependencies

1. Recommend using [asdf-vm](https://asdf-vm.com/guide/getting-started.html) to manage Node version. The exact Node version required is specified in the `.tool-versions` file at the root of this repo.
1. Have the [Tauri 1.60 dependencies](https://tauri.app/v1/guides/getting-started/prerequisites) installed for your platform.

### Running in development

1. In the root project folder, execute `npm start`

### Directory walkthrough

```
.
└── selph-app/
    ├── public/
    │   └── index.html          <- This file is the entry point to the entire front-end app, including image assets and compiled JS files
    ├── src-tauri/              <- Folder containing all Tauri-related Rust code
    │   ├── tauri.config.json   <- Configures Tauri settings
    │   ├── Cargo.toml          <- Specifies Rust dependencies
    │   ├── icons/              <- Specifies the app icons, the only asset folder under src-tauri/
    │   ├── build.rs            <- Tauri build command
    │   └── src/
    │       └── main.rs         <- Rust application logic and initialised the Tauri app.
    ├── README.md               <- This file :)
    └── package.json            <- npm commands and JS dependencies
```

### Building the application

TBD...

_Copyright 2024 Selph.ai contributors._
