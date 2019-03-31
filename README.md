```bash
docker run --rm -it -t deadc/gobuster \
  -u http://10.10.10.109/sparklays/ \
  -k -w /data/wordlists/dirbuster/directory-list-2.3-medium.txt \
  -x php,txt,html,xml,jsp \
  -t 50
```
