# qlv
qlever automation script
# Links
- https://github.com/ad-freiburg/qlever

# Usage
```
Usage: /home/wf/bin/qlv [OPTIONS]
Options:
  -h, --help             Show this help message
  -c, --current          Show the disk currently used by QLever
  -d, --debug            Enable debug output
  --disk [DISK]          select the disk to be used
  -ir, --index-run       Run QLever wikidata indexing on today's disk
  -l, --list             List used paths
  -p, --pull             Pull QLever Docker images
  -qc, --qlever-control  setup qlever-control
  -s, --space            Show free disk space
  -t, --today            Show disk to be used today
  -v, --version          Show version information
```
## Example
```bash
./qlv --disk tepig --kg olympics -ir
✅:Created directory /hd/tepig/qlever/wikidata_20250213
✅:Started screen session qlever_wikidata_20250213.
✅:Logging to /hd/tepig/qlever/wikidata_20250213/screen.log
```
