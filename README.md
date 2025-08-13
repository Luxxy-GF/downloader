<div align="center">
  <h3 align="center">Proxmox Templates Downloader</h3>

  <p align="center">
    A tool for importing pre-made templates to your Proxmox node. (Default templates provided free of charge!)
  </p>
</div>

## About The Project

Proxmox Templates Downloader is a utility created by Performave to help users import pre-made templates to their Proxmox node. This
tool is designed to be used with Convoy Panel, but it can be used standalone too.

## Usage

1. Download the binary onto your Proxmox node for the corresponding architecture from
   the [releases](https://github.com/Luxxy-GF/proxmox-downloader/releases/latest) page.
2. Make the binary executable (e.g., `chmod +x downloader_x86`)
3. Run the binary from the terminal (e.g., `./downloader_x86`)

```sh
wget https://github.com/Luxxy-GF/proxmox-downloader/releases/latest/download/downloader_x86 && chmod +x downloader_x86 && ./downloader_x86
```

### Custom Images List

You can specify a custom images list by providing the URL as an argument when running the binary. For example:

```sh
./downloader_x86 https://images.cdn.luxxysystems.com/images.json
```

To understand the structure of the JSON file, you can view the default images
list [here](https://images.cdn.luxxysystems.com/images.json).

## License

Distributed under the AGPL-3.0 License. See `LICENSE` for more information.

## Credits
[Creator](https://github.com/ConvoyPanel/downloader)
