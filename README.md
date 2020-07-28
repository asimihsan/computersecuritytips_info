# computersecuritytips_info
Blog about computer security tips for everyday folk. Hugo-based static blog.

## How to get started after cloning

```
git submodule init
git submodule update

(cd themes/minimo && npm install)
```

When you first clone the repo you need to fix up the remote URI for the theme submodule:

```
(cd themes/minimo && git remote set-url origin git@github.com:asimihsan/minimo.git)
```

## Building for local view

```
(cd themes/minimo && npm run build) && hugo server -D --disableFastRender
```

## Building for deployment

```
HUGO_ENV=production HUGO_BASEURL='https://computersecuritytips.info' hugo --buildDrafts --destination build
```

## DNS

### Old NS record

```
ns-1035.awsdns-01.org.
ns-468.awsdns-58.com.
ns-1917.awsdns-47.co.uk.
ns-967.awsdns-56.net.
```

### Old SOA record

```
ns-1035.awsdns-01.org. awsdns-hostmaster.amazon.com. 1 7200 900 1209600 86400
```