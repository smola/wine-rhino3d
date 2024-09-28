# wine-rhino3d

Installer for [Rhino 3D](https://www.rhino3d.com/) on [Wine](https://www.winehq.org/).

> [!NOTE]
> This project is not affiliated with or officially supported by McNeel.

> [!WARNING]
> Rhino is only officially supported on Windows and macOS. This projects aims to help installing and running Rhino on Linux with Wine on a best effort basis, and without any support from McNeel..

## Supported versions

| Version | Installs | Runs |
| ------- | -------- | ---- |
| 6       | Yes      | ?    |
| 7       | Yes      | Yes  |
| 8       | Yes      | No   |
| wip     | ?        | ?    |

## Usage

### 1. Install Wine

You will need to have Wine installed on your system. You can find instructions on how to install Wine on the [WineHQ website](https://www.winehq.org/)..

### 2. Download wine-rhino3d

```
# With git:
git clone https://github.com/smola/wine-rhino3d.git
cd wine-rhino3d

# Or download the ZIP archive:
wget https://github.com/smola/wine-rhino3d/archive/refs/heads/main.zip
unzip wine-rhino3d-main.zip
mv wine-rhino3d-main wine-rhino3d
cd wine-rhino3d
```

### 3. Install Rhino

```
# You can pick the version you want to install with --version
./install-rhino --version 7
```

### 4. Run Rhino

```
./run-rhino --version 7
```

## Issues?

If you find any problem when using this project, feel free to [open an issue](https://github.com/smola/wine-rhino3d/issues).

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE).
