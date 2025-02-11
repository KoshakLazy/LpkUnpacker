## Requirements
`python -m pip install -r requirements.txt`

## Usage
```
usage: LpkUnpacker.py [-h] [-v] [-c CONFIG] target_lpk output_dir

positional arguments:
  target_lpk            path to lpk file
  output_dir            directory to store result

options:
  -h, --help            show this help message and exit
  -v, --verbosity       increase output verbosity
  -c CONFIG, --config CONFIG
                        config.json
```

Steam workshop .lpk file needs config.json to decrypt.

.lpk file can be found at `path/to/your/steam/steamapps/workshop/content/616720/...` or `path/to/your/steam/steamapps/common/Live2DViewerEX/shared/workshop/...`

To decrypt .wpk file, you need to unzip it with 7zip or other unzip tools, and you will get .lpk file and config.json. 