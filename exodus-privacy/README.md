# About

Both scripts `exodus.py` and `exodus-ipv4.py` are based on a slightly adjusted Python script originally created by Karol Gusak, Co-Founder of Blokada.

Blogpost: [Introducing Exodus Privacy to Blokada](https://community.blokada.org/t/introducing-exodus-privacy-to-blokada/7358)  
Script: <https://github.com/blokadaorg/landing-github-pages/blob/master/scripts/exodus.py>

The IPv4 version maps the IP address [0.0.0.0](http://0.0.0.0) to each hostname, while the simple hosts list is just a list of hostnames.

## Usage

```bash
mkdir -p dist
python exodus.py -i https://reports.exodus-privacy.eu.org/api/trackers -o dist/hosts
python exodus-ipv4.py -i https://reports.exodus-privacy.eu.org/api/trackers -o dist/hosts-ipv4
```
