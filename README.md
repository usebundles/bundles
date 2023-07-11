# Bundles

A Linux-first solution to electron.

## Requirements

To use Bundles, you will need to install ``pywebview``, which renders the windows.

To install it:
```pip install pywebview```

If you use Arch Linux, you may need to use the system package, which requires building it.
```paru -S python-pywebview```

## Usage

To use the software:

- Open a terminal and cd into the directory with the bundle you want to install
  
- Run the command:

```bash
./bundle-install
```

- The program will be available in your start menu.
Alternatively, you may run the software without having to install it:
- Open a terminal and cd into the directory with the bundle you want to run

- Allow the program to be run. For example:

```bash
chmod +x ./example-bundle
```

- Run the bundle:

```bash
./example-bundle
```
