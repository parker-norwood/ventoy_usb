# Ventoy USB Config

A repository with my custom configuration files for creating a Ventoy USB.

Ventoy USB uses [Ventoy](https://github.com/ventoy/Ventoy) to create a multiboot live USB.  
Customized using a slightly altered [grub2-themes](https://github.com/vinceliuice/grub2-themes) Vimix theme.

# Install

1. Install following the instructions on the Ventoy [website](https://www.ventoy.net/en/doc_start.html)
2. Copy the `iso/`, `persistence/`, and `ventoy/` folders to the `Ventoy` partition created on the USB
3. Download `.iso` files to the `iso/` directory for each OS you want on your device
4. [Create](https://www.ventoy.net/download/CreatePersistentImg.sh) or [download](https://github.com/ventoy/backend/releases) persistence `.dat` files using the [persistence plugin guide](https://www.ventoy.net/en/plugin_persistence.html) for each OS you want with a persistence feature
5. Edit [ventoy/ventoy.json](ventoy/ventoy.json) `menu_alias`, `menu_class`, and `persistence` if using an OS that is not already present in the file