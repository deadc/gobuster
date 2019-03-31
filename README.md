![automated](https://img.shields.io/docker/cloud/automated/deadc/gobuster.svg) ![status](https://img.shields.io/docker/cloud/build/deadc/gobuster.svg)
```bash
docker run --rm -it -t deadc/gobuster \
  -u http://url.me/path/ \
  -k -w /data/wordlists/dirbuster/directory-list-2.3-medium.txt \
  -x php,txt,html,xml,jsp \
  -t 50
```
