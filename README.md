```bash
docker run --rm -it -t deadc/gobuster \
  -u http://url.me/path/ \
  -k -w /data/wordlists/dirbuster/directory-list-2.3-medium.txt \
  -x php,txt,html,xml,jsp \
  -t 50
```
