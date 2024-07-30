# Bootstrap

## Install Mise for dependency managemente
```shell
# Install Mise
curl https://mise.run | sh
```

## Install Mise for dependency managemente
```shell
# Install desired version of rust
mise local rust@1.80.0
mise install
```

## For the repo, get the rust gitignore
```shell
wget https://raw.githubusercontent.com/github/gitignore/main/Rust.gitignore
```

## Install Tauri

### On macOS
```shell
sh <(curl https://create.tauri.app/sh)
```
### On Windows
```shell
irm https://create.tauri.app/ps | iex
```

## Run the empty app for the first time
```shell
cd tauri-app
npm install
npm run tauri dev
```