# jonasnic KiCad Addons

A custom **KiCad Plugin and Content Manager (PCM)** repository containing KiCad plugins by jonasnic.

---

## Add to KiCad PCM

1. Open **KiCad** → **Tools → Plugin and Content Manager**
2. Click the **Manage** button next to *Manage Custom Repositories*
3. Click **+** (Add) and paste the repository URL:

```
https://raw.githubusercontent.com/jonasnic/JonasNic-Kicad-plugins/main/repository.json
```

4. Click **OK**, then **Refresh**
5. Browse and install any of the plugins listed below

---

## Available Plugins

### EasyEDA to KiCad Importer

Import LCSC / JLCPCB components (schematic symbol, PCB footprint, 3D model) directly into your KiCad library.

- Paste a component ID such as `C294018` and click **Import**
- Choose to import **Symbol**, **Footprint**, **3D Model**, or all three at once
- Automatically installs the `easyeda2kicad` Python package on first use
- Configurable output folder and library name

**Source:** [jonasnic/Kicad_easyead2kicad_addon](https://github.com/jonasnic/Kicad_easyead2kicad_addon)

---

## Repository file

| File | Purpose |
|------|---------|
| [`repository.json`](repository.json) | PCM repository index (add this URL to KiCad) |

---

## License

MIT
