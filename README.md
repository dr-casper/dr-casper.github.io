# Dr. Casper static website
Visit: https://dr-casper.ru

## Roll out new version

## Install ngh
```bash
npm install -g angular-cli-ghpages
```

## Release changes
```bash
rm -rf dist && cp -r src dist && ngh -d dist -b master
```
